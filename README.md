# RetroShield

Porting an Applesoft on 6502

----------------------------------------------

Configuration:
==============
Debug:      0
LCD-DISP:   0
SPI-RAM:    0 Bytes
SRAM Size:  6144 Bytes
SRAM_START: 0x0
SRAM_END:   0x17FF

\
6000R

6000: 4C

]10 A=1

]20 A=A+2

]30 FOR I = 3 TO INT(A/2) STEP 2

]40 IF A/I=INT(A/I) THEN 70

]50 NEXT

]60 PRINT A;" ";

]70 GOTO 20

]RUN
5 7 11 13 17 19 23 29
