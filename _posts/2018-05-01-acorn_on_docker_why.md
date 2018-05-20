---
layout: post
title: "Acorn on Docker pt.1"
description: Learn what Docker is and why you might want to use it.
tags: blog docker acorn
date: 2018-05-01
---

**<u>What is Docker & why would you want to use it for BBC Micro/Electron?</u>**

You may have seen in some of my posts on the Stardot (Acorn User) forum - specifically about B-EM and B2 Emulators - that I have mentioned the application know as Docker, and that I have containerized various Acorn emulators. I am fairly sure some people will not know what Docker is or why they might want to use it. So here is a quick run through. This information is a regurgitation in my head from various sources of information. I shall put a few links at the bottom.

Containers have been around for a while, they were Zones in Solaris and then Linux added this ability (called LXC). Companies like Google have used containers for a  some time. One of the companies using Linux containers, a startup called dotcloud who were using containers for their cloud service, found the management of containers to be a bit clunky and unwieldy as things scaled up. They gradually wrote a management system to help build and control these containers. Their main business wasn’t going very well so they reinvented themselves as Docker (inc) and their infrastructure tool that was supporting the containers at the core of their original business became their new business. They now provide support and extra bits on top of the core Docker software (open sourced under Moby and released to the public as  Docker CE) and rebrand it as Docker EE (Enterprise Edition).

So there you have it. Docker is one way to do Linux Containers ….

<u>So why would YOU want Linux containers?</u> <br>
Containers are not VMs but it may help people to understand them as an ultra-lite VMs (which on the Mac they are but that is another story).

Whereas a VM will have the whole O/S duplicated inside it, you can think of a container as having a load of API’s to the kernel services on the host server rather than having the entire O/S installed inside. So to an application it might look like it is a VM or Hardware but it isn't either. So if we look at the structure of a container.

![Docker Container. Source: Docker Inc <https://www.docker.com/what-container>](https://www.docker.com/sites/default/files/Container%402x.png)


And then we compare it to the structure of a VM.

![Traditional VM. Source: Docker Inc <https://www.docker.com/what-containe>](https://www.docker.com/sites/default/files/VM%402x.png)

You can see the additional bloat that a VM would have if it has more than one Guest. A Bare Metal VM server with just a single guest would overall perhaps be around the same size as a server running one container. But in the real world no one buys servers to run a single VM or a single container. As soon as you start adding more application the container method becomes much more efficient. Some companies are running thousands of containers. While this doesn't really apply to Acorn Emulators, in that some one is unlikely to want to run up 3000 of them in a cloud, it is fun to do it at a mini project.

Containers also use cgroups so you can lock down resource usage and stop a container eating the all the servers cpu or memory. But in the case of compiling emulators what it really gets around is dependancies, they can be a large pain when compiling code. This solution gets around the dependancy issues because if it runs on docker on one machine it will run on docker on another machine (with the caveat if you use advanced feature on the latest release those feature may not exist on previous versions. But generally backwards compatibility is solid). 

So as an example take the B-EM Allegro 5 Linux Docker X86 image. If you try to compile this from source on Ubuntu 16.04 you will find it won't work as Allegro5 is not complete and it is also the wrong version (an early version of 5). You could fix this by upgrading ubuntu, compiling Allegro 5 from source or getting 3rd party packages from elsewhere (updating source list for apt etc.). But these fixes may not be feasible for one reason or another, and you might only want to test something quickly for 10 mins and then not use it again for 6 months. This is where docker comes in, you can run any docker image create by anyone else. Dependancies and versions are a thing of the past

The other nice thing about Docker is it is cross platform. Originally there was only Linux containers and these would run on Linux, MacOS or Windows x86 (generally 64bit, unless running on ARM). Basically the latter two O/S would run an ultralight Linux VM and then run the Docker Linux Container on top. This isn't as much saving as running naively on Linux (which does not require the light touch VM) but still vastly smaller than a full VM. Recently with Windows 10 64bit and Windows Server 2016 there has been the introduction of Windows containers, so now windows application can be containerised as well. This is because Microsoft have put kernel hooks into windows so that Docker can access the low level services it requires. Unfortunately currently there is no easy way to make a Windows Container run on Linux without resorting to a full VM. Therefore it is better to do Linux containers as a priority (unless you are a windows only shop) as they will run in more places out of the box.

As mentioned above we can use docker to run ARM images. Although you can run an X86 Linux container on ARM directly you can use the same docker build file (known as a Dockerfile) to build the ARM version. Images are are not containers but potential containers, i.e. an image can be used to spawn many containers but a container is only using one 'full' image. An image is the code that creates a run time container. An image is actually made of many slices, so if you change config in your dockerfile it only has to rebuild from that change onward. Therefore if you keep you most dynamic config near the bottom of a dockerfile you can reduce the build time vastly. We can see the various sizes of the images in the raspberry pi:

    REPOSITORY                  TAG                 IMAGE ID            CREATED             SIZE
    <none>                      <none>              17d68edb50a9        2 days ago          1.61GB
    elminster/b-em-arm32v6      allegro5-pre2       021ce29a6948        9 days ago          275MB
    elminster/b-em-arm32v6      latest              021ce29a6948        9 days ago          275MB
    elminster/b2-arm32v6        latest              5714c7c93400        10 days ago         304MB

To get an idea of the size difference on x86.

> * B-EM just shipping the app. 20MB (including docs, rows and tapes that come with it)
> * B-EM as a container - 351 MB
> * B-EM on a ‘lite’ implementation of Debian - 5 GB

'The container is huge', you say but when you knock off the dependancies required to run B-EM it is much smaller in size. An ‘empty’ Ubuntu container is about 100MB.  So the actual size of the B-EM application is 250MB, although generally you would have most of these dependancies installed anyway. But either way it  is much smaller than trying to throw VMs around the web. In this case about 15 times smaller.

In Part 2 I will cover installing Docker and running an ‘Acorn’ container. Some supporting links.

*  <https://www.docker.com/what-docker>
*  <https://hub.docker.com/u/elminster/>
*  [Alex Ellis' getting started with RPi on Docker blog post](https://blog.alexellis.io/getting-started-with-docker-on-raspberry-pi/)
* <https://docs.microsoft.com/en-us/virtualization/windowscontainers/about/>
