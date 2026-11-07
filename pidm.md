---
layout: default
title: "PiDM — a dual-screen DM console (coming soon)"
permalink: /pidm/
---

# PiDM — coming soon

**PiDM** is a dual-screen Dungeon Master console for tabletop role-playing games
played **in person**. The DM runs the session from a tabbed control screen; the
players see a separate full-screen display (a TV or second monitor) that the DM
drives. Remote players can follow along in any web browser, with nothing to
install.

It is built to run on a **Raspberry Pi 5** with two HDMI screens, and on
ordinary Linux desktops.

**Status:** in private testing before its first public release. It will be
released as open source under the MIT licence. This page will be updated when
it is available.

## What it does

- **Player screen:** show images, maps (with fog of war and tokens), video and
  a webcam to the table; blank or revert in one click.
- **Sound:** layered ambient beds, a sound-effects board and text-to-speech
  NPC voices.
- **Campaign:** adventures, chapters and sessions, each with its own maps,
  images, sounds, documents and notes, ready to open mid-session.
- **Reference:** a configurable DM Screen, D&D 5e SRD spells, monsters, magic
  items and equipment, imported D&D Beyond character sheets, PDFs and
  generators.
- **Table aids:** captions, a countdown timer, progress clocks, a marching
  order and an in-world calendar with weather.
- **Notes:** a scratchpad, session-prep sheets and search across everything.

## Obsidian Portal integration

PiDM can link and post to [Obsidian Portal](https://www.obsidianportal.com/)
using its official API:

- **Read:** your campaign's wiki pages and characters, so names in your session
  notes can be turned into Obsidian Portal links automatically.
- **Write:** post a session note as an **Adventure Log** entry, tagged and
  linked. New posts are always created **GM-only**; PiDM never changes a post's
  visibility, so nothing is revealed to players unless you publish it yourself.
- **Only when you ask:** every request is started by you (Connect, Refresh or
  Post). There is no background polling.
- **Your keys stay on your machine:** you register your own application and
  sign in with Obsidian Portal's PIN flow. The keys and access token are stored
  only on your own computer, in a file only you can read, and are never shared
  or uploaded anywhere else.
- **Works without the API too:** a campaign backup file can be imported
  offline instead.

## Contact

Questions about PiDM: [github.com/elminster](https://github.com/elminster).
