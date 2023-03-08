## Copyright and Disclaimer
Copyright: GDWoody

This documentation describes Open Hardware and is licensed under the CERN Open Hardware License Version 2 - Strongly Reciprocal. (CERN-OHL-S)

You may redistribute and modify this documentation under the terms of the CERN OHL-S-v2 (https://ohwr.org/cern_ohl_s_v2.txt). This documentation is distributed WITHOUT ANY EXPRESS OR IMPLIED WARRANTY, INCLUDING OF MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A PARTICULAR PURPOSE. Please see the CERN OHL v2-S for applicable conditions

Under CERN OHL-S-v2, derivative work must be publicly released as defined in subsection 3.3

---
## JLCPCB PCB's and LCSC Part Ordering
Following the instructions below your boards will arrive with only the SMD components fitted. To complete them you will also need to get and fit the 'Additional Components'.  


## To order PCB's From JLCPCB:

* Select the board you wish to make

* Download the  **Gerber_xxxxxxx.zip** from the jlcpcb\gerber folder.

* Download the  **BOM_xxxxxxx.xlsx** file in the jlcpcb\assembly folder.

* Download the **CPL_BBB_xxxxxxx.xlsx** file in the jlcpcb\assembly folder.

*  Goto [**jlcpcb.com**](https://jlcpcb.com), sign in or make a new account, select Instant Quote and Upload the the Gerber_xxxxxx.zip file.

* The default settings should be ok. However you can choose 'PCB Color' and change 'Remove Order Number' to 'Specify a location'.

* Enable the SMD service, 'BOM_xxxxxxx.xlsx' is the BOM file and 'CPL_xxxxxxx.xlsx' is the CPL file.

* [**See here for detailed PCB ordering instructions for JLCPCB**](https://github.com/GDWoody/Pixel-Controllers/blob/main/JLC_PCB.md)


## To order Additional Required Parts from LCSC

* Download the **BOM_xxxxxxx_Other_Parts.xlsx** file in the lcsc folder.

* Goto [**lcsc.com**](https://lcsc.com), sign in or make a new account and select 'BOM Tool' and upload the BOM_xxxxxxx_Other_Parts.xlsx file.

* [**See here for detailed Parts ordering instructions for LCSC**](https://github.com/GDWoody/Pixel-Controllers/blob/main/LCSC.md)


## [**Controller DIY Build Instructions**](https://github.com/GDWoody/Pixel-Controllers/blob/main/Controller_DIY.md)


## [**Interactive Bom**](https://gdwoody.github.io/bbb_16/BOM_BBB_16v2_SMD_ibom.html)

---
## Additional Hardware Required

* A good quality SD card with FPP installed on it. FPP images can be found at [**https://github.com/FalconChristmas/fpp/releases**](https://github.com/FalconChristmas/fpp/releases)

* A BeagleBone Black, BeagleBone Black Wireless, BeagleBone Green, or SanCloud BeagleBone enhanced 

* A SSD1306 128x64 OLED Display

---
Be sure to fit these three parts to the **underside**.
