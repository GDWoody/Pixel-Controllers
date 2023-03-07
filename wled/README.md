## Copyright and Disclaimer
Copyright: GDWoody

This documentation describes Open Hardware and is licensed under the CERN Open Hardware License Version 2 - Strongly Reciprocal. (CERN-OHL-S)

You may redistribute and modify this documentation under the terms of the CERN OHL-S-v2 (https://ohwr.org/cern_ohl_s_v2.txt). This documentation is distributed WITHOUT ANY EXPRESS OR IMPLIED WARRANTY, INCLUDING OF MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A PARTICULAR PURPOSE. Please see the CERN OHL v2-S for applicable conditions

Under CERN OHL-S-v2, derivative work must be publicly released as defined in subsection 3.3

# WLED 4 Port Controller

Customised Pixel Controller based on Scott Hanson's BBB 16v2 SMD controller [https://github.com/computergeek1507/PB_16](https://github.com/computergeek1507/PB_16/blob/master/BBB_16_SMD/README.md). The board is largely the same as Scott's, but with a few modifications.

Note: The WLED 4 Port Controller requires a 5v DC only! Connecting any other size power source will damage the board. The board does not supply power outputs for pixels, only pixel data and ground connections.

# Features

* 4 local ports

* Reverse Voltage Protection

* GPIO 15 Relay Connector

* Timer Delay Connections

## Additional Hardware Required

* A ESP32 WT32-ETH01 with WLED Software installed.


![Image of WLED 4 Port
Out](https://github.com/GDWoody/Pixel-Controllers/blob/main/wled/image/WLED_WT32.png)



