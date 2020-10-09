
[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

# Disclaimer

You are free to:

Share — copy and redistribute the material in any medium or format

Adapt — remix, transform, and build upon the material

________________________________________

Attribution — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

NonCommercial — You may not use the material for commercial purposes.

___________________________________________

THE HARDWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE HARDWARE OR THE USE OR OTHER DEALINGS IN THE HARDWARE.

_____________________________________________

# Overview

This repo contains both the CAD for the 3D printed cover for the Pocket Operator and the PCB schematic for the adapter. PCB is created using KiCad. Software can be found [here](https://github.com/PO-MIDI-Adapter/midi-adapter-software/tree/v2)

## For assmebly instruction please go to the [wiki](https://github.com/PO-MIDI-Adapter/midi-adapter-hardware/wiki)

[![PO-MA](https://raw.githubusercontent.com/PO-MIDI-Adapter/midi-adapter-hardware/master/photos/title.jpg)](https://www.youtube.com/watch?v=iIQ18DAJAU0 "PO-MA")

# Photos

![Cover](https://raw.githubusercontent.com/PO-MIDI-Adapter/midi-adapter-v2-hardware/main/photos/pomav2.jpg)

![Standalone](https://raw.githubusercontent.com/PO-MIDI-Adapter/midi-adapter-v2-hardware/main/photos/pomav2-17.jpg)

![Pins](https://raw.githubusercontent.com/PO-MIDI-Adapter/midi-adapter-v2-hardware/main/photos/pomav2bottom.jpg)

![With volca and beatstep](https://raw.githubusercontent.com/PO-MIDI-Adapter/midi-adapter-hardware/main/photos/beatstep.jpg "Setup")

![With volca and beatstep](https://raw.githubusercontent.com/PO-MIDI-Adapter/midi-adapter-hardware/main/photos/opz.jpg "Setup")

![Layout](https://raw.githubusercontent.com/PO-MIDI-Adapter/midi-adapter-v2-hardware/main/photos/layout.PNG)

# BOM

1. 1 x PCB board
2. 1 x 3D printed cover (Found in the cad folder)
3. 2 x cover holders  (Found in the cad folder)
4. 25 x pogo pins [ebay](https://www.ebay.ca/itm/100pcs-9mm-Length-Spring-Loaded-Test-Probes-Pogo-Pins-Cusp-Spear-for-Testing/163156710143?ssPageName=STRK%3AMEBIDX%3AIT&_trksid=p2057872.m2749.l46252)
5. 1 x PJ320B 3.5MM Audio Jack (ebay)

In addition, you would need the following electronics from Digikey (bom.csv)

|Manufacturer Part Number|Manufacturer               |Digi-Key Part Number|Quantity|Description                     |Placement|
|------------------------|---------------------------|--------------------|--------|--------------------------------|---------|
|SN74HC125N              |Texas Instruments          |296-1572-5-ND       |1       |IC BUFFER NON-INVERT 6V 14DIP   |U2
|A 14-LC-TT              |Assmann WSW Components     |AE9989-ND           |1       |CONN IC DIP SOCKET 14POS TIN    |U2
|1-2199298-1             |TE Connectivity            |A120346-ND          |1       |CONN IC DIP SOCKET 6POS TIN     |U3
|H11L1M                  |ON Semiconductors          |H11L1-MQT-ND        |1       |OPTOISO 4.17KV OPN COLL 6DIP    |U3
|PRPC028SACN-RC          |Sullins Connector Solutions|S1131EC-28-ND       |2       |CONN HEADER VERT 28POS 2.54MM   |U1
|DEV-16771               |SparkFun Electronics       |1568-DEV-16771-ND   |1       |TEENSY 4.1 W/OUT HDRS K66 EVAL  |U1
|SDS-50J                 |CUI Inc.                   |CP-2350-ND          |2       |CONN RCPT FMALE DIN 5POS SOLDER |J29,J30
|CF14JT220R              |Stackpole Electronics Inc  |CF14JT220RCT-ND     |3       |RES 220 OHM 1/4W 5% AXIAL       |R2,R3,R7
|CF14JT10K0              |Stackpole Electronics Inc  |CF14JT10K0CT-ND     |1       |RES 10K OHM 1/4W 5% AXIAL       |R4
|CF14JT470R              |Stackpole Electronics Inc  |CF14JT470RTR-ND     |1       |RES 470 OHM 1/4W 5% AXIAL       |R8
|USB-A1HSW6              |On Shore Technology Incs   |ED2989-ND           |1       |USB-A Receptacle Connector 4 Pos|J19
|C315C104M5U5TA7303M     |KEMET                      |399-9859-2-ND       |2       |CAP CER 0.1UF 50V Z5U RADIAL    |C2,C1
|PPTC041LFBN-RC          |Sullins Connector Solutions|S7002-ND            |1       |CONN HDR 4POS 0.1 TIN PCB       |J32
|1N914                   |ON Semiconductor           |1N914FS-ND          |1       |DIODE GEN PURP 100V 200MA DO35  |D1

Optional

|Manufacturer Part Number|Manufacturer               |Digi-Key Part Number|Quantity  |Description                   |Placement|
|------------------------|---------------------------|--------------------|--------|--------------------------------|---------|
|PPTC241LFBN-RC          |Sullins Connector Solutions|S7022-ND            |2       |CONN HDR 24POS 0.1 TIN PCB      |U1


