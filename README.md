# RVPC_TinyBasic
Simple BASIC interpreter for [Olimex RVPC (1€ PC)](https://www.olimex.com/Products/Retro-Computers/RVPC/open-source-hardware)

## Compiling
Install [Visual Studio Code](https://visualstudio.microsoft.com/downloads/) for your platform, add the [PlatformIO](https://platformio.org/install/ide?install=vscode). Download or sync this repository and open it using vscode, then compile it clicking on the "check" symbol on the lower left status bar.

There are plenty of tutorial to use vscode/platformio. If you don't feel inclined to compile, you can download the binary from the release section.

## Flashing
The official way to flash and debug software on ch32vxxx series of MCUs is using the [WCH-LinkE USB programmer](https://www.wch-ic.com/products/WCH-Link.html). Only the "E" model works.
There are also at least two other ways at moment, to flash: using a raspi pico or an ESP32 as a programmer. This is the raspi pico implementation: [picorvd](https://github.com/aappleby/picorvd).

If you own a Flipper Zero is possible to flash ch32Vxxx MCUs using this useful tool: [wch_swio_flasher](https://github.com/sukvojte/wch_swio_flasher)

## Credits
This project is heavly based on [TinyBasic](https://github.com/shippoiincho/TinyBASIC) by @shippoiincho but was made possible thanks this proposed [pull request](https://github.com/OLIMEX/RVPC/pull/3/commits/d1d416dbf3e879105c517889b9d8018fe1263e56) by @jrudolph


![RVPC_TinyBasic](https://github.com/user-attachments/assets/54f6ad24-80e6-4b03-b8c9-9e75a055fe56)
