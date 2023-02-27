# Pixel-Controllers
## Copyright and Disclaimer
Copyright: GDWoody

This documentation describes Open Hardware and is licensed under the CERN Open Hardware License Version 2 - Strongly Reciprocal. (CERN-OHL-S)

You may redistribute and modify this documentation under the terms of the CERN OHL-S-v2 (https://ohwr.org/cern_ohl_s_v2.txt). This documentation is distributed WITHOUT ANY EXPRESS OR IMPLIED WARRANTY, INCLUDING OF MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A PARTICULAR PURPOSE. Please see the CERN OHL v2-S for applicable conditions

Under CERN OHL-S-v2, derivative work must be publicly released as defined in subsection 3.3

# BBB 16v2 SMD Controller

Customised Pixel Controller based on Scott Hanson's BBB 16v2 SMD controller [https://github.com/computergeek1507/PB_16](https://github.com/computergeek1507/PB_16/blob/master/BBB_16_SMD/README.md). The board is largely the same as Scott's but with a few modifications.

# Modifications.

The BBB 16v2 SMD Controller requires a 5v DC power source only! Connecting any other size power source will damage the board.

There are no power outputs for pixels, only pixel data and ground connections.

A RTC DS3231 AT24C32 can be connected to the board, either top mount or under mount.
 

![Image of BBB16
Out](https://github.com/GDWoody/Pixel-Controllers/blob/main/image/BBB_16v2_SMD.png)

	
