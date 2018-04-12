---
layout: default
title: "Stardot Retro Hardware List"
date: 2018-04-12
---

<style>
table{
    border-collapse: collapse;
    border-spacing: 0;
    border:2px solid #000000;
}

th{
    border:2px solid #000000;
}

td{
    border:1px solid #000000;
}
tr:nth-child(even) {background: #CCC}
tr:nth-child(odd) {background: #FFF}
 a:link {
color: #cc0000;
}
a:visited {
color: #999999;
}
a:hover {
color: #ff3300;
}
</style>

# Modern Retro Hardware List for the BBC Micro Master and Acorn Electron

Following is a list of Modern Hardware projects that have been created for the Acorn 8bit series of computers. They may be commercial or produced by hobbists; they could be open source or propritey and they might be supplied as a PCB, a kit, fully built or anywhere in between!

## _**The Main List**_

| Product | Description | Designers | ActiveSupplier | Connection | Compatible | Category | Built | License | Org_Type | URLs |
|---------|-------------|-----------|----------------|------------|------------|----------|-------|---------|----------|------|
| GoMMC | MMC storage system | John Kortink | EOL | ROM Slot | ALL * | Storage | Prebuild | Propriety | Commercial | <http://www.zeridajh.org/hardware/gommc/index.htm> |
| GoSDC | SDC Storage system | John Kortink | Y | ROM Slot | ALL * | Storage | Prebuild | Propriety | Commercial | <http://www.zeridajh.org/hardware/gosdc/index.htm> |
| ReCo6502 | Remake of Acorn 6502 CoPro | John Kortink | EOL | Cheese | BBC B, Master | CoPro | Prebuild | Propriety | Commercial | <http://www.zeridajh.org/hardware/reco6502/index.htm> |
| ReTuLa | Remake of Acorn Tube ULA | John Kortink | EOL | N/A | BBC B, Master | Tube | Prebuild | Propriety | Commercial | <http://www.zeridajh.org/hardware/retula/index.htm> |
| TubeSilencer | Tube Interface voltage step down (aka silencer, muffler) | John Kortink | Y | Tube | BBC B, Master | Tube | Prebuild | Propriety | Commercial | <http://www.zeridajh.org/hardware/tubesilencer/index.htm> |
| ReCo6502Mini | Remake of 65C102 Internal CoPro | John Kortink | Y | Internal Tube | Master | CoPro | Prebuild | Propriety | Commercial | <http://www.zeridajh.org/hardware/reco6502mini/index.htm> |
| Ethernet Module | Master series 10/100Mbps ethernet module | Sprow | Y | Internal Econet | Master | Comms | Prebuild | Propriety | Commercial | <http://www.sprow.co.uk/bbc/masternet.htm> |
| 3.5" Floppy | 3.5 Disc drives compatible with the 8271 DFS via pulse modification | Sprow | ? | Disc | BBC B, Master | Storage | Prebuild | Propriety | Commercial | <http://www.sprow.co.uk/bbc/floppydrives.htm> |
| Extra Serial Port | Add-on board for extra serial port | Sprow | Y | 1Mhz Bus | BBC B, Master | Comms | Prebuild | Propriety | Commercial | <http://www.sprow.co.uk/bbc/extraserial.htm> |
| ARM7 Internal CoPro | Internal ARM7 coprocessor | Sprow | ? | Internal Tube | Master | CoPro | Prebuild | Propriety | Commercial | <http://www.sprow.co.uk/bbc/armcopro.htm> |
| ARM7 External CoPro | External ARM7 coprocessor | Sprow | ? | Tube | BBC B, Master | CoPro | Prebuild | Propriety | Commercial | <http://www.sprow.co.uk/bbc/armcopro.htm> |
| Speech Kit | Reprogrammable speech system | Sprow | Y | Speech Sockets | BBC B | Audio | Prebuild | Propriety | Commercial | <http://www.sprow.co.uk/bbc/speechupgrade.htm> |
| BeebIDE Interface | BeebIDE harddisc interface  | Sprow | Y | 1Mhz Bus | BBC B, Master | Storage | Prebuild | Propriety | Commercial | <http://www.sprow.co.uk/bbc/beebide.htm> |
| MiniB | The floppy disc sized BBC micro | Sprow | Y | N/A | N/A | Computer | Prebuild | Propriety | Commercial | <http://www.sprow.co.uk/bbc/minib.htm> |
| MS DOS FS Rom | PC DOS and Windows 95 long filename format | Sprow | Y | ROM Slot | BBC B, Master | ROM | Prebuild | Propriety | Commercial | <http://www.sprow.co.uk/bbc/dosfs.htm> |
| 8MB RAM Disc | High Speed RAM disc | Sprow | Y | 1Mhz Bus | BBC B, Master | Storage | Prebuild | Propriety | Commercial | <http://www.sprow.co.uk/bbc/ramdisc.htm> |
| Y2k ROM | Fixes Year 2000 problem on Master | Sprow | Y | ROM Slot | Master | ROM | Prebuild | Propriety | Commercial | <http://www.sprow.co.uk/bbc/doomsday.htm> |
| ROM Cartridge | Spare ROM/RAM cartridges | Sprow | Y | Cartridge | Electron, Master | Cartridge | Prebuild | Propriety | Commercial | <http://www.sprow.co.uk/bbc/cartridges.htm> |
| BeebSID | Expansion with C64 SID Music Chip | MartinB/TomW | S: Prime | 1Mhz Bus | ALL *E | Audio | Kit | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=2530&hilit=Beebsid> |
| Master Ram Board | Remake of Slogger MRB | Prime | ? | CPU Socket | Electron | ShadowRAM | Prebuild | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=6729> |
| Electron Plus 3 RAM/ROM  | Plus 3 RAM/ROM board | Prime | ? | Internal Plus3 | Electron | Expansion | Kit | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=8706> |
| Electron User/UPURS Ports | Twin User and One UPURS Port | MartinB | Sixxdog_uk | Cartridge | Electron | Expansion |  | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=8&t=12817&hilit=Electron+user+port> |
| Internal Data Centre | USB, CF, IDE, NVRAM with 1MB Flash RAM. Fits internally. | RetroClinic | Y | 1Mhz Bus | BBC B, Master | Storage | Prebuild | Propriety | Commercial | <http://www.retroclinic.com/acorn/datacentre/datacentre.htm> |
| External Data Centre | USB, CF, IDE, NVRAM with 1MB Flash RAM. Fits iexternally. | RetroClinic | Y | 1Mhz Bus | ALL *E | Storage | Prebuild | Propriety | Commercial | <http://www.ebay.co.uk/usr/retroclinic> |
| BBC 1770 Upgrade | 1770 Disc Upgrade Kit | RetroClinic | Y | Disc IC Socket | BBC B | Storage | Kit | Other | Commercial | <http://www.ebay.co.uk/usr/retroclinic> |
| BBC B+ ROM Switcher | B+ MOS switch between 2.0 and 1.2 | RetroClinic | Y | ROM Slot | BBC B+ | MOS | Prebuild | Other | Commercial | <http://www.ebay.co.uk/usr/retroclinic> |
| Master ROM Switcher | Master MOS Switch - 3.5, 3.2, 2.0 and 1.2 | RetroClinic | Y | ROM Slot | Master | MOS | Prebuild | Other | Commercial | <http://www.ebay.co.uk/usr/retroclinic> |
| BeebMaster Econet Clock | Econet Clock for running your own Econet network | Beebmaster | Y | Econet | BBC B, Master | Comms | Prebuild | Other | Not for Profit | <http://www.beebmaster.co.uk/BeebShop/BMClock.html> |
| BeedMaster Econet Module | Remake of Master Intenral Econet Module | Beebmaster | Y | Internal Econet | Master | Comms | Prebuild | Other | Not for Profit | <http://www.beebmaster.co.uk/BeebShop/BMEconet.html> |
| VideoNuLA | Palettemate Remada and improved. GFX mode that gives 16 colours in mode 2 and 4096 palette in  all modes | RobC | Y | Video Socket | Master | Video | Prebuild | Other | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?p=169107#p169107> |
| Internal 1Mhz connector Adaptor | Converts internal SCSI/Modem connect in Master to a stnadard 1Mhz bus connector. | simoni | ? | Internal SCSI/Modem | Master | Storage | Design Only | Open Source | Not for Profit | <http://www.domesday86.com/?page_id=409> |
| BeebSCSI | Emulate the original BBC Domesday Laser Video Disc system and provides a microSD storage card | simoni | Y - flynnjs | 1Mhz Bus | ALL * E | Storage | Design Only | Open Source | Not for Profit | <http://www.domesday86.com/?page_id=400> |
| SmallyMouse2 | Universal USB to Quadrature mouse converter | simoni | TheCorfiot | User Port | ALL * E | User Interface | Prebuild | Open Source | Not for Profit | <http://www.waitingforfriday.com/?p=827> |
| ATI | Tube Interface for the Electron | Dave Hitchins | Y | Cartridge |  | Expansion | Custom | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=5588> |
| ARA | ROM Cartridge | Dave Hitchins | Y | Cartridge | Electron, Master | Expansion | Custom | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=5555> |
| ABR | Advance Battery Backed Ram Cartridge | Dave Hitchins | Y | Cartridge | Electron, Master | Expansion | Custom | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=5672> |
| AP6 | Remake of PRES AP6. Internal ROM expansion for Plus1 | Dave Hitchins | Y | Internal Plus1 | Electron | Expansion | Custom | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=6280> |
| MGC | Mega Games Cartridge. Programmable 200+ Game slots with interative menu | Dave Hitchins | Y | Cartridge | Electron | Expansion | Prebuild | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=1&t=8246> |
| AP5 | Remake of PRES AP5. User, Tube and 1Mhz Port Cart | Dave Hitchins | Y | Cartridge | Electron | Expansion | Custom | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=8602> |
| Match box copro | CoPro reproduced on a matchbox  | Hoglet/Flynnjs/BigEd | Y - flynnjs | Tube | ALL *E | CoPro | Kit | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=8&t=8932> |
| BeebOPL | Yamaha circa 1980 Midi Chip Expansion | lazarusr | N | 1Mhz Bus | ALL *E | Audio | Kit | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?t=11434> |
| Acorn Master Switcher | MOS ROM Switcher for BBC Master | ctorwy31 | Y | ROM Slot | Master | MOS | Prebuild | Other | Commercial | <http://www.ebay.co.uk/usr/ctorwy31> |
| Turbo MMC | MMC Storage for Acorns | ctorwy31 | Y | User Port | ALL *E | Storage | Prebuild | Other | Commercial | <http://www.ebay.co.uk/usr/ctorwy31> |
| ROM/SRAM Cartiridge  | Acorn BBC Micro Master RAM/ROM cartridge preloaded with eight ROM images | ctorwy31 | Y | Cartridge | Master | Cartridge | Prebuild | Other | Commercial | <http://www.ebay.co.uk/usr/ctorwy31> |
| EEPROM Cartridge | Acorn BBC Micro Master non-volatile EEPROM ROM cartridge + Free Snapper ROM | ctorwy31 | Y | Cartridge | Master | Cartridge | Prebuild | Other | Commercial | <http://www.ebay.co.uk/usr/ctorwy31> |
| BBC Micro 1772 Disc Upgrade | 1772 Disc Upgrade PCB + DFS & DDFS ROMS | ctorwy31 | Y | Disc IC Socket | BBC B | Storage | Prebuild | Other | Commercial | <http://www.ebay.co.uk/usr/ctorwy31> |
| 32kB RAM & 32kB ROM | 32 kB RAM/ROM kit | cmorley | Y | ROM Slot | BBC B | Expansion | Prebuild | Other | Not for Profit | <http://www.boobip.com/index.php/hardware/32kb-ram-32kb-rom> |
| 64kB EEPROM Module | 64kB EEPROM kit | cmorley | Y | ROM Slot | BBC B | Expansion | Prebuild | Other | Not for Profit | <http://www.boobip.com/index.php/hardware/64kb-eeprom> |
| OS RAM Module (Extra 30k) | Code needs to be OS RAM Mod Aware | cmorley | Y | ROM Slot | BBC B | Expansion | Prebuild | Other | Not for Profit | <http://www.boobip.com/hardware/osram/osram-technical> |
| Model B paged ROM breakout boards | Access BBCs ROM externally | cmorley | Last Run | ROM Slot | BBC B | Expansion | Custom | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=12753> |
| External PiTubeDirect Signal Converter | Steps down voltage from 5v to 3.3v | Kjell | Y | Tube | ALL *E | Tube | Prebuild | Open Source | Not for Profit | <https://github.com/hoglet67/PiTubeDirect/wiki/Level-Shifter-options> |
| Under PiTubeDirect Signal Converter | Steps down voltage from 5v to 3.3v, fits underneath to the external tube connector for use with Pi Zero only. | Kjell | Y | Tube | BBC, Master | Tube | Prebuild | Open Source | Not for Profit | <https://github.com/hoglet67/PiTubeDirect/wiki/Level-Shifter-options> |
| Internal PiTubeDirect Signal Converter | Steps down voltage from 5v to 3.3v | Kjell | Y | Internal Tube | Master | Tube | Prebuild | Open Source | Not for Profit | <https://github.com/hoglet67/PiTubeDirect/wiki/Level-Shifter-options> |
| DIY Master Quad ROM Switch | Kit based ROM MOS Switcher | Kjell | Y | ROM Slot | Master | MOS | Kit | Open Source | Not for Profit | <http://www.sundby.com/index.php/diy-bbc-master-quad-os-rom-switch/> |
| Dual Digital Joystick Adapters | Dual Digital Joystick Adapters, converts analoge port to digital | Bryce | Y | Analogue Port | ALL | User Interface | Prebuild | Other | Not for Profit | <http://www.amibay.com/showthread.php?76794-BBC-Electron-Dual-Digital-Joystick-Adapters/page11> |
| RAMagic | PC to Beeb File Transfer. RTC, 32KB NVRAM, 16K SRAM | MartinB | EOL? | ROM Slot | BBC B, Master | Expansion | Prebuild | Other | Not for Profit | <http://chrisacorns.computinghistory.org.uk/New4Old/MBarr_RAMagic.html> |
| Atom 32K RAM/ROM | Provides 32K RAM, sideways Rom and a faster 6502 Clock Speed. | Prime | ? |  | Atom | Expansion | Prebuild | Other | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?t=5056> |
| Atom Floppy Board | WD177x Floppy Controller board | Prime | ? |  | Atom | Storage | Prebuild | Other | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=44&t=10351> |
| Atom Colour Board |  | Prime | Shelved? |  | Atom | Video |  |  | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=44&t=10158> |
| AtoMMC2 SC Card | MMC Storage for Acorn Atoms | SirMorris |  |  | Atom | Storage |  |  |  | <http://stardot.org.uk/forums/viewtopic.php?f=8&t=2888> |
| Atom 6809 Second Processor | 6809 CoPro fro the Atom | Roland |  |  | Atom | CoPro |  |  |  | <http://stardot.org.uk/forums/viewtopic.php?f=44&t=8518> |
| Atom 2015 Remake | Remake of the Atom from ground up | Roland | Y | N/A | Atom | Computer | PCB Only | Open Source | Not for Profit | <http://diy.acornatom.nl/links.html> |
| Atom GODIL Video Adapter |  | Hoglet |  |  | Atom | Video |  |  |  | <http://stardot.org.uk/forums/viewtopic.php?f=44&t=7320> |
| Atom Tube Interface | Tube interface for CoPro on ATOM | Hoglet |  |  | Atom | Tube |  |  |  | <http://stardot.org.uk/forums/viewtopic.php?f=44&t=10090> |
| Atom FPGA |  | Hoglet (AlanD) |  | Tube | Atom | CoPro |  |  |  | <http://stardot.org.uk/forums/viewtopic.php?f=44&t=6313> |
| Beeb SD Card | Beeb SD card interfaces | SirMorris | Y | User Port | ALL *E | Storage | Prebuild | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=8&t=12689> |


***

## _**Hardware System Integration Software**_

| Product | Description | Designers | Active | Connection | Compatible | Category | Built | License | Org_Type | URLs |
|---------|-------------|-----------|--------|------------|------------|----------|-------|---------|----------|------|
| PiTube | RPi Software + 5v Step down design to turn RPi into a CoPro | Hoglet/BigEd | Y | N/A | ALL *E | CoPro | Custom | Open Source | Not for Profit | <https://github.com/hoglet67/PiTubeDirect> |
| UPURS | The main software for the UPURS system. Also requires a user port serial cable and the correct USB Serial dongle. | MartinB | Y | User Port | All *E | Comms | Custom | Open Source | Not for Profit | <http://www.retro-kit.co.uk/UPURS/\n> |
| I2C (4 U) | Software on a ROM to glue an Acorn to I2C devices | MartinB | Y | User Port | All *E | Comms | Custom | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=10966> |


***
## _**DIY - Relevant DIY project not covered by above**_
This section covers any recent new or remakes of DIY projects that dont have an equivalent kit/prebuilt option above. There are 1000's of other DIY projects in Mags, Books and on the Web; But only a handful of really useful ones (that have been reimagined) currently appear here.

| Product | Description | Designers | Active | Connection | Compatible | Category | Built | License | Org_Type | URLs |
|---------|-------------|-----------|--------|------------|------------|----------|-------|---------|----------|------|
| 2 or more User Ports | Need more user ports on your BBC | Mike Cook | Sweh Rework | User Port | BBC B | Expansion | Design Only | Open Source | Not for Profit | <http://sweh.spuddy.org/Beeb/2nd_User_Port/> |
| Electron Breakout Cartridge | Breakout circuit board in cartridge format for the Electron | Paul Boddie | N/A | Cartridge | Electron | Prototyping | PCB Only | Open Source | Not for Profit | <https://oshpark.com/shared_projects/648KdmKd> |
| 32k Flash Cart | Simple Flash memory cartridge | myelin | Y | Cartridge | Electron | Storage | Design Only | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=12730> |
| USB Cart Interface | Read Electrons Cartridges from a PC/MAC | myelin | Y | Cartridge | Electron | Cart Reader | Design Only | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=12964> |
| 3-Cart Expansion | Plus1 Carrtridge Slot replacement, with one extra cartridge slots | myelin | Y | Cartridge | Electron | Expansion | Design Only | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=13089> |
| Elk PiTubeDirect | Electron cartridge interface for PiTubeDirect | myelin | Y | Cartridge | Electron | CoPro | Design Only | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=11325&start=720#p166961> |
| Microcontroller UPURS cable | ATMEGA32U4-based UPURS cable | myelin | Y | User Port | ALL *E | Comms | Design Only | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=13299&sid=abc4d45cc022b22e1448e6e08a48da91> |
| EEPROM  | Original EEPROM 'ROM' design, now incorporated into many projecs in the list. | MartinB | Various | ROM Slot | All | Expansion | Design Only | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=7393&hilit=Eeprom> |
| Master UPURS Port | Plus 6522 boardinto internal Econet to turn into a user port for UPURS | Sydney | Y | Internal Econet | Master | Comms | Design Only | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=7149> |
| Extra Master User Ports | Use the Internal SCSI/Modem port  for some extra user ports | Sydney | Y | Internal SCSI/Modem | Master | Comms | Design Only | Open Source | Not for Profit | <http://www.stardot.org.uk/forums/viewtopic.php?f=3&t=9403> |
| High Density Disk 1772 Mod | High Density Disk Mod, versions for Beeb and Electron AP4 | MartinB | Y | Disc IC Socket | All | Storage | Design Only | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=1884&start=60#p14648> |
| MMBeeb | Much copied and tweaked MMC storage medium for the Beeb (and anything with a user port) | Martin Mather | Y - Stardot | User Port | ALL *E | Storage | Design Only | Open Source | Not for Profit | <http://www.stardot.org.uk/forums/viewtopic.php?f=3&t=1919&start=0> |
| Acorn Econet Clock V2 | Acorn Econet Clock V2 remake | simoni | Y | Econet | ALL *E | Comms | Design Only | Open Source | Not for Profit | <http://www.waitingforfriday.com/?p=19> |
| Acorn Speech PHROM TMS6100 | Speech PHROM TMS6100 Remake | simoni | Y | Speech IC Sockets | BBC B | Audio | Design Only | Open Source | Not for Profit | <http://www.waitingforfriday.com/?p=30> |
| BBC Master PSU Upgrade | 60W Acorn BBC Master power supply upgrade | simoni | Y | N/A | Master | Power | Design Only | Open Source | Not for Profit | <http://www.waitingforfriday.com/?p=794> |
| beeb816 | 65816 upgrade for BBC Micro, including lots of fast RAM | BigEd/RichardE | Y | CPU Socket | BBC B, Master | Expansion | Design Only | Open Source | Not for Profit | <https://github.com/BigEd/beeb816/> |
| ICE-T65/Z80/6809 | In-Circuit Emulator for the 6502, 65C02, Z80, 6809 and 6809E 8-bit processors (socketed cpu req.) | Hoglet | Y | CPU Socket | ALL | Diagnostics | Design Only | Open Source | Not for Profit | <https://github.com/hoglet67/AtomBusMon/wiki> |
| Upgrading 64k B+ to 128K | Instructions for DIYing a 128K B+ | Various | Stardot | ROM Slot | BBC B+ | Expansion | Design Only | Open Source | Not for Profit | <http://www.stardot.org.uk/forums/viewtopic.php?f=3&t=9483> |
| Cheap 32k SRAM mod for Beeb | BBC Model B DIY 32K Sideways RAM | Retroclinic ? | Stardot | N/A | BBC B | Expansion | Design Only | Open Source | Not for Profit | <http://www.retroclinic.com/acorn/swr/swr.htm> |
| Atom YARRB | Yet Another RAM/ROM Board | Roland | Stardot | ROM Slot | Atom | Expansion | Design Only | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=44&t=11373> |
| AtomSID | AtomSID Music Expansion | Prime | Stardot |  | Atom | Audio | Design Only | Other | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=44&t=5053> |
| AtomSID | AtomSID Music Expansion | oss003 | Stardot |  | Atom | Audio | Design Only | Other | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=44&t=5053> |
| Master Config Backup Mod | Using supercaps instead of batteries | Various | Stardot | N/A | Master | Repair | Design Only | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=13353> |



***

## _**Resellers**_

| Product | Description | Designers | Active | Connection | Compatible | Category | Built | License | Org_Type | URLs |
|---------|-------------|-----------|--------|------------|------------|----------|-------|---------|----------|------|
| C.J.Micros | ReSeller of various new (and old) products | N/A | N/A | N/A | N/A | N/A | Custom | Other | Commercial | <http://www.cjemicros.co.uk/> |
| RetroClinic | Many spares, refurbs and repair services | N/A | N/A | N/A | N/A | N/A | Custom | Other | Commercial | <http://www.retroclinic.com/> |



***

## _**Connectors, Cables & Spares**_

| Product | Description | Designers | Active | Connection | Compatible | Category | Built | License | Org_Type | URLs |
|---------|-------------|-----------|--------|------------|------------|----------|-------|---------|----------|------|
| Econet Terminator | Terminators to terminate an Econet | Beebmaster | Y | Econet | Master, BBC *O | Comms | Prebuild | Open Source | Not for Profit | <http://www.beebmaster.co.uk/BeebShop/Default.html> |
| Econet Lead | Connection leads for Econet | Beebmaster | Y | Econet | Master, BBC *O | Comms | Prebuild | Open Source | Not for Profit | <http://www.beebmaster.co.uk/BeebShop/Default.html> |
| Power and ribbons? | Various power and Ribbon Cables | Beebmaster | Y |  | BBC, Master | Various | Prebuild | Other | Not for Profit | <http://www.beebmaster.co.uk/BeebShop/Default.html> |
| Serial Cables | BBC to PC Serial Crossover Cable | Sprow | Y | RS432 | BBC, Master | Comms | Prebuild | Open Source | Commercial | <http://www.sprow.co.uk/bbc/extraserial.htm> |
| Ethernet Cables DIN-&gt;RJ45 | Connect Sprow Ethernet Module to a Switch/Router | Sprow | Y | Econet | Master | Comms | Prebuild | Open Source | Commercial | <http://www.sprow.co.uk/bbc/masternet.htm> |
| Cap Replacement Kit | Kit containing the Caps to be replaced in PSU on old Beebs | RetroClinic | Y | N/A | BBC | Repair | Kit | Other | Commercial | <http://www.ebay.co.uk/usr/retroclinic> |
| Cap Replacement Kit | Kit containing the Caps to be replaced in PSU on old Beebs | ctorwy31 | Y | N/A | BBC | Repair | Kit | Other | Commercial | <http://www.ebay.co.uk/usr/ctorwy31> |
| Battery Packs | Replacement Battery Pack for Master | RetroClinic | Y | N/A | Master | Repair | Prebuild | Other | Commercial | <http://www.retroclinic.com/acorn/mbattery/mbattery.htm> |
| Manuals | Various Manual Reprints for Acrorn's | RetroClinic | Y | N/A | ALL | Books | Prebuild | Other | Commercial | <http://www.retroclinic.com/acorn/manuals/manuals.htm> |
| RGB Scart Lead | RGB Scart Lead Video TV Cable | retrocomputershack | Y | RGB | ALL | Video | Prebuild | Other | Commercial | <http://www.ebay.co.uk/itm/250877464070?_trksid=p2060353.m1438.l2649&ssPageName=STRK%3AMEBIDX%3AIT> |
| Cassette Lead | Cable to connect Beeb to Cassette | retrocomputershack | Y | Cassette Port | ALL | Storage | Prebuild | Other | Commercial | <http://www.ebay.co.uk/itm/250877464070> |
