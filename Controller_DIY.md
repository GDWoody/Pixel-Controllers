## Copyright and Disclaimer
Copyright: GDWoody

This documentation describes Open Hardware and is licensed under the CERN Open Hardware License Version 2 - Strongly Reciprocal. (CERN-OHL-S)

You may redistribute and modify this documentation under the terms of the CERN OHL-S-v2 (https://ohwr.org/cern_ohl_s_v2.txt). This documentation is distributed WITHOUT ANY EXPRESS OR IMPLIED WARRANTY, INCLUDING OF MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A PARTICULAR PURPOSE. Please see the CERN OHL v2-S for applicable conditions

Under CERN OHL-S-v2, derivative work must be publicly released as defined in subsection 3.3

# DIY Instructions for all Controller Boards


### Instructions apply to all Controller Boards, the example images shown here are for the BBB 16v2.

## SMD Parts

* When you recieve your PCB's from JLCPCB they will only have the SMD parts fitted.


![SMD Only](https://github.com/GDWoody/Pixel-Controllers/blob/main/bbb_16/image/BBB_16v2_SMD_Only.png)


## Upper side DIY Parts

You can now complete the boards with the additional parts you ordered from LCSC.com


* Install the parts with the correct orientation 

* Make sure LED 2 is installed with the correct polarity!

* I recomend to use a DIP IC Socket for the 24LC256 EEPROM


![Upper Side ](https://github.com/GDWoody/Pixel-Controllers/blob/main/bbb_16/image/BBB_16v2_Other_Only.png)


## Under side DIY Parts

* Two 46 pin headers

* One 6 pin right angle header 


![Upper Side](https://github.com/GDWoody/Pixel-Controllers/blob/main/bbb_16/image/BBB_16v2_SMD_Under.png)


## You should now have a completed board


![Completed](https://github.com/GDWoody/Pixel-Controllers/blob/main/bbb_16/image/BBB_16v2_Completed.png)


## SSD1306 128x64 OLED Display

* Note: Some SSD1306 OLED displays have different VCC and GND pin layout

* Before powering up use the 'SSD1306 Select Switch' to set Pin1 and Pin2 on the SSD1306 128x64 header for your OLED display!


![SSD1306](https://github.com/GDWoody/Pixel-Controllers/blob/main/bbb_16/image/BBB_16v2_SMD.png)


 ## EEPROM

 * [EEPROM Download](https://github.com/GDWoody/Pixel-Controllers/blob/main/eeprom/BBB16v2-221118135219-eeprom.bin)

 * [Scott's EEPROM lashing instructions](https://github.com/computergeek1507/PB_16/blob/master/Flashing_EEPROM.md)

---
## Controller Interactive Bom's

* ## [**BBB 16v2 Push Fit iBom**](https://gdwoody.github.io/bbb_16_push/BBB_16v2_SMD_Push_ibom.html{:target="_blank"})

 ## Additional Hardware Required

* A good quality SD card with FPP installed on it. FPP images can be found at [**https://github.com/FalconChristmas/fpp/releases**](https://github.com/FalconChristmas/fpp/releases)

* A BeagleBone Black, BeagleBone Black Wireless, BeagleBone Green, or SanCloud BeagleBone enhanced 

* A SSD1306 128x64 OLED Display

---