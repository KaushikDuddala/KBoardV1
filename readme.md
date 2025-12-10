# KBoard

The KBoard is a simple RP2040 devboard designed from the guide!! I made some changes visually like the orientation of the chip bc lowk 45 degrees looks cooler. routing was a nightmate tho!!

## Features:

- RP2040 microcontroller  
- USB-C connector for programming/power  
- Standard pin headers

## Future Features:

- Convert to a BadUSB design
- Wi-Fi/BT support  
- Battery Support?

## Final Design

![Front](https://github.com/KaushikDuddala/KBoardV1/blob/main/Images/final1front.png?raw=true)  
![Back 1](https://github.com/KaushikDuddala/KBoardV1/blob/main/Images/final1back.png?raw=true)  
![Back 2](https://github.com/KaushikDuddala/KBoardV1/blob/main/Images/final2back.png?raw=true)

## PCB Design

![PCB Front](https://github.com/KaushikDuddala/KBoardV1/blob/main/Images/pcbFront.png?raw=true)  
![PCB Back](https://github.com/KaushikDuddala/KBoardV1/blob/main/Images/pcbBack.png?raw=true)  
![PCB Total](https://github.com/KaushikDuddala/KBoardV1/blob/main/Images/pcbTotal.png?raw=true)  
![Schematic](https://github.com/KaushikDuddala/KBoardV1/blob/main/Images/schematic.png?raw=true)

## Bill of Materials (BOM)

A combined BOM including JLCPCB part numbers:

|Id|Designator|Footprint|Quantity|Designation|Supplier & Ref|JLCPCB Part #|Unit Price|
|--|----------|---------|--------|-----------|---------------|------------|----------|
|1|J3,J2|PinHeader_1x20_P2.54mm_Vertical|2|Conn_01x20||| |
|2|U1|QFN-56-1EP_7x7mm_P0.4mm_EP3.2x3.2mm|1|RP2040||C2040|$1.8330|
|3|U3|Winbond_USON-8-1EP_3x2mm_P0.5mm_EP0.2x1.6mm|1|W25Q128JVS||C2843335|$1.1730|
|4|C8,C5,C2,C11,C17,C12,C9,C7,C6,C4,C3|C_0402_1005Metric|11|0.1uF||C1525|$0.0264|
|5|R5,R7|R_0402_1005Metric|2|1K||C11702|$0.0024|
|6|C16,C15|C_0402_1005Metric|2|33pF||C1562|$0.0040|
|7|Y1|Crystal_SMD_3225-4Pin_3.2x2.5mm|1|12 MHz||C9002|$0.1290|
|8|U2|SOT-23|1|MCP1700x-330xxTT||C39051|$1.9695|
|9|SW1|SW_Push_SPST_NO_Alps_SKRK|1|SW_Push||C720477|$0.0850|
|10|R6|R_0402_1005Metric|1|10K||C25744|$0.0010|
|11|R4,R3|R_0402_1005Metric|2|27||C25100|$0.0120|
|12|R2,R1|R_0402_1005Metric|2|5.1k||C25905|$0.0020|
|13|J4|PinHeader_1x03_P2.54mm_Vertical|1|Conn_01x03||| |
|14|C14,C13|C_0402_1005Metric|2|10uF||C19702|$0.0224|
|15|C10,C1|C_0402_1005Metric|2|1uF||C52923|$0.0116|
|16|J1|USB_C_Receptacle_HRO_TYPE-C-31-M-12|1|USB_C_Receptacle_USB2.0_14P||C165948|$0.3388|

