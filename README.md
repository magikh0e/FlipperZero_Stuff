# FlipperZero_Stuff repo

[![GitHub stars](https://img.shields.io/github/stars/magikh0e/FlipperZero_Stuff?style=flat-square&color=FF8200)](https://github.com/magikh0e/FlipperZero_Stuff/stargazers) ![GitHub last commit](https://img.shields.io/github/last-commit/magikh0e/FlipperZero_Stuff?style=flat-square) ![Flipper Zero](https://img.shields.io/badge/for-Flipper%20Zero-FF8200?style=flat-square)

![A FlipperZero Dolphin image](https://thumb.tildacdn.com/tild3139-3163-4538-b437-643239623131/-/resize/690x/-/format/webp/fpr_web_1.jpg)

My collection of IR, Sub-Ghz, remotes, links, and other files for the [Flipper Zero](https://flipper.net/), plus my own [Guides](Guides), [BadUSB Payloads](BadUSB), and [Remote UIs](Remotes).

## Contents
- [In This Repo (my files)](#in-this-repo-my-files)
- [Firmware](#firmware)
- [Instructions / Documentation / Forums](#instructions--documentation--forums)
- [Plugin / Development](#plugin--development)
- [Flipper Tools & Apps](#flipper-tools--apps)
- [Sub-Ghz, Remotes, IR, Files, Databases & Dumps](#sub-ghz-remotes-ir-files-databases--dumps)
- [NFC & RFID](#nfc--rfid)
- [BadUSB Stuff](#badusb-stuff)
- [External Hardware: Plugins](#external-hardware-plugins)
- [Off-device & Debugging](#off-device--debugging)


## In This Repo (my files)
Original files I've made, as opposed to the curated outbound links further down.

### [Guides](Guides)
- **[Creating a Custom Infrared Remote UI](Guides/Infrared%20Remote%20UI.md)** -- walkthrough for building a custom IR remote interface on the device (`Apps -> Tools -> IR Remote`).

### [BadUSB Payloads](BadUSB)
- **[Send a message via Signal Desktop](BadUSB)** -- sends a message from the target PC via Signal Desktop, if installed.
- **[Disable Firewall & Create Admin User](BadUSB)** -- disables the local firewall and adds an admin user.
- **[Information Stealer](BadUSB)** -- gathers host / user info, installed programs & updates, wireless profiles, a screen capture, the Firefox profile, and SAM hives; exfils via email.

> ⚠️ BadUSB payloads are for authorized testing and education only. Don't run them on devices you don't own or have permission to test.

### [Remotes](Remotes)
- **[Custom Infrared Remote UI](Remotes/Infrared/remote)** -- example custom remote UI built from a captured IR controller (Arizer XQ2).


## Firmware
[Flipper Zero](https://github.com/flipperdevices/flipperzero-firmware) -- Official Flipper Zero firmware


### Custom  
[Momentum](https://github.com/Next-Flip/Momentum-Firmware) -- Based on the Official Firmware, and includes most of the awesome features from Unleashed. It is a direct continuation of the Xtreme firmware, built by the same (and only) developers who made that project special.  
[Rogue Master](https://github.com/RogueMaster/flipperzero-firmware-wPlugins) -- Fork of Unleashed and the main Flipper Devices FW  
[Unleashed Firmware](https://github.com/DarkFlippers/unleashed-firmware) -- Based on the official firmware and is suitable for those who already know what they need and what the official firmware does not provide. Minimal changes in the interface, the emphasis is on functional and useful changes. 

### Outdated / Unmaintained  
No longer maintained; Xtreme lives on as Momentum (above). Kept here for reference only.  
~~[Flipper Xtreme](https://github.com/ClaraCrazy/Flipper-Xtreme) -- The goal of this Firmware is to regularly bring out amazing updates based on what the community wants, with an actual understanding of what is going on. Fixing bugs that are regularly talked about, removing unstable / broken applications (.FAP) and actually using the level system that just sits abandoned everywhere else.~~   
~~[SquachWare](https://github.com/skizzophrenic/SquachWare-CFW) -- Flipper Zero Official fork. Adds Custom Graphics, Community apps and misc files~~  

### Companion / Alternative Devices
Firmware for separate ESP32 / CC1101 gadgets that pair with or stand in for the Flipper. These do NOT flash onto the Flipper Zero itself.

[Bruce](https://github.com/BruceDevices/firmware) -- Offensive-security firmware for ESP32 devices (M5Stack, Cardputer, etc.): WiFi, BLE, RF, RFID, and IR tooling; reads/writes Flipper-compatible files  
[Willy Firmware](https://github.com/h-RAT/Willy_Firmware_V2_ESP32_Flipper_Zero_Alternative) -- Flipper-style firmware for an ESP32 T-Display-S3 + CC1101 with touchscreen; uses Flipper-compatible Sub-GHz files  
[EvilCrowRF Custom Firmware](https://github.com/h-RAT/EvilCrowRF_Custom_Firmware_CC1101_FlipperZero) -- Alternative firmware for the Evil Crow RF (dual CC1101) that reads/writes Flipper .sub files  


## Instructions / Documentation / Forums
[Flipper Zero](https://docs.flipper.net/zero) -- Official Documentation  
[Firmware Recovery](https://docs.flipper.net/zero/basics/firmware-update/firmware-recovery) -- Troubleshooting firmware problems  
[Battery Troubleshooting](https://cdn.flipperzero.one/self-repair-guide.pdf) -- Troubleshooting battery problems  
[Awesome Flipper Zero](https://awesome-flipper.com/) -- Community-curated hub of firmware, apps, guides, and resources  
[Awesome Flipper Zero (djsime1)](https://github.com/djsime1/awesome-flipperzero) -- A collection of Awesome resources for the Flipper Zero device  
[How to Upload .bin to ESP32/ESP8266](https://github.com/SequoiaSan/Guide-How-To-Upload-bin-to-ESP8266-ESP32) -- Guide on how to upload precompiled bin files to ESP8266/ESP32  
[Using FlipperZero's GPIOs to Crack A Sentry Safe](https://github.com/DarkFlippers/unleashed-firmware/blob/dev/documentation/SentrySafe.md) -- Using Flipper zero to exploit a vulnerability to open any Sentry Safe and Master Lock electronic safe without the need for a pin code.  
[Reset Forgotten PIN](https://gist.github.com/djsime1/18d73b981249859f17aab3e2bfd2b600) -- How to reset your device's PIN code  
[Flipper Zero Hacking 101](https://flipper.pingywon.com/) -- Guides with screenshots, files, and general help.  
[Flipper Zero GPIO Pinout](https://miro.com/app/board/uXjVO_LaYYI=/?moveToWidget=3458764522696947614&cot=10) -- Official GPIO pinouts.  
[Flipper Zero Disassembly Guide](https://www.ifixit.com/Teardown/Flipper+Zero+Teardown/151455) -- Difficulty: Moderate, Time: 8-15 Minutes. [Video](https://youtu.be/38pHe7M4vl8)  
[r/flipperzero](https://reddit.com/r/flipperzero) -- The main community subreddit  
[Official Flipper Discord](https://flipperzero.one/discord) -- Official community chat: firmware help, app dev, showcases  
[Flipper Forum](https://forum.flipper.net) -- Official Flipper Devices support forum  
[Flipper Community Wiki](https://flipper.wiki) -- Community-run wiki: guides, hardware, and how-tos  


## Plugin / Development

[Official Development Docs](https://docs.flipper.net/development) -- Flipper's official firmware and app development documentation  
[ufbt](https://github.com/flipperdevices/flipperzero-ufbt) -- Official micro Flipper Build Tool: build, debug, and flash apps with a prebuilt SDK (`pip install ufbt`), plus VS Code config  
[Flipper Application Catalog (submit apps)](https://github.com/flipperdevices/flipper-application-catalog) -- Repo for submitting your app to the official on-device catalog  
[Flipper Plugin Tutorial](https://github.com/DroomOne/Flipper-Plugin-Tutorial) -- Hello World!  
[ GUI editor/design builder for Flipper Zero](https://ilin.pt/stuff/fui-editor/) -- Draw any graphics and use generated code in your Flipper application  
[CLion IDE - How to setup workspace for flipper firmware development](https://krasovs.ky/2022/11/01/flipper-zero-clion.html) -- Writing and Debugging in CLion  
[Flipper Plugin Howto](https://github.com/csBlueChip/FlipperZero_plugin_howto) -- A simple plugin for the FlipperZero written as a tutorial example  
[The Hitchhiker's Guide to the Flipper Releasing](https://gist.github.com/Th3Un1q3/233fa6900d13caa95c6383e53a92bed1) -- The purpose of this document is to simplify development for Flipper Zero platform.  


## Flipper Tools & Apps
[all-the-plugins](https://github.com/xMasterX/all-the-plugins) -- Large community app pack: hundreds of extra .fap apps not in the official catalog  

### Sub-GHz & IR tools
[FlipperZero-bruteforce](https://github.com/tobiabocchi/flipperzero-bruteforce) -- Generate .sub files to brute force Sub-GHz OOK.  
[T119 Brute Forcer](https://github.com/xb8/t119bruteforcer) -- Triggers Retekess T119 restaurant pagers  
[Spectrum Analyzer](https://github.com/jolcese/flipperzero-firmware/tree/spectrum/applications/spectrum_analyzer) -- Sub-Ghz spectrum analyzer  
[OOK to .sub](https://gist.github.com/jinschoi/f39dbd82e4e3d99d32ab6a9b8dfc2f55) -- Python script to generate Flipper RAW .sub files from OOK bitstreams.  
[SerialHex2FlipperZeroInfrared](https://github.com/maehw/SerialHex2FlipperZeroInfrared) -- Convert IR serial messages into FlipperZero compatible IR files  
[csv2ir](https://github.com/Spexivus/csv2ir) -- Convert IRDB CSVs into Flipper .ir format  

### File & data tools
[Flipper Maker](https://flippermaker.github.io/) -- Generate Flipper Zero Files on the fly  
[Flipper File Toolbox](https://github.com/evilpete/flipper_toolbox) -- Scripts for generating Flipper data files.  
[dolphin_state.py](https://github.com/DroomOne/FlipperScripts) -- Reads/Writes the DolphinStoreData struct from dolphin.state files.  
[MusicXML to Flipper Music Format](https://github.com/white-gecko/musicxml2fmf) -- This script reads a (not compressed) [MusicXML](https://en.wikipedia.org/wiki/MusicXML) file and transforms it to the Flipper Music Format  


## Sub-Ghz, Remotes, IR, Files, Databases & Dumps

[UberGuidoZ Playground - Large collection of files - Github](https://github.com/UberGuidoZ/Flipper) -- Large collection of files, documentation, and dumps of all kinds.  
[FlipperZero-TouchTunes](https://github.com/jimilinuxguy/flipperzero-touchtunes) -- TouchTunes jukebox remote dump  
[Universal Intercom Keys](https://github.com/glutesha/Flipper-Starnew) -- Sub-GHz key dumps for common building intercom systems  
[FlipperZero-Goodies](https://github.com/wetox-team/flipperzero-goodies) -- Intercom key dumps and helper scripts  
[Flipper-IRDB](https://github.com/Lucaslhm/Flipper-IRDB) -- Large community IR remote database (TVs, ACs, audio, projectors, and more)  
[XBox IR Controller](https://github.com/gebeto/flipper-xbox-controller) -- Control XBox One via IR  
[PAGGER](https://meoker.github.io/pagger/) -- A collection of Sub-GHz files generators compatible with the Flipper Zero to handle restaurants/kiosks paging systems.  


## NFC & RFID

[FlipperMfkey](https://github.com/noproto/FlipperMfkey) -- On-device MFKey32: crack MIFARE Classic 1K/4K keys from captured reader nonces; cracked keys land in your user dictionary automatically  
[FlipperNested](https://github.com/AloneLiberty/FlipperNested) -- Recover MIFARE Classic keys with a Nested attack when you already have at least one key  
[Extended MIFARE Classic Dictionary](https://github.com/UberGuidoZ/Flipper/tree/main/NFC/mf_classic_dict) -- Greatly expanded mf_classic_dict (Proxmark3 Iceman / RFIDResearchGroup keys); drop it under nfc/assets for bigger dictionary attacks  
[Multi_Fuzzer](https://github.com/DarkFlippers/Multi_Fuzzer) -- Combined iButton and 125 kHz RFID reader fuzzer  


## BadUSB Stuff

[I-Am-Jakoby Flipper BadUSB](https://github.com/I-Am-Jakoby/Flipper-Zero-BadUSB) -- Popular, nearly plug-and-play payload collection: WiFi/IP grabbers, recon, browser data, keylogger, and more  
[Official Hak5 Ducky Payloads](https://github.com/hak5/usbrubberducky-payloads) -- Hak5's official USB Rubber Ducky payload library; DuckyScript runs on the Flipper as-is  
[dsymbol ducky-payloads](https://github.com/dsymbol/ducky-payloads) -- Cross-platform payloads for Rubber Ducky, Flipper Zero BadUSB, and Pico-Ducky  
[BadBT](https://github.com/AGO061/BadBT) -- Run BadUSB (DuckyScript) payloads over Bluetooth by emulating a BT keyboard (needs custom firmware)  
[Hak5 Payload Studio](https://payloadstudio.hak5.org) -- Browser IDE for writing and validating DuckyScript payloads  
[Official Bad USB Docs](https://docs.flipper.net/zero/bad-usb) -- Flipper's Bad USB documentation and DuckyScript reference  
[Adding new keyboard layouts](https://github.com/dummy-decoy/flipperzero_badusb_kl) -- Keyboard layout file generator  
[FalsePhilosophers Flipper BadUSB](https://github.com/FalsePhilosopher/badusb) -- Flipper zero community ducky payload repo.  
[Generic BadUSB Payloads](https://github.com/nocomp/Flipper_Zero_Badusb_hack5_payloads) -- Hak5 Ducky script payloads  
[USB HID Autofire](https://github.com/pbek/usb_hid_autofire) -- Send left clicks as a USB HID Device  
[Mouse Jiggler](https://github.com/MuddledBox/flipperzero-firmware/tree/Mouse_Jiggler/applications/mouse_jiggler) -- Keeps a computer awake by nudging the mouse over USB HID  
[FlipperZero-USB-Keyboard](https://github.com/huuck/FlipperZeroUSBKeyboard) -- A refactor of the BT remote keyboard to work over USB.  
[BadUSB Keyboard Converter](https://helppox.com/badusbconvert.html) -- Payload converter for non-US keyboard layouts  


## External Hardware: Plugins

[Add-on Modules](https://github.com/UberGuidoZ/Flipper/tree/main/GPIO) -- (ESP32, ESP8266, ESP32-CAM, ESP32-S2 WROVER, NRF24, Raspberry PI UART etc..)  
[ESP32 Marauder](https://github.com/justcallmekoko/ESP32Marauder/wiki/flipper-zero) -- Portable Wifi / Bluetooth penetration testing -- [Video](https://youtu.be/_YLTpNo5xa0)  
[ESP32 - Wifi Marauder](https://github.com/UberGuidoZ/Flipper/tree/main/Wifi_DevBoard) -- ESP32 Wi-Fi Pentest Tool  
[Flipper WiFi Marauder companion app](https://github.com/0xchocolate/flipperzero-wifi-marauder) -- On-Flipper .fap that drives the ESP32 Marauder firmware (WiFi/BLE attacks, wardriving with a GPS module)  
[FZEasyMarauderFlash](https://github.com/SkeletonMan03/FZEasyMarauderFlash) -- One-click flasher for the ESP32 WiFi dev board (Marauder or BlackMagic), no Arduino IDE needed  
[WiFi Scanner](https://github.com/SequoiaSan/FlipperZero-WiFi-Scanner_Module#readme) -- WiFi Scanner Module for FlipperZero based on ESP8266/ESP32 (results with ESP8266 much better than with ESP32)  
[WiFi Scanner Module Flasher Tool](https://sequoiasan.github.io/FlipperZero-WiFi-Scanner_Module/) -- Sequoia has been kind enough to create a web flasher for the modules, if you want to avoid having to use the Arduino IDE.  
[ESP8266 - Deauther](https://github.com/SequoiaSan/FlipperZero-Wifi-ESP8266-Deauther-Module#readme) -- WiFi Deauther Module for FlipperZero based on ESP8266. This module is full analog of DSTIKE Deauther.  
[NRF24 Plugins](https://github.com/DarkFlippers/unleashed-firmware/blob/dev/documentation/NRF24.md) -- An NRF24 driver for the Flipper Zero device. The NRF24 is a popular line of 2.4GHz radio transceivers from Nordic Semiconductors. This library is not currently complete, but functional.  
[NRF24: Mousejack & Sniffer](https://github.com/mothball187/flipperzero-nrf24) -- The apps behind the NRF24 driver: sniff NRF24 addresses and run mousejack keystroke-injection attacks  
[nrf24tool](https://github.com/OuinOuin74/nrf24tool) -- Enhanced NRF24 toolkit (expanded libnrf24) for the Flipper  
[i2c tools](https://github.com/xMasterX/all-the-plugins/blob/dev/base_pack/flipper_i2ctools/README.md) -- Guide on using FlipperZero's i2c tools  
[Unitemp](https://github.com/quen0n/unitemp-flipperzero) -- Read DHT11/22, DS18B20, BMP280, HTU21 and more temperature/humidity/pressure sensors over GPIO, i2c, or 1-Wire  
[FlipperZero-GPS](https://github.com/ezod/flipperzero-gps) -- Display data from a serial GPS module  
[Video Game Module (Official)](https://github.com/flipperdevices/video-game-module) -- Official Raspberry Pi RP2040 add-on module; open-source firmware and schematics, also usable as a Pico-like RP2040 board  
[Video Game Module Docs](https://docs.flipper.net/zero/video-game-module) -- Setup, official/custom firmware flashing, and development reference  
[Sentry Safe Crack](https://github.com/H4ckd4ddy/flipperzero-sentry-safe-plugin) -- Flipper zero exploiting vulnerability to open any Sentry Safe and Master Lock electronic safe without any pin code.  


## Off-device & Debugging

[Official Web Interface](https://lab.flipper.net/) -- Web interface to interact with Flipper, including Paint and SUB/IR analyzer.  
[qFlipper](https://flipper.net/pages/downloads) -- Official cross-platform desktop app: firmware updates, file manager, and screen streaming.  
[Flipper Mobile App (Android)](https://github.com/flipperdevices/Flipper-Android-App) -- Official Android companion app (Play Store, F-Droid, or direct)  
[Flipper Mobile App (iOS)](https://github.com/flipperdevices/Flipper-iOS-App) -- Official iOS companion app  
[Flipper Apps Catalog](https://lab.flipper.net/apps) -- Official catalog of installable Flipper apps (.fap), browsable and installable over the web.  
[FlipperZero CLI Tools](https://github.com/lomalkin/flipperzero-cli-tools) -- Python scripts to screenshot/stream the flipper zero screen  
[FZTEA](https://github.com/jon4hz/fztea) -- Connect to your flippers UI over serial or SSH  
[fzfs](https://github.com/dakhnod/fzfs) -- Flipper Zero filesystem driver  
[Viewing System Logs](https://gist.github.com/jaflo/50c35c46f3ecada7a18c9e5cc203a3f8) -- Dump system logs to serial CLI  


## Support

This is a free, curated collection shared for the Flipper community. If it has saved you some digging, a beer is always appreciated and helps keep it maintained.

<a href="https://buymeacoffee.com/magikh0e"><img src="https://img.buymeacoffee.com/button-api/?text=Buy%20me%20a%20beer&emoji=%F0%9F%8D%BA&slug=magikh0e&button_colour=FFDD00&font_colour=000000&font_family=Cookie&outline_colour=000000&coffee_colour=ffffff" alt="Buy me a beer" height="42"></a>

## License
Link collection -- all linked projects and resources belong to their respective authors. Original files in this repo (Guides, BadUSB payloads, Remote UIs) are provided as-is for educational use.
