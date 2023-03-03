
## Copyright and Disclaimer
Copyright: GDWoody

This documentation describes Open Hardware and is licensed under the CERN Open Hardware License Version 2 - Strongly Reciprocal. (CERN-OHL-S)

You may redistribute and modify this documentation under the terms of the CERN OHL-S-v2 (https://ohwr.org/cern_ohl_s_v2.txt). This documentation is distributed WITHOUT ANY EXPRESS OR IMPLIED WARRANTY, INCLUDING OF MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A PARTICULAR PURPOSE. Please see the CERN OHL v2-S for applicable conditions

Under CERN OHL-S-v2, derivative work must be publicly released as defined in subsection 3.3

---
## BBB 16v2 SMD Controller DIY Instructions
Following the instructions below your boards will arrive with only the SMD components fitted. To complete them you will also need to get and fit the 'Additional Components'.  


## To order PCBs:

* Download the  [**Gerber_BBB_16v2_SMD_PCB.zip**](https://github.com/GDWoody/Pixel-Controllers/blob/main/bbb_16/jlcpcb/gerber/Gerber_BBB_16v2_SMD_PCB.zip) file in the jlcpcb\gerber folder.

* Download the  [**BOM_BBB_16v2_SMD_PCB.xlsx**](https://github.com/GDWoody/Pixel-Controllers/blob/main/bbb_16/jlcpcb/assembly/BOM_BBB_16v2_SMD_PCB.xlsx) file in the jlcpcb\assembly folder.

* Download the  [**PickAndPlace_BBB_16v2_SMD_PCB.xlsx**](https://github.com/GDWoody/Pixel-Controllers/blob/main/bbb_16/jlcpcb/assembly/PickAndPlace_BBB_16v2_SMD_PCB.xlsx) file in the jlcpcb\assembly folder.

...Goto [**jlcpcb.com**](https://jlcpcb.com), sign in or make a new account, select Instant Quote and Upload the the Gerber_BBB_16v2_SMD_PCB.zip file.

Enable the SMD service, 'BOM_BBB_16v2_SMD_PCB.xlsx' is the BOM file and 'PickAndPlace_BBB_16v2_SMD_PCB.xlsx' is the Pick and Place file.
 

## Additional Components Required

* Download the [**BOM_BBB_16v2_SMD_PCB_Other_Parts.xlsx**](https://github.com/GDWoody/Pixel-Controllers/blob/main/bbb_16/lcsc/BOM_BBB_16v2_SMD_PCB_Other_Parts.xlsx) file in the lcsc folder.

Goto [**lcsc.com**](https://lcsc.com), sign in or make a new account and select 'BOM Tool' and upload the BOM_BBB_16v2_SMD_PCB_Other_Parts.xlsx file.

---
## Additional Hardware Required

* A good quality SD card with FPP installed on it. FPP images can be found at [**https://github.com/FalconChristmas/fpp/releases**](https://github.com/FalconChristmas/fpp/releases)

* A BeagleBone Black, BeagleBone Black Wireless, BeagleBone Green, or SanCloud BeagleBone enhanced 

* A SSD1306 128x64 OLED Display

---
Be sure to fit these three parts to the **underside**.

<img width="960" alt="BBB 16v2 SMD Under" src="https://user-images.githubusercontent.com/117477621/222299693-d09da43c-f987-42a9-9be3-f5594341e06f.png">
