# FlipperZero_Stuff repo
My Flipper Zero Creations: [Guides](Guides) -- [BadUSB Payloads](BadUSB) -- [Remote UIs](Remotes)

![A FlipperZero Dolphin image](https://thumb.tildacdn.com/tild3139-3163-4538-b437-643239623131/-/resize/690x/-/format/webp/fpr_web_1.jpg)

My collection of IR, Sub-Ghz, remotes, links and other misc files related to the [Flipper Zero](https://www.flipperzero.one/) device


## Firmware
[Flipper Zero](https://github.com/flipperdevices/flipperzero-firmware) -- Official Flipper Zero firmware


### Custom  
[Momentum](https://awesome-flipper.com/firmware/momentum/)  -- Based on the Official Firmware, and includes most of the awesome features from Unleashed. It is a direct continuation of the Xtreme firmware, built by the same (and only) developers who made that project special.  
[Rouge Master](https://github.com/RogueMaster/flipperzero-firmware-wPlugins) -- Fork of Unleashed and the main Flipper Devices FW  
[Unleashed Firmware](https://github.com/DarkFlippers/unleashed-firmware) --  Based on the official firmware and is suitable for those who already know what they need and what the official firmware does not provide. Minimal changes in the interface, the emphasis is on functional and useful changes. 

### Outdated / Unmaintained  
~~[Flipper Xtreme](https://github.com/ClaraCrazy/Flipper-Xtreme) -- The goal of this Firmware is to regularly bring out amazing updates based on what the community wants, with an actual understanding of whats going on. Fixing bugs that are regularly talked about, removing unstable / broken applications (.FAP) and actually using the level system that just sits abandoned everywhere else.~~   
[Dexv](https://github.com/DXVVAY/Dexvmaster0) -- Flipper-Xtreme fork  
[SquachWare](https://github.com/skizzophrenic/SquachWare-CFW) -- Flipper Zero Official fork. Adds Custom Graphics, Community apps and misc files  

 
 
 
## Instructions / Documentation / Forums
[Flipper Zero](https://docs.flipperzero.one/)  -- Official Documentation  
[Firmware Recovery](https://docs.flipperzero.one/basics/firmware-update/firmware-recovery) -- Troubleshooting firmware problems  
[Battery Troubleshooting](https://cdn.flipperzero.one/self-repair-guide.pdf) -- Troubleshooting battery problems  
[Unofficial Community Wiki](https://flipperzero.miraheze.org/wiki/Main_Page)  
[How to Upload .bin to ESP32/ESP8266](https://github.com/SequoiaSan/Guide-How-To-Upload-bin-to-ESP8266-ESP32) -- Guide on how to upload precompiled bin files to ESP8266/ESP32  
[Using FlipperZeros GPIOs to Crack A Sentry Safe](https://github.com/DarkFlippers/unleashed-firmware/blob/dev/documentation/SentrySafe.md) -- Using Flipper zero to exploit a vulnerability to open any Sentry Safe and Master Lock electronic safe without the need for a pin code.  
[Reset Forgotten PIN](https://gist.github.com/djsime1/18d73b981249859f17aab3e2bfd2b600) - How to reset your device's PIN code  
[Flipper Zero Hacking 101](https://flipper.pingywon.com/) --  Guides with screenshots, files, and general help.  
[Flipper Zero GPIO Pinout](https://miro.com/app/board/uXjVO_LaYYI=/?moveToWidget=3458764522696947614&cot=10) -- Official GPIO pinouts.  
[Flipper Zero Disasembly Guide](https://www.ifixit.com/Guide/Flipper+Zero+Disassembly/151455) -- Difficulty: Moderate, Time: 8-15 Minutes. [Video](https://youtu.be/38pHe7M4vl8)  
[ESP32 Marauder](https://github.com/justcallmekoko/ESP32Marauder/wiki/flipper-zero) -- Portable Wifi / Bluetooth penetration testing -- [Video](https://youtu.be/_YLTpNo5xa0)  


## Plugin / Development

[Flipper Plugin Tutorial](https://github.com/DroomOne/Flipper-Plugin-Tutorial) -- Hello World!  
[ GUI editor/design builder for Flipper Zero](https://ilin.pt/stuff/fui-editor/) -- Draw any graphics and use generated code in your Flipper application  
[CLion IDE - How to setup workspace for flipper firmware development](https://krasovs.ky/2022/11/01/flipper-zero-clion.html) -- Writing and Debugging in CLion  
[Flipper Plugin Howto](https://github.com/csBlueChip/FlipperZero_plugin_howto) -- A simple plugin for the FlipperZero written as a tutorial example  
[The Hitchhiker's Guide to the Flipper Releasing](https://gist.github.com/Th3Un1q3/233fa6900d13caa95c6383e53a92bed1) -- The purpose of this document is to simplify development for Flipper Zero platform.  


## Flipper Tools & Apps
[Flipper Maker](https://flippermaker.github.io/) -- Generate Flipper Zero Files on the fly  
[Flipper File Toolbox](https://github.com/evilpete/flipper_toolbox) -- Scripts for generating Flipper data files.  
[FlipperZero CLI Tools](https://github.com/lomalkin/flipperzero-cli-tools) -- Python scripts to screenshot/stream the flipper zero screen  
[Viewing System Logs](https://gist.github.com/jaflo/50c35c46f3ecada7a18c9e5cc203a3f8) -- Dump system logs to serial CLI  
[FlipperZero-bruteforce](https://github.com/tobiabocchi/flipperzero-bruteforce) -- Generate .sub files to brute force Sub-GHz OOK.  
[T119 Brute Forcer](https://github.com/xb8/t119bruteforcer) -- Triggers Retekess T119 restaraunt pagers  
[SerialHex2FlipperZeroInfrared](https://github.com/maehw/SerialHex2FlipperZeroInfrared) - Convert IR serial messages into FlipperZero compatible IR files  
[Spectrum Analyzer](https://github.com/jolcese/flipperzero-firmware/tree/spectrum/applications/spectrum_analyzer) -- Sub-Ghz spectrum analyzer  
[OOK to .sub](https://gist.github.com/jinschoi/f39dbd82e4e3d99d32ab6a9b8dfc2f55) -- Python script to generate Flipper RAW .sub files from OOK bitstreams.  
[FZTEA](https://github.com/jon4hz/fztea) -- Connect to your flippers UI over serial or SSH  
[fzfs](https://github.com/dakhnod/fzfs) -- Flipper Zero filesystem driver  
[csv2ir](https://github.com/Spexivus/csv2ir) -- Convert IRDB CSV's into Flipper .ir format  
[dolphin_state.py](https://github.com/DroomOne/FlipperScripts) -- Reads/Writes the DolphinStoreData struct from dolphin.state files.  
[MusicXML to Flipper Music Format](https://github.com/white-gecko/musicxml2fmf0) -- This script reads a (not compressed) [MusicXML](https://en.wikipedia.org/wiki/MusicXML) file and transforms it to the Flipper Music Format  

## External Hardware: Plugins

[Add-on Modules](https://github.com/UberGuidoZ/Flipper/tree/main/GPIO) -- (ESP32, ESP8266, ESP32-CAM, ESP32-S2 WROVER, NRF24, Raspberry PI UART etc..)  
[i2c tools](https://github.com/DarkFlippers/unleashed-firmware/blob/dev/applications/external/flipper_i2ctools/README.md) -- Guide on using FlipperZeros i2c tools  
[WiFi Scanner](https://github.com/SequoiaSan/FlipperZero-WiFi-Scanner_Module#readme) -- WiFi Scanner Module for FlipperZero based on ESP8266/ESP32 (results with ESP8266 much better than with ESP32)  
[WiFi Scanner Module Flasher Tool](https://sequoiasan.github.io/FlipperZero-WiFi-Scanner_Module/) -- Sequoia has been kind enough to create a web flasher for the modules, if you want to avoid having to use the Arduino IDE.  
[ESP32 - Wifi Marauder](https://github.com/UberGuidoZ/Flipper/tree/main/Wifi_DevBoard) -- ESP32 Wi-Fi Pentest Tool  
[ESP8266 - Deauther](https://github.com/SequoiaSan/FlipperZero-Wifi-ESP8266-Deauther-Module#readme) --  WiFi Deauther Module for FlipperZero based on ESP8266. This module is full analog of DSTIKE Deauther.   
[NRF24 Plugins](https://github.com/DarkFlippers/unleashed-firmware/blob/dev/documentation/NRF24.md) -- An NRF24 driver for the Flipper Zero device. The NRF24 is a popular line of 2.4GHz radio transceivers from Nordic Semiconductors. This library is not currently complete, but functional.  
[Sentry Safe Crack](https://github.com/H4ckd4ddy/flipperzero-sentry-safe-plugin) - Flipper zero exploiting vulnerability to open any Sentry Safe and Master Lock electronic safe without any pin code.  
[FlipperZero-GPS](https://github.com/ezod/flipperzero-gps) -- Display data from a serial GPS module  

[]()
[]()
[]()
[]()


## Sub-Ghz, Remotes, IR, Files, Databases & Dumps etc..

[UberGuidoZ Playground - Large collection of files - Github](https://github.com/UberGuidoZ/Flipper) -- Large collection of files, documentation, and dumps of all kinds.  
[Awesome Flipper Zero](https://github.com/djsime1/awesome-flipperzero) -- A collection of Awesome resources for the Flipper Zero device.  
[FlipperZero-TouchTunes](https://github.com/jimilinuxguy/flipperzero-touchtunes) -- TouchTunes remote dump  
[Universal Intercom Keys](https://github.com/GlUTEN-BASH/Flipper-Starnew) -- Universal Intercom Keys  
[FlipperZero-Goodies](https://github.com/wetox-team/flipperzero-goodies) -- Intercom keys, scripts.  
[Flipper-IRDB](https://github.com/Lucaslhm/Flipper-IRDB) -- IR dumps  
[XBox IR Controller](https://github.com/gebeto/flipper-xbox-controller) -- Control XBox One via IR  
[PAGGER](https://meoker.github.io/pagger/) -- A collection of Sub-GHz files generators compatible with the Flipper Zero to handle restaurants/kiosks paging systems.  




## BadUSB Stuff

[Adding new keyboard layouts](https://github.com/dummy-decoy/flipperzero_badusb_kl) -- Keyboard layout file generator  
[UNC0V3R3D BadUSB collection](https://github.com/UNC0V3R3D/Flipper_Zero-BadUsb) -- The Ultimate Flipper Zero Badusb Collection  
[FalsePhilosophers Flipper BadUSB](https://github.com/FalsePhilosopher/badusb) -- Flipper zero community ducky payload repo.  
[Generic BadUSB Payloads](https://github.com/nocomp/Flipper_Zero_Badusb_hack5_payloads) -- Hak5 Ducky script payloads  
[USB HID Autofire](https://github.com/pbek/usb_hid_autofire) -- Send left clicks as a USB HID Device  
[Mouse Jiggler](https://github.com/MuddledBox/flipperzero-firmware/tree/Mouse_Jiggler/applications/mouse_jiggler) -- Mouse Jiggler  
[FlipperZero-USB-Keyboard](https://github.com/huuck/FlipperZeroUSBKeyboard) -- A refactor of the BT remote keyboard to work over USB.  
[BadUSB Keyboard Converter](http://helppox.com/badusbconvert.html) -- Payload converter for non-US keyboard layouts  


## Off-device & Debugging

[Official Web Interface](https://lab.flipper.net/) -- Web interface to interact with Flipper, including Paint and SUB/IR analyzer.

