## Copyright and Disclaimer
Copyright: GDWoody

This documentation describes Open Hardware and is licensed under the CERN Open Hardware License Version 2 - Strongly Reciprocal. (CERN-OHL-S)

You may redistribute and modify this documentation under the terms of the CERN OHL-S-v2 (https://ohwr.org/cern_ohl_s_v2.txt). This documentation is distributed WITHOUT ANY EXPRESS OR IMPLIED WARRANTY, INCLUDING OF MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A PARTICULAR PURPOSE. Please see the CERN OHL v2-S for applicable conditions

Under CERN OHL-S-v2, derivative work must be publicly released as defined in subsection 3.3

# BBB 16v2 SMD Controller

Customised Pixel Controller based on Scott Hanson's BBB 16v2 SMD controller [https://github.com/computergeek1507/PB_16](https://github.com/computergeek1507/PB_16/blob/master/BBB_16_SMD/README.md). The board is largely the same as Scott's, but with a few modifications.

Note: The BBB 16v2 SMD Controller requires a 5v DC only! Connecting any other size power source will damage the board. The board does not supply power outputs for pixels, only pixel data and ground connections.


# Features

* 16 local ports with 2 pin Phoenix style connectors

* 1 Differential RJ45 port

* 2 DMX Serial ports, DMX 1 can be selected as a DMX or LOR port

* 2 GPIO header

* 24 Pin expansion header

* SSD1306 128x64 OLED header

* Onboard 24LC256 eeprom

* Reverse Voltage Protection LED

* A RTC DS3231 AT24C32 can be connected to the board by either the top header RTC 1 or the under board header RTC 2

* Onboard Resettable Fuse

* Screw Terminal Block with 4 Additional GND connections

---
## [**Interactive Bom**](https://gdwoody.github.io/bbb_16/BOM_BBB_16v2_SMD_ibom.html)

## [**Order PCB's from JLCPCB**](jlcpcb/)


## [**Download Gerber file**](https://github.com/GDWoody/Pixel-Controllers/blob/main/bbb_16/jlcpcb/gerber/Gerber_BBB_16v2_SMD_PCB.zip)


## [**Download SMD Parts Bom**](https://github.com/GDWoody/Pixel-Controllers/blob/main/bbb_16/jlcpcb/assembly/BOM_BBB_16v2_SMD_PCB.xlsx)


## [**Download Additional Parts Bom**](https://github.com/GDWoody/Pixel-Controllers/blob/main/bbb_16/lcsc/BOM_BBB_16v2_SMD_PCB_Other_Parts.xlsx)


## [**DIY Instructions**](https://github.com/GDWoody/Pixel-Controllers/blob/main/bbb_16/BBB_16v2_DIY.md)

 <img width="1151" alt="BBB_16v2_SMD" src="https://user-images.githubusercontent.com/117477621/222923293-f8d01a0a-f948-42b5-8b08-5e0a1fc355fc.png">

