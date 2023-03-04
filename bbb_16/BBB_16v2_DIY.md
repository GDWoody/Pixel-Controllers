## Copyright and Disclaimer
Copyright: GDWoody

This documentation describes Open Hardware and is licensed under the CERN Open Hardware License Version 2 - Strongly Reciprocal. (CERN-OHL-S)

You may redistribute and modify this documentation under the terms of the CERN OHL-S-v2 (https://ohwr.org/cern_ohl_s_v2.txt). This documentation is distributed WITHOUT ANY EXPRESS OR IMPLIED WARRANTY, INCLUDING OF MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A PARTICULAR PURPOSE. Please see the CERN OHL v2-S for applicable conditions

Under CERN OHL-S-v2, derivative work must be publicly released as defined in subsection 3.3

# DIY Instructions for a BBB 16v2 SMD Controller build


When you recieve your PCB's from JLCPCB they will only have the SMD parts fitted.


![SMD Only](https://github.com/GDWoody/Pixel-Controllers/blob/main/image/BBB_16v2_SMD_Parts_Only.png)


You can now complete the boards with the additional parts you ordered from LCSC.com

## The upper side

* Install the parts with the corrcet orientation 

* Make sure you install LED 2 with the correct polarity!

* I recomend to use a DIP IC Socket for the 24LC256 EEPROM


![Upper Side ](https://github.com/GDWoody/Pixel-Controllers/blob/main/image/BBB_16v2_Other_Only.png)


## The under side


![Upper Side](https://github.com/GDWoody/Pixel-Controllers/blob/main/image/BBB_16v2_SMD_Under.png)


You should now have a completed board


![Completed](https://github.com/GDWoody/Pixel-Controllers/blob/main/image/BBB_16v2_Completed.png)


---
 ## Additional Hardware Required

* A good quality SD card with FPP installed on it. FPP images can be found at [**https://github.com/FalconChristmas/fpp/releases**](https://github.com/FalconChristmas/fpp/releases)

* A BeagleBone Black, BeagleBone Black Wireless, BeagleBone Green, or SanCloud BeagleBone enhanced 

* A SSD1306 128x64 OLED Display

---