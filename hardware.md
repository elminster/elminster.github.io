---
layout: default
title: "Stardot Retro Hardware List"
date: 2021-03-17
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
   #mytable a {
       text-decoration: none;
       color: blue;
   }
   #mytable a:visited {
       color: purple;
    }
   #mytable a:hover { text-decoration: underline }
</style>

# Modern Retro Hardware List for the BBC Micro Master and Acorn Electron

Following is a list of Modern Hardware projects that have been created for the Acorn 8bit series of computers. They may be commercial or produced by hobbyists; they could be open source or propriety and they might be supplied as a PCB, a kit, fully built or anywhere in between!

<div id="mytable" markdown="1">

## _**The Main List**_

| Product | Description | Designers | ActiveSupplier | Connection | Compatible | Category | Built | License | Org_Type | URLs |
|---------|-------------|-----------|----------------|------------|------------|----------|-------|---------|----------|------|
| GoMMC | MMC storage system | John Kortink | EOL | ROM Slot | ALL * | Storage | Prebuild | Propriety | Commercial | <http://www.zeridajh.org/hardware/gommc/index.htm> |
| GoSDC | SDC Storage system | John Kortink | Y | ROM Slot | ALL * | Storage | Prebuild | Propriety | Commercial | <http://www.zeridajh.org/hardware/gosdc/index.htm> |
| ReCo6502 | Remake of Acorn 6502 CoPro | John Kortink | EOL | Cheese | BBC B, Master | CoPro | Prebuild | Propriety | Commercial | <http://www.zeridajh.org/hardware/reco6502/index.htm> |
| ReTuLa | Remake of Acorn Tube ULA | John Kortink | EOL | N/A | BBC B, Master | Tube | Prebuild | Propriety | Commercial | <http://www.zeridajh.org/hardware/retula/index.htm> |
| TubeSilencer | Tube Interface voltage step down (aka silencer, muffler) | John Kortink | Y | Tube | BBC B, Master | Tube | Prebuild | Propriety | Commercial | <http://www.zeridajh.org/hardware/tubesilencer/index.htm> |
| ReCo6502Mini | Remake of 65C102 Internal CoPro | John Kortink | Y | Internal Tube | Master | CoPro | Prebuild | Propriety | Commercial | <http://www.zeridajh.org/hardware/reco6502mini/index.htm> |
| BBC2DVI | Allows your Acorn BBC or Electron to connect to modern monitors | John Kortink | Y | RGB | All | Video | Prebuild | Propriety | Commercial | <http://www.zeridajh.org/hardware/bbc2dvi/index.htm> |
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
| BeebSID  | Expansion with C64 SID Music Chip | MartinB/TomW/Prime | Y | 1Mhz Bus | ALL *E | Audio | Kit | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=14803> |
| Master Ram Board | Remake of Slogger MRB | Prime | ? | CPU Socket | Electron | ShadowRAM | Prebuild | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=6729> |
| Electron Plus 3 RAM/ROM  | Plus 3 RAM/ROM board | Prime | ? | Internal Plus3 | Electron | Expansion | Kit | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=8706> |
| Electron User/UPURS Ports | Twin User and One UPURS Port | MartinB | Sixxdog_uk | Cartridge | Electron | Expansion |  | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=8&t=12817&hilit=Electron+user+port> |
| Internal Data Centre | USB, CF, IDE, NVRAM with 1MB Flash RAM. Fits internally. | RetroClinic | N | 1Mhz Bus | BBC B, Master | Storage | Prebuild | Open Source | Commercial | <http://www.retroclinic.com/acorn/datacentre/datacentre.htm> |
| External Data Centre | USB, CF, IDE, NVRAM with 1MB Flash RAM. Fits externally. | RetroClinic | N | 1Mhz Bus | ALL *E | Storage | Prebuild | Open Source | Commercial | <http://www.ebay.co.uk/usr/retroclinic> |
| Micro-SPI MMC | Micro-SPI MMC Jukebox | RetroClinic | Y | Disc | BBC, Master | Storage | Kit | Other | Commercial | <http://www.ebay.co.uk/usr/retroclinic> |
| BBC 1770 Upgrade | 1770 Disc Upgrade Kit | RetroClinic | Y | Disc IC Socket | BBC B | Storage | Kit | Other | Commercial | <http://www.ebay.co.uk/usr/retroclinic> |
| BBC B+ ROM Switcher | B+ MOS switch between 2.0 and 1.2 | RetroClinic | Y | ROM Slot | BBC B+ | MOS | Prebuild | Other | Commercial | <http://www.ebay.co.uk/usr/retroclinic> |
| Master ROM Switcher | Master MOS Switch - 3.5, 3.2, 2.0 and 1.2 | RetroClinic | Y | ROM Slot | Master | MOS | Prebuild | Other | Commercial | <http://www.ebay.co.uk/usr/retroclinic> |
| BeebMaster Econet Clock | Econet Clock for running your own Econet network | Beebmaster | Y | Econet | BBC B, Master | Comms | Prebuild | Other | Not for Profit | <http://www.beebmaster.co.uk/BeebShop/BMClock.html> |
| BeedMaster Econet Module | Remake of Master Intenral Econet Module | Beebmaster | Y | Internal Econet | Master | Comms | Prebuild | Other | Not for Profit | <http://www.beebmaster.co.uk/BeebShop/BMEconet.html> |
| VideoNuLA | Palettemate Remada and improved. GFX mode that gives 16 colours in mode 2 and 4096 palette in  all modes | RobC | Y | Video Socket | BBC, Master | Video | Prebuild | Other | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?p=169107#p169107> |
| Internal 1Mhz connector Adaptor | Converts internal SCSI/Modem connect in Master to a stnadard 1Mhz bus connector. | simoni | ? | Internal SCSI/Modem | Master | Storage | Design Only | Open Source | Not for Profit | <http://www.domesday86.com/?page_id=409> |
| BeebSCSI | Emulate the original BBC Domesday Laser Video Disc system and provides a microSD storage card | simoni | Y - danielj | 1Mhz Bus | ALL * E | Storage | Design Only | Open Source | Not for Profit | <http://www.domesday86.com/?page_id=400> |
| BeebSCSI Mini | Mini BeebSCSI fitting under Beeb  | Flynnjs | N | 1MHz Bus | ALL *E | Storage | PreBuilt | TBC | TBC | <https://stardot.org.uk/forums/viewtopic.php?f=8&t=13224> |
| SmallyMouse2 | Universal USB to Quadrature mouse converter | simoni | TheCorfiot | User Port | ALL * E | User Interface | Prebuild | Open Source | Not for Profit | <http://www.waitingforfriday.com/?p=827> |
| ATI | Tube Interface for the Electron | Dave Hitchins | Y | Cartridge |  | Expansion | Custom | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=5588> |
| ARA | ROM Cartridge | Dave Hitchins | Y | Cartridge | Electron, Master | Expansion | Custom | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=5555> |
| ABR | Advance Battery Backed Ram Cartridge | Dave Hitchins | Y | Cartridge | Electron, Master | Expansion | Custom | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=5672> |
| AP6 | Remake of PRES AP6. Internal ROM expansion for Plus1 | Dave Hitchins | Y | Internal Plus1 | Electron | Expansion | Custom | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=6280> |
| MGC | Mega Games Cartridge. Programmable 200+ Game slots with interative menu | Dave Hitchins | Y | Cartridge | Electron | Expansion | Prebuild | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=1&t=8246> |
| MGC Mk II |  Mk. II | Dave Hitchins | In Development | Cartridge | Electron | Expansion | Prebuild | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=14517> |
| AP5 | Remake of PRES AP5. User, Tube and 1Mhz Port Cart | Dave Hitchins | Y | Cartridge | Electron | Expansion | Custom | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=8602> |
| Metal Cartridge Cases | Pegasus, New AP5 and New AP3/4 Painted Metal case | Dave Hitchins | Y | Cartridge | Electron | Case | Kit | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=13284> |
| Ultimate Electron Upgrade | ReMake of Electron ULA with a few extra features | Dave Hitchins/Hoglet/myelin | In Development | ULA | Electron | Expansion | TBC | Open Source | Not for Profit | <https://stardot.org.uk/forums/viewtopic.php?f=3&t=9223> |
| Electron ULA Basic Board | ReMake of Electron ULA  Lite | Budgie/(Hoglet) | In Development | ULA | Electron | Expansion | TBC | Open Source | Not for Profit | <https://stardot.org.uk/forums/viewtopic.php?f=3&t=19463> |
| Match box copro | CoPro reproduced on a matchbox  | Hoglet/Flynnjs/BigEd | Y - flynnjs | Tube | ALL *E | CoPro | Kit | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=8&t=8932> |
| Level shifter : 5v DIP to 3v3 DE0-nano | Used to allow other Spartan FPGAs to be used with ICE-T  | Flynnjs | Y | CPU Socket | ALL *E | Diagnostics | Prebuild | Other | Not for Profit | <http://www.xeropage.co.uk/shop/index.php?id_product=16&controller=product> |
| Femto Flash Floppy | Mini Gotek using SDCard fitting under Beeb  | Flynnjs | Development | Disc | ALL *E | Storage | TBC | TBC | TBC | <https://stardot.org.uk/forums/viewtopic.php?f=3&t=17753> |
| BeebOPL | Yamaha circa 1980 Midi Chip Expansion | lazarusr | N | 1Mhz Bus | ALL *E | Audio | Kit | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?t=11434> |
| Acorn Master Switcher | MOS ROM Switcher for BBC Master | ctorwy31/IFEL | Y | ROM Slot | Master | MOS | Prebuild | Other | Commercial | <http://www.ebay.co.uk/usr/ctorwy31> |
| Turbo MMC | MMC Storage for Acorns | ctorwy31/IFEL | Y | User Port | ALL *E | Storage | Prebuild | Other | Commercial | <http://www.ebay.co.uk/usr/ctorwy31> |
| ROM/SRAM Cartiridge  | Acorn BBC Micro Master RAM/ROM cartridge preloaded with eight ROM images | ctorwy31/IFEL | Y | Cartridge | Master | Cartridge | Prebuild | Other | Commercial | <http://www.ebay.co.uk/usr/ctorwy31> |
| EEPROM Cartridge | Acorn BBC Micro Master non-volatile EEPROM ROM cartridge + Free Snapper ROM | ctorwy31/IFEL | Y | Cartridge | Master | Cartridge | Prebuild | Other | Commercial | <http://www.ebay.co.uk/usr/ctorwy31> |
| BBC Micro 1772 Disc Upgrade | 1772 Disc Upgrade PCB + DFS & DDFS ROMS | ctorwy31/IFEL | Y | Disc IC Socket | BBC B | Storage | Prebuild | Other | Commercial | <http://www.ebay.co.uk/usr/ctorwy31> |
| 16 socket BB RAM/ROM EEPROM Board | Acorn BBC Micro 16 socket battery backed RAM ROM EEPROM expansion board | ctorwy31/IFEL | Y | Rom Slot | BBC B | Expansion | Prebuild | Other | Commercial | <http://www.ebay.co.uk/usr/ctorwy31> |
| 32kB RAM & 32kB ROM | 32 kB RAM/ROM kit | cmorley | Y | ROM Slot | BBC B | Expansion | Prebuild | Other | Not for Profit | <http://www.boobip.com/index.php/hardware/32kb-ram-32kb-rom> |
| 64kB EEPROM Module | 64kB EEPROM kit | cmorley | Y | ROM Slot | BBC B | Expansion | Prebuild | Other | Not for Profit | <http://www.boobip.com/index.php/hardware/64kb-eeprom> |
| OS RAM Module (Extra 30k) | Code needs to be OS RAM Mod Aware | cmorley | Y | ROM Slot | BBC B | Expansion | Prebuild | Other | Not for Profit | <http://www.boobip.com/hardware/osram/osram-technical> |
| Model B paged ROM breakout boards | Access BBCs ROM externally | cmorley | Last Run | ROM Slot | BBC B | Expansion | Custom | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=12753> |
| Master ROM switcher | 27C400/800/160/320 emulator/ROM switcher | cmorley | Dev | ROM Slot | Master | Mos | Prebuilt | TBC | TBC | <https://stardot.org.uk/forums/viewtopic.php?t=17715> |
| External PiTubeDirect Signal Converter | Steps down voltage from 5v to 3.3v | Kjell | Y | Tube | ALL *E | Tube | Prebuild | Open Source | Not for Profit | <https://github.com/hoglet67/PiTubeDirect/wiki/Level-Shifter-options> |
| Under PiTubeDirect Signal Converter | Steps down voltage from 5v to 3.3v, fits underneath to the external tube connector for use with Pi Zero only. | Kjell | Y | Tube | BBC, Master | Tube | Prebuild | Open Source | Not for Profit | <https://github.com/hoglet67/PiTubeDirect/wiki/Level-Shifter-options> |
| Internal PiTubeDirect Signal Converter | Steps down voltage from 5v to 3.3v | Kjell | Y | Internal Tube | Master | Tube | Prebuild | Open Source | Not for Profit | <https://github.com/hoglet67/PiTubeDirect/wiki/Level-Shifter-options> |
| DIY Master Quad ROM Switch | Kit based ROM MOS Switcher | Kjell | Y | ROM Slot | Master | MOS | Kit | Open Source | Not for Profit | <http://www.sundby.com/index.php/diy-bbc-master-quad-os-rom-switch/> |
| Dual Digital Joystick Adapters | Dual Digital Joystick Adapters, converts analoge port to digital | Bryce | Y | Analogue Port | ALL | User Interface | Prebuild | Other | Not for Profit | <http://www.amibay.com/showthread.php?76794-BBC-Electron-Dual-Digital-Joystick-Adapters/page11> |
| RAMagic | PC to Beeb File Transfer. RTC, 32KB NVRAM, 16K SRAM | MartinB | EOL? | ROM Slot | BBC B, Master | Expansion | Prebuild | Other | Not for Profit | <http://chrisacorns.computinghistory.org.uk/New4Old/MBarr_RAMagic.html> |
| Atom 32K RAM/ROM | Provides 32K RAM, sideways Rom and a faster 6502 Clock Speed. | Prime | Y | IC22/44 Sockets | Atom | Expansion | Prebuild | Other | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?t=5056> |
| Atom Floppy Board | WD177x Floppy Controller board | Prime | ? |  | Atom | Storage | Prebuild | Other | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=44&t=10351> |
| Atom Colour Board |  | Prime | Y | IC31 Socket | Atom | Video | Prebuild |  | Not for Profit | <https://stardot.org.uk/forums/viewtopic.php?f=44&t=17032> |
| AtoMMC2 SC Card | MMC Storage for Acorn Atoms | SirMorris |  |  | Atom | Storage |  |  |  | <http://stardot.org.uk/forums/viewtopic.php?f=8&t=2888> |
| Atom 6809 Second Processor | 6809 CoPro for the Atom | Roland |  |  | Atom | CoPro |  |  |  | <http://stardot.org.uk/forums/viewtopic.php?f=44&t=8518> |
| Atom 2015 Remake | Remake of the Atom from ground up | Roland | N | N/A | Atom | Computer | PCB Only | Open Source | Not for Profit | <http://diy.acornatom.nl/links.html> |
| Atom 2018 Remake | Remake of the Atom from ground up | Roland | Development | N/A | Atom | Computer | PCB Only | Open Source | Not for Profit | <https://stardot.org.uk/forums/viewtopic.php?f=44&t=15197> |
| Atomic ESP8266 WiFi | WiFi interfacefor the Atom | Roland | Dev | Serial Port | Atom | Network | TBC | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=44&t=8518> |
| Atom Dual Serial Port |  | Roland | Y | TBC | Atom | Serial | TBC | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=44&t=8518> |
| Electron Wifi | ESP8266 Wifi Cartridge for the Electron | Roland | Dev | Cartridge | Electron | Network| TBC | Open Source | Not for Profit | <https://stardot.org.uk/forums/viewtopic.php?f=3&t=19013&start=60#p276032> |
| Atom GODIL Video Adapter |  | Hoglet |  |  | Atom | Video |  |  |  | <http://stardot.org.uk/forums/viewtopic.php?f=44&t=7320> |
| Atom Tube Interface | Tube interface for CoPro on ATOM | Hoglet |  |  | Atom | Tube |  |  |  | <http://stardot.org.uk/forums/viewtopic.php?f=44&t=10090> |
| Atom FPGA |  | Hoglet (+AlanD) |  | Tube | Atom | CoPro |  |  |  | <http://stardot.org.uk/forums/viewtopic.php?f=44&t=6313> |
| Acorn RGBHDMI Adaptor | RGB to HDMI using a Pi Zero and a small CPLD  | Hoglet  |  Y | RGB | ALL | Video |  TBC | Open Source | Not for Profit | <https://stardot.org.uk/forums/viewtopic.php?f=3&t=14430> |
| Pi to 1MHz Interface | Raspberry Pi to 1MHz bus interface | dp11 | N | 1MHz | ALL *E | Expansion | PCB Only | Open Source | Not for Profit | <https://stardot.org.uk/forums/viewtopic.php?f=3&t=15848> |
| Beeb Blitterator | Blitter for the Beeb | dominicbeesley | In Development | CPU Socket | BBC B, Master | Expansion | PCB Only | TBC | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?p=187133#p187133> |
| FreeFi-232 v2 | Internet access on your Beeb via your serial port | danielj | Y | Serial  | BBC B, Master | Comms | TBC  | Open Source | Not for Profit | <https://stardot.org.uk/forums/viewtopic.php?f=3&t=15211> |
| Music 4000 Converters | MIDI to Music 4000 controller interface | danielj | Y | User Port | ALL *E | Audio | PreBuild | Open Source | Not for Profit | <https://www.stardot.org.uk/forums/viewtopic.php?t=18213> |
| Beeb SD Card | Beeb SD card interfaces | SirMorris | N | User Port | ALL *E | Storage | Prebuild | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=8&t=12689> |
| Electron MicroSD & SRAM Card | Electron SD card and SRAM interface | Ramtop | Y | Electron Ext Edge | Electron | Storage | Prebuild | TBC | Not for Profit | <https://stardot.org.uk/forums/viewtopic.php?t=17347> |
| Electron SD Card | Electron SD card interfaces | Ramtop | N | Electron Ext Edge | Electron | Storage | Prebuild | TBC | Not for Profit | <https://stardot.org.uk/forums/viewtopic.php?t=16840> |
| Electron MicroSD Card | Electron SD card interfaces | Ramtop | N | Electron Ext Edge | Electron | Storage | Prebuild | TBC | Not for Profit | <https://stardot.org.uk/forums/viewtopic.php?f=8&t=16481> |
| SD Interface for Plus 1 | Electron SD card interface for Plus 1 | Ramtop | Dev | Cartridge | Electron | Storage | Prebuild | TBC | Not for Profit | <https://stardot.org.uk/forums/viewtopic.php?t=18055> |
| MasterSD | Master SD card interface | Ramtop | Y | Cartridge | Master | Storage | Prebuild | TBC | Not for Profit | <https://stardot.org.uk/forums/viewtopic.php?p=396908> |
| Computer Concept PALROM redesign | 128K Software ROMs | KenLowe | Y | ROM Slot | BBC, Master | Utilities | Prebuild | TBC | Not for Profit | <https://stardot.org.uk/forums/viewtopic.php?f=3&t=17124> |
| Integra-B Remake | Modern build of the Integra-B ROM/RAM board | KenLowe | Y | ROM Slot | BBC, Master | Expansion | Prebuild | TBC | Not for Profit | <https://stardot.org.uk/forums/viewtopic.php?f=8&t=16825> |
| IntegraB V2 | Modern improvement of the Integra-B ROM/RAM board | KenLowe | In Development| ROM Slot | BBC, Master | Expansion | Prebuild | TBC | Not for Profit | <https://stardot.org.uk/forums/viewtopic.php?f=3&t=19392&p=269720#p269720> |
| User Port Extender / SD Card Reader Interface | Allows power to be drawn from user port and still be used | KenLowe | Y | User Port | BBC, Master | Expansion | Prebuild | TBC | Not for Profit | <https://stardot.org.uk/forums/viewtopic.php?f=3&t=19788#p275822> |
| New Raspberry Pi to 1MHz bus interface | Alternative level shifter using less components | KenLowe | Y | 1MHz | BBC, Master | Expansion | Prebuild | TBC | Not for Profit | <https://stardot.org.uk/forums/viewtopic.php?f=3&t=18513> |
| New Tube Level Shifter | Alternative level shifter using less components for Tube | KenLowe | Y | Tube | BBC, Master | Expansion | Prebuild | TBC | Not for Profit | <https://stardot.org.uk/forums/viewtopic.php?f=3&t=18513&start=60#p258205> |
| New SCSI Host Adaptor | Connect old SCSI HDs to the 1MHz port | KenLowe | Y | 1MHz | BBC, Master | Storage | Prebuild | TBC | Not for Profit | <https://stardot.org.uk/forums/viewtopic.php?f=3&t=18815> |
| Compact Beeb SD Card | A Compact option for Beeb MMC | Tricky et al. | Y | User Port | ALL *E | Storage | Prebuild & Design Only | Open Source | Not for Profit | <https://stardot.org.uk/forums/viewtopic.php?f=3&t=12869> |
| Atari Joystick Adaptor | BitSeeker Joystick Adaptor | BitSeeker | Y | Analogue Port | ALL | User Interface | Kit | Other | Not for Profit | <https://stardot.org.uk/forums/viewtopic.php?f=3&t=15037> |
| Atari Joystick Adaptor | Tricky Atari Joystick Adaptor | Tricky | Y | Analogue Port | ALL | User Interface | Prebuild | Other | Not for Profit | <https://stardot.org.uk/forums/viewtopic.php?f=3&t=14355> |
| SEGA Joypad Adaptor | Tricky SEGA Joypad Adaptor | Tricky | Y | Analogue Port | ALL | User Interface | Prebuild | Other | Not for Profit | <https://stardot.org.uk/forums/viewtopic.php?t=17547> |
| Music 5000 Interface | MIDI Input Interface for Music 5000 | BrokenARM | Y | User Port | ALL *E | Audio| PreBuild | Propriety | TBC | <https://stardot.org.uk/forums/viewtopic.php?f=3&t=16893> |
| E2P Remake | Remake of Electron Second Process Cart | jms2 | Y | Cartridge | Electron | CoPro | PCB Only | TBC | Not for Profit | <https://stardot.org.uk/forums/viewtopic.php?f=3&t=17069> |
| E2P 512K Expansion | Daughter board for E2P board giving extra RAM Banks | iwasjafa | Y | E2P RAM | Electron | RAM | PCB Only | TBC | Not for Profit | <https://stardot.org.uk/forums/viewtopic.php?p=261209> |
| Electron User Port Splitter | Electron Riser/Splitter & the User Port  | walkerworks | Y | Cartridge | Electron | User Port | PCB Only | TBC | Not for Profit | <http://www.bygonebytes.co.uk/Acorn_revival.html#UserPort> |
| Electron Synth Interface | A Synth/Sequencer Interface for the Electron  | walkerworks | Y | User Port | Electron | Sound | PCB Only | TBC | Not for Profit | <http://www.bygonebytes.co.uk/Electron_Sequencer.html#User_Interface> |
| TTL RGB Switch | Din Style RGB Switcher for Acorn Machines | walkerworks | Y | RGB | ALL | Video | PCB Only | TBC | Not for Profit | <http://www.bygonebytes.co.uk/Acorn_revival.html#RGB%20Switch> |
| 32-16 ROM Board | 4x16K instead of 2x32k ROM Board for the BBC Master | walkerworks | Y | ROM Slot | ALL | Expansion | PCB Only | TBC | Not for Profit | <http://www.bygonebytes.co.uk/Acorn_revival.html#Master> |
| Remake of Mertec companion | Expansion to provide missing ports on Master Compact | aotta | Y | Edge Connector | Compact| Expansion | PCB Only | TBC | Not for Profit | <https://www.stardot.org.uk/forums/viewtopic.php?t=25129> |

***

## _**Hardware System Integration Software**_

| Product | Description | Designers | Active | Connection | Compatible | Category | Built | License | Org_Type | URLs |
|---------|-------------|-----------|--------|------------|------------|----------|-------|---------|----------|------|
| PiTube | RPi Software + 5v Step down design to turn RPi into a CoPro | Hoglet/BigEd | Y | N/A | ALL *E | CoPro | Custom | Open Source | Not for Profit | <https://github.com/hoglet67/PiTubeDirect> |
| UPURS | The main software for the UPURS system. Also requires a user port serial cable and the correct USB Serial dongle. | MartinB | Y | User Port | All *E | Comms | Custom | Open Source | Not for Profit | <http://www.retro-kit.co.uk/UPURS/> |
| I2C (4 U) | Software on a ROM to glue an Acorn to I2C devices | MartinB | Y | User/Analogue Port | All *E | Comms | Custom | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=10966> |
| Flashfloppy (& Gotek) | Open Source Firmware that support Acorns Filesystems on Gotek USB Floppy Drive | Keir Fraser | Y | Disc Port | All *E | Storage | Custom | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=14994#p201604> |
| Beeblink | A file storage system (using a PC) for the BBC Micro | Tom Seddon | Y | User Port | BBC B, Master  | Storage/Comms | Custom | Open Source | Not for Profit | <https://stardot.org.uk/forums/viewtopic.php?f=53&t=15605> |
| Godil Adaptor | Godil 50 to 40 pin Adaptor | bprosman | Y | N/A | All *E | Comms | Custom | TBC | Not for Profit | <https://stardot.org.uk/forums/viewtopic.php?t=12954&start=30#p221943> |

***

## _**DIY - Relevant DIY project not covered by above**_

This section covers any recent new or remakes of DIY projects that don't have an equivalent kit/prebuilt option above. There are 1000's of other DIY projects in Mags, Books and on the Web; But only a handful of really useful ones (that have been reimagined) currently appear here.

| Product | Description | Designers | Active | Connection | Compatible | Category | Built | License | Org_Type | URLs |
|---------|-------------|-----------|--------|------------|------------|----------|-------|---------|----------|------|
| 2 or more User Ports | Need more user ports on your BBC | Mike Cook | Sweh Rework | User Port | BBC B | Expansion | Design Only | Open Source | Not for Profit | <http://sweh.spuddy.org/Beeb/2nd_User_Port/> |
| Electron Breakout Cartridge | Breakout circuit board in cartridge format for the Electron | Paul Boddie | N/A | Cartridge | Electron | Prototyping | PCB Only | Open Source | Not for Profit | <https://oshpark.com/shared_projects/648KdmKd> |
| 32k Flash Cart | Simple Flash memory cartridge | myelin | Y | Cartridge | Electron | Storage | PCB Only | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=12730> |
| USB Cart Interface | Read Electron Cartridges from a PC/MAC | myelin | Y | USB | Electron | Cart Reader | PCB Only | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=12964> |
| 3-Cart Expansion | Cartridge-only Plus 1 replacement, with one extra cartridge slots | myelin | Y | Electron Ext Edge | Electron | Expansion | PCB Only | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=13089> |
| Elk PiTubeDirect | Electron cartridge interface for PiTubeDirect | myelin | Y | Cartridge | Electron | CoPro | PCB Only | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=11325&start=720#p166961> |
| Microcontroller UPURS cable | ATMEGA32U4-based UPURS cable | myelin | Y | User Port | ALL *E | Comms | Design Only | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=13299&sid=abc4d45cc022b22e1448e6e08a48da91> |
| Updateable MegaROM for the BBC Master 128 | In-system updateable MegaROM for the BBC Master 128 | myelin | Y | ROM Slot | Master | MOS | PCB Only | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=14032> |
| FX2 Tube/Cartridge Adapter | An adapter board to make it easy to monitor your Electron, BBC Micro, or BBC Master's bus using a cheap logic analyzer | myelin | Y | Tube or Cartridge | ALL *E | Diagnostics | PCB Only | Open Source | Not for Profit | <http://myelin.nz/acorn/fx2tube> |
| Fast serial port/SD card adapter | Fast serial port/SD card adapter for the 1MHz Bus | myelin | Y | 1Mhz Bus | ALL *E | Comms | PCB Only | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=14033> |
| Electron +1ROM & SD Interface | Electron Plus 1 ROM emulation and SD interface using an STM32F4 | kernelcrash | Y | Electron Ext Edge | Electron | Expansion | Design Only | Open Source | Not for Profit | <https://stardot.org.uk/forums/viewtopic.php?f=3&t=16821> |
| EEPROM  | Original EEPROM 'ROM' design, now incorporated into many projecs in the list. | MartinB | Various | ROM Slot | All | Expansion | Design Only | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=7393&hilit=Eeprom> |
| Master UPURS Port | Plus 6522 boardinto internal Econet to turn into a user port for UPURS | Sydney | Y | Internal Econet | Master | Comms | Design Only | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=7149> |
| Extra Master User Ports | Use the Internal SCSI/Modem port  for some extra user ports | Sydney | Y | Internal SCSI/Modem | Master | Comms | Design Only | Open Source | Not for Profit | <http://www.stardot.org.uk/forums/viewtopic.php?f=3&t=9403> |
| High Density Disk 1772 Mod | High Density Disk Mod, versions for Beeb and Electron AP4 | MartinB | Y | Disc IC Socket | All | Storage | Design Only | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=1884&start=60#p14648> |
| MMBeeb | Much copied and tweaked MMC storage medium for the Beeb (and anything with a user port) | Martin Mather | Y - Stardot | User Port | ALL *E | Storage | Design Only | Open Source | Not for Profit | <http://www.stardot.org.uk/forums/viewtopic.php?f=3&t=1919&start=0> |
| MMFS Parallel | Tweaked version of MMB software/hardware to run from the Parallel Port | Hoglet/Martin Mather | Y - Stardot | Parallel Port | ALL *E | Storage | Design Only | Open Source | Not for Profit | <https://stardot.org.uk/forums/viewtopic.php?f=3&t=17827> |
| Acorn Econet Clock V2 | Acorn Econet Clock V2 remake | simoni | Y | Econet | ALL *E | Comms | Design Only | Open Source | Not for Profit | <http://www.waitingforfriday.com/?p=19> |
| Acorn Speech PHROM TMS6100 | Speech PHROM TMS6100 Remake | simoni | Y | Speech IC Sockets | BBC B | Audio | Design Only | Open Source | Not for Profit | <http://www.waitingforfriday.com/?p=30> |
| BBC Master PSU Upgrade | 60W Acorn BBC Master power supply upgrade | simoni | Y | N/A | Master | Power | Design Only | Open Source | Not for Profit | <http://www.waitingforfriday.com/?p=794> |
| Domesday AIV SCSI Board | Recreation of Acorn AIV SCSI Adapter card | simoni | Y | N/A | Master | Storage | Design Only | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=15020> |
| Acorn Econet Clock V2 | Second version of remake of Acorn Econet Clock | simoni | Y | Econet | BBC, Master | Comms | Design Only | Open Source | Not for Profit | <https://www.waitingforfriday.com/?p=19> |
| Acorn Cartridge Breakout | Acorn Master and Electron Cartridge Breakout Board | simoni | Y | Cartridge | Electron & Master | Development | Design Only | Open Source | Not for Profit | <https://stardot.org.uk/forums/viewtopic.php?f=3&t=15158> |
| 1MHz Breakout | 1MHz bus breakout board | dominicbeesley | N | 1Mhz Bus | BBC B, Master | Expansion | Part Build | TBC | Not for Profit | <https://stardot.org.uk/forums/viewtopic.php?t=16436> |
| HostFS+TCPIP | Transfer files between Beeb and PC using ethernet | dominicbeesley | Dev | 1Mhz Bus | BBC B, Master | Expansion | TBC | TBC | Not for Profit | <https://stardot.org.uk/forums/viewtopic.php?t=16565> |
| beeb816 | 65816 upgrade for BBC Micro, including lots of fast RAM, shadow mode, sideways RAM, fast CPU | BigEd/Revaldinho | Y | CPU Socket | BBC B | Expansion | Design Only | Open Source | Not for Profit | <https://github.com/BigEd/beeb816/> |
| ICE-T65/Z80/6809 | In-Circuit Emulator for the 6502, 65C02, Z80, 6809 and 6809E 8-bit processors (socketed cpu req.) | Hoglet | Y | CPU Socket | ALL | Diagnostics | Design Only | Open Source | Not for Profit | <https://github.com/hoglet67/AtomBusMon/wiki> |
| Beeb 1MHz Bus FPGA Adaptor | Allows a Xilinx FPGA Spartan 6 XC6SLX9 board to be connected to a Beeb | Hoglet | Y | 1 MHz Bus | BBC B, Master | Expansion | PCB Only | Open Source | Not for Profit | <https://github.com/hoglet67/Beeb1MHzBusFpga/wiki> |
| 6502 Code Profiling | A holistic method of diagnostics using various projects and techniques. | Hoglet, BigEd, myelin and cmorley | Y | N/A | ALL | Diagnostics | Custom | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=14885&p=199582&hilit=Dave+6502+profiler#p199582> |
| Upgrading 64k B+ to 128K | Instructions for DIYing a 128K B+ | Various | Stardot | ROM Slot | BBC B+ | Expansion | Design Only | Open Source | Not for Profit | <http://www.stardot.org.uk/forums/viewtopic.php?f=3&t=9483> |
| Cheap 32k SRAM mod for Beeb | BBC Model B DIY 32K Sideways RAM | Retroclinic ? | Stardot | N/A | BBC B | Expansion | Design Only | Open Source | Not for Profit | <http://www.retroclinic.com/acorn/swr/swr.htm> |
| Atom YARRB | Yet Another RAM/ROM Board | Roland | Stardot | ROM Slot | Atom | Expansion | Design Only | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=44&t=11373> |
| AtomSID v1.8 | AtomSID Music Expansion | Prime | Stardot |  | Atom | Audio | Design Only | Other | Not for Profit | <https://stardot.org.uk/forums/viewtopic.php?t=17572> |
| AtomSID | AtomSID Music Expansion | oss003 | Stardot |  | Atom | Audio | Design Only | Other | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=44&t=5053> |
| Master Config Backup Mod | Using supercaps instead of batteries | Various | Stardot | N/A | Master | Repair | Design Only | Open Source | Not for Profit | <http://stardot.org.uk/forums/viewtopic.php?f=3&t=13353> |
| 128K Banked Flash ROM | Electron 128K Banked Flash ROM Cartridge | davidb | Y | Cartridge | Electron | Cartridge| Design Only | Open Source | Not for Profit | <https://oshpark.com/shared_projects/wV3DlKuX> <br> <https://aisler.net/davidb/acorn-electron-128k-banked-flash-rom-cartridge/main-pcb> |
| Mini 128K Banked Flash ROM | Mini 128K Banked Flash ROM Cartridge  | davidb | Y | Cartridge | Electron | Cartridge | Design Only | Open Source | Not for Profit | <https://oshpark.com/shared_projects/D69NmI70> |
| 32K Banked Flash ROM | Electron 32K Banked Flash ROM Cartridge | davidb | Y | Cartridge | Electron | Cartridge| Design Only | Open Source | Not for Profit | URL TBC|
| Music 5000/3000 Clone | Music 5000/3000 Clone in KiCAD  | jasonl | Y | 1 MhZ Bus | BBC & Master | Audio| Design Only | Open Source | Not for Profit | <https://stardot.org.uk/forums/viewtopic.php?f=3&t=16895> |
| Music 4000 Interface | Music 4000 Keyboard(less) Interface | jasonl | Y | User Port | BBC & Master | Audio| Design Only | Open Source | Not for Profit | <https://github.com/jlbeebprojects/music4xxx-AtMega> |
| Music 2000 Clone | Music 2000 Midi Interface Clone  | jasonl | Y | Music 5000 | BBC & Master | Audio| Design Only | Open Source | Not for Profit | <https://github.com/jlbeebprojects/music2xxx> |
| ArduinoFilestore | Arduino based Econet Filestore  | garethdavisbbc | Y | Econet Port | BBC & Master | Network | Design Only | Open Source | Not for Profit | <https://github.com/stardot/ArduinoFilestore> |
| Beeb Bot Clone | Clone design of the BBC Micro Bot  | simoni | Y | Robot | BBC & Master | Other | Design Only | Open Source | Not for Profit | <https://github.com/simoninns/Beeb-Bot/wiki> |
| BBC B+ SRAM Clone| BBC B+64K Acorn expansion board  | pmul128 | Y | BBC B+ Expansion Slot | BBC B+| Expansion| Design Only | Open Source | Not for Profit | <http://www.bygonebytes.co.uk/BBCBPlus_SRAM.html> |
| Pegasus Disc Layout | New Pegasus Disc Interface PCB Layout  | davejhitchins | Y | Electron Cartridge Slot | Electron| Expansion| Design Only | Open Source | Not for Profit | <https://stardot.org.uk/forums/viewtopic.php?f=3&t=22291> |

***

## _**Accessories and Miscellaneous**_

This section covers acessories, miscellaneous or quality of life improvements that don't fit in other categories.

| Product | Description | Designers | Active |  Category | Built | License | Org_Type | URLs |
|---------|-------------|-----------|--------|----------|-------|---------|----------|------|
| Acorn UV resistant dust covers  | Keep that Acorn from going yellow | Lando Boffin | Y |  Cover | Y | Open Source | Not for Profit | <https://stardot.org.uk/forums/viewtopic.php?p=346759#p346759> |

***

## _**3D Printing - 3D Printing Projects for the Acorn 8bit**_

This section covers 3d prints that relate to 8 bit Acorn machines. Bear in mind there are other non Acorn based designs that are not listed here, e.g. Amiga Gotek Designs could be used.

| Product Description | Designer | Rafts | Support | Infill | Category | Format | License | URLs |
|---------------------|-----------|--------|------------|------------|----------|-------|---------|------|
PiTubeDirect Case | aerobaticant | N/A | Yes | 10-20% | Case | STL | Creative Commons | <https://www.thingiverse.com/thing:4131308> |
Joystick Adapter Case for Monster Joystick adapter | Tom_DD | N/A | N/A | TBC | Case | STL | Creative Commons | <https://www.thingiverse.com/thing:3320298> |
BBC Micro Joystick Adapter Case (REMIX) | Pledg | N/A | N/A | TBC | Case | STL | Creative Commons | https://www.thingiverse.com/thing:4917665 |
3.5" Drive Bay Gotek Floppy Emulator Bracket |Tom_DD | N/A | N/A | TBC | Drive Bracket | STL | Creative Commons | <https://www.thingiverse.com/thing:3387674> |
Acorn Electron Transformer Box | DigitalDunc | N/A | N/A | TBC | Case | STL | Creative Commons | <https://www.thingiverse.com/thing:3563581> |
Acorn Electron Edge Connector Cover | DigitalDunc | No | No | TBC | Cover | STL/FCStd | Creative Commons | <https://www.thingiverse.com/thing:3561356> |
Beeb "Ashtray" cover | OldVersion | No | No | 20% | Cover | STL/FCStd | Creative Commons | <https://www.thingiverse.com/thing:4256116> |
Electron/Master ROM Cartridge Case | daveejhitchins | N/A | N/A | TBC | Case | STL | TBC | <https://stardot.org.uk/forums/viewtopic.php?f=3&t=18607> |
BeebSCSI Case  | Simon Inns | No | No | 15% | Case |STL/SCAD | Creative Commons | <https://github.com/simoninns/BeebSCSI/tree/master/BeebSCSI_OpenSCAD> |
BeebSCSI "Vertical" Case Remix | Elminster | No | Optional | 15% | Case | STL | Creative Commons | <https://www.thingiverse.com/thing:4549392> |
FreeFi232 Case | Elminster | No | No | 15% | Case | STL | Creative Commons | <https://www.thingiverse.com/thing:4540983> |
BeebSID 2.4 Case | Elminster | No | No | 15% | Case | STL | Creative Commons | <https://www.thingiverse.com/thing:4545234> |
BBC Micro Coprocessor Tube Hat with Raspberry Pi 3A+ Case | Tom_DD | No | Yes | TBC | Case | STL | Creative Commons | <https://www.thingiverse.com/thing:3290517> |
Mini BBC Micro Model B | RabbitEngineering | N/A | N/A | TBC | Model | STL | Creative Commons | <https://www.thingiverse.com/thing:2465712> |
GoTek USB Floppy Emulator External Mini Caddy | Tom_DD | No | Yes | 20% | Caddy | STL | Creative Commons |  <https://www.thingiverse.com/thing:2878265> |
BBC Micro Owl Logo | chrislogic | N/A | N/A | TBC | Artifact | STL | Creative Commons | <https://www.thingiverse.com/thing:839200> |
BBC Master Cartridge Slot Cover | Commisioned by bleister | N/A | N/A | TBC | Cover | STL | TBC | <https://stardot.org.uk/forums/viewtopic.php?p=318857&sid=05ea84f8a38f5e07ff661a65e66d016d#p318857> |
BBC Type 1 KeyCaps | Piedg | No | No | TBC | Keyboard | STL | Creative Commons | <https://stardot.org.uk/forums/viewtopic.php?p=322854#p322854> <https://www.thingiverse.com/thing:4867915>|
BBC Micro Speaker Mount | Piedg | No | No | TBC | Cover | STL | Creative Commons | <https://stardot.org.uk/forums/viewtopic.php?p=325885#p325885> <https://www.thingiverse.com/thing:4890893>|
Gotek Drive Top Replacement | Piedg | No | No | TBC | Case | STL | Creative Commons | <https://stardot.org.uk/forums/viewtopic.php?p=326610#p326610> <https://www.thingiverse.com/thing:4897514>|
BBC Micro Turbo SPI Case | MrLurch | No | No | 38% | Case | STL | Creative Commons | <https://www.thingiverse.com/thing:4885518>|
 (BBC) Gotek USB floppy emulator case  | Magma/Matt | No | No | TBC | Case | STL | GNU V3.0 | <https://www.prusaprinters.org/prints/71645-gotek-usb-floppy-emulator-case>|


***

## _**Resellers**_

| Product | Description | Designers | Active | Connection | Compatible | Category | Built | License | Org_Type | URLs |
|---------|-------------|-----------|--------|------------|------------|----------|-------|---------|----------|------|
| C.J.Micros | ReSeller of various new (and old) products | N/A | N/A | N/A | N/A | N/A | Custom | Other | Commercial | <http://www.cjemicros.co.uk/> |
| RetroClinic | Many spares, refurbs and repair services | N/A | N/A | N/A | N/A | N/A | Custom | Other | Commercial | <http://www.retroclinic.com/> |

***

## _**6502 SBC Kits**_

This section covers a few of the popular 'to buy' DIY 6502 Single Board Computer Kits that are available. For a complete list of 6502 homebrew projects check out <http://6502.org/homebuilt>, <https://hackaday.io/search?term=6502>, & <https://hackaday.com/?s=6502>

| Product | Description | Designers | Active | Connection | Compatible | Category | Built | License | Org_Type | URLs |
|---------|-------------|-----------|--------|------------|------------|----------|-------|---------|----------|------|
| L-Star Plus | Software-Defined 6502 Computer | Jac Goudsmit | Y | N/A | N/A | SBC | Kit | Open Source | Not for Profit | <https://www.l-star.org/> |
| PE6502 | PE6502 single board computer | Putnam Electronics | Y | N/A | N/A | SBC | Kit | ?? | ?? | <http://putnamelectronics.com/products.html> |
| RC2014 | Simple 8 bit Z80 based modular computer | Spencer Owen | Y | N/A | N/A | SBC | Kit | Open Architecture | ?? | <https://rc2014.co.uk//> |
| RC2014 6502 Modules | Turn an RC2014 into a 6502 system | Ben Chong  | Y | N/A | N/A | SBC | Kit | Open ?? | Not for Profit | <https://www.tindie.com/stores/ancientcomputing/> |

Note the RC2014 requires the 3rd party 6502 modules by Ben Chong (or design your own), otherwise you have a Spectrum and not a BBC Micro!

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
| Cap Replacement Kit | Kit containing the Caps to be replaced in PSU on old Beebs | ctorwy31/IFEL | Y | N/A | BBC | Repair | Kit | Other | Commercial | <http://www.ebay.co.uk/usr/ctorwy31> |
| Battery Packs | Replacement Battery Pack for Master | RetroClinic | Y | N/A | Master | Repair | Prebuild | Other | Commercial | <http://www.retroclinic.com/acorn/mbattery/mbattery.htm> |
| Manuals | Various Manual Reprints for Acrorn's | RetroClinic | Y | N/A | ALL | Books | Prebuild | Other | Commercial | <http://www.retroclinic.com/acorn/manuals/manuals.htm> |
| RGB Scart Lead | RGB Scart Lead Video TV Cable | retrocomputershack | Y | RGB | ALL | Video | Prebuild | Other | Commercial | <http://www.ebay.co.uk/itm/250877464070?_trksid=p2060353.m1438.l2649&ssPageName=STRK%3AMEBIDX%3AIT> |
| Cassette Lead | Cable to connect Beeb to Cassette | retrocomputershack | Y | Cassette Port | ALL | Storage | Prebuild | Other | Commercial | <http://www.ebay.co.uk/itm/250877464070> |
| BBC Keyboard Surround | Remake of the BBC B Keyboard Surround/Facial | baz4096 | Y | N/A | BBC | Case | Prebuild | Other | TBC | <https://stardot.org.uk/forums/viewtopic.php?t=25315> |

***

</div>
