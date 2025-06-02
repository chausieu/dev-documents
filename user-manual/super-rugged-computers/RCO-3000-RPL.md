# USER’S MANUAL

## RCO- 3000 - RPL

**Small Form Factor Computer**

## Table of Contents

- Prefaces
  - Revision
  - Disclaimer
  - Copyright Notice
  - Trademarks Acknowledgment
  - Environmental Protection Announcement
  - Safety Precautions
  - Technical Support and Assistance
  - Conventions Used in this Manual
  - Package Contents
  - Ordering Information
  - Optional Accessory
- Chapter 1 Product Introductions - 1.1 Overview - Key Feature - 1.2 Hardware Specification - 1.3 System I/O - 1.3.1 EDGEBoostI/O Bracket [EBIO] - 1.4 Mechanical Dimension
- Chapter 2 Mechanical Specifications.............................................................. - 2.1 Switch and connector Locations - 2.1.1 Top View - 2.1.2 Bottom View - 2.2 Connector / Switch Definition - 2.3 I/O Interface Descriptions
- Chapter 3 System Setup - unscrewing 3.1 Set torque force to 3.5 kgf-cm to execute all the screwing and - 3.2 Removing chassis bottom cover - 3.3 Removing chassis top cover - 3.4 Installing CPU - 3.5 Installing SODIMM - 3.6 Installing 4G/5G Module and Antenna - 3.7 Installing Wi-Fi Module and Antenna - 3.8 Installing HDD on internal SATA HDD bay - 3.9 Installing HDD on removable SATA HDD tray - 3.1 0 Assemble chassis top cover - 3.11 Assembling chassis bottom cover - 3.1 2 Installing SIM card - 3.13 SIM OS Settings - 3.14 Installing Wall-Mount Kit - 3.15 Installing DIN rail holder
- Chapter 4 BIOS Setup - 4.1 BIOS Introduction - 4.2 Main Setup - 4.3 Advanced Setup - 4.3.1 Connectivity Configuration - 4.3.4 Trusted Computing - 4.3.5 ACPI Settings - 4.3.6 Super IO Configuration - 4.3.7 Hardware Monitor - 4.3.8 Power IGN Mode - 4.3.9 Wake system from S5
  - 4.3.10 Serial Port Console Redirection
    - 4.3.11 USB Configuration
    - 4.3.12 Network Stack Configuration
    - 4.3.13 NVMeConfiguration...............................................................................
    - 4.3.14 RST (UEFI RAID) Configuration
  - 4.4 Chipset
    - 4.4.1 System Agent (SA) Configuration
    - 4.4.2 PCH-IO Configuration
  - 4.5 Security
  - 4.6 Boot
  - 4.7 Save & Exit
  - 4.8 MEBx....................................................................................................................
- Appendix WDT & GPIO
  - WDT Sample Code
  - GPIO Sample Code
    - 4.3.2 CPU Configuration
    - 4.3.3 PCH-FW Configuration

### Revision

### Disclaimer

All specifications and information in this User’s Manual are believed to be accurate and up to date. Premio
Inc. does not guarantee that the contents herein are complete, true, accurate or non-misleading. The
information in this document is subject to change without notice and does not represent a commitment on
the part of Premio Inc.
Premio Inc. disclaims all warranties, express or implied, including, without limitation, those of
merchantability, fitness for a particular purpose with respect to contents of this User’s Manual. Users must
take full responsibility for the application of the product.

### Copyright Notice

All rights reserved. No part of this manual may be reproduced or transmitted in any form or by any means,
electronic or mechanical, including photocopying, recording, or information storage and retrieval systems,
without the prior written permission of PremioInc. Copyright © Premio Inc.

### Trademarks Acknowledgment

Intel®, Celeron® and Pentium® are trademarks of Intel Corporation.
Windows® is registered trademark of Microsoft Corporation.
AMI is trademark of American Megatrend Inc.
IBM, XT, AT, PS/2 and Personal System/2 are trademarks of International Business Machines Corporation
All other products and trademarks mentioned in this manual are trademarks of their respective owners.

### Environmental Protection Announcement

Do not dispose this electronic device into the trash while discarding. Please recycle to minimize pollution
and ensure environment protection.

## Prefaces

```
Revision Description Date
1.0 Manual Released 2024/5/
```

### Safety Precautions

```
Before installing and using the equipment, please read the following precautions:
⚫Put this equipment on a reliable surface during installation. Dropping it or letting it fall could
cause damage.
⚫The power outlet shall be installed near the equipment and shall be easily accessible.
⚫Turn off the system power and disconnect the power cord from its source before making any
installation. Be sure both the system and the external devices are turned OFF. Sudden surge
⚫of power could ruin sensitive components. Make sure the equipment is properly grounded.
⚫When the power is connected, never open the equipment. The equipment should be opened
only by qualified service personnel.
⚫Make sure the voltage of the power source is correct before connecting the equipment to the
power outlet.
⚫Disconnect this equipment from the power before cleaning. Use a damp cloth. Do not use
liquid or spray detergents for cleaning.
⚫Avoid the dusty, humidity and temperature extremes.
⚫Do not place heavy objects on the equipment.
⚫If the equipment is not used for long time, disconnect it from the power to avoid being
damaged by transient over-voltage.
⚫The storage temperature shall be above - 30 °C and below 85°C.
⚫The computer is provided with a battery-powered real-time clock circuit. There is a danger of
explosion if incorrectly replaced. Replace only with the same or equivalent type
recommended by the manufacturer.
⚫If one of the following situation arises, get the equipment checked be service personnel:
```

- The power cord or plug is damaged.
- Liquid has penetrated into the equipment.
- The equipment has been exposed to moisture.
- The equipment does not work well or it cannot work according the user’s manual.
- The equipment has been dropped and damaged.
- The equipment has obvious signs of breakage.

**Preface**

### Technical Support and Assistance

1. Visit the Premio Inc website at [http://www.premioinc.comwhere](http://www.premioinc.comwhere) you can find the latest information about
   the product.
2. Contact your distributor, our technical support team or sales representative for technical support if
   you need additional assistance. Please have following information ready before you call:
   ⚫ Model name and serial number
   ⚫ Description of your peripheral attachments
   ⚫ Description of your software (operating system, version, application software, etc.)
   ⚫ A complete description of the problem
   ⚫ The exact wording of any error messages

### Conventions Used in this Manual

**Preface**

```
This indication alerts operators to an operation that, if not strictly observed,
may result in severe injury.
W
```

```
ARNING
```

```
This indication alerts operators to an operation that, if not strictly observed,
may result in safety hazards to personnel or damage to equipment.
CAUTION
```

```
This indication provides additional information to complete a task easily.
NOTE
```

### Package Contents

```
Before installation, please ensure all the items listed in the following table are included in the package.
Item Description Q’ty
1 RCO- 3000 - RPL Series 1
2 Wall Mounting kit with Vibration Isolation 1
3 Accessory Kit 1
```

### Ordering Information

**Preface**

```
Model No. Product Description
```

```
RCO- 3000 - RPL Small Form Factor Computer with LGA 1700 for 12/13/14th Gen Intel CPU & Q670 PCH, 2x LAN
```

```
RCO- 3000 - RPL-4L Small Form Factor Computer with LGA 1700 for 12/13/14th Gen Intel CPU & Q670 PCH, 6x LAN
```

```
RCO- 3000 - RPL-4LM12 Small Form Factor Computer with LGA 1700 for 12/13/14th Gen Intel CPU & Q670 PCH, 2x LAN, 4x M12 LAN
```

```
RCO- 3000 - RPL-4P Small Form Factor Computer with LGA 1700 for 12/13/14th Gen Intel CPU & Q670 PCH, 2x LAN, 4x PoE
```

```
RCO- 3000 - RPL-4PM12 Small Form Factor Computer with LGA 1700 for 12/13/14th Gen Intel CPU & Q670 PCH, 2x LAN, 4x M12 PoE
```

```
RCO- 3000 - RPL-D10G Small Form Factor Computer with LGA 1700 for 12/13/14th Gen Intel CPU & Q670 PCH, 2x LAN, 2x 10G LAN
```

```
RCO- 3000 - RPL-4U3 Small Form Factor Computer with LGA 1700 for 12/13/14th Gen Intel CPU & Q670 PCH, 2x LAN, 10x USB
```

```
RCO- 3000 - RPL-2M2BK Small Form Factor Computer with LGA 1700 for 12/13/14th Gen Intel CPU & Q670 PCH, 2x LAN, 3x M.2 B-Key
```

```
RCO- 3000 - RPL-M2MK Small Form Factor Computer with LGA 1700 for 12/13/14th Gen Intel CPU & Q670 PCH, 2x LAN, 1x M.2 M-Key
```

**Preface**

### Optional Accessory

```
Model No. Product Description
1 - E09A12002 Adapter AC/DC 24V 9.2A 220W with 3pin Terminal Block Plug 5.0mm Pitch
```

```
1 - E09A22801 Adapter AC/DC 24V 11.6A 280W with 3pin Terminal Block Plug 5.0mm Pitch
```

```
1 - TPCD00005 Power Cord, 3-pin US Type, 180cm
```

```
1 - TPCD00002 Power Cord, European Type, 180cm
```

```
1 - TPCD00001 Power Cord, 3-pin UK Type, 180cm
```

```
3 - DINR- 0004 DinRail-2MountingKit
```

## Chapter 1 Product Introductions

##### 1.1 Overview

```
The Advanced FanlessEmbedded Systems RCO- 3000 - RPL series are designed with rich I/O, high
flexibility and easy expansion capabilities which are ideal for diverse industrial applications.Support
12/13/14th Gen. Intel® Core processor, RCO- 3000 - RPL Series is an extreme features integration,
outstanding system performance, versatile I/O connections, and rugged reliability fanlessembedded
systems. It offers dramatically enhanced CPU and graphics performance, wide power and feature
advanced features, rich connectivity interfaces, wide range 9~48 VDC power input, and high reliability
even operating in temperature extremes (- 25 °C to 70°C).
```

**Chapter 1: Product Introductions**

```
Rear Panel Front Panel
```

###### Key Feature

```
⚫Support 12/13/14th Gen Intel® RPL S / ADL Processor (LGA 1700, 35W TDP)
⚫Intel® Q670 Express Chipset
⚫4x Independent Displays
⚫2x Intel® 2.5GbE supporting Wake-on-LAN and PXE, 3x External SIM socket
⚫2x 2.5" SATA SSD Bay (1x Internal) with RAID 0, 1, 5 support
⚫1x M.2 E Key, 2230 (PCIe x1, USB 2.0)
⚫1x M.2 B Key, 2242/3042/3052 (PCIe x2,or PCIe x1 & USB 3.2 Gen1; Support AI Module/NVMe
Storage/4G/5G)
⚫1x M.2 B Key, 2242/3042/3052 (PCIe x2 or SATA; Support AI Module/NVMe/SATA Storage/4G/5G)
⚫3x RS-232/422/485, 6x USB 3.2 Gen 2 (10 Gbps)
⚫8x DI + 8x DO with isolation
⚫9 to 48VDC Wide Range Power Input Supporting AT/ATX Mode
⚫Wide Operating Temperature (- 25 °C to 70°C)
⚫TPM 2.0 Supported
```

##### 1.2 Hardware Specification

```
Chapter 1: Product Introductions
```

**System**
Processor
**Support 12/13/14th Gen Intel® ADL & RPL S Processor (LGA 1700, 35W TDP)**

- Intel® Core i9-14900T/i9-13900TE/i9-12900TE, up to 24 Cores, 36MB Cache, up to 5.5 GHz
- Intel® Core i7-14700T, up to 20 Cores, 33MB Cache, up to 5.2 GHz
- Intel® Core i7-13700TE/i7-12700TE, up to 16 Cores, 30MB cache, up to 4.8 GHz
- Intel® Core i5-14500T/i5-13500TE/i5-12500TE, up to 14 Core, 24MB Cache, up to 4.8 GHz
- Intel® Core i3-14100T/i3-13100TE/i3-12100TE, up to 4 Cores, 12MB Cache, up to 4.4 GHz
- Intel® Core 300T, up to 2 Cores, 6MB Cache, up to 3.4 GHz
- Intel® Pentium® G7400TE, 2 Cores, 6MB Cache, 3.0 GHz
- Intel® Celeron® G6900TE, 2 Cores, 4MB Cache, 2.4 GHz

System Chipset Intel® Q670 Express Chipset

LAN Chipset •• 2.5 GbE1: Intel I226 (Support Wake2.5 GbE2: Intel I226 (Support Wake--onon--LAN and PXE, Support TSN)LAN and PXE, Support TSN)
Audio Codec RealtekALC888S
System Memory 1x DDR5 4800/5600MHz SODIMM. Max. up to 32GB
Graphics Integrated Intel® UHD Graphics 770/
BIOS AMI 256Mbit SPI BIOS
Watchdog Software Programmable Supports 1~255 sec. System Reset
TPM TPM 2.

**Display**

Display Port

4x DisplayPort, support resolution 4096
x 2304, Up to 7680 x 4320
(1x DP Port Co-layout HDMI Connector)
HDMI Yes, Shared by 1x DP port
Multiple Display 4x Independent Displays

```
Power
Power Adaptor Optional AC/DC 24V/9.2A, 220WOptional AC/DC 24V/11.67A, 280W
Power Mode AT, ATX (ATX Default)
Power Ignition
Sensing Power Ignition Management
Power Supply
Voltage 9~48VDC
Power Connector 3 - pin Terminal Block
Power Protection
```

```
OVP (Over Voltage Protection)
OCP (Over Current Protection)
Reverse Protection
```

```
Storage
```

```
SSD/HDD
```

- 1x 9mm 2.5" SATA SSD Bay (Internal)
- 1x 7mm 2.5" SATA SSD Bay (Hot-
  swappable)
  Support RAID 0, 1, 5
  **Operating System**
  Windows Windows 10/
  Linux Linux kernel 5.x

**Chapter 1: Product Introductions**

**Expansion**

M.

```
1x M.2 B key Type: 2242/3042/
```

- Support PCIe x2/PCIe x1 & USB 3.2 Gen
- Support NVMeStorage/AI Module/4G/5G
  1x M.2 B key Type: 2242/3042/
- Support PCIe x2/SATA signal
- Support NVMe/SATA Storage/AI Module/4G/5G
  1x M.2 E key slot (2230)
- Support PCIe x1 & USB 2.0; Support CNVi
- Support WifiModule

SIM Socket 1x External Standard SIM socket1x External Dual Nano SIM socket

Expansion Modules Occupied One Universal I/O Slot:

- 4 - port 1GbE module with Intel® I350 Chipset, RJ-45 or M12 connector (PoE optional)
- 2 - Port 10GbE RJ45 with Intel X710 Chipset
- 4 - Port USB with Renesas uPD720201K8 host controller (share PCIe Gen2 x
  bandwidth)
- 1x RJ45 port for OOB Management Module
- 1x M.2 M-Key (PCIe x4 Lane, 2242/2260) for NVMe/AI Module
- 2x M.2 B-Key 2242/3042/3052:
  - 2x M.2 (PCIe x2 Lane) for NVMe/AI Module
  - 1x M.2 (PCIe x2 Lane) for NVMe/AI Module and 1x M.
    (PCIe x1 Lane + USB 3.2 Gen 1) for 4G/5G Module, 1x External SIM socket
    (M.2 attached)

**I/O**
Audio 1x Line-out
CAN 2x CAN 2.0 A/B 2-pin Internal header
COM 3x RS-232/422/485 (Optional Isolation)
DIO 8 in / 8 out (Isolated)
LAN 2x 2.5GbE RJ
USB 6x USB 3.2 Gen 2 (10Gbps)
Others 5x WiFiAntenna Holes
1x Power Switch, 1x AT/ATX Switch
1x Remote Power On/Off
1x PC/Car Mode Switch
1x Delay Time Switch
1x Clear CMOS Switch
1x Mic In Header (Internal)

```
Environment
Operating
Temp.
UL: - 25 °C to 50°C (35W CPU)
CE/FCC/IC: - 25 °C to 70°C (35W CPU)
Storage Temp. - 30 °C to 85°C
Relative
Humidity 10% to 95% (non-condensing)
```

```
Vibration
```

```
With SSD: 5 Grms, 5 -500 Hz,
0.5 hr/axis
With HDD: 1 Grms, 5 -500 Hz,
0.5 hr/axis
Shock With SSD: 50G, half sine, 11ms
Certification
```

```
UL, CE, FCC Class A,
EMC Conformity with EN50155 &
EN50121- 3 - 2
```

**Physical**
Construction Extruded Aluminum with Heavy Duty Metal
Dimension 192 (W) x 227 (D) x 60.3 (H) mm
Weight 2.8kg -3.6 kg

Mounting ‧‧^ Wall Mounting kit with Vibration IsolationDIN-rail mounting (optional)

##### 1.3 System I/O

###### RCO- 3000 - RPL

**Chapter 1: Product Introductions**

```
Rear Panel
DP/HDMI port
Used to connect a DP/HDMI monitor or connect
optional split cable for dual display mode
Digital I/O Terminal Block
The Digital I/O terminal block supports 8 digital
input and 8 digital output
DisplayPort
Used to connect a DisplayPort monitor
COM port
COM1 ~ COM3 support RS232/422/485 serial
device
```

```
USB 3.2 Gen 2 Port
Used to connect USB 3.2 Gen 2
LAN port
Used to connect the system to a local area
network
Antenna hole
Used to connect an antenna for optional Mini-
PCIeWiFimodule
DC IN
Used to plug a DC power input with terminal
block
```

```
Front Panel
ATX power on/off switch
Press to power-on or power-off the system
Power LED
Indicates the power status of the system
HDD LED
Indicates the status of the hard drive
Antenna hole
Used to connect an antenna for optional Mini-
PCIeWiFimodule
USB 3.2 Gen 2 port (10 Gbps)
Used to connect USB 3.2 device
Removable HDD
Removable 2.5" SATA HDD Bay
(support H=7mm, hot-swappable)
Support RAID 0, 1, 5
AT/ATX mode select switch
Used to select AT or ATX power mode
```

```
Remote Power on/off Terminal Block
Used to plug a remote power on/off terminal
block
PC/Car mode select switch
Used to select PC or Car mode
Clear CMOS
Used to clear CMOS
Line-out
Used to connect a speaker
SIM card
Used to insert SIM card
EDGEBoostI/O bracket (optional)
```

**Chapter 1: Product Introductions**

###### RCO- 3000 - RPL

###### 1.3.1 EDGEBoostI/O Bracket [EBIO]

**Chapter 1: Product Introductions**

```
Model No :
```

- RCO- 3000 - RPL-4L
- RCO- 3000 - RPL-4LM
- RCO- 3000 - RPL-4P
- RCO- 3000 - RPL-4PM
  - RCO- 3000 - RPL-D10G
  - RCO- 3000 - RPL-4U
  - RCO- 3000 - RPL-2M2BK
  - RCO- 3000 - RPL-M2MK

### 1.4 Mechanical Dimensions

```
Unit: mm
```

**Chapter 1: Product Introductions**

###### RCO- 3000 - RPL

## Chapter 2 Mechanical Specifications..............................................................

##### 2.1 Switch and connector Locations

```
Chapter 2: Mechanical Specifications
```

###### 2.1.1 Top View

```
POWER1 JESPI
```

```
DC IN
```

```
POWER3 JP
```

```
AT_ATX
CAR_PWR
```

```
MIC_IN
```

```
CLR_CMOS
```

```
RESET
```

```
CN1 , CN
```

```
LAN1, LAN2 DP1, DP2, DP3 DP_HDMI
```

```
CAN
```

```
CAN
```

```
FAN_SIO
```

```
SMB
```

```
M2_KB
```

```
M2_KE
```

```
LAN_L
```

```
PSE_M
```

```
OOB
```

```
JP4, JP
```

```
Chapter 2: Mechanical Specifications
```

###### 2.1.2 Bottom View

```
COM5 , COM
```

```
LINE_OUT
PWR_SW
```

```
PWR_SW
```

```
PWR_SW
```

```
USB3_1 ,
USB3_
```

```
SIM1 SIM
```

```
M2_KB
```

```
SATA
```

```
SATA
```

```
SW
```

##### 2.2 Connector / Switch Definition

```
Chapter 2: Mechanical Specifications
```

```
Connector Location Definition
AT_ATX AT / ATX Power Mode Switch
PWR_SW 1~3 Power Switch
RESET Reset Switch
DC_IN 3 - pin DC +9V~48V Power Input Connector
DIO1 8DI / 8DO Connector
COM 1~6 RS232 / RS422 / RS485 Connector
DP 1~3 DP Connector
DP_HDMI DP / HDMI Connector
LAN 1~2 LAN Connector
FAN_SIO Smart FAN Connector
Power1 +12V /+5V Power Connector
USB3_1~3 USB 3 Gen2 , USB 3 Gen1 , USB2.
CN 1 ~2 USB 3 Gen1 , USB2.
SIM 1~2 SIM Card Socket
CAR_PWR PC mode / CAR mode select
MIC Mic-in Connector
LINE_OUT LINE-OUT Jack
LAN_L1 PCIe x4 Slot
M2_KB1 M.2 B Key Socket for PCIe / SATA
M2_KB2 M.2 B Key Socket for PCIe / USB
M2_KE M.2 E Key Socket for PCIe / CNVI
PWR_LED Power LED Status
HDD_LED HDD Access LED Status
WDT_LED Watchdog LED Status
SATA 1~2 SATA with Power Connector
OOB OOB control signal
JP4 OOB Auto Link
JP5 OOB Remote Debug port
SW17 COM1 or OOB Remote Debug port selection
```

##### 2.3 I/O Interface Descriptions

```
Chapter 2: Mechanical Specifications
```

**2.3.1 ESPI Debug Con**

```
JESPI1
Pin Signal Pin Signal
1 ESPI_IO_0 2 3.3V
3 ESPI_IO_1 4 ESPI_RESET#
5 ESPI_IO_2 6 ESPI_CS#
7 ESPI_IO_3 8 ESPI_CLOCK
9 N/A 10 GND
```

```
2 1
```

```
10 9
```

```
Chapter 2: Mechanical Specifications
```

**2.3.2 Power Con**

```
POWER1
Pin Signal
1 +5V
2 GND
3 GND
4 +12V
```

```
DC IN : +9V ~ +48V
```

```
Pin Signal
1 +9V ~ +48V
2 IGN
3 GND
```

```
3 - pin DC Power Input Connector
```

```
1 4
```

**Chapter 2: Mechanical Specifications**

```
POWER3 : +9V ~ +36V
Pin Signal
1 +9V ~ +36V
2 GND
3 GND
4 +9V ~ +36V
```

```
1
```

```
4
```

```
Chapter 2: Mechanical Specifications
```

**2.3.3 COM Con**

```
COM5 , COM6
Pin Signal Pin Signal
1 DCD# 2 DSR#
3 RXD 4 RTS#
5 TXD 6 CTS#
7 DTR# 8 RI#
9 GND 10 GND
RS232 / RS422 / RS485 Connector 2x5 10-pin box header, 2.0mm pitch
Pin RS232 Definition RS422 / 485 Full Duplex Definition RS485 Half Duplex Definition
1 DCD# TX- DATA-
2 DSR#
3 RxD TX+ DATA+
4 RTS#
5 TxD RX+
6 CTS#
7 DTR# RX-
8 RI#
9 GND GND GND
10 GND GND GND
```

```
1 2
```

```
Chapter 2: Mechanical Specifications
```

```
COM1_2_3
RS232 / RS422 / RS485 Connector Type: 9-pin D-Sub
```

```
Pin RS232 Definition RS422 / 485 Full Duplex Definition RS485 Half Duplex Definition
1 DCD# TX- DATA-
2 RxD TX+ DATA+
3 TxD RX+
4 DTR# RX-
5 GND GND GND
6 DSR#
7 RTS#
8 CTS#
9 RI#
```

```
1 5
```

```
6 9
```

```
1 5
```

```
6 9
```

```
1 5
```

```
6 9
```

**COM1 , COM2 , COM3**

```
Chapter 2: Mechanical Specifications
```

**2.3.4 SF100 SPI Con**

```
JP1
Pin Signal Pin Signal
1 Power ( 3V ) 2 GND
3 CS# 4 CLK
5 MISO 6 MOSI
7 NC 8 SPI_GATE#
```

```
AT_ATX
AT / ATX Power Mode Switch
Switch Definition
```

```
1 - 2 (Left) ATX Power Mode(Default)
```

```
2 - 3 (Right) AT Power Mode
```

```
1
```

```
2
7
```

```
8
```

**Chapter 2: Mechanical Specifications**

```
CAR_PWR
PC / Car Mode Switch
Switch Definition
1 - 2 (Left) PC Power Mode(Default)
```

```
2 - 3 (Right) Power Ignition Mode
```

```
LINE_OUT
Line-out Jack (Green) Connector Type:
5 - pin Phone Jack
Pin Definition
1 GND
2 OUT_R
3 GND
4 GND
5 OUT_L
```

```
Chapter 2: Mechanical Specifications
```

```
MIC_IN
```

```
CLR_CMOS
```

```
Switch Definition
1 , 2 RTCRST-L
3 , 4 GND
```

```
Pin Definition
1 MICIN_L
2 GND
3 MICIN_R
```

**Mic-in Connector**

**Clear BIOS Switch**

```
1
```

```
3
```

```
Chapter 2: Mechanical Specifications
```

```
PWR_SW1
Power Button
```

```
PWR_SW2
Remote Power Switch Type:
Terminal Block 1x2 2-pin, 3.5mm pitch
Pin Definition
1 Power Button
2 GND
```

```
Pin Definition Pin Definition
1 NC 4 GND
```

(^2) ButtonPower 5 NC
3 NC 6 GND
**Power Switch**

```
Chapter 2: Mechanical Specifications
```

```
PWR_SW3
For RCO- 3000 - RPL
```

```
RESET
Pin Definition
1,2 RESET
3,4 GND
```

```
Pin Definition
1 Power Button
2 PWR_LED
3 HDD_LED
4 GND
```

**Power Switch**

**Reset Switch**

```
Chapter 2: Mechanical Specifications
```

```
USB3_1 , USB3_2 , USB3_3 :
USB3.1 Connector, GEN2 x6 ports, Type A
```

```
CN1 , CN2
USB3.0 Connector 2x5 10-pin header,
2.0mm pitch
```

```
Pin Definition Pin Definition
1 +5V 6 USB3_RX+
2 USB2_D- 7 GND
3 USB2_D+ 8 USB3_TX-
4 GND 9 USB3_TX+
5 USB3_RX-
```

```
Pin Definition Pin Definition
1 +5V 2 USB3_TX-
3 USB_D- 4 USB3_TX+
5 USB_D+ 6 GND
7 GND 8 USB3_RX-
9 NC 10 USB3_RX+
```

**USB Connector**

```
1
```

```
9
4
```

```
5
```

```
Chapter 2: Mechanical Specifications
```

```
LAN1 LAN2
LAN Ports Connector Type:RJ45 port
with LEDs
```

```
DP1 , DP2 , DP3
```

```
Pin Definition
1 LAN1_MDI0P
2 LAN1_MDI0N
3 LAN1_MDI1P
4 LAN1_MDI2P
5 LAN1_MDI2N
6 LAN1_MDI1N
7 LAN1_MDI3P
8 LAN1_MDI3N
```

```
Pin Definition Pin Definition
1 DP_LANE0_P 11 GND
2 GND 12 DP_LANE3_N
3 DP_LANE0_N 13 GND
4 DP_LANE1_P 14 GND
5 GND 15 DP_AUX_P
6 DP_LANE1_N 16 GND
7 DP_LANE2_P 17 DP_AUX_N
8 GND 18 DP_HPD
9 DP_LANE2_N 19 GND
10 DP_LANE3_P 20 +3.3V
```

**LAN Connector**

**Display Port Connector**

```
8 1
```

```
Chapter 2: Mechanical Specifications
```

**Display Port / HDMI Connector**

```
DP_HDMI
Pin Definition Pin Definition
1 DP 0_P / HDMI 2_P 11 GND
2 GND 12 DP 3_N / HDMI CK_N
3 DP 0_N / HDMI 2_N 13 GND / CEC
4 DP 1_P / HDMI 1_P 14 GND / Reserved
5 GND 15 DP_AUX_P / SCL
6 DP 1_N / HDMI 1_N 16 GND / SDA
7 DP 2_P / HDMI 0_P 17 DP_AUX_N / GND
8 GND 18 DP_HPD / +5V
9 DP 2_N / HDMI 0_N 19 GND / HPD
10 DP 3_P / HDMI CK_P 20 +3.3V / NC
```

```
Chapter 2: Mechanical Specifications
```

**Digital Input / Output Connector**

```
DIO : Digital Input / Output Connector
Type: Terminal Block 2x9 18-pin, 3.5mm pitch
```

```
Pin Definition Pin Definition
1 DIN1 2 DOUT1
3 DIN2 4 DOUT2
5 DIN3 6 DOUT3
7 DIN4 8 DOUT4
9 DIN5 10 DOUT5
11 DIN6 12 DOUT6
13 DIN7 14 DOUT7
15 DIN8 16 DOUT8
17 DC power input (+5V~+24V) 18 GND
```

```
1
```

```
2
```

```
17
```

```
18
```

**Chapter 2: Mechanical Specifications**

```
CAN1 CAN2
```

```
FAN_SIO
```

```
Pin Signal
1 GND
2 +12V
3 Sense
4 Control
```

```
Pin Signal
1 CAN_L
2 CAN_H
```

### CAN1

### CAN2

```
1
```

```
2
```

```
1
```

```
2
```

```
4 1
```

**Chapter 2: Mechanical Specifications**

```
SMB
Pin Signal
1 NC
2 SMB_CLK
3 SMB_DATA
4 GND
```

```
Act LED Status Definition
Blinking Yellow Data Activity
Off No Activity
```

```
Link LED Status LAN1 LAN2
Steady Green 2.5Gbps Network Link 2.5Gbps Network Link
Steady Orange 1Gbps Network Link 1Gbps Network Link
Off 100Mbps Network Link 100Mbps Network Link
```

```
4 1
```

```
LED Status
```

```
Chapter 2: Mechanical Specifications
```

```
Pin Definition
1 WDTOUT LED+
2 WDTOUT LED-
```

```
PWR_LED1
Power LED Status
Pin Definition
1 POWER LED +
2 POWER LED -
```

```
HDD_LED1
HDD Access LED Status
Pin Definition
1 HDD LED+
2 HDD LED-
```

```
WDT_LED
WDTOUT LED Status
```

**LED Status**

```
Chapter 2: Mechanical Specifications
```

**SIM Card Socket**

```
SIM1 (for Bottom size M.2 B Key)
Pin Definition Pin Definition
C1 UIM_PWR C6 UIM_VPP
C2 UIM_RESET C7 UIM_DATA
C3 UIM_CLK CD NC
C5 GND COM GND
```

```
C1
COM
```

```
Chapter 2: Mechanical Specifications
```

**Dual Nano SIM Card Socket**

```
SIM2 (for Top size M.2 B Key)
Pin Definition Pin Definition
C1 UIM_PWR C6 UIM_VPP
C2 UIM_RESET C7 UIM_DATA I/O
C3 UIM_CLK CD Card Detect Switch
C5 GND
```

```
Chapter 2: Mechanical Specifications
```

**M.2 B Key Socket**

```
M2_KB2
Pin Definition Pin Definition
1 CONFIG_3 2 +3.3V
3 GND 4 +3.3V
5 GND 6 FULL_CARD_POWER_OFF#
7 USB_D+ 8 W_DISABLE1#
9 USB_D- 10 WWAN_LED#
11 GND 20 NC
21 CONFIG_0 22 NC
23 GPIO_11(0/1.8V) 24 NC
25 DPR 26 W_DISABLE2#
27 GND 28 NC
29 PERn1/USB3.0-Rx- 30 USIM1_RST
31 PERp1/USB3.0-Rx+ 32 USIM1_CLK
33 GND 34 USIM1_DATA
```

```
1
```

```
75
```

```
2
```

```
74
```

**Chapter 2: Mechanical Specifications**

```
35 PETn1/USB3.0-Tx- 36 USIM1_VDD
37 PETp1/USB3.0-Tx+ 38 NC
39 GND 40 USIM2_DET
41 PERn0 42 USIM2_DATA
43 PERp0 44 USIM2_CLK
45 GND 46 USIM2_RST
47 PETn0 48 USIM2_VDD
49 PETp0 50 PCIE_RST_N
51 GND 52 PCIE_CLKREQ_N
53 PCIE_REFCLK_M 54 PCIE_WAKE_N
55 PCIE_REFCLK_P 56 NC
57 GND 58 NC
59 NC 60 NC
61 NC 62 NC
63 NC 64 NC
65 NC 66 USIM1_DET
67 NC 68 SUSCLK(32kHz)
69 CONFIG_1 70 +3.3VAUX
71 GND 72 +3.3VAUX
73 GND 74 +3.3VAUX
75 CONFIG_2
```

```
Chapter 2: Mechanical Specifications
```

**M.2 E Key Socket**

```
M2_KE
Pin Definition Pin Definition
1 GND 2 +3.3VAUX
3 USB2_D+ 4 +3.3VAUX
5 USB2_D- 6 NC
7 GND 8 I2S2_SCLK
9 CNV_WR_1_DN 10 CNV_RF_RESET#
11 CNV_WR_1_DP 12 I2S2_RXD
13 GND 14 MODEM_CLKREQ
15 CNV_WR_0_DN 16 NC
17 CNV_WR_0_DP 18 GND
19 GND 20 UART_WAKE_L
21 CNV_WR_CLK_DN 22 CNV_BRI_RSP
23 CNV_WR_CLK_DP 32 CNV_RGI_DT
33 GND 34 CNV_RGI_RSP
```

```
1
```

```
75
```

```
2
```

```
74
```

**Chapter 2: Mechanical Specifications**

```
35 TxP0 36 CNV_BRI_DT
37 TxN0 38 CL_RST#
39 GND 40 CL_DATA
41 RxP0 42 CL_CLK
43 RxN0 44 CNV_PA_BLANKING
45 GND 46 CNV_MFUART2_TXD
47 REFCLK0+ 48 CNV_MFUART2_RXD
49 REFCLK0- 50 SUSCLK
51 GND 52 PERST0#
53 NC 54 M2_KEY-E_BT_DIS2#
55 WAKE0# 56 M2_KEY-E_WIFI_DIS1#
57 GND 58 SMBDATAS_DUAL
59 CNV_WT_1_DN 60 SMBCLKS_DUAL
61 CNV_WT_1_DP 62 SMBALERT#
63 GND 64 Pull Low
65 CNV_WT_0_DN 66 PERST1#
67 CNV_WT_0_DP 68 NC
69 GND 70 WAKE1#
71 CNV_WT_CLK_DN 72 +3.3VAUX
73 CNV_WT_CLK_DP 74 +3.3VAUX
75 GND
```

```
Chapter 2: Mechanical Specifications
```

**M.2 B Key Socket**

```
M2_KB1
Pin Definition Pin Definition
1 CONFIG_3 2 +3.3V
3 GND 4 +3.3V
5 GND 6 FULL_CARD_POWER_OFF#
7 USB_D+ 8 W_DISABLE1#
9 USB_D- 10 WWAN_LED#
11 GND 20 NC
21 CONFIG_0 22 NC
23 GPIO_11(0/1.8V) 24 NC
25 DPR 26 NC
27 GND 28 P_UIM_VPP
29 PERn1 30 USIM1_RST
31 PERp1 32 USIM1_CLK
33 GND 34 USIM1_DATA
```

```
1
```

```
75
```

```
2
```

```
74
```

**Chapter 2: Mechanical Specifications**

```
35 PETn1 36 USIM1_VDD
37 PETp1 38 NC
39 GND 40 NC
41 PERn0/SATA-B+ 42 NC
43 PERp0/SATA-B- 44 NC
45 GND 46 NC
47 PETn0/SATA-A- 48 NC
49 PETp0/SATA-A+ 50 PCIE_RST_N
51 GND 52 PCIE_CLKREQ_N
53 PCIE_REFCLK_M 54 PCIE_WAKE_N
55 PCIE_REFCLK_P 56 NC
57 GND 58 NC
59 NC 60 NC
61 NC 62 NC
63 NC 64 NC
65 NC 66 USIM1_DET
67 NC 68 SUSCLK(32kHz)
69 CONFIG_1 70 +3.3VAUX
71 GND 72 +3.3VAUX
73 GND 74 +3.3VAUX
75 CONFIG_2
```

```
Chapter 2: Mechanical Specifications
```

**PCI-Express x1 Slot R/A**

```
LAN_L1
Pin Definition Pin Definition
B1 TxP0 A1 RxP0
B2 TxN0 A2 RxN0
B3 GND A3 PSE_OUT1
B4 TxP1 A4 RxP1
B5 TxN1 A5 RxN1
B6 GND A6 PSE_OUT2
B7 TxP2 A7 RxP2
B8 TxN2 A8 RxN2
B9 NC A9 PSE_OUT3
B10 TxP3 A10 RxP3
B11 TxN3 A11 RxN3
B12 WAKE# A12 PSE_OUT4
B13 RESET# A13 REFCLK+
B14 +3.3V A14 REFCLK-
B15 +3.3V A15 SMB_DATA
B16 +5V A16 SMB_CLK
B17 +56V A17 +3.3VAUX
B18 +56V A18 +3.3VAUX
```

```
Chapter 2: Mechanical Specifications
```

**PCI-Express x4 Slot**

```
PSE_M1
Pin Definition Pin Definition
B1 9_48VSB_IN A1 9_48VSB_IN
B2 9_48VSB_IN A2 9_48VSB_IN
B3 9_48VSB_IN A3 9_48VSB_IN
B4 9_48VSB_IN A4 9_48VSB_IN
B5 9_48VSB_IN A5 9_48VSB_IN
B6 9_48VSB_IN A6 9_48VSB_IN
B7 9_48VSB_IN A7 9_48VSB_IN
B8 9_48VSB_IN A8 9_48VSB_IN
B9 9_48VSB_IN A9 9_48VSB_IN
B10 9_48VSB_IN A10 9_48VSB_IN
B11 GND A11 GND
B12 GND A12 GND
B13 GND A13 GND
```

**Chapter 2: Mechanical Specifications**

```
B14 GND A14 GND
B15 GND A15 GND
B16 GND A16 GND
B17 GND A17 GND
B18 GND A18 GND
B19 GND A19 GND
B20 GND A20 GND
B21 I2C DATA A21 5V
B22 I2C CLOCK A22 5V
B23 12V A23 5V
B24 12V A24 3.3V
B25 PSE_OUT1 A25 3.3V
B26 PSE_OUT2 A26 3.3V
B27 PSE_OUT3 A27 56V
B28 PSE_OUT4 A28 56V
B29 PSE_OUT5 A29 56V
B30 PSE_OUT6 A30 56V
B31 PSE_OUT7 A31 56V
B32 PSE_OUT8 A32 56V
```

```
Chapter 2: Mechanical Specifications
```

**SATA with Power Connector**

```
SATA
Pin Definition Pin Definition
1 GND 12 GND
2 TxP 13 GND
3 TxN 14 +5V
4 GND 15 +5V
5 RxN 16 +5V
6 RxP 17 GND
7 GND 18 GND
8 NC 19 GND
9 NC 20 NC
10 DEVSLP 21 NC
11 GND 22 NC
```

```
Chapter 2: Mechanical Specifications
```

```
OOB
```

```
JP4 OOB Auto Link
Pin Signal
1 COM4_Rx
2 COM4_Tx
3 GND
```

```
Pin Signal
1 5V
2 GND
3 PWRBTN#
4 SLP_RSTBTN#
5 SYS_PWROK
```

```
JP5 OOB Remote Debug port
Pin Signal
1 COM1_Rx
2 COM1_Tx
3 GND
```

**OOB control signal**

```
5
```

```
1
```

```
3
1
```

```
Chapter 2: Mechanical Specifications
```

**COM1 or OOB Remote Debug port selection**

```
SW17
Pin ON OFF
1,4 COM1 Tx OOB Remote Tx
2,3 COM1 Rx OOB Remote Rx
```

```
ON
2
1
SW17
```

```
2PIN NHDS-02
1
```

```
2 3
4
```

## Chapter 3 System Setup

```
In order to prevent electric shock or system damage, before removing the
chassis cover, must turn off power and disconnect the unit from power source.
W
```

```
ARNING
```

```
Chapter 3: System Setup
```

### 3.1 Set torque force to 3.5 kgf-cm to execute all the screwing and

### unscrewing.

##### 3.2 Removing chassis bottom cover

1. Place the system faced upside down and unscrew the 6 screws (M3x5L) on the bottom cover.
2. Now you can remove the bottom cover.

**Chapter 3: System Setup**

##### 3.3 Removing chassis top cover

1. Unscrew the four screws (M3x5L) as highlighted below.
2. Hold the body of the system and remove from the external cover in an upward motion away from
   the external cover as pictured below.
3. Pictured below is the separated system body (left) and external cover (right).

**Chapter 3: System Setup**

##### 3.4 Installing CPU

1. CPU socket is located at the top side, as highlighted below.
2. Remove the CPU protective cover.
3. Press down the CPU socket lever in order to release the socket.

```
Chapter 3: System Setup
```

4. Insert CPU gently. (Pay attention to the CPU fool-proof notch)
5. Put the CPU retainer bracket back in place.
6. Press down the CPU socket lever in order to secure the socket.

7. Attach the thermal pad to the CPU and remove the plastic mold.
   (Note: Remove the plastic film of the thermal pad before attaching it to the CPU)
8. Place the designated heat block onto the CPU with thermal pad. Lock the heat block with three
   screws (M3x5L) as highlighted in red circles below. The three screws will safely lock the heat block
   onto the three copper studs that are screwed into the motherboard.
9. Attach the thermal pad to the CPU heat sink and remove the plastic mold.
   (Note: Remove the plastic film of the thermal pad before attaching it to the CPU heat sink)

**Chapter 3: System Setup**

```
Chapter 3: System Setup
```

##### 3.5 Installing SODIMM

1. Place the system body with SODIMM socket facing upward.
2. Insert memory module at a 45-degree angle.
3. Press the memory module vertically downward until you hear the “click” sound. Make sure the
   memory module is firmly in place.

**Chapter 3: System Setup**

4. Place the designated thermal pad heat block onto the Memory with thermal pad. Lock the heat
   block with four screws (M3x5L) as highlighted in red circles below. The four screws will safely lock
   the heat block onto the four copper studs that are screwed into the motherboard.
5. Attach the thermal pad to the Memory heat sink and remove the plastic mold.
   (Note: Remove the plastic film of the thermal pad before attaching it to the Memory heat sink)

```
Chapter 3: System Setup
```

```
M.2 B Key 2
```

##### 3.6 Installing 4G/5G Module and Antenna

**RCO- 3000 - RPL Series PCBA features two M.2 B Key slots, with the first one located on the top (M.2 B
Key 2) and the second on the back (M.2 B Key 1). We will focus on the M.2 B Key 2 slot at the top first.**

1. Place a copper pillar (M3x6.6L) at the location highlighted in the picture below.
2. Insert 4G/5G card at a 45-degree angle.

**Chapter 3: System Setup**

3. Press the 4G/5G card down and secure with one screw (M2x4L).
4. RCO- 3000 - RPL Series system has 5 antenna holes, 2 are located on the rear panel and the
   other 3 are located on the front panel as pictured below.
5. Remove antenna hole cover on the system panel.

**Chapter 3: System Setup**

6. Install the SMA female jack through the antenna holes, and then fasten on the SMA male plug.
7. Fix the end of the cable of the Wireless RF connector onto the communication module as shown in
   the picture below.
8. Assemble the antenna and SMA jack together, the outcome should look like the picture below.

RCO- 3000 - RPL lUser’s Manual
**Chapter 3: System Setup**

```
M.2 B Key 1
```

```
Now, let’s set up the other M.2 B Key slot at the back.
```

1. Place a copper pillar (M.3x6.6L) at the location highlighted below.
2. Insert 4G/5G card at a 45-degree angle.
3. Press the 4G /5G card down and secure with one screw (M2x4L).

**Chapter 3: System Setup**

4. Remove antenna hole cover on the system panel.
5. Install the SMA female jack through the antenna holes, and then fasten on the SMA male plug.
6. Fix the end of the cable of the Wireless RF connector onto the communication module as shown in the
   picture below.
7. Assemble the antenna and SMA jack together, the outcome should look like the picture below.

```
Chapter 3: System Setup
```

```
M.2 E Key
```

##### 3.7 Installing Wi-Fi Module and Antenna

**RCO- 3000 - RPL Series PCBA has an M.2 E Key slot on the top, which currently supports Wi-Fi
application.**

1. Insert Wi-Fi card at a 45-degree angle.
2. Press the Wi-Fi card down and secure with one screw (M2x4L).

**Chapter 3: System Setup**

3. Remove antenna hole cover on the system panel.
4. Install the SMA female jack through the antenna holes, and then fasten on the SMA male plug.
5. Fix the end of the cable of the Wireless RF connector onto the communication module as shown
   in the picture below.
6. Assemble the antenna and SMA jack together, the outcome should look like the picture below.

##### 3.8 Installing HDD on internal SATA HDD bay

1. One internal SATA HDD bay is available for RCO- 3000 - RPL series.
2. Unscrew the four screws (M3x5L) to remove the internal SATA HDD bay.
3. Lock the 2.5” HDD with HDD bracket using four screws (M3x4L).

```
Chapter 3: System Setup
```

**Chapter 3: System Setup**

4. Install the HDD bracket following the direction below.
5. Fasten the four screws to lock the internal HDD bracket.

```
Chapter 3: System Setup
```

##### 3.9 Installing HDD on removable SATA HDD tray

1. One removable SATA HDD tray available for RCO- 3000 - RPL Series.
   Open the tray lock (as highlighted in red circle) ,and remove the tray.
2. Unlock the drive lock and insert the HDD/SSD.
3. Slide the HDD tray back and close the tray lock.

```
Chapter 3: System Setup
```

##### 3.1 0 Assemble chassis top cover

1. Pictured below is the separated system body (left) and external cover (right).
2. Turn the system body upside down and place it vertically towards the external cover.
3. Secure the system body with four screws (M3x5L).

##### 3.11 Assembling chassis bottom cover

1. Place the bottom cover according to the below direction and make sure the rail is facing inside the
   system.
2. Secure the bottom cover with the six screws (M3x5L).

```
Chapter 3: System Setup
```

```
Chapter 3: System Setup
```

##### 3.1 2 Installing SIM card

1. Pull out the SIM card tray in order to put the Mini SIM cards.
2. Place the Mini SIM card on the front of the tray for SIM1.
3. Place the Mini SIM card on the back of the tray for SIM2.

```
Chapter 3: System Setup
```

###### SIM Card Socket Number Matching M.2 B Key slots

### SIM 1/2 M.2 B Key 2

### SIM 3 M.2 B Key 1

4. Insert SIM card into the socket for SIM3.
5. Please note that the installation of SIM cards has to match the installation of M.2 B Key slots

##### 3.13 SIM OS Settings

Place the Mini SIM card on front of the tray for SIM1. The Cellular menu will show the SIM 1/2 option.

When the Mini SIM card on the front tray for SIM1 is inserted,
the operating system will connect to SIM 1.

```
Chapter 3: System Setup
```

### SIM 1

Place the Mini SIM card on back of the tray for SIM2. The Cellular menu will show the SIM 1/2 option.

When the Mini SIM card on the back tray for SIM2 is inserted,
the operating system will connect to SIM 2.

```
Chapter 3: System Setup
```

### SIM 2

Insert a SIM card into the SIM 3 socket. The Cellular menu will show the SIM 1/2 option. Once the SIM
card is inserted, the operating system will automatically connect to SIM1 (as shown in the image).

```
Chapter 3: System Setup
```

### SIM 1

When SIM cards are inserted into both the SIM1/2 slot and the SIM3 socket, the Cellular menu will
display two separate SIM options. Users can select which SIM card to use for external connections as
shown in the image below.

```
Chapter 3: System Setup
```

### 1

### 2

##### 3.14 Installing Wall-Mount Kit

1. The Wall-Mount Kit is provided with the RCO- 3000 - RPL as a standard package.
2. Place the system upside down so you can see the bottom cover. Secure the wall-mount kit with
   eight screws (M3x5L, Nylok) as highlighted in red circles below.

```
Chapter 3: System Setup
```

```
M4*13
```

##### 3.15 Installing DIN rail holder

1. Din rail holder is available for RCO- 3000 - RPL series as optional accessories.
2. Place the system upside down so you can see the bottom cover with two screw holes for din rail
   holder.

**Chapter 3: System Setup**

```
(3-DINR-0004) DinRail-2MountingKit
```

3. Place the din rail holder on top of the bottom cover and secure with two screws (M4x5L, Nylok).

**Chapter 3: System Setup**

**Chapter 3: System Setup**

### Appendix A Optional CANBus Cable

1. 1 - TCAN00001 > Dual Channel
2. 1 - TCAN00002 > Single Channel

```
1
```

```
5
```

```
6
9
```

```
1
```

```
5
```

```
6
9
```

```
2 1 2 1 2 1
```

```
Green
White
Blue
White
```

```
Green
White
```

## Chapter 4 BIOS Setup

##### 4.1 BIOS Introduction

```
The BIOS provides an interface to modify the configuration. When the battery is removed, all the
parameters will be reset.
BIOS Setup
Power on the embedded system and by pressing <Del>immediately allows you to enter the
setup screens.If the message disappears before you respond and you still wish to enter the
Setup, restart the system by turning it OFF and ON or pressing the RESET button.
You may also restart the system by simultaneously pressing <Ctrl>, <Alt>, and <Delete> keys.
```

```
Main Setup
The main menu lists the setup functions you can make changes to. You can use the arrow keys
( ↑↓ ) to select the item. The on-line description of the highlighted setup function is displayed
at the bottom of the screen.
General Help <F1>
The BIOS setup program provides a General Help screen. You can call up this screen from any
menu by simply pressing <F1>. The Help screen lists the appropriate keys to use and the possible
selections for the highlighted item. Press <Esc> to exit the Help screen.
```

**Chapter 4: BIOS Setup**

### Control Keys

```
<→> <←> Select Screen
<↑> <↓> Select Item
<Enter> Select
<Page Up/+> Increases the numeric value or makes changes
<Page Down/-> Decreases the numeric value or makes changes
<F1> General Help
<F2> Previous Value
<F3> Load Optimized Defaults
<F4> Save Configuration and Exit
<Tab> Select Setup Fields
<Esc> Exit BIOS Setup
```

##### 4.2 Main Setup

```
Press <Del> to enter BIOS CMOS Setup Utility. The Main setup screen is showed as following
when the setup utility is entered. System Date/Time is set up in the Main Menu.
```

```
■ System Date
Set the system date. Please use <Tab> to switch between data elements.
■ System Time
Set the system time. Please use <Tab> to switch between time elements.
```

**Chapter 4: BIOS Setup**

##### 4.3 Advanced Setup

**Chapter 4: BIOS Setup**

###### 4.3.1 Connectivity Configuration

**Chapter 4: BIOS Setup**

```
Item Options Description
CNViMode Disable Integrated,
Auto Detection [Default]
This option configures Connectivity. [Auto
Detection] means that if Discrete solution is
discovered it will be enabled by default.
Otherwise Integrated solution (CNVi) will be
enabled; [Disable Integrated] disables
Integrated Solution.
NOTE: When CNViis present, the GPIO pins
that are used for radio interface cannot be
assigned to the other native function.
Wi-Fi Core Enabled [Default] ,
Disabled
```

```
This is an option intended to Enable/Disable
Wi-Fi Core in CNVi
BT Core Enabled [Default] ,
Disabled
This is an option intended to Enable/Disable BT
Core in CNVi.
```

#### 4.3.2 CPU Configuration

**Chapter 4: BIOS Setup**

```
Item Options Description
Intel (VMX) Virtualization
Technology
Disabled,
Enabled [Default]
When enabled, a VMM can utilize the
additional hardware capabilities provided by
Virtualization Technology.
Active Performance-cores All [Default] ,
5,4,3,
2,1
```

```
Number of P-cores to enable in each processor
package. Note: Number of Cores and E-cores are
looked at together. When both are {0,0}, Pcode
will enable all cores.
Active Efficient-cores All [Default] ,
3,2,
1,0
```

```
Number of E-cores to enable in each processor
package. Note: Number of Cores and E-cores are
looked at together. When both are {0,0}, Pcode
will enable all cores.
Hyper-Threading Disabled,
Enabled [Default]
Enabled for Windows XP and Linux (OS
optimized for Hyper-Threading Technology)
and Disabled for other OS (OS not optimized
for Hyper-Threading Technology).
Intel(R) SpeedStep(tm) Disabled,
Enabled [Default]
Allows more than two frequency ranges to be
supported.
Intel(R) Speed Shift Technology Disabled,
Enabled [Default]
Enable/Disable Intel(R) Speed Shift Technology
support. Enabling will expose the CPPC v2
interface to allow for hardware controlled P-
states.
Turbo Mode Disabled,
Enabled [Default]
Enable/Disable processor Turbo Mode.
C states Disabled,
Enabled [Default]
Enable/Disable CPU Power Management. Allows
CPU to go to C states when it's not 100% utilized.
```

```
4.3.2.1 Efficient-core Information
```

```
4.3.2.2 Performance-core Information
```

**Chapter 4: BIOS Setup**

#### 4.3.3 PCH-FW Configuration

**Chapter 4: BIOS Setup**

```
Item Options Description
AMT BIOS Features Disabled,
Enabled [Default]
When disabled AMT BIOS Features are no longer
supported and user is no longer able to access
MEBxSetup.
Note:Thisoption does not disable Manageability
Features in FW.
Unconfigure ME Disabled [Default] ,
Enabled
Unconfigure ME with resetting MEBxpassword
to default on next boot.
```

#### 4.3.4 Trusted Computing

```
Chapter 4: BIOS Setup
```

```
Item Options Description
Security Device Support Enabled,
Disabled [Default] ,
Enable/Disable BIOS support for security
device. O.S. will not show Security
Device.TCGEFI protocol and INT1A interface
will not be available.
Pending operation None [Default] ,
TPM Clear
Schedule an Operation for the Security Device.
NOTE: Your Computer will reboot during restart
in order to change State of Security Device.
```

#### 4.3.5 ACPI Settings

**Chapter 4: BIOS Setup**

```
Item Options Description
Enable Hibernation Disabled ,
Enabled [Default],
Enables or Disables System ability to
Hibernate (OS/S4 Sleep State). This option
may not be effective with some operating
systems.
ACPI Sleep State Suspend Disabled,
S3 (Suspend to RAM )[Default]
Select the highest ACPI sleep state the
system will enter when the SUSPEDN
button is pressed.
```

**Chapter 4: BIOS Setup**

#### 4.3.6 Super IO Configuration

```
This setting allows you to select options for the Super IO Configuration, and change the value of
the selected option.
```

```
Item Options Description
Watch Dog Timer Disabled [Default],
Enabled
Enabled or Disabled Watch Dog Timer
function.
Watch Dog Timer Count Mode Second Mode [Default] ,
Minute Mode
Select Second Mode or Minute Mode.
```

```
Watch Dog Timer Time out
Value
20~255(Second) [Default],
1~255(Minute)
Watch Dog Timer Time out Value.
```

```
Item Description
Serial Port 1 Configuration(COM Port / OOB
debug: JP5)
Set Parameters of Serial Port 1 (COMA /OOB debug:JP5).
Serial Port 2 Configuration Set Parameters of Serial Port 2 (COMB).
Serial Port 3 Configuration Set Parameters of Serial Port 3 (COMC).
Serial Port 4 Configuration(OOB Auto
Link:JP4)
Set Parameters of Serial Port 4 (COMD /OOB Auto Link:JP4)).
Serial Port 5 Configuration Set Parameters of Serial Port 5 (COME).
Serial Port 6 Configuration Set Parameters of Serial Port 6
```

```
■ Serial Port 1 Configuration
```

**Chapter 4: BIOS Setup**

```
Item Options Description
Serial Port Disabled,
Enabled [Default]
Enable or Disable Serial Port (COM).
Change Settings Auto [Default] ,
IO=3F8h; IRQ=4; ,
IO=3F8h; IRQ=3,4,5,6,7,9,10,11,12; ,
IO=2F8h; IRQ=3,4,5,6,7,9,10,11,12;,
IO=3E8h; IRQ=3,4,5,6,7,9,10,11,12;,
IO=2E8h; IRQ=3,4,5,6,7,9,10,11,12;
```

```
This item allows you to change the address &
IRQ settings ofthe specified serial port.
```

```
Device Type Select UART 232 [Default],
UART 422,
UART 485
```

```
Set the Serial Port to RS232 & RS422 & RS485
```

```
RS-485 Auto Flow
Function
Disabled,
Enabled [Default]
Enabled/Disabled RS485 Autoflow Function
```

```
■ Serial Port 2 Configuration
```

**Chapter 4: BIOS Setup**

```
Item Options Description
Serial Port Disabled,
Enabled [Default]
Enable or Disable Serial Port (COM).
Change Settings Auto [Default] ,
IO=2F8h; IRQ=3; ,
IO=3F8h; IRQ=3,4,5,6,7,9,10,11,12; ,
IO=2F8h; IRQ=3,4,5,6,7,9,10,11,12;,
IO=3E8h; IRQ=3,4,5,6,7,9,10,11,12;,
IO=2E8h; IRQ=3,4,5,6,7,9,10,11,12;
```

```
This item allows you to change the address &
IRQ settings ofthe specified serial port.
```

```
Device Type Select UART 232 [Default],
UART 422,
UART 485
```

```
Set the Serial Port to RS232 & RS422 & RS485
```

```
RS-485 Auto Flow
Function
Disabled,
Enabled [Default]
Enabled/Disabled RS485 Autoflow Function
```

```
■ Serial Port 3 Configuration
```

**Chapter 4: BIOS Setup**

```
Item Options Description
Serial Port Disabled,
Enabled [Default]
Enable or Disable Serial Port (COM).
Change Settings Auto [Default] ,
IO=3E8h; IRQ=7; ,
IO=3E8h; IRQ=3,4,5,6,7,9,10,11,12; ,
IO=2E8h; IRQ=3,4,5,6,7,9,10,11,12;,
IO=2F0h; IRQ=3,4,5,6,7,9,10,11,12;,
IO=2E0h; IRQ=3,4,5,6,7,9,10,11,12;
```

```
This item allows you to change the address &
IRQ settings ofthe specified serial port.
```

```
Device Type Select UART 232 [Default],
UART 422,
UART 485
```

```
Set the Serial Port to RS232 & RS422 & RS485
```

```
RS-485 Auto Flow
Function
Disabled,
Enabled [Default]
Enabled/Disabled RS485 Autoflow Function
```

```
■ Serial Port 4 Configuration
```

**Chapter 4: BIOS Setup**

```
Item Options Description
Serial Port Disabled,
Enabled [Default]
Enable or Disable Serial Port (COM).
Change Settings Auto [Default] ,
IO=2F0h; IRQ=7; ,
IO=3E8h; IRQ=3,4,5,6,7,9,10,11,12; ,
IO=2E8h; IRQ=3,4,5,6,7,9,10,11,12;,
IO=2F0h; IRQ=3,4,5,6,7,9,10,11,12;,
IO=2E0h; IRQ=3,4,5,6,7,9,10,11,12;
```

```
This item allows you to change the address &
IRQ settings ofthe specified serial port.
```

```
Device Type Select UART 232 [Default],
UART 422,
UART 485
```

```
Set the Serial Port to RS232 & RS422 & RS485
```

```
RS-485 Auto Flow
Function
Disabled,
Enabled [Default]
Enabled/Disabled RS485 Autoflow Function
```

```
■ Serial Port 5 Configuration
```

**Chapter 4: BIOS Setup**

```
Item Options Description
Serial Port Disabled,
Enabled [Default]
Enable or Disable Serial Port (COM).
Change Settings Auto [Default] ,
IO=2E0h; IRQ=7; ,
IO=3E8h; IRQ=3,4,5,6,7,9,10,11,12; ,
IO=3E8h; IRQ=3,4,5,6,7,9,10,11,12;,
IO=2F0h; IRQ=3,4,5,6,7,9,10,11,12;,
IO=2E0h; IRQ=3,4,5,6,7,9,10,11,12;
```

```
This item allows you to change the address &
IRQ settings ofthe specified serial port.
```

```
Device Type Select UART 232 [Default],
UART 422,
UART 485
```

```
Set the Serial Port to RS232 & RS422 & RS485
```

```
RS-485 Auto Flow
Function
Disabled,
Enabled [Default]
Enabled/Disabled RS485 Autoflow Function
```

```
■ Serial Port 6 Configuration
```

**Chapter 4: BIOS Setup**

```
Item Options Description
Serial Port Disabled,
Enabled [Default]
Enable or Disable Serial Port (COM).
Change Settings Auto [Default] ,
IO=2E8h; IRQ=7; ,
IO=3E8h; IRQ=3,4,5,6,7,9,10,11,12; ,
IO=2E8h; IRQ=3,4,5,6,7,9,10,11,12;,
IO=2F0h; IRQ=3,4,5,6,7,9,10,11,12;,
IO=2E0h; IRQ=3,4,5,6,7,9,10,11,12;
```

```
This item allows you to change the address &
IRQ settings ofthe specified serial port.
```

**Chapter 4: BIOS Setup**

#### 4.3.7 Hardware Monitor

```
These items display the current status of all monitored hardware devices/ components such as voltages
and temperatures.
```

```
Item Options Description
Smart Fan Function Disabled ,
Enabled [Default],
Enabled or Disable Smart Fan
```

**Chapter 4: BIOS Setup**

```
■ Smart Fan Mode Configuration
```

```
Item Options Description
FanSIOSmartFan
Control
Manual Mode,
Auto Duty-Cycle Mode [Default],
Smart Fan Mode Select
Temperature 1~4 1~100 Auto fan speed control. Temperature 1- 100
Duty Cycle 1~4 20~100 Auto fan speed control. Duty 20- 100
```

**Chapter 4: BIOS Setup**

#### 4.3.8 Power IGN Mode

```
Item Options Description
IGN Setting Read mode [Default]
Write IGN
Read IGN: BIOS will only read settings from IGN
module. Write IGN: BIOS will overwrite settings
in IGN module.
Power On Delay 10 Sec [Default]
20 Sec
30 Sec
40 Sec
50 Sec
1 Min
Manual Mode
```

```
Power On Delay Select
```

```
Manual Mode 10 Sec [Default] 10~60 Sec
Power Off Delay 3 Sec [Default] ,
1 Min,
5 Min,
10 Min,
30 Min,
1 Hour,
2 Hour,
Manual Mode
```

```
Power Off Delay Select
```

```
Manual Mode 3 Sec [Default] 3~7200 Sec
```

**Chapter 4: BIOS Setup**

#### 4.3.9 Wake system from S5

```
Item Options Description
Wake system from S5 Disabled [Default] ,
Fixed Time,
Dynamic Time,
ByPass
```

```
Enable or disable System wake on alarm event.
Select FixedTime, system will wake on the
hr::min::sec specified. Select DynamicTime,
System will wake on the current time +
Increase minute(s),Bypass : BIOS will not
control RTC wake function during system
shutdown
Wake up day 0[Default] Date (of month) Alarm (0 is mean daily or you
can setup a specific month)
Wake up hour 0[Default] select 0-23 For example enter 3 for 3am and 15
for 3pm
Wake up minute 0[Default] select 0-59 for Minute
```

```
Wake up second 0[Default] select 0-59 for Second
```

```
Wake up minute
increase
0[Default] 1 - 5
```

### 4.3.10 Serial Port Console Redirection

**Chapter 4: BIOS Setup**

```
Item Options Description
Console Redirection Disabled [Default],
Enabled
These items allows you to enable or disable
COM1 console redirection
```

#### 4.3.11 USB Configuration

**Chapter 4: BIOS Setup**

```
Item Options Description
Legacy USB Support Enabled [Default]
Disabled
Auto
```

```
Enables Legacy USB support. AUTO option
disables legacy support if no USB devices are
connected. DISABLE option will keep USB
devices available only for EFI applications.
XHCI Hand-off Enabled [Default]
Disabled
This is a workaround for OSewwithout XHCI
hand-off support. The XHCI ownership change
should be claimed by XHCI driver.
USB Mass Storage
Driver Support
Enabled [Default]
Disabled
Enable/Disable USB Mass Storage Driver
Support.
USB transfer time-out 1 sec ,
5 sec ,
10 sec ,
20 sec [Default]
```

```
The time-out value for Control, Bulk, and
Interrupt transfers.
```

```
Device reset time-out 10 sec ,
20 sec [Default] ,
30 sec,
40 sec
```

```
USB mass storage device Start Unit command
time-out.
```

```
Device power-up delay Auto [Default]
Manual
Maximum time the device will take before it
properly reports itself to the Host Controller.
‘Auto’ uses default value: for a Root port it is
100ms, for a Hub port the delay is taken form
Hub descriptor.
```

#### 4.3.12 Network Stack Configuration

**Chapter 4: BIOS Setup**

```
Item Options Description
Network Stack Disabled [Default] ,
Enabled
Enable/Disable UEFI Network Stack.
IPv4 PXE Support Disabled [Default] ,
Enabled
Enable/Disable IPv4 PXE boot support. If
disabled, IPv4 PXE boot support will not be
available.
IPv4 HTTP Support Disabled [Default] ,
Enabled
Enable/Disable IPv4 HTTP boot support. If
disabled, IPv4 HTTP boot support will not be
available.
IPv6 PXE Support Disabled [Default] ,
Enabled
Enable/Disable IPv4 PXE boot support. If
disabled, IPv6 PXE boot support will not be
available.
IPv6 HTTP Support Disabled [Default] ,
Enabled
Enable/Disable IPv6 HTTP boot support. If
disabled, IPv6 HTTP boot support will not be
available.
PXE boot wait time 0[Default] Wait time in seconds to press ESC key to
abort the PXE boot. Use either +/-or numeric
keys to set the value.
Media detect count 1[Default] Number of times the presence of media will
be checked. Use either +/-or numeric keys to
set the value.
```

#### 4.3.13 NVMeConfiguration...............................................................................

**Chapter 4: BIOS Setup**

#### 4.3.14 RST (UEFI RAID) Configuration

```
How to set the UEFI RAID:
```

1. When set to “Enable VMD controller“, please save change reset system.
2. After reboot the system, please into BIOS utility and then will see “Intel (R) Rapid Storage
   Technology”

**Chapter 4: BIOS Setup**

3. Into Intel(R) Rapid Storage Technology, and start create RAID volume.
4. Start Create the RAID

```
■Select Disk that you want to do the RAID
■Select [x]; No-Select [ ]
```

**Chapter 4: BIOS Setup**

### 4.4 Chipset

```
This section allows you to configure and improve your system and allows you to set up some
system features according to your preference.
```

#### 4.4.1 System Agent (SA) Configuration

**Chapter 4: BIOS Setup**

```
Item Options Description
Above 4GB MMIO BIOS
assignment
Enabled,
Disabled [Default]
Enable/Disable above 4GB
MemoryMappedIOBIOS assignment
This is enabled automatically when Aperture
Size is set to 2048MB.
```

```
■ Memory Configuration
```

**Chapter 4: BIOS Setup**

```
■ Graphic Configuration
```

**Chapter 4: BIOS Setup**

```
Item Options Description
GTT Size 2MB,
4MB,
8MB [Default]
```

```
Select the GTT Size.
```

```
Aperture Size 128MB,
256MB [Default] ,
512MB,
1024MB
```

```
Select the Aperture Size.
Note : Above 4GB MMIO BIOS assignment is
automatically enabled when selecting 2048MB
aperture. To use this feature, please disable
CSM Support.
DVMT Pre-Allocated 32M , 64M,96M,128M,
160M, 36M, 40M,44M,
48M,52M,56M,
60M [Default]
```

```
Select DVMT 5.0 Pre-Allocated (Fixed) Graphics
Memory size used by the Internal Graphics
Device.
DVMT Total GfxMem 128M,
256M [Default] ,
MAX
```

```
Select DVMT5.0 Total Graphic Memory size
used by the Internal Graphics Device.
DP1 selection DP,
HDMI[Default]
Selects DP1 function: DP or HDMI
```

■ **VMD Configuration**

**Chapter 4: BIOS Setup**

```
Item Options Description
Enable VMD
controller
Enabled [Default] ,
Disabled
Enable/Disable to VMD controller
```

#### 4.4.2 PCH-IO Configuration

```
■ PCI Express Configuration
```

**Chapter 4: BIOS Setup**

```
Item Options Description
Restore AC Power Loss Power On,
Power Off [Default] ,
Lase State
```

```
Specify what state to go to when power is re-
applied after a power failure (G3 state).
M.2 B-Key
Selection(M2_KB2)
USB + PCIe x1 [Default],
PCIe x2
Selects M.2 B-KEyfunction: PCIe x2 or USB +
PCIe x1.
M.2 B-Key
Selection(M2_KB1)
Sata [Default],
PCIe x2
Selects M.2 B-Key(KB1) function: PCIe x2 or Sata.
```

```
■PCI Express Configuration
```

**Chapter 4: BIOS Setup**

```
■ PCI Express Root Port 1 /3 /7 /21 /23 /27
```

**Chapter 4: BIOS Setup**

```
Item Options Description
PCI Express Root Port
1 /3 /7 /21 /23 /27
```

```
Disabled ,
Enabled [Default]
Control the PCI Express Root Port.
ASPM Disabled [Default] ,
L1,
Auto
```

```
Set the ASPM Level.
```

```
PCIe Speed Auto [Default] ,
Gen1 ,
Gen2,
Gen3,
Gen4
```

```
Configure PCIe speed.
```

■ **SATA Configuration**

```
Chapter 4: BIOS Setup
```

```
Item Options Description
SATA Controller(s) Enabled [Default]
Disabled
Enable/Disable SATA Device.
```

```
SATA Port Disabled,
Enabled [Default]
Enable/Disable SATA Port.
Hot Plug Disabled,
Enabled [Default]
Designates this port as Hot Pluggable.
SATA Device Type Hard Disk Drive [Default] ,
Solid State Drive
Identify the SATA port is connected to Solid
State Drive or Hard Disk Drive.
```

■ **HD Audio Configuration**

**Chapter 4: BIOS Setup**

```
Item Options Description
HD Audio Disabled ,
Enabled [Default]
Control Detection of the HD-Audio device.
Disabled = HDA will be unconditionally disabled
Enabled = HDA will be unconditionally enabled.
```

### 4.5 Security

```
Security menu allow users to change administrator password and user password settings.
```

```
■ Administrator Password
This item allows you to set Administrator Password.
■ User Password
This item allows you to set User Password.
```

**Chapter 4: BIOS Setup**

■ **Security Boot**

**Chapter 4: BIOS Setup**

```
Item Options Description
Secure Boot Disabled [Default] ,
Enabled
Secure Boot feature is Active if Secure Boot is
Enabled,PlatformKey(PK) is enrolled and the
System is in User mode.
The mode change requires platform reset
Secure Boot Mode Standard,
Custom [Default]
Secure Boot mode options:Standardor Custom.
In Custom mode, Secure Boot Policy variables
can be configured by a physically present user
without full authentication
```

```
■ Key Management
```

**Chapter 4: BIOS Setup**

```
Item Options Description
Factory Key Provision Disabled [Default] ,
Enabled
Install factory default Secure Boot keys after
the platform reset and while the System is in
Setup mode
```

### 4.6 Boot

```
This menu allows you to setup the system boot options.
```

**Chapter 4: BIOS Setup**

```
Item Options Description
Setup Prompt Timeout 1 [Default] Number of seconds to wait for setup activation
key. 65535(0xFFFF) means indefinite waiting.
Bootup NumLock State On [Default] ,
Off
Select the Keyboard NumLockstate.
Quiet Boot Disabled [Default] ,
Enabled
Enables or disables Quiet Boot option.
Fast Boot Disabled [Default] ,
Enabled
Enables/Disables boot with initialization of a
minimal set of devices required to launch active
boot option. Has no effect for BBS boot options.
```

### 4.7 Save & Exit

```
This setting allows users to configure the boot settings.
```

```
■ Save Changes and Reset
This item allows user to reset the system after saving the changes. This item allows user to
reset the system after saving the changes.
■ Discard Changes and Reset
This item allows user to reset the system without saving any changes.
■ Restore Defaults
Use this item to restore /load default values for all the setup options.
```

**Chapter 4: BIOS Setup**

### 4.8 MEBx....................................................................................................................

**Chapter 4: BIOS Setup**

```
Item Options Description
Intel(R) ME
Password
MEBxLogin
```

## Appendix WDT & GPIO

This appendix provides the sample codes of WDT (Watch
Dog Timer) and GPIO (General Purpose Input/ Output).

### WDT Sample Code

WDT Setting
PsuedoCode
// IO Address 0xA16 is time value(second)
// IO Address 0xA15 is WDT enable and configuration
Example, Set 0xA16=-0x02, 0xA15=0x31, it will reset after 2 seconds
#define TimePort 0xA16
#define TimeEnablePort 0xA15
//Set WDT Time Unit
buf1 = ReadByte(TimeEnablePort) & 0xf7; //Clear WDT mode.
// buf1 |= 0x08; //Bit3 :(1:Minute Mode/0:Second Mode)
WriteByte(TimeEnablePort, buf1);
//Set WDT Time Value
WriteByte(TimePort, 0x02); // Set 2 seconds
//Enable WDT
buf1 = ReadByte(TimeEnablePort);
buf1 |= 0x31;
//Bit5 :WD_EN,Ifthis bit is set to 1, the counting of watchdog time is enabled.
//Bit4 :WD_PULSE ,Select output mode (0: level, 1: pulse) of WDTRST# by setting this bit.
//Bit1~0: Select output pulse width of WDTRST#. 0: 1 ms, 1: 25 ms, 2: 125 ms, 3: 5 sec.
WriteByte(TimeEnablePort, buf1);
// Disable WDT
buf1 = ReadByte(TimeEnablePort); // Read current WDT setting
buf1= buf1& 0xDF; // Disable WDT by set WD_EN (bit 5) to 0.
WriteByte(TimeEnablePort, buf1); // Write back WDT setting.

**Appendix –WDT & GPIO**

**Appendix –WDT & GPIO**

### GPIO Sample Code

GPIO Setting

The GPIO function is provided by NuvotonM058SSAN , and it can be accessed through Smbus/I2C port.
The configuration on the RCO- 3000 - RPL is described as below.

**PsuedoCode**
#define GPI_ADDR 0x02 // Define Input port Address
#define GPO_ADDR 0x01 // Define Output port Address
#define Slave_ADDR0x40 //Slave Address = 0x40( 7 - bit address)

//Set DOUT1~DOUT8 Value

//Set GPO to 0x55
//set DOUT1, DOUT3, DOUT5, DOUT17 to high; Set DOUT2, DOUT4, DOUT6, DOUT8 to Low
SmbusWrite (Slave_ADDR,GPO_ADDR, 0x55);

// Read DIN1~DIN8 value

Data= SmbusReads(Slave_ADDR,GPI_ADDR); //Read DIN1~DIN8 value

```
Bit 7 Bit 6 Bit 5 Bit 4 Bit 3 Bit 2 Bit 1 Bit 0
DOUT8 DOUT7 DOUT6 DOUT5 DOUT4 DOUT3 DOUT2 DOUT1
```

```
Bit 7 Bit 6 Bit 5 Bit 4 Bit 3 Bit 2 Bit 1 Bit 0
DIN8 DIN7 DIN6 DIN5 DIN4 DIN3 DIN2 DIN1
```

Premio Inc. All Rights Reserved
**[http://www.premioinc.com](http://www.premioinc.com)**
