

# Copyright and Disclaimer
Copyright: GDWoody

This documentation describes Open Hardware and is licensed under the CERN Open Hardware License Version 2 - Strongly Reciprocal. (CERN-OHL-S)

You may redistribute and modify this documentation under the terms of the CERN OHL-S-v2 (https://ohwr.org/cern_ohl_s_v2.txt). This documentation is distributed WITHOUT ANY EXPRESS OR IMPLIED WARRANTY, INCLUDING OF MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A PARTICULAR PURPOSE. Please see the CERN OHL v2-S for applicable conditions

Under CERN OHL-S-v2, derivative work must be publicly released as defined in subsection 3.3

---
# Controllers & Expansion Boards

These Pixel Controllers are based on Scott Hanson's BBB 16v2 SMD controller [https://github.com/computergeek1507/PB_16](https://github.com/computergeek1507/PB_16/blob/master/BBB_16_SMD/README.md) with a few modifications and are designed as open source DIY hobbyist controllers. They are **not** intended to be sold as commercial products. All controller boards are 5v DC only and do not supply power for Pixel Strings, only data and ground. They all run FPP to drive the pixel and serial ports. Connection to a network/internet is by ethernet also WIFI and audio are supported via the USB port. All design files are open source and available on github, EasyEDA was used to create the designs.

Disclaimer: If you wish to build your own boards, please do so at your own risk. I use [jlcpcb.com](https://jlcpcb.com) for PCB manufacture and [lcsc.co](https://www.lcsc.com/) for parts, all the nessasary files are in the jlcpcb folders.


## [**BBB 16v2 SMD**](bbb_16/)


![Image of BBB 16v2 SMD
Out](https://github.com/GDWoody/Pixel-Controllers/blob/main/bbb_16/image/BBB_16v2_SMD.png)

---
## [**Ordering PCB's from JLCPCB Instructions**](https://github.com/GDWoody/Pixel-Controllers/blob/main/JLC_PCB.md)

## [**Ordering Parts from LCSC Instructions**](https://github.com/GDWoody/Pixel-Controllers/blob/main/LCSC.md)

---
# Variants
I created different variants of the BB 16v2 SMD, to give more options for specific needs.


* [**BBB 16v2 SMD Push Fit**](bbb_16_push/) - 16 local ports with push fit connectors, 1 Differential port and 2 serial ports.


* [**BBB 8v1 SMD**](bbb_8/) - 8 local ports, 3 Differnetial ports and 2 serial ports.


* [**BBB 8v1 SMD Push Fit**](bbb_8_push/) - 8 local ports with push fit connectors, 3 Differential ports and 2 serial ports.


* [**BBB 4v1 SMD**](bbb_4/) - 4 local ports, 4 Differential ports and 2 serial ports.


* [**BBB 4v1 SMD Push Fit**](bbb_4_push/) - 4 local ports with push fit connectors, 4 Differential ports and 2 serial ports


* [**BBB All Diff v1**](bbb_all_diff/) - No local ports, 5 Differential ports and 2 serial ports.


---
# Expansion Boards
 All Expansion Boards are compatable with my BBB boards and variants.


* [**Differential Expansion**](bbb_diff_expansion/) - 4 Port Remote Differential Expansion (24 pins).


* [**16 Port Expansion**](bbb_16_expansion/) - 16 Port Local Expansion.

---
# Differential Receiver Boards
 All Receiver Boards are compatable with my BBB boards and variants.


* [**Differential Receivers**](diff_receiver/) - 4 Port Remote Differential Receivers.

---
## Additional Hardware Required

* A good quality SD card with FPP installed on it

* FPP images can be found at [**https://github.com/FalconChristmas/fpp/releases**](https://github.com/FalconChristmas/fpp/releases)

* A BeagleBone Black, BeagleBone Black Wireless, BeagleBone Green, or SanCloud BeagleBone enhanced 

* A SSD1306 128x64 OLED Display


---
# WLED Controllers

* [**WLED Controller with 4 output ports**](wled/)

* [**WLED Controller with 1 Differential port**](wled_d/)

---
* [**View All Boardss**](image/)
