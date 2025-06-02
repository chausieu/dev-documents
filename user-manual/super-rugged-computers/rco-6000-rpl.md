# USER’S

# MANUAL

## RCO- 6000 - RPL

## AI Edge Inference Computer

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
- Chapter 1 Product Introductions - 1.1 Overview - 1.1.1 Key Feature - 1.2 Hardware Specification - 1.3 System I/O - 1.3.1 RCO- 6000 - RPL - 1.3.2 RCO- 6000 - RPL-2E16 - 1.3.3 RCO- 6000 - RPL-2E16-4B7M - 1.3.4 RCO- 6000 - RPL-2E16-2B15M / RCO- 6000 - RPL-2E16-2N15M - 1.3.5 RCO- 6000 - RPL-2E16-2PWR - 1.3.6 RCO- 6000 - RPL-4NH - 1.3.7 RCO- 6000 - RPL-4NS - 1.3.8 RCO- 6000 - RPL-8NS - 1.3.9 RCO- 6000 - RPL-A2000 - 1.3.10 RCO- 6000 - RPL-2NA2000 - 1.3.11 RCO- 6000 - RPL-4NA2000 - 1.3.12 EDGEBoostI/O Bracket (Available EDGEBoostI/O) - 1.4 Mechanical Dimension - 1.4.1 RCO- 6000 - RPL - 1.4.2 RCO- 6000 - RPL-2E16 - 1.4.3 RCO- 6000 - RPL-2E16-4B7M - 1.4.4 RCO- 6000 - RPL- 2 E16-2B15M / RCO- 6000 - RPL-2E16-2N15M - 1.4.5 RCO- 6000 - RPL- 2 E16-2PWR - 1.4. 6 RCO- 6000 - RPL-4NH................................................................................... - 1.4. 7 RCO- 6000 - RPL-4NS................................................................................... - 1.4. 8 RCO- 6000 - RPL-8NS.................................................................................. - 1.4. 9 RCO- 6000 - RPL-A2000............................................................................... - 1.4. 10 RCO- 6000 - RPL-2NA2000......................................................................... - 1.4. 11 RCO- 6000 - RPL-4NA2000.........................................................................
- Chapter 2 Mechanical Specifications.............................................................. - 2.1 Switch and connector Locations - 2.1.1 Top View - 2.1.2 Bottom View - 2.2 Connector / Switch Definition - 2.3 I/O Interface Descriptions
- Chapter 3 System Setup - unscrewing 3.1 Set torque force to 3.5 kgf-cm to execute all the screwing and - 4.3.4 SATA and RST Configuration - 4.3.5 RST (UEFI RAID) Configuration - 4.3.6 Trusted Computing - 4.3.7 ACPI Settings - 4.3.8 Super IO Configuration - 4.3.9 Hardware Monitor
  - 4.3.10. Power IGN Mode
    - 4.3.11 Wake system from S5
  - 4.3.12 Serial Port Console Redirection
    - 4.3.13 USB Configuration
    - 4.3.14 Network Stack Configuration
    - 4.3.15 CSM Configuration
    - 4.3.16 NVMe Configuration
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
- Chapter 4 BIOS Setup
  - 4.1 BIOS Introduction
  - 4.2 Main Setup
  - 4.3 Advanced Setup
    - 4.3.1 Connectivity Configuration
    - 4.3.2 CPU Configuration
    - 4.3.3 PCH-FW Configuration
  - 3.5 Install the first DRAM and the heating block internally
  - 3.6 Install the second DRAM externally
  - 3.7 Installing CPU & SODIMM heat block
  - 3.8 Installing M.2 SSD card
  - 3.9 Installing WiFiModule
  - 3.10 Installing Mini PCIe card / 4G LTE
  - 3.11 Installing Antenna
  - 3.12 Install HDD/SSD on the internal SATA bay
  - 3.13 Installing HDD on removable SATA HDD/SSD bay
  - 3.14 Installing HDD on removable HDD bay (RCO- 6000 - RPL-2E16-4B7M)
  - 3.15 Installing HDD on removable HDD bay (RCO- 6000 - RPL-2 E16-2B15M)
  - 3.16 Installing HDD on removable HDD bay (RCO- 6000 - RPL-8NS)
  - 3.17 Installing PCIe expansion Card (for RCO- 6000 - RPL-2E16)
  - 3.18 Installing PCIe/PCI expansion Card (for RCO- 6000 - RPL-8NS)
  - 3.19 Appendix A Optional CANBus Cable
  - 3.20 Appendix B Fan Power Cable
  - 3.21 Double Fan Module
  - 3.22 Installing wall mount kit
  - 3.23 AC Adapter with 3P terminal block
  - 3.24 AC Adapter with 4P terminal block
  - 3.25 AC Adapter with 5P terminal block
  - 3.2 Separating the expansion module from main computer module...............
  - 3.3 Removing chassis top cover
  - 3.4 Installing CPU

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
without the prior written permission of Premio Inc. Copyright © Premio Inc.

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
```

```
1.0 Manual Released 2023/10/
```

### Safety Precautions

```
Before installing and using the equipment, please read the following precautions:
```

```
⚫Put this equipment on a reliable surface during installation. Dropping it or letting it fall could
cause damage.
```

```
⚫The power outlet shall be installed near the equipment and shall be easily accessible.
⚫Turn off the system power and disconnect the power cord from its source before making any
```

```
installation. Be sure both the system and the external devices are turned OFF. Sudden surge
```

```
⚫of power could ruin sensitive components. Make sure the equipment is properly grounded.
⚫When the power is connected, never open the equipment. The equipment should be opened
```

```
only by qualified service personnel.
⚫Make sure the voltage of the power source is correct before connecting the equipment to the
```

```
power outlet.
```

```
⚫Disconnect this equipment from the power before cleaning. Use a damp cloth. Do not use
liquid or spray detergents for cleaning.
```

```
⚫Avoid the dusty, humidity and temperature extremes.
⚫Do not place heavy objects on the equipment.
```

```
⚫If the equipment is not used for long time, disconnect it from the power to avoid being
```

```
damaged by transient over-voltage.
⚫The storage temperature shall be above - 30 °C and below 85°C.
```

```
⚫The computer is provided with a battery-powered real-time clock circuit. There is a danger of
explosion if incorrectly replaced. Replace only with the same or equivalent type
```

```
recommended by the manufacturer.
```

```
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

1. Visit the Premio Incwebsite at [http://www.premioinc.comwhere](http://www.premioinc.comwhere) you can find the latest information about

```
the product.
```

2. Contact your distributor, our technical support team or sales representative for technical support if

```
you need additional assistance. Please have following information ready before you call:
```

```
⚫ Model name and serial number
```

```
⚫ Description of your peripheral attachments
```

```
⚫ Description of your software (operating system, version, application software, etc.)
```

```
⚫ A complete description of the problem
```

```
⚫ The exact wording of any error messages
```

### Conventions Used in this Manual

**Preface**

```
This indication alerts operators to an operation that, if not strictly observed,
may result in severe injury.
```

###### W

###### ARNING

```
This indication alerts operators to an operation that, if not strictly observed,
may result in safety hazards to personnel or damage to equipment.
```

###### CAUTION

```
This indication provides additional information to complete a task easily.
```

###### NOTE

```
Preface
```

### Package Contents

Before installation, please ensure all the items listed in the following table are included in the package.

```
Item Description Q’ty
```

```
1
```

```
Choosing one ：
```

- **RCO- 6000 - RPL** Superior FanlessIndustrial Computer
- **RCO- 6000 - RPL-2E16** Superior FanlessIndustrial Computer
- **RCO- 6000 - RPL-2E16-4B7M** Flash Storage Computing
- **RCO- 6000 - RPL-2E16-2B15M** Flash Storage Computing
- **RCO- 6000 - RPL-2E16-2N15M** Flash Storage Computing
- **RCO- 6000 - RPL-2E16-2PWR** GPU Computing System
- **RCO- 6000 - RPL-4NH** AI Edge Inference Computer
- **RCO- 6000 - RPL-4NS** AI Edge Inference Computer
- **RCO- 6000 - RPL- 8 NS** AI Edge Inference Computer
- **RCO- 6000 - RPL-A2000** GPU Computing System
- **RCO- 6000 - RPL-2NA2000** GPU Computing System
- **RCO- 6000 - RPL-4NA2000** GPU Computing System

```
1
```

```
2 Wall Mount Kit 1
```

```
3 Accessory Kit 1
```

```
4 DVI to VGA Adapter 1
```

### Ordering Information

```
Model No. Product Description
```

```
RCO- 6000 - RPL Industrial Computer w/ LGA 1700 for Intel 12/13/14thGen CPU & R680E
PCH
```

```
Available EDGEBoostI/O：
```

- 4L：4x LAN Ports
- 4P：4x LAN PoE Ports
- 8L：8x LAN Ports
- 8P：8x LAN PoE Ports
- D10G：2x 10Gb Ports
- 4U3：4x USB 3.2 Gen 1 Ports
- 8U3：8x USB 3.2 Gen 1 Ports

```
RCO- 6000 - RPL-2E16 Industrial Computer w/ LGA 1700 for Intel 12/13/14thGen CPU & R680E
PCH, 1x PCIe x16 (Gen4), 1x PCIe x1 (Gen3)
```

```
Available Expansion：
```

- 2E16：1x PCIe x16 (Gen4), 1x PCIe x1 (Gen3)
- 2E8 (Optional)： 1x PCIe x16 (8-lane, Gen4), 1x PCIe x8 (8-lane, Gen4)

```
Available EDGEBoostI/O：
```

- 4L：4x LAN Ports
- 4P：4x LAN PoE Ports
- 8L：8x LAN Ports
- 8P：8x LAN PoEPorts
- D10G：2x 10Gb Ports
- 4U3：4xUSB 3.2 Gen 1 Ports
- 8U3：8x USB 3.2 Gen 1 Ports
  - 4LM12：4x M12 LAN Ports
  - 4PM12：4x M12 LAN PoEPorts
  - 8LM12：8x M12 LAN Ports
  - 8PM12：8x M12 LAN PoE Ports
  - 5G：2x 5G SIM Slots
  - 2x M.2 B-Key (1x 5G SIM)
  - 1x M.2 M-Key (4-Lane)
  - 4LM12：4x M12 LAN Ports
  - 4PM12：4x M12 LAN PoEPorts
  - 8LM12：8x M12 LAN Ports
  - 8PM12：8x M12 LAN PoE Ports
  - 5G：2x 5G SIM Slots
  - 2x M.2 B-Key (1x 5G SIM)
  - 1x M.2 M-Key (4-Lane)

**Preface**

```
Model No. Product Description
```

```
RCO- 6000 - RPL-2E16-2PWR AI Edge Inference Computer with LGA 1700 for Intel 12/13/14thGen
Processor and R680E PCH, 1x PCIe x16 (Gen4), 1x PCIe x1 (Gen3),
2x Power input
```

```
Available Expansion：
```

- 2E16：1x PCIe x16 (Gen4), 1x PCIe x1 (Gen3)
- 2E8 (Optional)： 1x PCIe x16 (8-lane, Gen4), 1x PCIe x8 (8-lane, Gen4)

```
Available EDGEBoostI/O：
```

- 4L：4x LAN Ports
- 4P：4x LAN PoE Ports
- 8L：8x LAN Ports
- 8P：8x LAN PoEPorts
- D10G：2x 10Gb Ports
- 4U3：4x USB 3.2 Gen 1 Ports
- 8U3：8x USB 3.2 Gen 1 Ports

```
RCO- 6000 - RPL-2E16-4B7M
```

```
Modeloptional：
```

- **RCO- 6000 - RPL-2E16-**
  **2B15M**
- **RCO- 6000 - RPL-2E16-**
  **2N15M**

```
AI Edge Inference Computer W/ LGA 1700 for Intel 12/13/14thGen CPU &
R680E PCH, 2x LAN, 6x HDD, 1x PCIe x16 (Gen4), 1x PCIe x1 (Gen3)
```

```
Available Storage Expansion：
```

- 4B7M：4 Bay 7mm Hot-swappable 2.5" SATA HDD/SSD Bay
- 2B15M：2 Bay 15mm Hot-swappable 2.5" SATA HDD/SSD Bay
- 2N15M：2 Bay 15mm Hot-swappable 2.5" NVMeBay

```
Available Expansion：
```

- 2E16：1x PCIe x16 (Gen4), 1x PCIe x1 (Gen3)
- 2E8 (Optional)： 1x PCIe x16 (8-lane, Gen4), 1x PCIe x8 (8-lane, Gen4)

```
Available EDGEBoostI/O：
```

- 4L：4x LAN Ports
- 4P：4x LAN PoE Ports
- 8L：8x LAN Ports
- 8P：8x LAN PoEPorts
- D10G：2x 10Gb Ports
- 4U3：4xUSB 3.2 Gen 1 Ports
- 8U3：8x USB 3.2 Gen 1 Ports
  - 4LM12：4x M12 LAN Ports
  - 4PM12：4x M12 LAN PoEPorts
  - 8LM12：8x M12 LAN Ports
  - 8PM12：8x M12 LAN PoE Ports
  - 5G：2x 5G SIM Slots
  - 2x M.2 B-Key (1x 5G SIM)
  - 1x M.2 M-Key (4-Lane)
  - 4LM12：4x M12 LAN Ports
  - 4PM12：4x M12 LAN PoEPorts
  - 8LM12：8x M12 LAN Ports
  - 8PM12：8x M12 LAN PoE Ports
  - 5G：2x 5G SIM Slots
  - 2x M.2 B-Key (1x 5G SIM)
  - 1x M.2 M-Key (4-Lane)

**Preface**

```
Model No. Product Description
```

```
RCO- 6000 - RPL-4NS AI Edge Inference Computer w/ LGA 1700 for Intel 12/13/14thGen CPU &
R680E PCH, 4x U.2 15mm NVMe, Software RAID
```

```
Available EDGEBoostI/O：
```

- 4L：4x LAN Ports
- 4P：4x LAN PoE Ports
- 8L：8x LAN Ports
- 8P：8x LAN PoEPorts
- D10G：2x 10Gb Ports
- 4U3：4x USB 3.2 Gen 1 Ports
- 8U3：8x USB 3.2 Gen 1 Ports

```
RCO- 6000 - RPL-4NH AI Edge Inference Computer w/ LGA 1700 for Intel 12/13/14thGen CPU & R680E
PCH, 4x U.2 15mm NVMe, Hardware RAID
```

```
Available EDGEBoostI/O：
```

- 4L：4x LAN Ports
- 4P：4x LAN PoE Ports
- 8L：8x LAN Ports
- 8P：8x LAN PoEPorts
- D10G：2x 10Gb Ports
- 4U3：4x USB 3.2 Gen 1 Ports
- 8U3：8x USB 3.2 Gen 1 Ports

```
RCO- 6000 - RPL-8NS AI Edge Inference Computer w/ LGA 1700 for Intel 12/13/14thGen CPU &
R680E PCH, Flash Storage 8x U.2 NVMeBay, 1x PCIe x4 (1-lane)
Expansion
```

```
Available EDGEBoostI/O：
```

- 4L：4x LAN Ports
- 4P：4x LAN PoE Ports
- 8L：8x LAN Ports
- 8P：8x LAN PoEPorts
- D10G：2x 10Gb Ports
- 4U3：4xUSB 3.2 Gen 1 Ports
- 8U3：8x USB 3.2 Gen 1 Ports
  - 4LM12：4x M12 LAN Ports
  - 4PM12：4x M12 LAN PoEPorts
  - 8LM12：8x M12 LAN Ports
  - 8PM12：8x M12 LAN PoE Ports
  - 5G：2x 5G SIM Slots
  - 2x M.2 B-Key (1x 5G SIM)
  - 1x M.2 M-Key (4-Lane)
  - 4LM12：4x M12 LAN Ports
  - 4PM12：4x M12 LAN PoEPorts
  - 8LM12：8x M12 LAN Ports
  - 8PM12：8x M12 LAN PoE Ports
  - 5G：2x 5G SIM Slots
  - 2x M.2 B-Key (1x 5G SIM)
  - 1x M.2 M-Key (4-Lane)
    - 4LM12：4x M12 LAN Ports
    - 4PM12：4x M12 LAN PoEPorts
    - 8LM12：8x M12 LAN Ports
    - 8PM12：8x M12 LAN PoE Ports
    - 5G：2x 5G SIM Slots
    - 2x M.2 B-Key (1x 5G SIM)
    - 1x M.2 M-Key (4-Lane)

**Preface**

```
Model No. Product Description
```

```
RCO- 6000 - RPL-A2000 AI Edge Inference Computer with LGA 1700 for Intel 12/13/14th Gen
Processor and R680E PCH, RTX A2000 integrated
Available EDGEBoostI/O：
```

- 4L：4x LAN Ports
- 4P：4x LAN PoE Ports
- 8L：8x LAN Ports
- 8P：8x LAN PoEPorts
- D10G：2x 10Gb Ports
- 4U3：4x USB 3.2 Gen 1 Ports
- 8U3：8x USB 3.2 Gen 1 Ports

```
RCO- 6000 - RPL-2NA2000 AI Edge Inference Computer w/ LGA 1700 for Intel 12/13/14th Gen CPU & R680E
PCH, 2 Bay U.2 15mm, RTX A2000 integrated
```

```
Available EDGEBoostI/O：
```

- 4L：4x LAN Ports
- 4P：4x LAN PoE Ports
- 8L：8x LAN Ports
- 8P：8x LAN PoEPorts
- D10G：2x 10Gb Ports
- 4U3：4x USB 3.2 Gen 1 Ports
- 8U3：8x USB 3.2 Gen 1 Ports

```
RCO- 6000 - RPL-4NA2000 AI Edge Inference Computer w/ LGA 1700 for Intel 12/13/14th Gen CPU
& R680E PCH, 4 Bay U.2 7mm, RTX A2000 integrated
```

```
Available EDGEBoostI/O：
```

- 4L：4x LAN Ports
- 4P：4x LAN PoE Ports
- 8L：8x LAN Ports
- 8P：8x LAN PoEPorts
- D10G：2x 10Gb Ports
- 4U3：4xUSB 3.2 Gen 1 Ports
- 8U3：8x USB 3.2 Gen 1 Ports
  - 4LM12：4x M12 LAN Ports
  - 4PM12：4x M12 LAN PoEPorts
  - 8LM12：8x M12 LAN Ports
  - 8PM12：8x M12 LAN PoE Ports
  - 5G：2x 5G SIM Slots
  - 2x M.2 B-Key (1x 5G SIM)
  - 1x M.2 M-Key (4-Lane)
  - 4LM12：4x M12 LAN Ports
  - 4PM12：4x M12 LAN PoEPorts
  - 8LM12：8x M12 LAN Ports
  - 8PM12：8x M12 LAN PoE Ports
  - 5G：2x 5G SIM Slots
  - 2x M.2 B-Key (1x 5G SIM)
  - 1x M.2 M-Key (4-Lane)
    - 4LM12：4x M12 LAN Ports
    - 4PM12：4x M12 LAN PoEPorts
    - 8LM12：8x M12 LAN Ports
    - 8PM12：8x M12 LAN PoE Ports
    - 5G：2x 5G SIM Slots
    - 2x M.2 B-Key (1x 5G SIM)
    - 1x M.2 M-Key (4-Lane)

###### GPU Computing System

**Preface**

### Optional Accessory

```
Model No. Product Description
```

```
1 - E09A22102 Adapter AC/DC 24V 9.2A 220W with 3pin Terminal Block Plug 5.0mm Pitch
```

```
1 - E09A22801 Adapter AC/DC 24V/11.67A 280W with 3pin Terminal Block Plug 5.0mm Pitch
```

```
1 - E09A36002 Adapter AC/DC 48V/7.5A 360W with 3pin Terminal Block Plug 5.0mm Pitch
```

```
SFICBL022 Power Cord, 3-pin US Type, 180cm
```

```
1 - TPCD00002 Power Cord, European Type, 180cm
```

```
1 - TPCD00001 Power Cord, 3-pin UK Type, 180cm
```

```
3 - RC6300EXFAN External Double FAN KIT^ (for Top Cover)
```

```
3 - EXFANK01S10-S0 External Double Fan Module Kit (for Product shipment)
```

```
3 - EXFANK01S10-S1 External Double Fan Module Kit (for system assembly)
```

```
1 - TFAN00005 FAN Extension Cable
```

## Chapter 1 Product Introductions

##### 1.1 Overview

```
The Superior Embedded Systems RCO- 6000 - RPL series are designed with rich I/O, high flexibility and
```

```
easy expansion capabilities which are ideal for diverse industrial applications.Support12/13/14thGen.
Intel® Core i9/i7/i3 or Intel® Pentium®/Intel® Celeron® Desktop processor, RCO- 6000 - RPL Series is an
```

```
extreme features integration, outstanding system performance, versatile I/O connections, and rugged
```

```
reliability fanlessembedded systems. It offers dramatically enhanced CPU and graphics performance,
wide power and feature advanced features, rich connectivity interfaces, wide range power input, and
```

```
high reliability even operating in temperature extremes.
```

**Chapter 1: Product Introductions**

```
Model No. Rear Panel Front Panel
```

```
RCO- 6000 - RPL
```

```
RCO- 6000 - RPL-2E
1x PCIe x16 (Gen4), 1x PCIe x1 (Gen3)
```

```
RCO- 6000 - RPL-2E16-2PWR
1x PCIe x16 (Gen4), 1x PCIe x1 (Gen3),
2x Power input
```

```
RCO- 6000 - RPL-2E16-4B7M
1x PCIe x16 (Gen4), 1x PCIe x1 (Gen3),
4x Removable 2.5" SATA HDD Bay
```

```
RCO- 6000 - RPL-2E16-2B15M
1x PCIe x16 (Gen4), 1x PCIe x1 (Gen3),
2x Removable 2.5" SATA HDD Bay
```

```
RCO- 6000 - RPL-2E16-2N15M
1x PCIe x16 (Gen4), 1x PCIe x1 (Gen3),
2x Removable 2.5" U.2 NVMeBay
```

```
Model No. Rear Panel Front Panel
```

```
RCO- 6000 - RPL-A
RTX A2000 integrated
```

```
RCO- 6000 - RPL-2NA
2 Bay U.2 15mm, RTX A2000 integrated
```

```
RCO- 6000 - RPL-4NA
4 Bay U.2 7mm, RTX A2000 integrated
```

**Chapter 1: Product Introductions**

```
Model No. Rear Panel Front Panel
```

```
RCO- 6000 - RPL-4NS
4x U.2 15mm NVMe, Software RAID
```

```
RCO- 6000 - RPL-4NH
4 Bay U.2 15mm, Hardware RAID
```

```
RCO- 6000 - RPL-8NS
8 Bay U.2 7mm
```

###### 1.1.1 Key Feature

```
⚫LGA 1700 socket for 12/13/14th Gen. Intel® ADL& RPL Processor (35W TDP)
⚫Intel® R680E Chipset
⚫2x DDR5 4800/5600MHz SODIMM. Max. up to 64GB
⚫Triple Independent Display by 1x DVI-I and 2x DisplayPort
⚫2x Intel® 2.5 GbE supporting Wake-on-LAN and PXE
⚫1x Full-size Mini PCIe for communication or expansion modules, 2x SIM socket
⚫2x 2.5” SATA HDD Bay (1x Internal) and with RAID 0, 1 support
⚫1x M.2 (E Key, PCIe x1, USB 2.0, 2230)
⚫1x M.2 (B Key, 2242/3042/3052, PCIe x2, Support AI Module/NVMeStorage,
PCIe x1 & USB 3.2 Gen1, Support 4G/5G)
⚫6x RS-232/422/485 (4x internal), 8x USB 3.2 Gen 2, 1x USB 3.2 Gen 1 (internal)
⚫8x DI + 8x DO with isolation
⚫9 to 48VDC Wide Range Power Input Supporting AT/ATX Mode
⚫Wide Operating Temperature
⚫TPM 2.0 Supported
```

**Chapter 1: Product Introductions**

```
Features Model No.
```

```
1x PCIe x16 (Gen4), 1x PCIe x1 (Gen3) Expansion
```

- RCO- 6000 - RPL-2E
- RCO- 6000 - RPL-2E16-2PWR
- RCO- 6000 - RPL-2E16-4B7M
- RCO- 6000 - RPL-2E16-2B15M
- RCO- 6000 - RPL-2E16-2N15M

```
1x PCIe x16 (8-lane, Gen4), 1x PCIe x8 (8-lane, Gen4) Expansion
```

- RCO- 6000 - RPL-2E
- RCO- 6000 - RPL-2E8-2PWR
- RCO- 6000 - RPL-2E8-4B7M
- RCO- 6000 - RPL-2E8-2B15M
- RCO- 6000 - RPL-2E8-2N15M

```
2x Power input
```

- RCO- 6000 - RPL-2E16-2PWR
- RCO- 6000 - RPL-2E8-2PWR
  Storage Expansion:
  4x 7mm Hot-swappable 2.5" SATA HDD/SSD Bay
  Support RAID 0, 1, 5, 10
- RCO- 6000 - RPL-2E16-4B7M
- RCO- 6000 - RPL-2E8-4B7M

```
Storage Expansion:
2x 15mm Hot-swappable 2.5" SATA HDD/SSD Bay
Support RAID 0, 1, 5, 10
```

- RCO- 6000 - RPL-2E16-2B15M
- RCO- 6000 - RPL-2E8-2B15M

```
Storage Expansion:
2x 15mm Hot-swappable 2.5" U.2 NVMeBay, Support RAID 0, 1
```

- RCO- 6000 - RPL-2E16-2N15M
- RCO- 6000 - RPL-2E8-2N15M
  Storage Expansion:
  2x Removable 2 Bay NVMeSSD Module (15mm)
  with RAID 0, 1, 5, 10 support
- RCO- 6000 - RPL-4NS

```
Storage Expansion:
2x Removable 2 Bay NVMeSSD Module (15mm)
with Hardware RAID 0, 1, 5, 6, 10 support
```

- RCO- 6000 - RPL-4NH

```
Storage Expansion:
2x Removable 4 Bay NVMeSSD Module (7mm)
with RAID 0, 1, 5, 10 support
```

- RCO- 6000 - RPL-8NS

```
RTX A2000 integrated
```

- RCO- 6000 - RPL-A
- RCO- 6000 - RPL-2NA
- RCO- 6000 - RPL-4NA

##### 1.2 Hardware Specification

```
Chapter 1: Product Introductions
```

**System**

Processor

###### Support 12/13th/14th(Non-vPRO) Gen Intel® ADL & RPL Processor (LGA 1700,

###### 65W/35W TDP)

- Intel® Core i9-14900T/i9-13900TE/i9-12900TE, up to 24 Cores, 36MB Cache, up to 5.5 GHz, 35W
- Intel® Core i7-14700T, up to 20 Cores, 33MB Cache, up to 5.2 GHz, 35W
- Intel® Core i7-13700TE/i7-12700TE, up to 16 Cores, 30MB cache, up to 4.8 GHz, 35W
- Intel® Core i5-14500T/i5-13500TE/i5-12500TE, up to 14 Core, 24MB Cache, up to 4.8 GHz, 35W
- Intel® Core i3-14100T/i3-13100TE/i3-12100TE, up to 4 Cores, 12MB Cache, up to 4.4 GHz, 35W
- Intel® Core 300T, up to 2 Cores, 6MB Cache, up to 3.4 GHz, 35W
- Intel® Pentium® G7400E,2 Cores, 6MB Cache, 3.6 GHz, 46W
- Intel® Pentium® G7400TE, 2 Cores, 6MB Cache, 3.0 GHz, 35W
- Intel® Celeron® G6900E, 2 Cores, 4MB Cache, 3.0 GHz, 46W
- Intel® Celeron® G6900TE, 2 Cores, 4MB Cache, 2.4 GHz, 35W

System Chipset Intel® R680E Express Chipset

LAN Chipset 2.5 GbE1: Intel I226,2.5 GbE2: Intel I226,^ Support WakeSupport Wake--onon--LAN and PXE, Support TSNLAN and PXE, Support TSN

Audio Codec Realtek ALC888S

System Memory 2x 262Max. up to 64GB (ECC and Non-Pin DDR5 4800/5600MHz SODIMM.-ECC)

Graphics Intel® UHD Graphics 770/

BIOS AMI 256Mbit SPI BIOS

Watchdog Software Programmable Supports 1~255 sec. System Reset

TPM TPM 2.

**Display**

DisplayPort 2x DisplayPort, Support resolution 5120 x 3200,Up to 7680 x 4320

DVI 1x DVI-I, support resolution 1920 x 1200

Multiple Display Triple Display

VGA Yes (by optional split cable)

```
Chapter 1: Product Introductions
```

**Storage** M.2 SIM Socket SATA^ SSD/HDD

RCO- 6000 - RPL

```
1x M.2 B Key,
2242/3042/
(PCIe x2, Support AI
Module/NVMeStorage)
(PCIe x1 & USB 3.
Gen1, Support 4G/5G)
```

```
2x External SIM
socket
(Mini PCIE attached)
```

```
1x Internal 2.5" SATA/SSD HDD Bay (support
H=9mm)
1x Removable 2.5" SATA HDD Bay (support
H=7mm, Hot-swappable)
Support RAID 0, 1
```

RCO- 6000 - RPL-2E

RCO- 6000 - RPL-2E16-2PWR /
RCO- 6000 - RPL-A

RCO- 6000 - RPL-2E16-4B7M

```
1x Internal 2.5" SATA/SSD HDD Bay (support
H=9mm)
5x 7mm Hot-swappable 2.5" SATA HDD/SSD Bay
Support RAID 0, 1, 5, 10
```

RCO- 6000 - RPL-2E16-2B15M

```
1x Internal 2.5" SATA/SSD HDD Bay (support
H=9mm)
1x 7mm, 2x 15mm Hot-swappable 2.5" SATA
HDD/SSD Bay
Support RAID 0, 1, 5, 10
```

RCO- 6000 - RPL-2E16-2N15M

```
1x Internal 2.5" SATA/SSD HDD Bay (support
H=9mm)
1x Removable 2.5" SATA HDD Bay (support
H=7mm, Hot-swappable)
Support RAID 0, 1
```

RCO- 6000 - RPL-4NS

RCO- 6000 - RPL-4NH

RCO- 6000 - RPL-8NS

RCO- 6000 - RPL-2NA
RCO- 6000 - RPL-4NA

**NVMeStorage**

RCO- 6000 - RPL-2E16-2N15M 2x Removable 2.5" U.2 NVMeBay (support H=15mm, Hot-swappable, Optional) Support RAID 0, 1

RCO- 6000 - RPL-4NS 2x Removable 2 Bay NVMeSSD Module (15mm) with RAID 0, 1, 5, 10 support

RCO- 6000 - RPL-4NH 2x Removable 2 Bay NVMeSSD Module (15mm) with Hardware RAID 0, 1, 5, 6, 10 support

RCO- 6000 - RPL-8NS 2x Removable 4 Bay NVMeSSD Module (7mm) with RAID 0, 1, 5, 10 support

RCO- 6000 - RPL-2NA2000 1x Removable Cannister Brick with 2.5“ 2 Bay U.2 NVMeSSD (Support H=15mm) with RAID 0, 1

RCO- 6000 - RPL-4NA2000 1x Removable Cannister Brick with 2.5“ 4 Bay U.2 NVMeSSD (Support H=7mm) with RAID 0, 1, 5

```
Expansion
```

```
M.2 1x M.2 (E Key, PCIe x1, USB 2.0, 2230)
Mini PCIe 1x Full-size Mini PCIe (1x shared by 1x mSATA)
```

```
PCIe
```

- 1x PCIe x16 (Gen4), 1x PCIe x1 (Gen3)：
  Model No
  RCO- 6000 - RPL-2E
  RCO- 6000 - RPL-2E16-2PWR
  RCO- 6000 - RPL-2E16-4B7M
  RCO- 6000 - RPL-2E16-2B15M
  RCO- 6000 - RPL-2E16-2N15M

```
Expansion EDGEBoostI/O
```

```
Occupied One EDGEBoostI/O Slot:
```

- 4 - port GbE module with Intel® I350 Chipset, RJ-45 or M12 connector (PoE optional)
- 2 - Port RJ45 10GbE with Intel X710 Chipset
- 4 - Port USB with Renesas uPD720201K8 host controller (share PCIe Gen2 x1 bandwidth)
- 1x M.2 for 5G (B Key, PCIe x1, USB 3.0, 3042/3052), Including 2x SIM socket, 1x SIM switch (1x
  EDGEBoostI/O Slot Only)
- 1x M.2 B-Key, 2242 for AI/NVMeModule, 1x M.2 B-Key, 3042/3052 for 5G/AI/NVMeModule (1x
  EDGEBoostI/O Slot Only)
- 1x M.2 M-Key, PCIe x4 Lane, 2242/2260 for AI Module and NVMeStorage

```
Ethernet
```

- 4x 802.3at Compliant PoE Port, The Maximum DC Power Delivery on Each PoE is 25.5W
  [RCO- 6000 - RPL-4P Series and RCO- 6000 - RPL-4PM12 Series only]
- 8x 802.3at Compliant PoE Port, The Maximum DC Power Delivery on Each PoE is 25.5W. 80W total
  power budget
  [RCO- 6000 - RPL-8P Series and RCO- 6000 - RPL-8PM12 Series only] - 1x PCIe x16 (8-lane, Gen4), 1x PCIe x8 (8-lane, Gen4)：
  Model No
  RCO- 6000 - RPL-2E
  RCO- 6000 - RPL-2E8-2PWR
  RCO- 6000 - RPL-2E8-4B7M
  RCO- 6000 - RPL-2E8-2B15M
  RCO- 6000 - RPL-2E8-2N15M

**Chapter 1: Product Introductions**

**Operating System**

Windows Windows 10

Linux Linux kernel

```
Power
```

```
Power Adapter
```

```
Optional AC/DC 24V/9.2A, 220W
Optional AC/DC 24V/11.67A, 280W (GPU/Card Expansion)
Optional AC/DC 24V/15A, 360W (i7/i9 CPU/GPU/Card Expansion)
Power Mode AT, ATX
Power Ignition Sensing Power Ignition Management
```

```
Power Supply Voltage
```

```
RCO- 6000 - RPL / RCO- 6000 - RPL-2E16 / RCO- 6000 - RPL-2E16-4B7M / RCO- 6000 - RPL-2E16-2B15M / RCO- 6000 -
RPL-2E16-2N15M ：9~48VDC
RCO- 6000 - RPL-2E16-2PWR / RCO- 6000 - RPL-4NS / RCO- 6000 - RPL-4NH / RCO- 6000 - RPL-8NS /
RCO- 6000 - RPL-A2000 / RCO- 6000 - RPL-2NA2000 / RCO- 6000 - RPL-4NA2000 ：
2x Power Input
```

- 9~48VDC
- 12~48VDC for GPU/NVMe/Card Expansion

```
Power Connector
```

```
RCO- 6000 - RPL / RCO- 6000 - RPL-2E16 / RCO- 6000 - RPL-2E16-4B7M ：
5 - pin Terminal Block
RCO- 6000 - RPL-2E16-2PWR / RCP- 6000 - RPL-A2000 ：
5 - pin Terminal Block
4 - pin Terminal Block for GPU Expansion
RCO- 6000 - RPL-4NS / RCO- 6000 - RPL-4NH / RCO- 6000 - RPL-8NS / RCO- 6000 - RPL-2NA2000 /
RCO- 6000 - RPL-4NA2000 ：
5 - pin Terminal Block
4 - pin Terminal Block for NVMeEDGEBoostNode
(12V requires 4-pin terminal block)
```

```
Power Protection
```

```
OVP (Over Voltage Protection);
OCP (Over Current Protection)
Reserve Protection
```

**I/O**

Audio 1x Mic-in, 1x Line-out

CAN 2x CAN 2.0 A/B 2-pin Internal header

COM 2x RS-232/422/485 ; 6x RS-232/422/485 (internal)

DIO 8 in / 8 out (Isolated)

LAN 2x RJ

EDGEBoostI/OBracket 2x EDGEBoostI/O Bracket (By mini PCIe interface)

USB 8x USB 3.2 Gen 2 (10 Gbps)
1x USB 3.2 Gen 1 (5 Gbps, 1x Internal)
2x USB 2.0 (internal)

Others 5x WiFiAntenna Holes
1x Power Switch, 1x AT/ATX Switch, 1x Remote Power On/Off
1x PC/Car Mode Switch
1x Removable CMOS Battery

```
Chapter 1: Product Introductions
```

```
Environment
Operating Temp. - 25 °C to 70°C (35W CPU)
```

```
RCO- 6000 - RPL-2E16-2PWR / RCO- 6000 - RPL-4NH / RCO- 6000 - RPL-4NS / RCO- 6000 -
RPL-8NS ：
```

- 25 °C to 60 °C
  **RCO- 6000 - RPL-A2000 / RCO- 6000 - RPL-2NA2000 / RCO- 6000 - RPL-4NA2000** ：
- 25 °C to 45 °C
  Storage Temp. - 30 °C to 85°C
  Relative Humidity 10% to 95% (non-condensing)
  Standards / Certification CE, FCC Class A
  Vibration With SSD: 5 Grms, 5 -500 Hz, 0.5 hr/axis
  With HDD: 1 Grms, 5 -500 Hz, 0.5 hr/axis

```
RCO- 6000 - RPL-2E16-2PWR / RCO- 6000 - RPL-4NS / RCO- 6000 - RPL-4NH / RCO- 6000 - RPL-8NS
/ RCO- 6000 - RPL-A2000 / RCO- 6000 - RPL-2NA2000 / RCO- 6000 - RPL-4NA2000 ：
With SSD: 3 Grms, 5 -500 Hz, 0.5 hr/axis
With HDD: 1 Grms, 5 -500 Hz, 0.5 hr/axis
Shock With SSD: 50G, half sine, 11ms
```

```
Physical
```

```
Construction Extruded Aluminum with Heavy Duty Metal
```

```
Dimension • RCO-^6000 - RPL ：
240 (W) x 261 (D) x 79 (H) mm
```

- **RCO- 6000 - RPL-2E16 / RCO- 6000 - RPL-2E16-4B7M / RCO- 6000 - RPL-2E16-2B15M / RCO- 6000 -**
  **RPL-2E16-2N15M / RCO- 6000 - RPL-2E16-2PWR / RCO- 6000 - RPL-A2000** ：
  240 (W) x 261 (D) x 126.8(H) mm
- **RCO- 6000 - RPL-4NS / RCO- 6000 - RPL-4NH / RCO- 6000 - RPL-8NS**
  **/ RCO- 6000 - RPL-2NA2000 / RCO- 6000 - RPL-4NA2000** ：
  240 (W) x 261 (D) x 166.9(H) mm
  Weight • **RCO-**^6000 **- RPL** ：^4 .5 kg
- **RCO- 6000 - RPL-2E16** ：6.5 ~ 7.5 kg
- **RCO- 6000 - RPL-2E16-2PWR** ：6.5 ~ 7.5 kg
- **RCO- 6000 - RPL-2E16-4B7M** ：6.5 ~ 7.5 kg
- **RCO- 6000 - RPL-2E16-2B15M** ：6.5 ~ 7.5 kg
- **RCO- 6000 - RPL-2E16-2N15M** ：6.5 ~ 7.5 kg
- **RCO- 6000 - RPL-4NH** ：10.5 ~ 11.5 kg
- **RCO- 6000 - RPL-4NS** ：10 ~ 11 kg
- **RCO- 6000 - RPL-8NS** ：10.5 ~ 11.5 kg
- **RCO- 6000 - RPL-A2000 :** 7 ~ 8.5 kg
- **RCO- 6000 - RPL-2NA2000 / RCO- 6000 - RPL-4NA2000 :** 11 ~ 12 kg

```
Mounting Wall Mounting
```

- All specifications and photos are subject to change without notice.

##### 1.3 System I/O

###### 1.3.1 RCO- 6000 - RPL

**Chapter 1: Product Introductions**

```
ATX power on/off switch
Press to power-on or power-off the system
```

```
Power LED
Indicates the power status of the system
```

```
HDD LED
Indicates the status of the hard drive
```

```
Antenna hole
Used to connect an antenna for optional Mini-
PCIeWiFimodule
```

```
USB 3.2 Gen 2 port (10 Gbps)
Used to connect USB 3.2 device
```

```
Removable HDD
Removable 2.5" SATA HDD Bay
(support H=7mm, hot-swappable)
Support RAID 0, 1
```

```
AT/ATX mode select switch
Used to select AT or ATX power mode
```

```
Clear CMOS
Used to clear CMOS
```

```
SIM card
Used to insert SIM card
```

```
Line-out
Used to connect a speaker
```

```
Mic-in
Used to connect a microphone
```

```
Remote Power on/off Terminal Block
Used to plug a remote power on/off terminal
block
```

```
PC/Car mode select switch
Used to select PC or Car mode
```

```
EDGEBoostI/O bracket (optional)
```

### Front Panel

```
EDGEBoost I/O Bracket
```

**Chapter 1: Product Introductions**

```
DVI-I port
Used to connect a DVI monitor or connect
optional split cable for dual display mode
```

```
Digital I/O Terminal Block
The Digital I/O terminal block supports 8 digital
input and 8 digital output
DisplayPort
Used to connect a DisplayPort monitor
COM port
COM1 ~ COM2 support RS232/422/485 serial
device
```

```
USB 3.2 Gen 2 port (10 Gbps)
Used to connect USB 3.2 device
```

```
LAN port
Used to connect the system to a local area
network
```

```
Antenna hole
Used to connect an antenna for optional Mini-
PCIeWiFimodule
DC IN
Used to plug a DC power input with terminal
block
```

### Rear Panel

###### RCO- 6000 - RPL

```
ATX power on/off switch
Press to power-on or power-off the system
Power LED
Indicates the power status of the system
HDD LED
Indicates the status of the hard drive
Antenna hole
Used to connect an antenna for optional Mini-
PCIeWiFimodule
```

```
USB 3.2 Gen 2 port (10 Gbps)
Used to connect USB 3.2 device
```

```
Removable HDD
Removable 2.5" SATA HDD Bay
(support H=7mm, hot-swappable)
Support RAID 0, 1
```

```
AT/ATX mode select switch
Used to select AT or ATX power mode
```

```
Clear CMOS
Used to clear CMOS
SIM card
Used to insert SIM card
Line-out
Used to connect a speaker
Mic-in
Used to connect a microphone
Remote Power on/off Terminal Block
Used to plug a remote power on/off terminal
block
```

```
PC/Car mode select switch
Used to select PC or Car mode
```

```
EDGEBoostI/O bracket (optional)
```

###### 1.3.2 RCO- 6000 - RPL-2E16

**Chapter 1: Product Introductions**

### Front Panel

```
Top Module (Industrial FanlessPC on Top)
```

```
EDGEBoost I/O Bracket
```

**Chapter 1: Product Introductions**

```
DVI-I port
Used to connect a DVI monitor or connect
optional split cable for dual display mode
```

```
Digital I/O Terminal Block
The Digital I/O terminal block supports 8 digital
input and 8 digital output
DisplayPort
Used to connect a DisplayPort monitor
COM port
COM1 ~ COM2 support RS232/422/485 serial
device
```

```
USB 3.2 Gen 2 port (10 Gbps)
Used to connect USB 3.2 device
LAN port
Used to connect the system to a local area
network
```

```
Antenna hole
Used to connect an antenna for optional Mini-
PCIeWiFimodule
DC IN (5-pin Terminal Block)
Used to plug a DC power input with terminal
block
```

### Rear Panel

###### RCO- 6000 - RPL-2E16

```
Expansion
PCIe Slot
```

```
Bottom Module (Flexible and Dedicated “EDGEBoostNodes” on Bottom)
```

```
Top Module (Industrial FanlessPC on Top)
```

```
ATX power on/off switch
Press to power-on or power-off the system
Power LED
Indicates the power status of the system
HDD LED
Indicates the status of the hard drive
Antenna hole
Used to connect an antenna for optional Mini-
PCIeWiFimodule
```

```
USB 3.2 Gen 2 port (10 Gbps)
Used to connect USB 3.2 device
```

```
Removable HDD
Removable 2.5" SATA HDD Bay
(support H=7mm, hot-swappable)
Support RAID 0, 1
```

```
AT/ATX mode select switch
Used to select AT or ATX power mode
```

```
Clear CMOS
Used to clear CMOS
SIM card
Used to insert SIM card
Line-out
Used to connect a speaker
Mic-in
Used to connect a microphone
Remote Power on/off Terminal Block
Used to plug a remote power on/off terminal
block
```

```
PC/Car mode select switch
Used to select PC or Car mode
```

```
EDGEBoostI/O bracket (optional)
```

```
SSD/HDD
4x 7mm Hot-swappable 2.5" SATA HDD/SSD Bay
```

###### 1.3.3 RCO- 6000 - RPL-2E16-4B7M

**Chapter 1: Product Introductions**

### Front Panel

```
Top Module (Industrial FanlessPC on Top)
```

```
Bottom Module (Flexible and Dedicated “EDGEBoostNodes” on Bottom)
```

```
EDGEBoost I/O Bracket
```

**Chapter 1: Product Introductions**

```
DVI-I port
Used to connect a DVI monitor or connect
optional split cable for dual display mode
```

```
Digital I/O Terminal Block
The Digital I/O terminal block supports 8 digital
input and 8 digital output
DisplayPort
Used to connect a DisplayPort monitor
COM port
COM1 ~ COM2 support RS232/422/485 serial
device
```

```
USB 3.2 Gen 2 port (10 Gbps)
Used to connect USB 3.2 device
LAN port
Used to connect the system to a local area
network
```

```
Antenna hole
Used to connect an antenna for optional Mini-
PCIeWiFimodule
DC IN (5-pin Terminal Block)
Used to plug a DC power input with terminal
block
```

### Rear Panel

###### RCO- 6000 - RPL-2E16-4B7M

```
Fan
Hot-Swappable Rear-Fan Exhaust design for
easy maintenance
Expansion
PCIe Slot
```

```
Bottom Module (Flexible and Dedicated “EDGEBoostNodes” on Bottom)
```

```
Top Module (Industrial FanlessPC on Top)
```

```
ATX power on/off switch
Press to power-on or power-off the system
Power LED
Indicates the power status of the system
HDD LED
Indicates the status of the hard drive
Antenna hole
Used to connect an antenna for optional Mini-
PCIeWiFimodule
```

```
USB 3.2 Gen 2 port (10 Gbps)
Used to connect USB 3.2 device
```

```
Removable HDD
Removable 2.5" SATA HDD Bay
(support H=7mm, hot-swappable)
Support RAID 0, 1
```

```
AT/ATX mode select switch
Used to select AT or ATX power mode
```

```
Clear CMOS
Used to clear CMOS
SIM card
Used to insert SIM card
Line-out
Used to connect a speaker
Mic-in
Used to connect a microphone
Remote Power on/off Terminal Block
Used to plug a remote power on/off terminal
block
```

```
PC/Car mode select switch
Used to select PC or Car mode
```

```
EDGEBoostI/O bracket (optional)
```

- **RCO- 6000 - RPL-2E16-2B15M :**
  2x 15mm Hot-swappable 2.5" SATA HDD/SSD Bay - **RCO- 6000 - RPL-2E16-2N15M :**
  2x 15mm Hot-swappable 2.5" U.2 NVMeBay

###### 1.3.4 RCO- 6000 - RPL-2E16-2B15M / RCO- 6000 - RPL-2E16-2N15M

**Chapter 1: Product Introductions**

### Front Panel

```
Top Module (Industrial FanlessPC on Top)
```

```
Bottom Module (Flexible and Dedicated “EDGEBoostNodes” on Bottom)
```

```
EDGEBoost I/O Bracket
```

- 2x 15mm Hot-swappable 2.5“ SATA HDD/SSD Bay(2B15M) or
  2x 15mm Hot-swappable 2.5" U.2 NVMeBay(2N15M)

**Chapter 1: Product Introductions**

```
DVI-I port
Used to connect a DVI monitor or connect
optional split cable for dual display mode
```

```
Digital I/O Terminal Block
The Digital I/O terminal block supports 8 digital
input and 8 digital output
DisplayPort
Used to connect a DisplayPort monitor
COM port
COM1 ~ COM2 support RS232/422/485 serial
device
```

```
USB 3.2 Gen 2 port (10 Gbps)
Used to connect USB 3.2 device
LAN port
Used to connect the system to a local area
network
```

```
Antenna hole
Used to connect an antenna for optional Mini-
PCIeWiFimodule
DC IN (5-pin Terminal Block)
Used to plug a DC power input with terminal
block
```

### Rear Panel

###### RCO- 6000 - RPL-2E16-2B15M / RCO- 6000 - RPL-2E16-2N15M

```
Bottom Module (Flexible and Dedicated “EDGEBoostNodes” on Bottom)
```

```
Top Module (Industrial FanlessPC on Top)
```

```
Fan
Hot-Swappable Rear-Fan Exhaust design for
easy maintenance
Expansion
PCIe Slot
```

```
ATX power on/off switch
Press to power-on or power-off the system
Power LED
Indicates the power status of the system
HDD LED
Indicates the status of the hard drive
Antenna hole
Used to connect an antenna for optional Mini-
PCIeWiFimodule
```

```
USB 3.2 Gen 2 port (10 Gbps)
Used to connect USB 3.2 device
```

```
Removable HDD
Removable 2.5" SATA HDD Bay
(support H=7mm, hot-swappable)
Support RAID 0, 1
```

```
AT/ATX mode select switch
Used to select AT or ATX power mode
```

```
Clear CMOS
Used to clear CMOS
SIM card
Used to insert SIM card
Line-out
Used to connect a speaker
Mic-in
Used to connect a microphone
Remote Power on/off Terminal Block
Used to plug a remote power on/off terminal
block
```

```
PC/Car mode select switch
Used to select PC or Car mode
```

```
EDGEBoostI/O bracket (optional)
```

```
Fan
Hot-Swappable Rear-Fan Exhaust design for
easy maintenance
```

###### 1.3.5 RCO- 6000 - RPL-2E16-2PWR

**Chapter 1: Product Introductions**

### Front Panel

```
Top Module (Industrial FanlessPC on Top)
```

```
Bottom Module (Flexible and Dedicated “EDGEBoostNodes” on Bottom)
```

```
EDGEBoost I/O Bracket
```

**Chapter 1: Product Introductions**

```
DVI-I port
Used to connect a DVI monitor or connect
optional split cable for dual display mode
```

```
Digital I/O Terminal Block
The Digital I/O terminal block supports 8 digital
input and 8 digital output
DisplayPort
Used to connect a DisplayPort monitor
COM port
COM1 ~ COM2 support RS232/422/485 serial
device
```

```
USB 3.2 Gen 2 port (10 Gbps)
Used to connect USB 3.2 device
LAN port
Used to connect the system to a local area
network
```

```
Antenna hole
Used to connect an antenna for optional Mini-
PCIeWiFimodule
DC IN (5-pin Terminal Block)
Used to plug a DC power input with terminal
block
```

### Rear Panel

###### RCO- 6000 - RPL-2E16-2PWR

```
DC IN
12~48VDC for GPU/Card Expansion
```

```
Expansion
PCIe Slot
```

```
Bottom Module (Flexible and Dedicated “EDGEBoostNodes” on Bottom)
```

```
Top Module (Industrial FanlessPC on Top)
```

```
ATX power on/off switch
Press to power-on or power-off the system
Power LED
Indicates the power status of the system
HDD LED
Indicates the status of the hard drive
Antenna hole
Used to connect an antenna for optional Mini-
PCIeWiFimodule
```

```
USB 3.2 Gen 2 port (10 Gbps)
Used to connect USB 3.2 device
```

```
Removable HDD
Removable 2.5" SATA HDD Bay
(support H=7mm, hot-swappable)
Support RAID 0, 1
```

```
AT/ATX mode select switch
Used to select AT or ATX power mode
```

```
Clear CMOS
Used to clear CMOS
SIM card
Used to insert SIM card
Line-out
Used to connect a speaker
Mic-in
Used to connect a microphone
Remote Power on/off Terminal Block
Used to plug a remote power on/off terminal
block
```

```
PC/Car mode select switch
Used to select PC or Car mode
```

```
EDGEBoostI/O bracket (optional)
```

###### 1.3.6 RCO- 6000 - RPL-4NH

**Chapter 1: Product Introductions**

### Front Panel

```
Top Module (Industrial FanlessPC on Top)
```

```
Bottom Module (Flexible and Dedicated “EDGEBoostNodes” on Bottom)
```

- **Data Cartridge A**
  Hot swappable NVMeSSD CannisterBricks,
  1x Removable 2 Bay NVMeSSD Module with Hardware
  RAID 0, 1, 5, 6, 10 support (Support H=15mm)
- **Lock**
  Used to key switch
- **Data Cartridge B**
  Hot swappable NVMeSSD CannisterBricks),
  1x Removable 2 Bay NVMeSSD Module with Hardware
  RAID 0, 1, 5, 6, 10 support (Support H=15mm)
- **Storage Ejection Button**
  Safety Storage Ejection Button to suspend all I/O
  operation, read-write to prevent loss or corruption of
  data

```
EDGEBoost I/O Bracket
```

**Chapter 1: Product Introductions**

```
DVI-I port
Used to connect a DVI monitor or connect
optional split cable for dual display mode
```

```
Digital I/O Terminal Block
The Digital I/O terminal block supports 8 digital
input and 8 digital output
DisplayPort
Used to connect a DisplayPort monitor
COM port
COM1 ~ COM2 support RS232/422/485 serial
device
```

```
USB 3.2 Gen 2 port (10 Gbps)
Used to connect USB 3.2 device
LAN port
Used to connect the system to a local area
network
```

```
Antenna hole
Used to connect an antenna for optional Mini-
PCIeWiFimodule
DC IN (5-pin Terminal Block)
Used to plug a DC power input with terminal
block
```

### Rear Panel

###### RCO- 6000 - RPL-4NH

```
Bottom Module (Flexible and Dedicated “EDGEBoostNodes” on Bottom)
```

```
Top Module (Industrial FanlessPC on Top)
```

- **DC IN** (4-pin Terminal Block)
  Used to plug a DC power input with terminal
  block
- **Fan**
  Hot-Swappable Rear-Fan Exhaust design for
  easy maintenance

```
ATX power on/off switch
Press to power-on or power-off the system
Power LED
Indicates the power status of the system
HDD LED
Indicates the status of the hard drive
Antenna hole
Used to connect an antenna for optional Mini-
PCIeWiFimodule
```

```
USB 3.2 Gen 2 port (10 Gbps)
Used to connect USB 3.2 device
```

```
Removable HDD
Removable 2.5" SATA HDD Bay
(support H=7mm, hot-swappable)
Support RAID 0, 1
```

```
AT/ATX mode select switch
Used to select AT or ATX power mode
```

```
Clear CMOS
Used to clear CMOS
SIM card
Used to insert SIM card
Line-out
Used to connect a speaker
Mic-in
Used to connect a microphone
Remote Power on/off Terminal Block
Used to plug a remote power on/off terminal
block
```

```
PC/Car mode select switch
Used to select PC or Car mode
```

```
EDGEBoostI/O bracket (optional)
```

###### 1.3.7 RCO- 6000 - RPL-4NS

**Chapter 1: Product Introductions**

### Front Panel

```
Top Module (Industrial FanlessPC on Top)
```

```
Bottom Module (Flexible and Dedicated “EDGEBoostNodes” on Bottom)
```

- **Data Cartridge A**
  Hot swappable NVMeSSD CannisterBricks,
  1x Removable 2 Bay NVMeSSD Module with Software
  RAID 0, 1, 5, 10 support (Support H=15mm)
- **Lock**
  Used to key switch
- **Data Cartridge B**
  Hot swappable NVMeSSD CannisterBricks),
  1x Removable 2 Bay NVMeSSD Module with Software
  RAID 0, 1, 5, 10 support (Support H=15mm)
- **Storage Ejection Button**
  Safety Storage Ejection Button to suspend all I/O
  operation, read-write to prevent loss or corruption of
  data

```
EDGEBoost I/O Bracket
```

**Chapter 1: Product Introductions**

```
DVI-I port
Used to connect a DVI monitor or connect
optional split cable for dual display mode
```

```
Digital I/O Terminal Block
The Digital I/O terminal block supports 8 digital
input and 8 digital output
DisplayPort
Used to connect a DisplayPort monitor
COM port
COM1 ~ COM2 support RS232/422/485 serial
device
```

```
USB 3.2 Gen 2 port (10 Gbps)
Used to connect USB 3.2 device
LAN port
Used to connect the system to a local area
network
```

```
Antenna hole
Used to connect an antenna for optional Mini-
PCIeWiFimodule
DC IN (5-pin Terminal Block)
Used to plug a DC power input with terminal
block
```

### Rear Panel

###### RCO- 6000 - RPL-4NS

```
Bottom Module (Flexible and Dedicated “EDGEBoostNodes” on Bottom)
```

```
Top Module (Industrial FanlessPC on Top)
```

- **DC IN** (4-pin Terminal Block)
  Used to plug a DC power input with terminal
  block
- **Fan**
  Hot-Swappable Rear-Fan Exhaust design for
  easy maintenance

```
ATX power on/off switch
Press to power-on or power-off the system
Power LED
Indicates the power status of the system
HDD LED
Indicates the status of the hard drive
Antenna hole
Used to connect an antenna for optional Mini-
PCIeWiFimodule
```

```
USB 3.2 Gen 2 port (10 Gbps)
Used to connect USB 3.2 device
```

```
Removable HDD
Removable 2.5" SATA HDD Bay
(support H=7mm, hot-swappable)
Support RAID 0, 1
```

```
AT/ATX mode select switch
Used to select AT or ATX power mode
```

```
Clear CMOS
Used to clear CMOS
SIM card
Used to insert SIM card
Line-out
Used to connect a speaker
Mic-in
Used to connect a microphone
Remote Power on/off Terminal Block
Used to plug a remote power on/off terminal
block
```

```
PC/Car mode select switch
Used to select PC or Car mode
```

```
EDGEBoostI/O bracket (optional)
```

###### 1.3.8 RCO- 6000 - RPL-8NS

**Chapter 1: Product Introductions**

### Front Panel

```
Top Module (Industrial FanlessPC on Top)
```

```
Bottom Module (Flexible and Dedicated “EDGEBoostNodes” on Bottom)
```

- **Data Cartridge A**
  Hot swappable NVMeSSD CannisterBricks,
  1x Removable 4 Bay NVMeSSD Module with RAID
  0, 1, 5, 10 support (Support H=7mm)
- **Lock**
  Used to key switch
- **Data Cartridge B**
  Hot swappable NVMeSSD CannisterBricks),
  1x Removable 4 Bay NVMeSSD Module with RAID
  0, 1, 5, 10 support (Support H=7mm)
- **Storage Ejection Button**
  Safety Storage Ejection Button to suspend all I/O
  operation, read-write to prevent loss or
  corruption of data

```
EDGEBoost I/O Bracket
```

**Chapter 1: Product Introductions**

```
DVI-I port
Used to connect a DVI monitor or connect
optional split cable for dual display mode
```

```
Digital I/O Terminal Block
The Digital I/O terminal block supports 8 digital
input and 8 digital output
DisplayPort
Used to connect a DisplayPort monitor
COM port
COM1 ~ COM2 support RS232/422/485 serial
device
```

```
USB 3.2 Gen 2 port (10 Gbps)
Used to connect USB 3.2 device
LAN port
Used to connect the system to a local area
network
```

```
Antenna hole
Used to connect an antenna for optional Mini-
PCIeWiFimodule
DC IN (5-pin Terminal Block)
Used to plug a DC power input with terminal
block
```

### Rear Panel

###### 1.3.9 RCO- 6000 - RPL-A2000

```
Bottom Module (Flexible and Dedicated “EDGEBoostNodes” on Bottom)
```

```
Top Module (Industrial FanlessPC on Top)
```

- **DC IN** (4-pin Terminal Block)
  Used to plug a DC power input with terminal
  block
- **Fan**
  Hot-Swappable Rear-Fan Exhaust design for
  easy maintenance

###### 1.3.9 RCO- 6000 - A2000

**Chapter 1: Product Introductions**

```
ATX power on/off switch
Press to power-on or power-off the system
Power LED
Indicates the power status of the system
HDD LED
Indicates the status of the hard drive
Antenna hole
Used to connect an antenna for optional Mini-
PCIeWiFimodule
```

```
USB 3.2 Gen 2 port (10 Gbps)
Used to connect USB 3.2 device
```

```
Removable HDD
Removable 2.5" SATA HDD Bay
(support H=7mm, hot-swappable)
```

```
AT/ATX mode select switch
Used to select AT or ATX power mode
```

```
Clear CMOS
Used to clear CMOS
SIM card
Used to insert SIM card
Line-out
Used to connect a speaker
Mic-in
Used to connect a microphone
Remote Power on/off Terminal Block
Used to plug a remote power on/off terminal
block
```

```
PC/Car mode select switch
Used to select PC or Car mode
```

```
EDGEBoostI/O bracket (optional)
```

```
Fan
Hot-Swappable Rear-Fan Exhaust design for
easy maintenance
```

### Front Panel

```
Top Module (Industrial FanlessPC on Top)
```

```
Bottom Module (Flexible and Dedicated “EDGEBoostNodes” on Bottom)
```

```
EDGEBoost I/O Bracket
```

**Chapter 1: Product Introductions**

###### RCO- 6000 - RPL-A2000

```
DVI-I port
Used to connect a DVI monitor or connect
optional split cable for dual display mode
```

```
Digital I/O Terminal Block
The Digital I/O terminal block supports 8 digital
input and 8 digital output
DisplayPort
Used to connect a DisplayPort monitor
COM port
COM1 ~ COM2 support RS232/422/485 serial
device
```

```
USB 3.2 Gen 2 port (10 Gbps)
Used to connect USB 3.2 device
LAN port
Used to connect the system to a local area
network
```

```
Antenna hole
Used to connect an antenna for optional Mini-
PCIeWiFimodule
DC IN (5-pin Terminal Block)
Used to plug a DC power input with terminal
block
```

### Rear Panel

```
DC IN
12~48VDC for GPU/Card Expansion
```

```
RTX A2000 integrated
```

```
Bottom Module (Flexible and Dedicated “EDGEBoostNodes” on Bottom)
```

```
Top Module (Industrial FanlessPC on Top)
```

```
ATX power on/off switch
Press to power-on or power-off the system
Power LED
Indicates the power status of the system
HDD LED
Indicates the status of the hard drive
Antenna hole
Used to connect an antenna for optional Mini-
PCIeWiFimodule
```

```
USB 3.2 Gen 2 port (10 Gbps)
Used to connect USB 3.2 device
```

```
Removable HDD
Removable 2.5" SATA HDD Bay
(support H=7mm, hot-swappable)
Support RAID 0, 1
```

```
AT/ATX mode select switch
Used to select AT or ATX power mode
```

```
Clear CMOS
Used to clear CMOS
SIM card
Used to insert SIM card
Line-out
Used to connect a speaker
Mic-in
Used to connect a microphone
Remote Power on/off Terminal Block
Used to plug a remote power on/off terminal
block
```

```
PC/Car mode select switch
Used to select PC or Car mode
```

```
EDGEBoostI/O bracket (optional)
```

###### 1.3.10 RCO- 6000 - RPL-2NA2000

**Chapter 1: Product Introductions**

### Front Panel

```
Top Module (Industrial FanlessPC on Top)
```

```
Bottom Module (Flexible and Dedicated “EDGEBoostNodes” on Bottom)
```

```
Fan
Hot-Swappable Rear-Fan Exhaust design for
easy maintenance
```

**Chapter 1: Product Introductions**

```
DVI-I port
Used to connect a DVI monitor or connect
optional split cable for dual display mode
```

```
Digital I/O Terminal Block
The Digital I/O terminal block supports 8 digital
input and 8 digital output
DisplayPort
Used to connect a DisplayPort monitor
COM port
COM1 ~ COM2 support RS232/422/485 serial
device
```

```
USB 3.2 Gen 2 port (10 Gbps)
Used to connect USB 3.2 device
LAN port
Used to connect the system to a local area
network
```

```
Antenna hole
Used to connect an antenna for optional Mini-
PCIeWiFimodule
DC IN (5-pin Terminal Block)
Used to plug a DC power input with terminal
block
```

### Rear Panel

###### RCO- 6000 - RPL-2NA2000

```
Bottom Module (Flexible and Dedicated “EDGEBoostNodes” on Bottom)
```

```
Top Module (Industrial FanlessPC on Top)
```

- **DC IN** (4-pin Terminal Block)
  Used to plug a DC power input with terminal
  block
- **Data Cartridge**
  1x Removable Cannister Brick with
  2.5" 2 Bay U.2 NVMeSSD (Support
  H=15mm)
- **RTX A2000 integrated**
  - **Storage Ejection Button**
    Safety Storage Ejection Button to suspend
    all I/O operation, read-write to prevent
    loss or corruption of data

```
ATX power on/off switch
Press to power-on or power-off the system
Power LED
Indicates the power status of the system
HDD LED
Indicates the status of the hard drive
Antenna hole
Used to connect an antenna for optional Mini-
PCIeWiFimodule
```

```
USB 3.2 Gen 2 port (10 Gbps)
Used to connect USB 3.2 device
```

```
Removable HDD
Removable 2.5" SATA HDD Bay
(support H=7mm, hot-swappable)
Support RAID 0, 1
```

```
AT/ATX mode select switch
Used to select AT or ATX power mode
```

```
Clear CMOS
Used to clear CMOS
SIM card
Used to insert SIM card
Line-out
Used to connect a speaker
Mic-in
Used to connect a microphone
Remote Power on/off Terminal Block
Used to plug a remote power on/off terminal
block
```

```
PC/Car mode select switch
Used to select PC or Car mode
```

```
EDGEBoostI/O bracket (optional)
```

###### 1.3.11 RCO- 6000 - RPL-4NA2000

**Chapter 1: Product Introductions**

### Front Panel

```
Top Module (Industrial FanlessPC on Top)
```

```
Bottom Module (Flexible and Dedicated “EDGEBoostNodes” on Bottom)
```

```
Fan
Hot-Swappable Rear-Fan Exhaust design for
easy maintenance
```

**Chapter 1: Product Introductions**

```
DVI-I port
Used to connect a DVI monitor or connect
optional split cable for dual display mode
```

```
Digital I/O Terminal Block
The Digital I/O terminal block supports 8 digital
input and 8 digital output
DisplayPort
Used to connect a DisplayPort monitor
COM port
COM1 ~ COM2 support RS232/422/485 serial
device
```

```
USB 3.2 Gen 2 port (10 Gbps)
Used to connect USB 3.2 device
LAN port
Used to connect the system to a local area
network
```

```
Antenna hole
Used to connect an antenna for optional Mini-
PCIeWiFimodule
DC IN (5-pin Terminal Block)
Used to plug a DC power input with terminal
block
```

### Rear Panel

###### RCO- 6000 - RPL-4NA2000

```
Bottom Module (Flexible and Dedicated “EDGEBoostNodes” on Bottom)
```

```
Top Module (Industrial FanlessPC on Top)
```

- **DC IN** (4-pin Terminal Block)
  Used to plug a DC power input with terminal
  block
- **Data Cartridge**
  1x Removable Cannister Brick with 2.5“
  4 Bay U.2 NVMeSSD (Support H=7mm)
- **RTX A2000 integrated**
  - **Storage Ejection Button**
    Safety Storage Ejection Button to suspend
    all I/O operation, read-write to prevent
    loss or corruption of data

###### 1.3.12 EDGEBoostI/O Bracket (Available EDGEBoostI/O)

**Chapter 1: Product Introductions**

###### Model No :

- **4x RJ45 LAN Ports**
- **4x RJ45 PoE Ports** (Left EBIO slot only)
- **4x M12 LAN Ports**
- **4x M12 PoE Ports** (Left EBIO slot only)
- **2x 10GbE Ports** (Right EBIO slot only)
- **4x USB 3.2 Gen 1 Ports**
  - **2x 5G SIM Slot** (Left EBIO Slot Only)
- RCO- 6000 - RPL
- RCO- 6000 - RPL-2E16
- RCO- 6000 - RPL-2E16-2PWR
- RCO- 6000 - RPL-2E16-4B7M
- RCO- 6000 - RPL-2E16-2B15M
- RCO- 6000 - RPL-2E16-2N15M

###### Available Module :

- RCO- 6000 - RPL-4NH
- RCO- 6000 - RPL-4NS
- RCO- 6000 - RPL-8NS
  - **2x M.2 B-Key (1x 5G SIM)** (Right EBIO Slot Only)
  - **1x M.2 M-Key (4-Lane)**
    - RCO- 6000 - RPL-A2000
    - RCO- 6000 - RPL-2NA2000
    - RCO- 6000 - RPL-4NA2000

```
Left EBIO Right EBIO
```

```
Unit: mm
```

**Chapter 1: Product Introductions**

### 1.4 Mechanical Dimensions

###### 1.4.1 RCO- 6000 - RPL

```
Unit: mm
```

**Chapter 1: Product Introductions**

###### 1.4.2 RCO- 6000 - RPL-2E16

```
Unit: mm
```

**Chapter 1: Product Introductions**

###### 1.4.3 RCO- 6000 - RPL-2E16-4B7M

```
Unit: mm
```

**Chapter 1: Product Introductions**

###### 1.4.4 RCO- 6000 - RPL- 2 E16-2B15M / RCO- 6000 - RPL-2E16-2N15M

```
Unit: mm
```

**Chapter 1: Product Introductions**

###### 1.4.5 RCO- 6000 - RPL- 2 E16-2PWR

```
Unit: mm
```

**Chapter 1: Product Introductions**

###### 1.4. 6 RCO- 6000 - RPL-4NH...................................................................................

```
Unit: mm
```

**Chapter 1: Product Introductions**

###### 1.4. 7 RCO- 6000 - RPL-4NS...................................................................................

```
Unit: mm
```

**Chapter 1: Product Introductions**

###### 1.4. 8 RCO- 6000 - RPL-8NS..................................................................................

```
Unit: mm
```

**Chapter 1: Product Introductions**

###### 1.4. 9 RCO- 6000 - RPL-A2000...............................................................................

```
Unit: mm
```

**Chapter 1: Product Introductions**

###### 1.4. 10 RCO- 6000 - RPL-2NA2000.........................................................................

```
Unit: mm
```

**Chapter 1: Product Introductions**

###### 1.4. 11 RCO- 6000 - RPL-4NA2000.........................................................................

## Chapter 2 Mechanical Specifications..............................................................

##### 2.1 Switch and connector Locations

```
Chapter 2: Mechanical Specifications
```

###### 2.1.1 Top View

```
ACC 1 DC_IN 1 DIO 1 COM 1_2 DVI_I 1 CN 4 CN 3 PWR_SW 2
```

```
DC_IN 2
```

```
CPU 1 SODIMM 1
```

```
FAN_MCU
```

```
PCH 1
M2_KB I2C
FAN_SIO
CAN 2
```

```
SMB
```

```
CAN 1
```

```
JP 1
```

```
POWER 3
```

```
POWER 4
```

```
USB 3_2 USB 3_4
```

```
AT_ATX USB 3_3
```

```
SIM 1
```

```
CAR_PWR
```

```
MIC_IN
LINE_OUT
```

```
USB 3_1
```

```
JA1
```

```
POWER 1
```

```
POWER 2
```

PWR_SW 1

```
USB 2_L
```

```
BH 1
```

```
COM 5
```

```
COM 6
```

```
TEMP 1
```

```
M2_KE
LAN_L LAN_R
```

```
MINI-PCIE COM 3
```

```
COM 4
```

```
JESPI 1
```

```
CN 1
```

```
BAT_F 1
```

```
DP 2 DP 1
```

```
Chapter 2: Mechanical Specifications
```

###### 2.1.2 Bottom View

```
SODIMM 2
```

```
SATA 3
```

```
SL 1
```

```
PCIE 2
```

```
SATA 1
```

```
SATA 2
```

```
PCIE 1
```

```
RESET SIM 2
```

```
BTB
```

##### 2.2 Connector / Switch Definition

```
Chapter 2: Mechanical Specifications
```

###### Connector Location Definition

```
AT_ATX AT / ATX Power Mode Switch
```

```
PWR_SW1,2,3 Power Switch
```

```
RESET Reset Switch
```

```
DC_IN1 5 - pin DC +9~48V Power Input Connector
```

```
DC_IN2 6 - pin DC +9~48V Power Input Connector
```

```
DIO1 8DI / 8DO Connector
```

```
COM1- 6 RS232 / RS422 / RS485 Connector
```

```
DP1,2 DP Connector
```

```
DVI_I1 DVI-I Connector
```

```
CN3,4 LAN and USB3. 2 GEN 2 Ports X2
```

```
FAN_CPU,FAN_SIO Smart FAN Connector
```

```
PWR1- 4 +12V / 5V Power Connector
```

```
USB3_1- 4 USB 3.2 Gen 2 、USB 3.2 Gen 1、USB2.0
```

```
SIM1, SIM2 SIM Card Socket
```

```
CAR_PWR PC mode / CAR mode select
```

```
SL1 PCI-Express X8 Slimline Connector
```

```
MIC_IN Mic-in Jack
```

```
LINE_OUT LINE-OUT Jack
```

```
M2_KE , M2_KB M.2 key E , key B Connector
```

```
PCIE1,2, LAN_L, LAN_R
PCI-Express X1 Slot, PCI-Express X8 Slot
(PCIex4 w POE) , PCI-Express x16 Slot
MINI-PCIE Mini PCI-Express Socket
```

```
PWR_LED Power LED Status
```

```
HDD_LED HDD Access LED Status
```

```
WDT_LED1 Watchdog LED Status
```

```
SATA3 SATA X 4 Port
```

```
SATA1,2 SATA with Power Connector
```

##### 2.3 I/O Interface Descriptions

```
Chapter 2: Mechanical Specifications
```

###### 2.3.1 ESPI Debug Con

###### JESPI 1

###### POWER 1~4

###### 2.3.2 Power Con

```
Pin Signal
```

```
1 +5V
```

```
2 GND
```

```
3 GND
```

```
4 +12V
```

**1**

**4**

**1**

**2**

**9**

**10**

```
Pin Signal Pin Signal
```

```
1 ESPI_IO_0 2 3.3V
```

```
3 ESPI_IO_1 4 ESPI_RESET#
```

```
5 ESPI_IO_2 6 ESPI_CS#
```

```
7 ESPI_IO_3 8 ESPI_CLOCK
```

```
9 N/A 10 GND
```

```
Chapter 2: Mechanical Specifications
```

###### 2.3.3 DC IN 1 : 9V ~ 48V

###### DC IN 1

###### DC IN 2

###### 2.3.4 DC IN 2 : 9V ~ 48V

```
Pin Signal
```

```
1 +9V ~ +48V
```

```
2 +9V ~ +48V
```

```
3 +9V ~ +48V
```

```
4 GND
```

```
5 GND
```

```
6 GND
```

**1 5**

```
Pin Signal
```

```
1 +9V ~ +48V
```

```
2 +9V ~ +48V
```

```
3 GND
```

```
4 GND
```

```
5 IGN
```

**1**

**6**

```
Chapter 2: Mechanical Specifications
```

###### 2.3.5 COM Con

###### COM 5, COM 6

```
Pin Signal Pin Signal
1 DCD# 2 DSR#
3 RXD 4 RTS#
5 TXD 6 CTS#
7 DTR# 8 RI#
9 GND 10 GND
```

###### RS232 / RS422 / RS485 Connector 2x5 10-pin box header, 2.0mm pitch

```
Pin Signal
RS422 / 485 Full Duplex
Definition
RS485 Half Duplex Definition
```

```
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

**1 2**

```
Chapter 2: Mechanical Specifications
```

###### COM 3 , COM 4

```
Pin Signal Pin Signal
```

```
1 DCD# 2 DSR#
```

```
3 RXD 4 RTS#
```

```
5 TXD 6 CTS#
```

```
7 DTR# 8 RI#
```

```
9 GND 10 GND
```

###### COM Con

**1**

**2**

```
Chapter 2: Mechanical Specifications
```

###### COM 1_2

```
Pin RS232 Definition
RS422 / 485 Full Duplex
Definition
RS485 Half Duplex Definition
```

```
1 DCD# TX- DATA-
```

```
2 RxD TX+ DATA+
```

```
3 TxD RX+
```

```
4 DTR# RX-
```

```
5 GND GND GND
```

```
6 DSR#
```

```
7 RTS#
```

```
8 CTS#
```

```
9 RI#
```

**1 5**

```
6 9
1 5
```

**6 9**

###### RS232 / RS422 / RS485 Connector Type: 9-pin D-Sub

###### COM Con

```
Chapter 2: Mechanical Specifications
```

###### 2.3.6 SF100 SPI Con

###### JP 1

```
Switch Definition
```

```
1 Power ( 3V )
```

```
2 GND
```

```
3 CS#
```

```
4 CLK
```

```
5 MISO
```

```
6 MOSI
```

```
7 NC
```

```
8 SPI_GATE#
```

**1 2**

**7 8**

```
Chapter 2: Mechanical Specifications
```

###### 2.3.7 AT / ATX Power Mode Switch

###### AT_ATX

```
Switch Definition
```

```
1 - 2 (Left) ATX Power Mode (Default)
```

```
2 - 3 (Right) AT Power Mode
```

###### 2.3.8 PC / Car Mode Switch

###### CAR_PWR

```
Switch Definition
```

```
1 - 2 (Left) PC Power Mode (Default)
```

```
2 - 3 (Right) Power Ignition Mode
```

```
Chapter 2: Mechanical Specifications
```

###### 2.3.9 Line-out Jack (Pink) Connector Type: 5-pin Phone Jack

###### LINE_OUT

```
Switch Definition
```

```
1 GND
```

```
2 OUT_R
```

```
3 GND
```

```
4 GND
```

```
5 OUT_L
```

###### MIC_IN

```
Switch Definition
```

```
1 GND
```

```
2 MIC_R
```

```
3 GND
```

```
4 GND
```

```
5 MIC_L
```

###### 2.3. 10 Microphone-in Jack (Green) Connector Type: 5-pin Phone Jack

```
Chapter 2: Mechanical Specifications
```

###### 2.3.11 Clear BIOS Switch

###### CLR_CMOS

```
Switch Definition
```

```
1 - 2 (Left) Normal Status (Default)
```

```
2 - 3 (Right) Clear BIOS
```

###### PWR_SW 1

```
Switch Definition
```

```
1 NC
```

```
2 Power Button
```

```
3 NC
```

```
4 GND
```

```
5 NC
```

```
6 GND
```

###### 2.3. 12 Power Button

```
Chapter 2: Mechanical Specifications
```

###### 2.3.13 Remote Power Switch Type: Terminal Block 1x2 2-pin, 3.5mm pitch

###### PWR_SW 2

###### PWR_SW 3

```
Pin Definition
```

```
1 Power Button
```

```
2 PWR_LED
```

```
3 HDD_LED
```

```
4 GND
```

###### 2.3. 14 For RCO- 6000 - RPL

**1 2**

```
Pin Definition
```

(^1) Power Button
2 GND
**1
4**

```
Chapter 2: Mechanical Specifications
```

###### 2.3.15 Reset Button

###### RESET

```
Switch Definition
```

```
1,2 RESET
```

```
3,4 GND
```

###### 2.3.16 USB 3.1 Connector, GEN2 x4 ports, Type A

###### USB 3_1 , USB 3_2 , USB 3_3 , USB 3_4

```
Pin Definition
```

```
1 +5V
```

```
2 USB2_D-
```

```
3 USB2_D+
```

```
4 GND
```

```
5 USB3_RX-
```

```
6 USB3_RX+
```

```
7 GND
```

```
8 USB3_TX-
```

```
9 USB3_TX+
```

```
Chapter 2: Mechanical Specifications
```

###### 2.3.17 USB3.0 Connector, 2x5 10-pin header, 2.0mm pitch

###### CN 1

```
Switch Definition
```

```
1 +5V
```

```
2 USB3_TX-
```

```
3 USB_D-
```

```
4 USB3_TX+
```

```
5 USB_D+
```

```
6 GND
```

```
7 GND
```

```
8 USB3_RX-
```

```
9 NC
```

```
10 USB3_RX+
```

**1 2**

**9 10**

```
Chapter 2: Mechanical Specifications
```

###### 2.3.18 USB2.0 Connector, 2x5 10-pin box header, 2.0mm pitch

###### USB 2_L

```
Switch Definition
```

```
1 NC
```

```
2 +5V
```

```
3 NC
```

```
4 USB2_D-
```

```
5 NC
```

```
6 USB2_D+
```

```
7 NC
```

```
8 GND
```

```
9 NC
```

```
10 GND
```

**9 10**

**1 2**

```
Chapter 2: Mechanical Specifications
```

###### 2.3.19 LAN and USB 3.1 GEN 2 Ports Connector Type: RJ45 port with LEDs and dual

###### USB 3.1 ports

###### CN3, CN4

```
Pin Definition Pin Definition Pin Definition
```

```
1 +5V 10 +5V 20 LAN1_MDI0P
```

```
2 USB2_D1- 11 USB2_D2- 21 LAN1_MDI0N
```

```
3 USB2_D1+ 12 USB2_D2+ 22 LAN1_MDI1P
```

```
4 GND 13 GND 23 LAN1_MDI2P
```

```
5 USB3_RX1- 14 USB3_RX2- 24 LAN1_MDI2N
```

```
6 USB3_RX1+ 15 USB3_RX2+ 25 LAN1_MDI1N
```

```
7 GND 16 GND 26 LAN1_MDI3P
```

```
8 USB3_TX1- 17 USB3_TX2- 27 LAN1_MDI3N
```

```
9 USB3_TX1+ 18 USB3_TX2+
```

```
Chapter 2: Mechanical Specifications
```

###### 2.3.20 DVI-I Connector

###### DVI_I 1

```
Pin Definition Pin Definition
```

```
1 DVI_TX2- 16 DVI Hot Plug Detect
```

```
2 DVI_TX2+ 17 DVI_TX0-
```

```
3 GND 18 DVI_TX0+
```

```
4 NC 19 GND
```

```
5 NC 20 VGA_DDC_CLOCK
```

```
6 DVI_DDC_CLOCK 21 VGA_DDC_DATA
```

```
7 DVI_DDC_DATA 22 GND
```

```
8 VGA VSYNC 23 DVI_TXCLK+
```

```
9 DVI_TX1- 24 DVI_TXCLK-
```

```
10 DVI_TX1+ C1 VGA_RED
```

```
11 GND C2 VGA_GREEN
```

```
12 NC C3 VGA_BLUE
```

```
13 NC C4 VGA_HSYNC
```

```
14 +5V C5 GND
```

```
15 GND
```

**1**

**17**

**8**

**24**

```
Chapter 2: Mechanical Specifications
```

###### 2.3.21 Display Port Connector

###### DP 1, DP 2

```
Pin Definition Pin Definition
```

```
1 DP_LANE0_P 11 GND
```

```
2 GND 12 DP_LANE3_N
```

```
3 DP_LANE0_N 13 GND
```

```
4 DP_LANE1_P 14 GND
```

```
5 GND 15 DP_AUX_P
```

```
6 DP_LANE1_N 16 GND
```

```
7 DP_LANE2_P 17 DP_AUX_N
```

```
8 GND 18 DP_HPD
```

```
9 DP_LANE2_N 19 GND
```

```
10 DP_LANE3_P 20 +3.3V
```

###### 1

###### 2

###### 19

###### 20

###### 1

###### 2

###### 19

###### 20

```
Chapter 2: Mechanical Specifications
```

###### 2.3.22 Digital Input / Output Connector Type: Terminal Block 2x9 18-pin, 3.5mm pitch

###### DIO

```
Pin Definition Pin Definition
```

```
1 DIN1 2 DOUT1
```

```
3 DIN2 4 DOUT2
```

```
5 DIN3 6 DOUT3
```

```
7 DIN4 8 DOUT4
```

```
9 DIN5 10 DOUT5
```

```
11 DIN6 12 DOUT6
```

```
13 DIN7 14 DOUT7
```

```
15 DIN8 16 DOUT8
```

```
17 DC power input (+5V~+24V) 18 GND
```

**1**

**2**

**17**

**18**

**Chapter 2: Mechanical Specifications**

###### CAN1 CAN2

```
Pin Signal
```

```
1 CAN_H
```

```
2 CAN_L
```

###### FAN_SIO

```
Switch Definition
```

```
1 GND
```

```
2 +12V
```

```
3 Sense
```

```
4 Control
```

**1**

**2**

**1**

**4**

**Chapter 2: Mechanical Specifications**

###### FAN_MCU

```
Pin Signal
```

```
1 GND
```

```
2 +12V
```

```
3 Sense
```

```
4 Control
```

**1**

**4**

###### For FAN_MCU RT

**1**

**2**

###### TEMP1

**Chapter 2: Mechanical Specifications**

###### BH 1

```
Pin Signal
```

```
1 +3.3V
```

```
2 PLTRST#
```

```
3 SLP S 4
```

```
4 SLP S5
```

```
5 RSTBTN#
```

```
6 GND
```

###### I2C

```
Switch Definition
```

```
1 I2C_DATA
```

```
2 I2C_CLK
```

```
3 GND
```

**1**

**6**

**1**

**3**

**Chapter 2: Mechanical Specifications**

###### SMB

```
Pin Signal
```

```
1 SMB_DATA
```

```
2 SMB_CLK
```

```
3 GND
```

**1**

**3**

```
Chapter 2: Mechanical Specifications
```

###### 2.3.23 LED Status

```
Act LED Status Definition
```

```
Blinking Yellow Data Activity
Off No Activity
```

###### PWR_LED1: Power LED Status

```
Pin Definition
```

```
1 POWER LED +
2 POWER LED -
```

```
Link LED Status CN3 Definition
```

```
Steady Orange 1 Gbps Network Link
Steady Green 100 Mbps Network Link
```

```
Off 10 Mbps Network Link
```

###### HDD_LED1: HDD Access LED Status

```
Pin Definition
```

```
1 HDD LED+
2 HDD LED-
```

```
Link LED Status CN4 Definition
```

```
Steady Orange 2.5 Gbps Network Link
```

```
Steady Green 1 Gbps Network Link
```

```
Off 100 Mbps Network Link
```

```
Chapter 2: Mechanical Specifications
```

###### LED Status

###### WDT_LED : WDTOUT LED Status

```
Pin Definition
```

(^1) WDTOUT LED+
(^2) WDTOUT LED-

```
Chapter 2: Mechanical Specifications
```

###### 2.3.24 Top size SIM Card Socket

###### SIM1 (Top size for M.2 B Key)

```
Pin Definition Pin Definition
```

```
C1 UIM_PWR C6 UIM_VPP
```

```
C2 UIM_RESET C7 UIM_DATA
```

```
C3 UIM_CLK CD NC
```

```
C5 GND COM GND
```

**C1**

**COM**

SIM1

```
Chapter 2: Mechanical Specifications
```

###### 2.3.25 Bottom size SIM Card Socket

###### SIM2 (Bottom size for Mini PCIe)

```
Pin Definition Pin Definition
```

```
C1 UIM_PWR C6 UIM_VPP
```

```
C2 UIM_RESET C7 UIM_DATA
```

```
C3 UIM_CLK CD NC
```

```
C5 GND COM GND
```

**C1**

**COM**

SIM2

```
Chapter 2: Mechanical Specifications
```

###### 2.3.26 Mini PCI-Express / mSATA Socket

###### MINIPCIE

```
Pin Definition Pin Definition
```

```
1 WAKE# 2 +3.3V
```

```
3 NC 4 GND
```

```
5 NC 6 +1.5V
```

```
7 CLKREQ# 8 UIM_PWR
```

```
9 GND 10 UIM_DATA
```

```
11 REFCLK- 12 UIM_CLK
```

```
13 REFCLK+ 14 UIM_RST
```

```
15 GND 16 UIM_VPP
```

```
17 NC 18 GND
```

```
19 NC 20 NC
```

```
21 GND 22 RESET#
```

```
23 RxN 24 +3.3VAUX
```

```
25 RxP 26 GND
```

```
27 GND 28 +1.5V
```

```
2 1
```

```
52 51
```

**Chapter 2: Mechanical Specifications**

```
Pin Definition Pin Definition
```

```
29 GND 30 SMB_CLK
```

```
31 TxN 32 SMB_DATA
```

```
33 TxP 34 GND
```

```
35 GND 36 USB2_D-
```

```
37 GND 38 USB2_D+
```

```
39 +3.3V 40 GND
```

```
41 +3.3V 42 NC
```

```
43 GND 44 DEVSLP
```

```
45 NC 46 NC
```

```
47 NC 48 +1.5V
```

```
49 NC 50 GND
```

```
51 PCIE_MSATA_SEL 52 +3.3V
```

```
Chapter 2: Mechanical Specifications
```

###### 2.3.27 M.2 E Key Socket

###### M2_KE

```
Pin Definition Pin Definition
```

```
1 GND 2 +3.3VAUX
```

```
3 USB2_D+ 4 +3.3VAUX
```

```
5 USB2_D- 6 NC
```

```
7 GND 8 I2S2_SCLK
```

```
9 CNV_WR_1_DN 10 CNV_RF_RESET#
```

```
11 CNV_WR_1_DP 12 I2S2_RXD
```

```
13 GND 14 MODEM_CLKREQ
```

```
15 CNV_WR_0_DN 16 NC
```

```
17 CNV_WR_0_DP 18 GND
```

```
19 GND 20 UART_WAKE_L
```

```
21 CNV_WR_CLK_DN 22 CNV_BRI_RSP
```

```
23 CNV_WR_CLK_DP 32 CNV_RGI_DT
```

```
33 GND 34 CNV_RGI_RSP
```

```
35 TxP0 36 CNV_BRI_DT
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
Pin Definition Pin Definition
```

```
37 TxN0 38 CL_RST#
```

```
39 GND 40 CL_DATA
```

```
41 RxP0 42 CL_CLK
```

```
43 RxN0 44 CNV_PA_BLANKING
```

```
45 GND 46 CNV_MFUART2_TXD
```

```
47 REFCLK0+ 48 CNV_MFUART2_RXD
```

```
49 REFCLK0- 50 SUSCLK
```

```
51 GND 52 PERST0#
```

```
53 NC 54 M2_KEY-E_BT_DIS2#
```

```
55 WAKE0# 56 M2_KEY-E_WIFI_DIS1#
```

```
57 GND 58 SMBDATAS_DUAL
```

```
59 CNV_WT_1_DN 60 SMBCLKS_DUAL
```

```
61 CNV_WT_1_DP 62 SMBALERT#
```

```
63 GND 64 Pull Low
```

```
65 CNV_WT_0_DN 66 PERST1#
```

```
67 CNV_WT_0_DP 68 NC
```

```
69 GND 70 WAKE1#
```

```
71 CNV_WT_CLK_DN 72 +3.3VAUX
```

```
73 CNV_WT_CLK_DP 74 +3.3VAUX
```

```
75 GND
```

```
Chapter 2: Mechanical Specifications
```

###### 2.3.28 M.2 B Key Socket

###### M2_KB

```
Pin Definition Pin Definition
```

```
1 CONFIG_3 2 +3.3V
```

```
3 GND 4 +3.3V
```

```
5 GND 6 FULL_CARD_POWER_OFF#
```

```
7 USB_D+ 8 W_DISABLE1#
```

```
9 USB_D- 10 WWAN_LED#
```

```
11 GND 20 NC
```

```
21 CONFIG_0 22 NC
```

```
23 GPIO_11(0/1.8V) 24 NC
```

```
25 DPR 26 NC
```

```
27 GND 28 P_UIM_VPP
```

```
29 PERn1/USB3.0-Rx- 30 USIM1_RST
```

```
31 PERp1/USB3.0-Rx+ 32 USIM1_CLK
```

```
33 GND 34 USIM1_DATA
```

```
35 PETn1/USB3.0-Tx- 36 USIM1_VDD
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
Pin Definition Pin Definition
```

```
37 PETp1/USB3.0-Tx+ 38 NC
```

```
39 GND 40 NC
```

```
41 PERn0/SATA-B+ 42 NC
```

```
43 PERp0/SATA-B- 44 NC
```

```
45 GND 46 NC
```

```
47 PETn0/SATA-A- 48 NC
```

```
49 PETp0/SATA-A+ 50 PCIE_RST_N
```

```
51 GND 52 PCIE_CLKREQ_N
```

```
53 PCIE_REFCLK_M 54 PCIE_WAKE_N
```

```
55 PCIE_REFCLK_P 56 NC
```

```
57 GND 58 NC
```

```
59 NC 60 NC
```

```
61 NC 62 NC
```

```
63 NC 64 NC
```

```
65 NC 66 USIM1_DET
```

```
67 NC 68 SUSCLK(32kHz)
```

```
69 CONFIG_1 70 +3.3VAUX
```

```
71 GND 72 +3.3VAUX
```

```
73 GND 74 +3.3VAUX
```

```
75 CONFIG_2
```

```
Chapter 2: Mechanical Specifications
```

###### 2.3.29 PCI-Express x1 Slot

###### PCIE 2

```
Pin Definition Pin Definition
B1 +12V A1 FAN_P4
B2 +12V A2 +12V
B3 +12V A3 +12V
B4 GND A4 GND
B5 SMB_CLK A5 NC
B6 SMB_DATA A6 NC
B7 GND A7 NC
B8 +3.3V A8 NC
B9 NC A9 +3.3V
B10 +3.3VAUX A10 +3.3V
B11 WAKE# A11 RESET#
B12 FAN_P3 A12 GND
B13 GND A13 REFCLK+
B14 TxP0 A14 REFCLK-
B15 TxN0 A15 GND
B16 GND A16 RxP0
B17 FAN_PER A17 RxN0
B18 GND A18 GND
```

```
Chapter 2: Mechanical Specifications
```

###### 2.3.30 PCI-Express x16 Slot

###### PCIE 1

```
Pin Definition Pin Definition
```

```
B1 +12V A1 NC
```

```
B2 +12V A2 +12V
```

```
B3 +12V A3 +12V
```

```
B4 GND A4 GND
```

```
B5 SMB_CLK A5 NC
```

```
B6 SMB_DATA A6 NC
```

```
B7 GND A7 NC
```

```
B8 +3.3V A8 NC
```

```
B9 NC A9 +3.3V
```

```
B10 +3.3VAUX A10 +3.3V
```

```
B11 WAKE# A11 RESET#
```

```
B12 NC A12 GND
```

```
B13 GND A13 REFCLK+
```

**Chapter 2: Mechanical Specifications**

```
Pin Definition Pin Definition
```

```
B14 TxP0 A14 REFCLK-
```

```
B15 TxN0 A15 GND
```

```
B16 GND A16 RxP0
```

```
B17 NC A17 RxN0
```

```
B18 GND A18 GND
```

```
B19 TxP1 A19 NC
```

```
B20 TxN1 A20 GND
```

```
B21 GND A21 RxP1
```

```
B22 GND A22 RxN1
```

```
B23 TxP2 A23 GND
```

```
B24 TxN2 A24 GND
```

```
B25 GND A25 RxP2
```

```
B26 GND A26 RxN2
```

```
B27 TxP3 A27 GND
```

```
B28 TxN3 A28 GND
```

```
B29 GND A29 RxP3
```

```
B30 NC A30 RxN3
```

```
B31 S3 A31 GND
```

```
B32 GND A32 CFG_5
```

```
B33 TxP4 A33 CFG_6
```

```
B34 TxN4 A34 GND
```

```
B35 GND A35 RxP4
```

```
B36 GND A36 RxN4
```

```
B37 TxP5 A37 GND
```

```
B38 TxN5 A38 GND
```

**Chapter 2: Mechanical Specifications**

```
Pin Definition Pin Definition
```

```
B39 GND A39 RxP5
```

```
B40 GND A40 RxN5
```

```
B41 TxP6 A41 GND
```

```
B42 TxN6 A42 GND
```

```
B43 GND A43 RxP6
```

```
B44 GND A44 RxN6
```

```
B45 TxP7 A45 GND
```

```
B46 TxN7 A46 GND
```

```
B47 GND A47 RxP7
```

```
B48 NC A48 RxN7
```

```
B49 GND A49 GND
```

```
B50 TxP8 A50 NC
```

```
B51 TxN8 A51 GND
```

```
B52 GND A52 RxP8
```

```
B53 GND A53 RxN8
```

```
B54 TxP9 A54 GND
```

```
B55 TxN9 A55 GND
```

```
B56 GND A56 RxP9
```

```
B57 GND A57 RxN9
```

```
B58 TxP10 A58 GND
```

```
B59 TxN10 A59 GND
```

```
B60 GND A60 RxP10
```

```
B61 GND A61 RxN10
```

```
B62 TxP11 A62 GND
```

```
B63 TxN11 A63 GND
```

**Chapter 2: Mechanical Specifications**

```
Pin Definition Pin Definition
```

```
B64 GND A64 RxP11
```

```
B65 GND A65 RxN11
```

```
B66 TxP12 A66 GND
```

```
B67 TxN12 A67 GND
```

```
B68 GND A68 RxP12
```

```
B69 GND A69 RxN12
```

```
B70 TxP13 A70 GND
```

```
B71 TxN13 A71 GND
```

```
B72 GND A72 RxP13
```

```
B73 GND A73 RxN13
```

```
B74 TxP14 A74 GND
```

```
B75 TxN14 A75 GND
```

```
B76 GND A76 RxP14
```

```
B77 GND A77 RxN14
```

```
B78 TxP15 A78 GND
```

```
B79 TxN15 A79 GND
```

```
B80 GND A80 RxP15
```

```
B81 NC A81 RxN15
```

```
B82 NC A82 GND
```

```
Chapter 2: Mechanical Specifications
```

###### 2.3.31 PCI-Express x8 Slot

###### PCIE (LAN_L , LAN_R)

```
Pin Definition Pin Definition
```

```
B1 +12V A1 NC
```

```
B2 +12V A2 +12V
```

```
B3 +12V A3 +12V
```

```
B4 GND A4 GND
```

```
B5 SMB_CLK A5 NC
```

```
B6 SMB_DATA A6 NC
```

```
B7 GND A7 NC
```

```
B8 +3.3V A8 NC
```

```
B9 NC A9 +3.3V
```

```
B10 +3.3VAUX A10 +3.3V
```

```
B11 WAKE# A11 RESET#
```

```
B12 NC A12 GND
```

```
B13 GND A13 REFCLK+
```

```
B14 TxP0 A14 REFCLK-
```

```
B15 TxN0 A15 GND
```

**Chapter 2: Mechanical Specifications**

```
Pin Definition Pin Definition
```

```
B16 GND A16 RxP0
B17 NC A17 RxN0
B18 GND A18 GND
B19 TxP1 A19 NC
B20 TxN1 A20 GND
B21 GND A21 RxP1
B22 GND A22 RxN1
B23 TxP2 A23 GND
B24 TxN2 A24 GND
B25 GND A25 RxP2
B26 GND A26 RxN2
B27 TxP3 A27 GND
B28 TxN3 A28 GND
B29 GND A29 RxP3
B30 NC A30 RxN3
B31 NC A31 GND
B32 GND A32 NC
B33 9_48VSB_IN A33 9_48VSB_IN
B34 9_48VSB_IN A34 9_48VSB_IN
B35 9_48VSB_IN A35 9_48VSB_IN
B36 9_48VSB_IN A36 9_48VSB_IN
B37 9_48VSB_IN A37 9_48VSB_IN
B38 9_48VSB_IN A38 9_48VSB_IN
B39 9_48VSB_IN A39 9_48VSB_IN
B40 9_48VSB_IN A40 9_48VSB_IN
B41 9_48VSB_IN A41 9_48VSB_IN
B42 9_48VSB_IN A42 9_48VSB_IN
B43 +3.3VAUX A43 +5V
B44 +3.3VAUX A44 +5V
B45 +3.3VAUX A45 +1.5V
B46 +3.3VAUX A46 +1.5V
B47 +1.0VAUX A47 +1.0VAUX
B48 +1.0VAUX A48 +1.0VAUX
B49 NC A49 NC
```

```
Chapter 2: Mechanical Specifications
```

###### 2.3.32 SATA with Power Connector

```
Pin Definition
```

```
1 GND
```

```
2 TxP
```

```
3 TxN
4 GND
```

```
5 RxN
```

```
6 RxP
```

```
7 GND
```

```
8 NC
9 NC
```

```
10 DEVSLP
```

```
11 GND
```

```
Pin Definition
```

```
12 GND
```

```
13 GND
```

```
14 +5V
15 +5V
```

```
16 +5V
```

```
17 GND
```

```
18 GND
```

```
19 GND
20 NC
```

```
21 NC
```

```
22 NC
```

###### SATA 1, SATA 2

**Chapter 2: Mechanical Specifications**

```
Pin Definition Pin Definition Pin Definition Pin Definition
```

```
A1 NC B1 NC C1 NC D1 NC
```

```
A2 NC B2 NC C2 NC D2 NC
```

```
A3 GND B3 GND C3 GND D3 GND
A4 RxP1 B4 RxP0 C4 TxP1 D4 TxP0
```

```
A5 RxN1 B5 RxN0 C5 TxN1 D5 TxN0
```

```
A6 GND B6 GND C6 GND D6 GND
```

```
A7 RxP3 B7 RxP2 C7 TxP3 D7 TxP2
```

```
A8 RxN3 B8 RxN2 C8 TxN3 D8 TxN2
A9 GND B9 GND C9 GND D9 GND
```

###### SATA 3

**Chapter 2: Mechanical Specifications**

```
Pin Definition Pin Definition
```

```
B1 GND A1 GND
```

```
B2 TxP0 A2 RxP0
```

```
B3 TxN0 A3 RxN0
B4 GND A4 GND
```

```
B5 TxP1 A5 RxP1
```

```
B6 TxN1 A6 RxN1
```

```
B7 GND A7 GND
```

```
B8 RST#1 A8 CLKP1
B9 RST#2 A9 CLKN1
```

```
B10 GND A10 GND
```

```
B11 RST#3 A11 CLKP2
```

```
B12 RST#4 A12 CLKN2
```

```
B13 GND A13 GND
```

```
B14 TxP2 A14 RxP2
B15 TxN2 A15 RxN2
```

###### SL 1 Slimline PCIe x8

```
A1
B1
```

```
A37
B37
```

**Chapter 2: Mechanical Specifications**

```
Pin Definition Pin Definition
```

```
B16 GND A16 GND
```

```
B17 TxP3 A17 RxP3
```

```
B18 TxN3 A18 RxN3
```

```
B19 GND A19 GND
```

```
B20 TxP4 A20 RxP4
```

```
B21 TxN4 A21 RxN4
```

```
B22 GND A22 GND
```

```
B23 TxP5 A23 RxP5
```

```
B24 TxN5 A24 RxN5
```

```
B25 GND A25 GND
```

```
B26 PRSNT#1 A26 CLKP3
```

```
B27 PRSNT#2 A27 CLKN3
```

```
B28 GND A28 GND
```

```
B29 RST#3 A29 CLKP4
```

```
B30 PRSNT#4 A30 CLKN4
```

```
B31 GND A31 GND
```

```
B32 TxP6 A32 RxP6
```

```
B33 TxN6 A33 RxN6
```

```
B34 GND A34 GND
```

```
B35 TxP7 A35 RxP7
```

```
B36 TxN7 A36 RxN7
```

```
B37 GND A37 GND
```

## Chapter 3 System Setup

```
To ensure safety and preventsystem damage, before disassembly, please
switch off the system and disconnect the unit from its power source.
```

###### W

###### ARNING

**Chapter 3: System Setup**

- RCO- 6000 - RPL
- RCO- 6000 - RPL-2E16-4B7M
- RCO- 6000 - RPL-2E16-2B15M
- RCO- 6000 - RPL-2E16-2N15M
- RCO- 6000 - RPL-2E16
- RCO- 6000 - RPL-2E16-2PWR
  - RCO- 6000 - RPL-4NH
  - RCO- 6000 - RPL-4NS
  - RCO- 6000 - RPL-8NS

### 3.1 Set torque force to 3.5 kgf-cm to screw or unscrew systemparts.

### 3.2 Separating the expansion module from main computer module...............

###### 1.Remove the 3 screws on the left and right side of the system as highlighted in the

###### pictures below.

```
Chapter 3: System Setup
```

###### 2.Remove 5screws located at the front and back of the system as pictured below. The

###### screw locations are highlighted in red.

###### 3.After removing all screws, the expansion module (left) can be separated from the

###### maincomputermodule (right) as pictured below.

**Chapter 3: System Setup**

### 3.3 Removing chassis top cover

###### 1.Place the system faced upside down and unscrew the four screws (M3x5L) located

###### at the red circles highlighted below.

###### 2.Hold the body of the system and remove from the external cover in an upward

###### motion away from the external cover as pictured below.

###### 3.Pictured below is the separated system body (left) andexternal cover (right).

**Chapter 3: System Setup**

### 3.4 Installing CPU

###### 1. Remove the CPU protective cover.

###### 2. Press down on the lever in order to release the socket, as shown below.

**Chapter 3: System Setup**

###### Hold the CPU by its edges, and carefullyalign the notches on the CPU with the notches

###### on the socketindicated by the red circles in the pictures below.Gently lower the CPU

###### into the socket without applying force.

###### 3.Once the CPU has been placed, press down on the lever again to secure the socket.

###### The outcome should look like the photo below.

### 3.5 Install the first DRAM and the heating block internally

###### 1. The RCO- 6000 - RPL board has one SODIMM slot on both the front and back sides.

###### The picture below shows the SODIMM slot on the back of the motherboard, and

###### you should prioritize inserting the first DRAM.

###### 2. Insert memory module at a45 degree angle.

###### 3. Push the memory module down against the board until you hear a “click”sound.

###### Makesure the memory module is secure.

###### .

**Chapter 3: System Setup**

###### 4. Paste the thermal pad on the heat block.

###### 5. Apply the heat sink with a thermal pad to the memory and secure the heat sink using

###### three screws (M3x5L). The screws can pass through the top holes and fasten onto the

###### copper pillars.

###### 6. Paste the thermal pad onto the installed DRAM heat block.

**Chapter 3: System Setup**

**Chapter 3: System Setup**

### 3.6 Install the second DRAM externally

###### 1. The picture below shows the SODIMM slot on the front of the motherboard. Insert

###### the second DRAM in order.

###### 2. Insert the memory module at a 45 - degree angle.

###### 3. Gently push the memory module down against the board until you hear a “click”

###### sound. Makesure the memory module is secured.

**Chapter 3: System Setup**

### 3.7 Installing CPU & SODIMM heat block

###### 1. Paste the thermal pad on the CPU.

###### 2. Place the designated heat block onto the CPU with thermal pad.

**Chapter 3: System Setup**

###### 3. Secure the heat block with two screws (M3x8L). The screwdriver can gothrough the

###### holes on top to fasten the screws below.

###### 4. Paste the thermal pad on the heat block.

###### 5. Place the designated heat block onto the DRAM with thermal pad.

###### 6. Securethe heat block with onescrew (M3x8L). The screwdriver can go

###### through the hole on the top to fasten the screw below.

**Chapter 3: System Setup**

###### 7. Secure the heat block with two screws (M3x5L). The screwdriver can gothrough the

###### holes on top to order to fasten the screws below.

###### 8. Paste the thermal pad onto the installed DRAM heat block.

**Chapter 3: System Setup**

**Chapter 3: System Setup**

###### 9. Paste the thermal pad onto the installed CPUheat block.

###### 10. Paste the thermal pad onto the PCH heat block.

###### 11. Paste thermal pad on the DRAM.(Picturedbelow is the SODIMM slot on the rear

###### sideof the board.)

###### 12. Lock the heat block with three screws(M3x5L). The screwdrivercango

###### through the holes on the top to fasten the screws with a copper stud.

###### 13. Paste the thermal pad onto the installed DRAM heat block.

**Chapter 3: System Setup**

```
Chapter 3: System Setup
```

```
M2_KB
```

### 3.8 Installing M.2 SSD card

###### RCO- 6000 - RPL series PCBA has an M.2 KB slot on the top, M2_B Key currently supports

###### SSD application

###### 1.Insert Mini PCIe card at a 45 degree angle.

###### 2.Gently press the Mini PCIe card down against the board and secure it with one screw

###### (Round Spacer and M3x6L).

### 3.9 Installing WiFiModule

###### RCO- 6000 - RPL series PCBA has an M.2 KE slot on the top, M2_E Key currently supports

###### WiFiapplication

###### 1.Insert M.2 E Key card at 45 degree angle.

###### 2.Press the M.2 E Key card down and secure it with one screw (M3x5L).

```
Chapter 3: System Setup
```

###### M2_KE

**Chapter 3: System Setup**

###### 3.The RCO- 6000 - RPL Series system has 5 antenna holes, 2 are located on the rear panel

###### and 3 are located on the front panel as pictured below.

###### 4.Install the SMA female jack through the antenna holes, and then fasten on the SMA

###### male plug.

###### 5.Assemble the antenna and SMA jack together, the outcome should look like the

###### picture below.

###### 6.Fix the end of the cable of the Wireless RF connector onto the communication module

###### as shown in the picture below.

**Chapter 3: System Setup**

### 3.10 Installing Mini PCIe card / 4G LTE

###### The RCO- 6000 - RPL Series PCBA has Mini PCIe slots on the top. It currently supports 4G

###### LTE applications.

###### 1.Insert Mini PCIe card at a 45 degree angle.

###### 2.Gently press the Mini PCIe card against the board and secure it with two screws

###### (M2x3.7L).

**Chapter 3: System Setup**

```
MINI-PCIE
```

### 3.11 Installing Antenna

###### 1.Remove antenna hole cover on the system panel as indicated by the red circles in the

###### photo below.

###### 2.Install the SMA female jack through the antenna holes, and then fasten on the SMA

###### male plug as shown below.

**Chapter 3: System Setup**

###### 3. Assemble the antennas and onto the SMA jack, the outcome should look like the

###### photo below.

###### 4. Fix the end of the cable of the Wireless RF connector onto the communication module

###### as shown below.

**Chapter 3: System Setup**

### 3.12 Install HDD/SSD on the internal SATA bay

###### 1.One internal SATA HDD/SSD bay is available for RCO- 6000 - RPL Series.

###### Unscrew the 4 screws (M3x5L)highlighted at the locations below in order to remove

###### the SATA HDD/SSD bay.

###### 2. Secure the 2.5” HDD with HDD/SSD bracket using four screws (M3x4L).

**Chapter 3: System Setup**

**Chapter 3: System Setup**

###### 3. Install the HDD/SSD bracket by aligning the holes with the notches on the board as

###### shown in the picture below.

###### 4. Fasten the 4 screws to secure the internal HDD/SSD bracket.

###### 4. Once the HDD/SSD card is secure, place the tray back into the bay and secure the tray

###### lock.

### 3.13 Installing HDD on removable SATA HDD/SSD bay

###### 1. To unlock the tray lock press the location highlighted at the red circle below and pull

###### the tray towards you to remove the SATA HDD/SSD bay.

**Chapter 3: System Setup**

###### 3.Secure the drive lock by pushing

###### it back down as shown below.

###### 2. Unlock the drive lock by lifting the it

###### up as shown below and insert the

###### HDD/SSD card.

**Chapter 3: System Setup**

### 3.14 Installing HDD on removable HDD bay (RCO- 6000 - RPL-2E16-4B7M)

**(for RCO- 6000 - RPL-2E16-4B7M)**

###### 1. Unscrew thetoolless screwas shown in the locations below to remove the HDD

###### bracket.

###### 2. To open the tray lock, press down onto the location at the red circle shown below and

###### remove the tray by pulling the tray out towards you.

###### 3. Unlock the drive lock (white color lever) by lifting it up as shown below and insert the

###### HDD/SSD card, then lock the drive lock by pressing it back down.

###### 4. Once the HDD/SSD card is secure, place the tray back into the bay and secure the tray

###### lock.

**Chapter 3: System Setup**

**Chapter 3: System Setup**

### 3.15 Installing HDD on removable HDD bay (RCO- 6000 - RPL-2 E16-2B15M)

### (for RCO- 6000 - RPL- 2 E16-2B15M)

###### 1.Unscrew thetoolless screwas highlighted in the two circles in the first picture below

###### to remove the HDD bracket.

###### To remove the tray, unlock the tray lock by pressing on the side of the silver tray and

###### pull the tray towards you.

###### 2. Once the tray is removed, place the HDD/SSD card (left) onto the tray (right).

###### 3. Align theHDD single side screw holes with the holes of the HDD tray as shown below.

###### 4. Gently press down on the HHD card on the other side as shown in the photo below

###### until you hear a “click” sound. Ensure the HDD is secured on the HDD tray.

```
Chapter 3: System Setup
```

###### 5. Re-insert thetray back into the system and secure the tray lock.

**Chapter 3: System Setup**

### Lock

### Unlock

### 3.16 Installing HDD on removable HDD bay (RCO- 6000 - RPL-8NS)

###### 1. Unscrew thetoolless screws at the locations circled below to remove the HDD bracket.

###### 2. Unlock the tray lock by pressing down on the right hand side of the tray indicated by

###### the red circle and remove the tray by pulling it towards you.

**Chapter 3: System Setup**

###### 3. Unlock the drive lock (white color) by pulling it in an upward direction and insert the

###### HDD/SSD. Then, push the drive lock back down until you hear a “click” sound. Ensure the

###### HDD/SSD card is secure.

###### 4.Ensure the tray is facing the right way up by aligning the tray lock with the other tray

###### locks, and slide it back inside the slot and secure the tray lock.

**Chapter 3: System Setup**

### 3.17 Installing PCIe expansion Card (for RCO- 6000 - RPL-2E16)

###### 1.First, remove the 4 screws indicated at the locations highlighted with red circles below.

**Chapter 3: System Setup**

###### 2. Remove the screws located at the highlighted red circles below.

###### 3. Install the PCIe/PCI extension card and ensure the gold finger is inserted properly.

###### Once the card is inserted, fasten the two screws.

**Chapter 3: System Setup**

### 3.18 Installing PCIe/PCI expansion Card (for RCO- 6000 - RPL-8NS)

###### 1.Remove the 5 screws located at the red circles below. Two are located outside of the

###### system, and three are located inside the system.

**Chapter 3: System Setup**

###### 2. Take out the PCIe/PCI expansion card bracket.

###### 3. Unscrewthe screw indicated at the circle below.

**Chapter 3: System Setup**

**Chapter 3: System Setup**

###### 4.Install the PCIe/PCI extension card and ensure the gold finger is inserted

###### properly.Once PCIe/PCI extension card is secured, fasten the screw.

###### 5. Re-insert the PCIe/PCI expansion card bracket back into the system.Once the PCIe and

###### PCI Expansion card bracket is secure, fasten the 5 screws.

**Chapter 3: System Setup**

### 3.19 Appendix A Optional CANBus Cable

###### 1. 1 - TCAN00001 > Dual Channel

###### 2. 1 - TCAN00002 > Single Channel

```
1
```

```
5
```

```
6
```

```
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
```

```
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

###### 3. Press the cutout indicated by the red arrow below in the top photo to create a hole.

###### The outcome should look like the bottom photo.

###### 4. Insert the CANBusconnector in the hole.

```
Chapter 3: System Setup
```

###### 5. Attach the CANBuscable end to the motherboard at the location indicated in the

###### pictures below.

**Chapter 3: System Setup**

**Chapter 3: System Setup**

### 3.20 Appendix B Fan Power Cable

###### 1. 1 - TFAN00005 > Fan Power Cable

### CONN1 CONN2

### Pin No# Color Pin No#

### 1 Black / GND 1

### 2 Red / +12V 2

### 3 Yellow / Sense 3

### 4 Brown / Control 4

###### 3. Press the cutout indicated by the red arrow below in the top photo to create a hole.

###### The outcome should look like the bottom photo.

###### 4. Insert the Fan Power connector in the hole.

```
Chapter 3: System Setup
```

**Chapter 3: System Setup**

###### 5. Attach the Fan Power cable end to the motherboard at the location indicated in the

###### pictures below.

```
Chapter 3: System Setup
```

### 3.21 Double Fan Module

###### 1. Slightly loosen the 4 screws on the Double Fan Module and install it on the RCO-

###### 6000 - RPL. Slide the upper cover from the back to the front.

###### 2. Tighten the 4 screws on the Double Fan Module and plug in the Fan Power Cable.

###### 15x26L 4x PCS

```
Chapter 3: System Setup
```

###### Double Fan Mechanical Dimensions

###### 261

###### 242

```
cable length
```

###### 250

###### 35

```
Unit: mm
```

**Chapter 3: System Setup**

### 3.22 Installing wall mount kit

###### 1. The Wall Mount Kit is provided with the RCO- 6000 - RPL as a standard package.

###### 2. The Wall Mount Kit requires 8 screws as pictured above. The 8 screws will fasten the

###### left mount piece to the right, as indicated by the picture below.

**Chapter 3: System Setup**

###### 3. If you have a 2-slot expansion module, fasten the 8 screws at the locations

###### indicated by the red circles on the left picture.

###### If you have a 3-slot expansion module, fasten the 8 screws at the locations

###### indicated by the red circles on the right picture.

**Chapter 3: System Setup**

- - - -

### 3.23 AC Adapter with 3P terminal block

###### 1. Below is a step-by-step photo sequence (from left to right) of how to wire a AC

###### Adapter (3P).

###### 2. Below is a picture of a wired DC Power Supply (3P) input.

**Chapter 3: System Setup**

- - - -

### 3.24 AC Adapter with 4P terminal block

- 12V requires 4-pin terminal block for card/storage expansion

###### 1. Below is a pictorial diagram of an AC adapter (4P).

###### 2. Below is a pictorial diagram of a DC power input (4P).

### 3.25 AC Adapter with 5P terminal block

- 12V requires 4-pin terminal block for card/storage expansion

###### 1. 5P Wiring Diagram of AC Adapter

###### 2. DC power input 5P wiring diagram

**Chapter 3: System Setup**

## Chapter 4 BIOS Setup

### 4.1 BIOS Introduction

```
The BIOS provides an interface to modify the configuration. When the battery is removed, all the
parameters will be reset.
```

```
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
```

```
General Help <F1>
The BIOS setup program provides a General Help screen. You can call up this screen from any
menu by simply pressing <F1>. The Help screen lists the appropriate keys to use and the possible
selections for the highlighted item. Press <Esc> to exit the Help screen.
```

**Chapter 4: BIOS Setup**

### Control Keys

```
<→> <←> Select Screen
```

```
<↑> <↓> Select Item
```

```
<Enter> Select
```

```
<Page Up/+> Increases the numeric value or makes changes
```

```
<Page Down/-> Decreases the numeric value or makes changes
```

```
<F1> General Help
```

```
<F2> Previous Value
```

```
<F3> Load Optimized Defaults
```

```
<F4> Save Configuration and Exit
```

```
<Tab> Select Setup Fields
```

```
<Esc> Exit BIOS Setup
```

### 4.2 Main Setup

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

### 4.3 Advanced Setup

**Chapter 4: BIOS Setup**

#### 4.3.1 Connectivity Configuration

**Chapter 4: BIOS Setup**

```
Item Options Description
CNViMode Disable Integrated,
Auto Detection [Default]
```

```
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
```

```
BT Core Enabled [Default] ,
Disabled
```

```
This is an option intended to Enable/Disable BT
Core in CNVi.
```

#### 4.3.2 CPU Configuration

**Chapter 4: BIOS Setup**

```
Item Options Description
Intel (VMX) Virtualization
Technology
```

```
Disabled,
Enabled [Default]
```

```
When enabled, a VMM can utilize the
additional hardware capabilities provided by
Virtualization Technology.
```

```
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
```

```
Hyper-Threading Disabled,
Enabled [Default]
```

```
Enabled for Windows XP and Linux (OS
optimized for Hyper-Threading Technology)
and Disabled for other OS (OS not optimized
for Hyper-Threading Technology).
```

```
Intel(R) SpeedStep(tm) Disabled,
Enabled [Default]
```

```
Allows more than two frequency ranges to be
supported.
```

```
Intel(R) Speed Shift Technology Disabled,
Enabled [Default]
```

```
Enable/Disable Intel(R) Speed Shift Technology
support. Enabling will expose the CPPC v2
interface to allow for hardware controlled P-
states.
Turbo Mode Disabled,
Enabled [Default]
```

```
Enable/Disable processor Turbo Mode.
```

```
C states Disabled,
Enabled [Default]
```

```
Enable/Disable CPU Power Management. Allows
CPU to go to C states when it's not 100% utilized.
```

###### 4.3.2.1 Efficient-core Information

###### 4.3.2.2 Performance-core Information

**Chapter 4: BIOS Setup**

#### 4.3.3 PCH-FW Configuration

**Chapter 4: BIOS Setup**

```
Item Options Description
AMT BIOS Features Disabled,
Enabled [Default]
```

```
When disabled AMT BIOS Features are no longer
supported and user is no longer able to access
MEBxSetup.
Note:Thisoption does not disable Manageability
Features in FW.
Unconfigure ME Disabled [Default] ,
Enabled
```

```
Unconfigure ME with resetting MEBxpassword
to default on next boot.
```

#### 4.3.4 SATA and RST Configuration

**Chapter 4: BIOS Setup**

```
Item Options Description
SATA Controller(s) Enabled [Default]
Disabled
```

```
Enable/Disable SATA Device.
```

```
SATA Port Disabled,
Enabled [Default]
```

```
Enable/Disable SATA Port.
```

```
Hot Plug Disabled,
Enabled [Default]
```

```
Designates this port as Hot Pluggable.
```

```
SATA Device Type Hard Disk Drive [Default] ,
Solid State Drive
```

```
Identify the SATA port is connected to Solid
State Drive or Hard Disk Drive.
```

#### 4.3.5 RST (UEFI RAID) Configuration

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

#### 4.3.6 Trusted Computing

```
Chapter 4: BIOS Setup
```

```
Item Options Description
Security Device Support Enabled,
Disabled [Default] ,
```

```
Enable/Disable BIOS support for security
device. O.S. will not show Security
Device.TCGEFI protocol and INT1A interface
will not be available.
Pending operation None [Default] ,
TPM Clear
```

```
Schedule an Operation for the Security Device.
NOTE: Your Computer will reboot during restart
in order to change State of Security Device.
```

#### 4.3.7 ACPI Settings

**Chapter 4: BIOS Setup**

```
Item Options Description
Enable Hibernation Disabled ,
Enabled [Default],
```

```
Enables or Disables System ability to
Hibernate (OS/S4 Sleep State). This option
may not be effective with some operating
systems.
```

```
ACPI Sleep State Suspend Disabled,
S3 (Suspend to RAM )[Default]
```

```
Select the highest ACPI sleep state the
system will enter when the SUSPEDN
button is pressed.
```

#### 4.3.8 Super IO Configuration

```
This setting allows you to select options for the Super IO Configuration, and change the value of
the selected option.
```

**Chapter 4: BIOS Setup**

```
Item Options Description
Watch Dog Timer Disabled [Default],
Enabled
```

```
Enabled or Disabled Watch Dog Timer
function.
Watch Dog Timer Count Mode Second Mode [Default] ,
Minute Mode
```

```
Select Second Mode or Minute Mode.
```

```
Watch Dog Timer Time out
Value
```

```
20~255(Second) [Default],
1~255(Minute)
```

```
Watch Dog Timer Time out Value.
```

```
Item Description
Serial Port 1 Configuration Set Parameters of Serial Port 1 (COMA).
Serial Port 2 Configuration Set Parameters of Serial Port 2 (COMB).
Serial Port 3 Configuration Set Parameters of Serial Port 3 (COMC).
Serial Port 4 Configuration Set Parameters of Serial Port 4 (COMD).
Serial Port 5 Configuration Set Parameters of Serial Port 5 (COME).
Serial Port 6 Configuration Set Parameters of Serial Port 6 (COMF).
```

```
■ Serial Port 1 Configuration
```

**Chapter 4: BIOS Setup**

```
Item Options Description
Serial Port Disabled,
Enabled [Default]
```

```
Enable or Disable Serial Port (COM).
```

```
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
```

```
Disabled,
Enabled [Default]
```

```
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
```

```
Enable or Disable Serial Port (COM).
```

```
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
```

```
Disabled,
Enabled [Default]
```

```
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
```

```
Enable or Disable Serial Port (COM).
```

```
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
```

```
Disabled,
Enabled [Default]
```

```
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
```

```
Enable or Disable Serial Port (COM).
```

```
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
```

```
Disabled,
Enabled [Default]
```

```
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
```

```
Enable or Disable Serial Port (COM).
```

```
Change Settings Auto [Default] ,
IO=2F0h; IRQ=7; ,
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
```

```
Disabled,
Enabled [Default]
```

```
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
```

```
Enable or Disable Serial Port (COM).
```

```
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
```

```
Disabled,
Enabled [Default]
```

```
Enabled/Disabled RS485 Autoflow Function
```

```
RS-422/RS-485 Terminal
Function
```

```
Disabled,
Enabled [Default]
```

```
RS-422/RS-485 Terminal Function
```

**Chapter 4: BIOS Setup**

#### 4.3.9 Hardware Monitor

```
These items display the current status of all monitored hardware devices/ components such as voltages
and temperatures.
```

```
Item Options Description
Smart Fan Function Disabled [Default],
Enabled
```

```
Enabled or Disable Smart Fan
```

**Chapter 4: BIOS Setup**

###### ■ Smart Fan Mode Configuration

```
Item Options Description
FanSIOSmartFan
Control
```

```
Manual Mode,
Auto Duty-Cycle Mode [Default],
```

```
Smart Fan Mode Select
```

```
Temperature 1~4 1~100 Auto fan speed control. Temperature 1- 100
```

```
Duty Cycle 1~4 20~100 Auto fan speed control. Duty 20- 100
```

**Chapter 4: BIOS Setup**

### 4.3.10. Power IGN Mode

```
Item Options Description
IGN Setting Read mode [Default]
Write IGN
```

```
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
```

```
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

#### 4.3.11 Wake system from S5

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
```

```
Wake up hour 0[Default] select 0-23 For example enter 3 for 3am and 15
for 3pm
```

```
Wake up minute 0[Default] select 0-59 for Minute
```

```
Wake up second 0[Default] select 0-59 for Second
```

```
Wake up minute
increase
```

```
0[Default] 1 - 5
```

### 4.3.12 Serial Port Console Redirection

**Chapter 4: BIOS Setup**

```
Item Options Description
Console Redirection Disabled [Default],
Enabled
```

```
These items allows you to enable or disable
COM1 console redirection
```

#### 4.3.13 USB Configuration

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
```

```
This is a workaround for OSewwithout XHCI
hand-off support. The XHCI ownership change
should be claimed by XHCI driver.
USB Mass Storage
Driver Support
```

```
Enabled [Default]
Disabled
```

```
Enable/Disable USB Mass Storage Driver
Support.
```

```
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
```

```
Maximum time the device will take before it
properly reports itself to the Host Controller.
‘Auto’ uses default value: for a Root port it is
100ms, for a Hub port the delay is taken form
Hub descriptor.
```

#### 4.3.14 Network Stack Configuration

**Chapter 4: BIOS Setup**

```
Item Options Description
Network Stack Disabled [Default] ,
Enabled
```

```
Enable/Disable UEFI Network Stack.
```

```
IPv4 PXE Support Disabled [Default] ,
Enabled
```

```
Enable/Disable IPv4 PXE boot support. If
disabled, IPv4 PXE boot support will not be
available.
IPv4 HTTP Support Disabled [Default] ,
Enabled
```

```
Enable/Disable IPv4 HTTP boot support. If
disabled, IPv4 HTTP boot support will not be
available.
IPv6 PXE Support Disabled [Default] ,
Enabled
```

```
Enable/Disable IPv4 PXE boot support. If
disabled, IPv6 PXE boot support will not be
available.
IPv6 HTTP Support Disabled [Default] ,
Enabled
```

```
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

#### 4.3.15 CSM Configuration

**Chapter 4: BIOS Setup**

```
Item Options Description
CSM Support Disabled [Default] ,
Enabled
```

```
This item allows users to enable or disable
for “CSM Support”.
```

```
GateA20 Active Upon Request [Default] ,
Always
```

```
This item allows users to set Upon
Request or Always for "GateA20 Active“.
```

```
INT19 Trap
Response
```

```
Immediate [Default] ,
Immediate
```

```
This item allows users to set the BIOS
reaction to INT19 trapping by Option
ROM: “Immediate” -execute the trap
right away;
“postponed” -execute the trap during
legacy boot.
Boot option filter UEFI and Legacy ,
Legacy only,
UEFI only [Default]
```

```
This item allows users to select which
type of operating system to boot by
option.
This item is configurable only when CSM
Support is set to Enabled.
Network PXE Do not launch [Default] ,
UEFI,
Legacy
```

```
Controls the execution of UEFI and Legacy
Video OpROM.
```

```
Storage Do not launch,
UEFI [Default] ,
Legacy
```

```
Controls the execution of UEFI and Legacy
Storage OpROM.
```

```
Other PCI devices Do not launch,
UEFI [Default] ,
Legacy
```

```
Determines OpROMexecution policy for
devices other than Network, Storage, or
Video.
```

#### 4.3.16 NVMe Configuration

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
```

```
Enabled,
Disabled [Default]
```

```
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
Item Options Description
Max TOLUD Dynamic [Default],
1GB,
1.25GB,
1.5 GB,
1.75 GB,
2 GB,
2.25 GB,
2.5 GB,
2.75 GB,
3 GB,
3.25 GB,
3.5 GB
```

```
Maximum Value of TOLUD. Dynamic
assignment would adjust TOLUD
automatically based on largest MMIO length
of installed graphic controller
```

```
■ Graphic Configuration
```

**Chapter 4: BIOS Setup**

```
Item Options Description
Primary Display Auto [Default] ,
PEG + IGFX
```

```
Select which of IGFX/PEG Graphics device
should be Primary Display.
PEG+IGFX(Multiple-Displays):
IGFX will be primary and only display under
BIOS and DOS mode.
Internal Graphics Auto [Default] ,
Disabled,
Enabled
```

```
Keep IGFX enabled based on the setup options.
```

```
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
DVMT Pre-Allocated 32M , 64M,4M,8M,
12M,16M, 20M,
24M, 28M,32M/F7,
36M, 40M,44M,
48M,52M,56M,
60M [Default]
```

```
Select DVMT 5.0 Pre-Allocated (Fixed) Graphics
Memory size used by the Internal Graphics
Device.
```

```
DVMT Total GfxMem 128M,
256M [Default] ,
MAX
```

```
Select DVMT5.0 Total Graphic Memory size
used by the Internal Graphics Device.
```

■ **VMD Configuration**

**Chapter 4: BIOS Setup**

```
Item Options Description
Enable VMD
controller
```

```
Enabled [Default] ,
Disabled
```

```
Enable/Disable to VMD controller
```

```
■ PCI Express Configuration
```

**Chapter 4: BIOS Setup**

```
■ PCI Express Configuration
```

**Chapter 4: BIOS Setup**

```
Item Options Description
PCI Express Root Port
1~3
```

```
Disabled,
Enabled [Default] ,
```

```
Control the PCI Express Root Port.
```

```
ASPM Disabled [Default] ,
L0s,
L1,
L0sL1
```

```
Set the ASPM Level.
```

```
PCIe Speed Aut0 [Default] ,
Gen1,
Gen2,
Gen3,
Gen4,
Gen5,
```

```
Configure PCIe Speed
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
```

```
M.2 B-Key Selection USB + PCIe x1 [Default],
PCIe x2
```

```
Selects M.2 B-KEyfunction: PCIe x2 or USB +
PCIe x1.
```

```
■PCI Express Configuration
```

**Chapter 4: BIOS Setup**

**Chapter 4: BIOS Setup**

```
Item Options Description
PCI Express Root Port
1 /3 /5 /6 /7 /8 /9
```

```
Disabled ,
Enabled [Default]
```

```
Control the PCI Express Root Port.
```

```
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

```
■ PCI Express Root Port 1 /3 /5 /6 /7 /8 /9
```

```
■ HD Audio Configuration
```

**Chapter 4: BIOS Setup**

```
Item Options Description
HD Audio Disabled ,
Enabled [Default]
```

```
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
```

```
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
```

```
Secure Boot feature is Active if Secure Boot is
Enabled,PlatformKey(PK) is enrolled and the
System is in User mode.
The mode change requires platform reset
Secure Boot Mode Standard,
Custom [Default]
```

```
Secure Boot mode options:Standardor Custom.
In Custom mode, Secure Boot Policy variables
can be configured by a physically present user
without full authentication
```

**Chapter 4: BIOS Setup**

```
Item Options Description
Factory Key Provision Disabled [Default] ,
Enabled
```

```
Install factory default Secure Boot keys after
the platform reset and while the System is in
Setup mode
```

```
■ Key Management
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
```

```
Select the Keyboard NumLockstate.
```

```
Quiet Boot Disabled [Default] ,
Enabled
```

```
Enables or disables Quiet Boot option.
```

```
Fast Boot Disabled [Default] ,
Enabled
```

```
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
Intel(R) ME Password MEBxLogin
```

## Appendix WDT & GPIO

This appendix provides the sample codes of WDT (Watch
Dog Timer) and GPIO (General Purpose Input/ Output).

### WDT Sample Code

WDT Setting

The WDTfunction is provided by FintekF81966 , and it can be accessed through IO Address. The
configuration on the RCO- 6000 – RPL is described as below.

PsuedoCode
// IO Address 0xA16 is time value(second)
// IO Address 0xA15 is WDT enable and configuration
Example, Set 0xA16=-0x03, 0xA15=0x31, it will reset after 3 seconds

#define TimePort 0xA16
#define TimeEnablePort0xA15

WriteByte _(_ TimePort _,0x_ 03 _)_
WriteByte _(_ TimeEnablePort _,_ 0x31 _)_

**Appendix –WDT & GPIO**

### GPIO Sample Code

GPIO Setting

The GPIO function is provided by NuvotonM058SSAN , and it can be accessed through Smbus/I2C port.
The configuration on the RCO- 6000 – RPL is described as below.

**PsuedoCode**
#define GPI_ADDR 0x02 // Define Input port Address
#define GPO_ADDR 0x01 // Define Output port Address
#define Slave_ADDR0x80 //Slave Address = 0x80( 7 - bit address)

//Set OUT1~OUT8 Value

//Set GPO to 0x55
//set IO_DO1,IO_DO3,IO_DO5,IO_DO7 to high; Set IO_DO2,IO_DO4,IO_DO6,IO_DO8 to Low
SmbusWrite (Slave_ADDR,GPO_ADDR, 0x55);

// Read In1~In8 value

Data= SmbusReads(Slave_ADDR,GPI_ADDR); //Read In1~In8 value

**Appendix –WDT & GPIO**

```
PIN# GPIO# Default Configuration
18 XCOM-
17 XCOM+
16 OUT8 DIO Output8
15 IN8 DIO Input8
14 OUT7 DIO Output7
13 IN7 DIO Input7
12 OUT6 DIO Output6
11 IN6 DIO Input6
10 OUT5 DIO Output5
9 IN5 DIO Input5
8 OUT4 DIO Output4
7 IN4 DIO Input4
6 OUT3 DIO Output3
5 IN3 DIO Input3
4 OUT2 DIO Output2
3 IN2 DIO Input2
2 OUT1 DIO Output1
1 IN1 DIO Input1
```

```
Bit 7 Bit 6 Bit 5 Bit 4 Bit 3 Bit 2 Bit 1 Bit 0
```

```
OUT8 OUT7 OUT6 OUT5 OUT4 OUT3 OUT2 OUT1
```

```
Bit 7 Bit 6 Bit 5 Bit 4 Bit 3 Bit 2 Bit 1 Bit 0
```

```
IN8 IN7 IN6 IN5 IN4 IN3 IN2 IN1
```

###### Premio Inc. All Rights Reserved

###### http://www.premioinc.com
