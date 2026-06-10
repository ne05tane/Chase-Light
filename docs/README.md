<img width="353" height="541" alt="Screenshot 2026-06-10 121149" src="https://github.com/user-attachments/assets/87ddcfb5-af5f-4d04-935d-39d57218c2bb" />

## Desc-
This Sequencer is my first ever attempt at pcb making. The 555 IC sends input to the main 4017 IC which controls all of the LED’s flashing. The circuit is powered by the C492401 header.

I wanted to be able to learn pcb design and the steps involved in manufacturing 
without being overwhelmed. For me, that meant a sequencer/blinky/LED Chaser- a classic hello world project in embedded systems and hardware

## 3D Model-
<img width="809" height="595" alt="Screenshot 2026-06-09 104715" src="https://github.com/user-attachments/assets/83ef4d47-d4e7-4aba-96f8-9e6d042d9517" />
<img width="733" height="447" alt="Screenshot 2026-06-09 104745" src="https://github.com/user-attachments/assets/e3ed027a-7633-4373-8adb-95911f88479e" />
<img width="813" height="592" alt="Screenshot 2026-06-08 095603" src="https://github.com/user-attachments/assets/73e41fab-b274-4019-89f4-1e9569477bb4" />

## PCB Design-
<img width="787" height="553" alt="Screenshot 2026-06-08 100735" src="https://github.com/user-attachments/assets/96c71f29-f02b-44ca-9f32-5b7536954681" />

<img width="810" height="574" alt="Screenshot 2026-06-08 100801" src="https://github.com/user-attachments/assets/d8701a08-a5ce-4bc2-a6db-e641b990f759" />

## BOM-
 **No\.** | **Quantity** | **Comment**     | **Designator**                                     | **Footprint**                                  | **Value**       | **Manufacturer Part** | **Manufacturer** | **Supplier Part** | **Supplier** | **LCSC Stock** | **JLCPCB Stock** | **JLCPCB Price** 
----------|--------------|-----------------|----------------------------------------------------|------------------------------------------------|-----------------|-----------------------|------------------|-------------------|--------------|----------------|------------------|------------------
 1        | 1            | 1uF             | C1                                                 | CAP\-TH\_BD5\.0\-P2\.00\-D0\.8\-FD             | 1uF             | KF010M050C110A        | CapXon\(丰宾\)     | C62934            | LCSC         | 6              | 0\.0039          |                  
 2        | 1            | 10nF            | C2                                                 | CAP\-TH\_L8\.0\-W4\.0\-P5\.00\-D1\.2           | 10nF            | N09F1B103MN0B0S0N0    | STE\(松田\)        | C249157           | LCSC         | 2035           | 0\.0059          |                  
 3        | 1            | PZ254V\-11\-02P | H1                                                 | HDR\-TH\_2P\-P2\.54\-V\-M                      | PZ254V\-11\-02P | XFCN\(兴飞\)            | C492401          | LCSC              | 1457454      | 0\.0026        |                  |                  
 4        | 10           | XL\-502UWC      | LED1,LED2,LED3,LED4,LED5,LED6,LED7,LED8,LED9,LED10 | LED\-TH\_BD5\.9\-P2\.54\-RD\_WHITE             | XL\-502UWC      | XINGLIGHT\(成兴光\)      | C2895480         | LCSC              | 18409        | 0\.005         |                  |                  
 5        | 1            | 2\.54\-1\*1P针   | P1                                                 | HDR\-TH\_1P\-P2\.54\-V\-M                      | 2\.54\-1\*1P针   | BOOMELE\(博穆精密\)       | C81276           | LCSC              | 118040       | 0\.002         |                  |                  
 6        | 1            | 1kΩ             | R1                                                 | RES\-TH\_BD2\.3\-L6\.5\-P10\.50\-D0\.5         | 1kΩ             | MF1/4W\-1KΩ±1%T52     | 华星机电             | C713997           | LCSC         | 452651         | 0\.0012          |                  
 7        | 1            | 470Ω            | R2                                                 | RES\-TH\_BD2\.2\-L6\.5\-P10\.50\-D0\.6         | 470Ω            | MFR0W4F4700A50        | UNI\-ROYAL\(厚声\) | C58592            | LCSC         | 1060           | 0\.0021          |                  
 8        | 1            | 50kΩ            | R3                                                 | RES\-ADJ\-TH\_3P\-L9\.5\-W4\.85\-P2\.50\-BL\-L | 50kΩ            | 3296X\-1\-503         | BOCHEN\(博晨\)     | C118912           | LCSC         | 1683           | 0\.0271          |                  
 9        | 1            | NE555P          | U1                                                 | DIP\-8\_L9\.8\-W6\.6\-P2\.54\-LS7\.6\-BL       | NE555P          | TI\(德州仪器\)            | C46749           | LCSC              | 12091        | 0\.0402        |                  |                  
 10       | 1            | CD4017BE\(LX\)  | U2                                                 | PDIP\-16\_L19\.3\-W6\.4\-P2\.54\-LS7\.94\-BL   | CD4017BE\(LX\)  | LX\(灵星芯微\)            | C32710674        | LCSC              | 1746         | 0\.0207        |                  |                  


## Note-
This repository contains my modified version of the original **Blinky Board** (https://blueprint.hackclub.com/starter-projects/blinky). 

Special thanks **@Keyaan** for helping me in the process

## License-

This project is licensed under the **MIT License**.

Permission is hereby granted, free of charge, to any person obtaining a copy of this hardware design and associated documentation files (the "Design"), to deal in the Design without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Design, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Design.

THE DESIGN IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED.

Copyright © [2026] [Ana]   
