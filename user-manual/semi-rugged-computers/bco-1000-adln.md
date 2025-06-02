**USER’S **

**MANUAL**

**BCO-1000-ADLN**

**Basic Fanless Embedded Computer**

BCO-1000-ADLN l User’s Manual

**Table of Contents**

**Prefaces …………………………………………………….……………………………………………. 04**

Revision …………………………………………………………………………………………..……………….……….. 04

Disclaimer ………………………………………………………..…….…….………………………….……………….. 04

Copyright Notice …………………………………….…………………….…………………………………………… 04

Trademarks Acknowledgment …………..………………………………………………………...................04

Environmental Protection Announcement …………………………….………………….……………….. 04

Safety Precautions ………………………………………….……………………………….…………….………….. 05

Technical Support and Assistance …………………………………….…………….…………….…………….06

Conventions Used in this Manual ………………………………………………………………….….………..06

Package Contents …………………………………………………………………………………………….………… 07

Ordering Information …………………………………….……………………………………….……….………… 07

Optional Accessory …………...……………………………………..................................................... 07

**Chapter 1**

**Product Introductions ………………………………………………………..… 08**

1.1

Overview ……………………….………………………………..………….………………………….. 09

Key Feature ………….……………………………………….……….…..…………….………....... 09

1.2

Hardware Specification ….………………………….....…………….…………..………..…… 10

1.3

System I/O ……………………………..……………………..…………………………………………12

1.4

Mechanical Dimension …………………………..…………………………..………….………. 14

**Chapter 2**

**Mechanical Specifications………………………………………………….…. 15**

2.1

Switch and connector Locations ………………………………………..…….……..…….... 16

2.1.1 Top View ………………………………………………………………………..……..……… 16

2.1.2 Rear I/O Panel ………………………………………………………………………….…….. 17

2.1.3 2.5 GbE RJ-45 LAN Jack …………………………………………………………….…….. 18

2.1.4 Board Dimension ……………………………………………………………………..…….. 19

2.2

Component Contents ……………………..…………………….……….…….………............ 20

**Chapter 3**

**System Setup …………………………..…………………………………………… 36**

3.1

Set torque force to 3.5 kgf-cm to screw or unscrew system parts .……..…... 37

3.2

Before installing the system, separate the top and the bottom Covers ….... 37

3.3

Install RAM …………………….………….................................................................. 40

2

BCO-1000-ADLN l User’s Manual

3.4

Install M.2 ……………………..………………….………………………………........................ 41

3.5

Install 2.5-inch hard drive ..………………………..…….……..……………………..…….... 43

3.6

Installing wall mount kit ……………………………………………………………............... 46

3.7

Installing DIN rail holder .…..….…………………………………….............................. 48

**Chapter 4**

**BIOS Setup ……………..…………………………………………………..……… 49**

4.1

BIOS Setup .…………………………………………………………………………………..…..…... 50

4.2

The Menu Bar …………………………….……………………………………..………………...... 52

4.2.1 Menu ………………………………………………………………………..…………...……… 53

4.2.2 Advanced ………………………………………………………………………..……..……… 54

4.3

Boot …………………………….…………………………………………..………..………………...... 61

4.4

Security …………………………….…………………………………………..………..……………... 62

4.5

Chipset …………………………….…………………………………………..………..……………... 72

4.6

Power …………………………….…………………………………………..………..……………...... 73

4.7

Save & Exit …………………………….…………………………………………..………..……....... 74

**Appendix GPIO WDT BKL SMBusAccess Programming ……………….……………… 75**

GeneralPurposedIO–GPIO/DIO …….………….…….……………………..….…….…….…………... 77

WatchdogTimer–WDT ……………………………..…………………………………………………………. 78

LVDS BacklightControl –BKL ……………………..…………………………………………………………. 80

SMBusAccess …………………………………………..…………………………………………………………. 81

3

BCO-1000-ADLN l User’s Manual

**Prefaces**

**Revision**

**Revision**

**Description**

**Date**

1.0

Manual Released

2024/04/18

**Disclaimer **

All specifications and information in this User’s Manual are believed to be accurate and up to date. Premio Solution Inc. does not guarantee that the contents herein are complete, true, accurate or non-misleading.

The information in this document is subject to change without notice and does not represent a commitment on the part of Premio Inc.

Premio Inc. disclaims all warranties, express or implied, including, without limitation, those of merchantability, fitness for a particular purpose with respect to contents of this User’s Manual. Users must take full responsibility for the application of the product.

**Copyright Notice**

All rights reserved. No part of this manual may be reproduced or transmitted in any form or by any means, electronic or mechanical, including photocopying, recording, or information storage and retrieval systems, without the prior written permission of Premio Inc. Copyright © Premio Inc.

**Trademarks Acknowledgment**

Intel®, Celeron® and Pentium® are trademarks of Intel Corporation.

Windows® is registered trademark of Microsoft Corporation.

AMI is trademark of American Megatrend Inc.

IBM, XT, AT, PS/2 and Personal System/2 are trademarks of International Business Machines Corporation All other products and trademarks mentioned in this manual are trademarks of their respective owners.

**Environmental Protection Announcement**

Do not dispose this electronic device into the trash while discarding. Please recycle to minimize pollution and ensure environment protection.

4

**Preface**

BCO-1000-ADLN l User’s Manual

**Safety Precautions**

Before installing and using the equipment, please read the following precautions:

⚫ Put this equipment on a reliable surface during installation. Dropping it or letting it fall could cause damage.

⚫ The power outlet shall be installed near the equipment and shall be easily accessible.

⚫ Turn off the system power and disconnect the power cord from its source before making any installation. Be sure both the system and the external devices are turned OFF. Sudden surge

⚫ of power could ruin sensitive components. Make sure the equipment is properly grounded.

⚫ When the power is connected, never open the equipment. The equipment should be opened only by qualified service personnel.

⚫ Make sure the voltage of the power source is correct before connecting the equipment to the power outlet.

⚫ Disconnect this equipment from the power before cleaning. Use a damp cloth. Do not use liquid or spray detergents for cleaning.

⚫ Avoid the dusty, humidity and temperature extremes.

⚫ Do not place heavy objects on the equipment.

⚫ If the equipment is not used for long time, disconnect it from the power to avoid being damaged by transient over-voltage.

⚫ The storage temperature shall be above -30°C and below 85°C.

⚫ The computer is provided with a battery-powered real-time clock circuit. There is a danger of explosion if incorrectly replaced. Replace only with the same or equivalent type recommended by the manufacturer.

⚫ If one of the following situation arises, get the equipment checked be service personnel:

• The power cord or plug is damaged.

• Liquid has penetrated into the equipment.

• The equipment has been exposed to moisture.

• The equipment does not work well or it cannot work according the user’s manual.

• The equipment has been dropped and damaged.

• The equipment has obvious signs of breakage.

5

**Preface**

BCO-1000-ADLN l User’s Manual

**Technical Support and Assistance**

1. Visit the Premio Inc website at www.premioinc.com where you can find the latest information about the product.

2. Contact your distributor, our technical support team or sales representative for technical support if you need additional assistance. Please have following information ready before you call:

⚫ Model name and serial number

⚫ Description of your peripheral attachments

⚫ Description of your software \(operating system, version, application software, etc.\)

⚫ A complete description of the problem

⚫ The exact wording of any error messages

**Conventions Used in this Manual**

This indication alerts operators to an operation that, if not strictly observed, may result in severe injury.

**ARNING**W

This indication alerts operators to an operation that, if not strictly observed, **TIONU **may result in safety hazards to personnel or damage to equipment.

**CA**

**TE**

This indication provides additional information to complete a task easily.

**NO**

6

**Preface**

BCO-1000-ADLN l User’s Manual

**Package Contents**

Before installation, please ensure all the items listed in the following table are included in the package.

**Item**

**Description**

**Q’ty**

1

**BCO-1000-ADLN **Basic Fanless Embedded Computer 1

2

Wall Mount Kit

1

3

Accessory Kit

1

Adapter AC/DC 12V 5A 60W with 3pin Terminal Block Plug 5.0mm Pitch 4

1

\(1-E09A06008\)

5

Power Cord, 3-pin US Type, 180cm \(1-TPCD00005\)

1

**Ordering Information**

**Model No. **

**Product Description**

**Basic Fanless Embedded Computer with Intel 12th® CPU, 1x DP, 2x COM,** **BCO-1000-ADLN**

**2x LAN, 1x 2.5" Drive Bay**

**Optional Accessories**

**Model No. **

**Product Description**

1-TPCD00002

Power Cord, European Type, 180cm

1-TPCD00001

Power Cord, 3-pin UK Type, 180cm

3-DINR-0004

Din Rail-2 Mounting Kit

7

**Chapter 1**

**Product Introductions**

**Chapter 1: Product Introductions**

BCO-1000-ADLN l User’s Manual

**1.1 Overview**

Premio Basic Fanless Embedded Systems are designed for entry-level applications and basic needs. The BCO series can oversee connected devices and manage the collection, storage, and transmission of sensor data, and is capable of distilling unexplored value in data. It is not only robust and can withstand dust, shock, and vibration, but also can suitable for industrial automation, industrial control, kiosk & retail, and digital signage \(without high demand in graphics\).

**Model No. **

Rear Panel

Front Panel

BCO-1000-ADLN

**Key Features**

⚫ Support 12th Gen Intel® IoTG Alder Lake-N Processor N97, QC, 12W

⚫ DDR5 SODIMM. Max. up to 16GB \(Default: 8GB\)

⚫ Dual Independent Display by 1x Display Port, 1x HDMI

⚫ 2x Intel® I225-V 2.5GbE LAN

⚫ 1x 2.5” Drive Bay

⚫ 1x M.2 \(B Key, \(2242/ 2280/ 3042\) \(Default: 128GB M.2 SSD\)

⚫ 2x COM, 2x USB 3.2 Gen2, 2x USB 3.2 Gen1, 2x USB 2.0

⚫ 9 to 36VDC Wide Range Power Input Supporting AT/ATX Mode

⚫ Wide Operating Temperature 0°C to 50°C \(12W CPU\)

⚫ TPM 2.0 Supported

⚫ CE, FCC Class A

9

**Chapter 1: Product Introductions** BCO-1000-ADLN l User’s Manual

**1.2 Hardware Specification**

**System**

Processor

**Support 12th Gen Intel® IoTG Alder Lake-N Processor N97, QC, 12W**

System Chipset

SoC integrated

LAN Chipset

2x Intel® I225-V 2.5GbE LAN

Audio Codec

Realtek ALC897

System Memory

DDR5 4800MT/s SODIMM. Max. up to 16 GB \(Default: 8GB\) Graphics

Intel® UHD Graphics

BIOS

AMI UEFI BIOS

Watchdog

Software Programmable Supports 1~255 sec. System Reset TPM

TPM 2.0

**I/O**

**Storage**

Audio

Line-in/Line-out/Mic-in

1x M.2 B Key slot \(2242/2280/3042\)

COM

2x DB9

• Supports PCIe x1 signal

COM1: RS232/422/485

M.2

• Supports B\+M Key SSD

COM2: RS232

• Default: 128GB

DIO

1x 8 GPIO

LAN

2x RJ45 \(2.5GbE\)

SATA

1 x 2.5” Drive Bay \(7mm or 9mm\)

USB

2x USB 3.2 Gen2

2x USB 3.2 Gen1

**Expansion**

2x USB 2.0 Type-A

Others

2x Antenna Holes

1x M.2 E Key \(2230, PCIe x1 & USB 2.0,

1x Power button

M.2

support Wi-Fi & BT\)

1x HD LED

1x Power LED

**Display**

**Power**

1x DisplayPort 1.4a

Power Adapter

AC/DC 24V/9.2A, 60W \(Default\)

DisplayPort

Max Resolution 4096 x 2304 @60Hz

Power Mode

AT, ATX \(Default ATX\)

1x HDMI 1.4b

HDMI

Max Resolution 3840 x 2160 @30Hz

Power Supply Voltage

9~36VDC

Multiple Display

2x Independent Displays

Power Connector

3-pin Terminal Block

**Operating System**

Windows

Windows 10/11

Linux

Linux kernel

10

**Chapter 1: Product Introductions** BCO-1000-ADLN l User’s Manual

**Environment**

Operating Temp.

0°C to 50°C \(12W CPU\)

Tested according to:

IEC60068-2-1:2007 \(Cold test procedure\)

IEC60068-2-2:2007 \(Dry heat test procedure\)

IEC60068-2-3:2007 \(Damp heat, steady state, test procedure\) IEC60068-2-14:2009 \(Wide temperature range thermal shock\) Storage Temp.

-30°C to 85°C

Relative Humidity

10% to 95% \(non-condensing\)

Certification

EMC:

• CE

• FCC Class A \(47 CFR part 15.109 and part 15.107\)

• ICES-003

• UKCA

Green Product:

• RoHS 3.0 \(Directive 2015/863/EU\)

• REACH

Vibration

IEC60068-2-64:2008

With SSD: 5 Grms \(5 - 500 Hz, 0.5 hr/axis\)

Designed to comply with MIL-STD-810G Method 514.7

Procedure I

Shock

IEC60068-2-27:2008

With SSD: 50G half-sin 11ms

Designed to comply with MIL-STD-810G Method 514.7

Procedure I

Package Drop Test: ISTA 2A

**Physical**

Construction

Extruded Aluminum with Heavy Duty Metal

Dimension

192\(W\) x 140\(D\) x 68\(H\) mm

Wall Mounting

Mounting

DIN-Rail Mounting \(Optional\)

\*All specifications and photos are subject to change without notice.

11

**Chapter 1: Product Introductions**

BCO-1000-ADLN l User’s Manual

**1.3 System I/O**

**BCO-1000-ADLN**

**Front Panel**

**USB 3.2 Gen 2 port \(10 Gbps\)**

**Line-in / Line-out**

Used to connect USB 3.2 device

Used to connect a speaker

**USB 3.2 Gen 1 port \(5 Gbps\)**

**Mic-in**

Used to connect USB 3.2 device

Used to connect a microphone

**DisplayPort**

**Digital I/O **

Used to connect a DisplayPort monitor

The Digital I/O terminal block supports 8 digital input and 8 digital output

**HDMI port**

Used to connect a HDMI monitor or connect

optional split cable for dual display mode

12

**Chapter 1: Product Introductions**

BCO-1000-ADLN l User’s Manual

**BCO-1000-ADLN**

**Rear Panel**

**USB 2.0 port**

**DC IN**

Used to connect USB 2.0 device

Used to plug a DC power input with terminal

**COM port**

block

COM1 ~ COM2 support RS232/422/485 serial

**Power LED**

device

Indicates the power status of the system

**Antenna hole**

**HDD LED**

Used to connect an antenna for optional Mini-

Indicates the status of the hard drive

PCIe WiFi module

13

**Chapter 1: Product Introductions**

BCO-1000-ADLN l User’s Manual

**1.4 Mechanical Dimensions**

**BCO-1000-ADLN**

Unit: mm

14

**Chapter 2**

**Mechanical Specifications**

**Chapter 2: Mechanical Specifications**

BCO-1000-ADLN l User’s Manual

**2.1 Switch and Connector Locations**

**2.1.1 TopView**

Rear I/OPanel

SYSFAN1

JAUD1

JLVDS1

JAMP1

JRTC1

JSMB1

JCOM2

JVDD1

JINV1

JCOM1

JINVDD1

JCOMP1

JEDP_VDD1

JGPIO1

JEDP1

JPWR1

JFP1

JUSB2 JUSB1

SATA1

M2_B1

JATX1

M2_E1

DIMM1

JUSB3

JPW1

JBF1

JCMOS1

JCSE_DIS1

16

**Chapter 2: Mechanical Specifications**

BCO-1000-ADLN l User’s Manual

**2.1.2 Rear I/O Panel**

USB 3.2Gen 1Ports

2.5GbE

Line-Out

DisplayPort

RJ-45 LAN Jacks

Jack

USB 3.2Gen 2Ports

**DisplayPort**

DisplayPortisa digitaldisplay interfacestandard. Thisconnector isused toconnect a monitor withDisplayPortinputs.

**Connector**

The High-DefinitionMultimedia Interface \(HDMI \) is an al-digitalaudio/ video interface capable oftransmitting uncompressed streams. HDMI supports al TV format,including

standard,enhanced, orhigh-definitionvideo,plus multi-channel digitalaudioon a singlecable.

**USB 3.2 Gen 2 Port**

USB 3.2Gen 2,the**SuperSpeed USB 10Gbps**,delivershigh-speed datatransferfor various devices, such as storagedevices, hard drives,videocameras, etc.

**USB 3.2 Gen 1 Port**

The USB \(UniversalSerialBus\) portisforattachingUSB devices such as keyboards, mouse, or other USB-compatible devices.USB 3.2Gen 1 supports datatransferrates upto**5 Gbps**.

17

**Chapter 2: Mechanical Specifications**

BCO-1000-ADLN l User’s Manual

**2.1.3 2.5 GbE RJ-45 LAN Jack**

**2.5 GbE RJ-45 LAN Jack**

The standard singleRJ45 LAN jackisprovided forconnectiontothe LocalArea Network \(LAN\).You can connect a network cable toit.

**Link/ Activity LED**

**Speed LED**

**Status**

**Description**

**Status**

**Description**

Off

No link

Off

10/100Mbps

Yellow

Linked

Green

1000 Mbps

Blinking

Dataactivity

Orange

2.5Gbps

**Important**

High-speed devices are recommended forUSB 3.2portswhereas low-speed devices, suchasmouse orkeyboard,are suggested tobe plugged intotheUSB 2.0ports.

**Line-Out Jack**

Thisconnector isprovided forheadphones orspeakers.

18

**Chapter 2: Mechanical Specifications**

BCO-1000-ADLN l User’s Manual

**2.1.4 Board Dimension**

Unit: mm

19

**Chapter 2: Mechanical Specifications** BCO-1000-ADLN l User’s Manual

**2.2 Component Contents**

Component

Component

Memory

JLVDS1: LVDS Wafer Connector

DIMM1: DDR5 SO DIMM Slot

JINVDD1: LVDS Inverter Box Header

Storage

SATA1: SATA 3.06Gb/s Port

JEDP1: eDP Connector

M2_B1: M.2 Slot\(B Key, 2242,3042, 2280\)

Other Connectors

Expansion Slots

SYSFAN1: P W M System Fan Box Header

M2_B1: M.2 Slot\(B Key, 2242,3042, 2280\)

JFP1: FrontPanelConnector

M2_E1: M.2 Slot\(EKey, 2230\)

JCOM1, JCOM2: C O M PortBox Headers

Connectors

JGPIO1: GPIO \(DIO\) Box Header

Power Connectors

JUSB1~3: USB 2.0Box Headers

JPWR1: 4-Pin DC-In Main Power Connector

JSMB1: SMBus Box Header

JPW1: 4-Pin SATA Power Connector

JRTC1: C MO S BatteryHeader

Audio Connectors

Replacing C MO S battery

JAUD1: Front Audio Header

Jumpers

JAMP1: Audio Amplifier Header

Graphics Connectors

20

**Chapter 2: Mechanical Specifications**

BCO-1000-ADLN l User’s Manual

**Memory**

**DIMM1 : DDR5 SO DIMM Slot**

The SO-DIMM slotsisintendedformemory modules.

DIMM1

**Installing DDR5 Memory**

1.LocatetheSO-DIMM slot.AlignthenotchontheDIMM withthekey ontheslot and inserttheDIMM intotheslot.

2.Push the DIMM gentlydownwards untilthe slotleversclickand lockthe DIMM inplace.

3.Touninstal theDIMM, fliptheslotleversoutwards and theDIMM wil be released instantly.

**Important**

•

YoucanbarelyseethegoldenfingeriftheDIMM isproperlyinsertedintheDIMM slot.

•

To ensure system stabilityforDual channel mode, memory modules must be ofthe same type,number and density.

21

**Chapter 2: Mechanical Specifications**

BCO-1000-ADLN l User’s Manual

**Storage**

**SATA1 : SATA 3.0 6Gb/s Port**

This connector is SATA 6Gb/s interface port, it can connect to one SATA device.

SATA1

**Important**

•

This SATA port supports hot plug.

•

Please do not fold the SATA cable at a 90-degree angle. Data loss may result during transmission otherwise.

•

SATA cables have identical plugs on either sides of the cable. However, it is recommended that the flat connector be connected to the motherboard for space saving purposes.

22

**Chapter 2: Mechanical Specifications**

BCO-1000-ADLN l User’s Manual

**M2_B1 : M.2 Slot \(B Key, 2242, 3042, 2280\)**

Please install the solid-state drive \(SSD\) into the M.2 slot as shown below.

**Feature**

∙ SupportsSATA 3.0signal.

∙ SupportsB\+M KeySATA

3.0SSD.

**Installing M.2 SSD**

**1. **Loosen the M.2 riser

screw from the

motherboard.

**2. **Set the M.2 riser screw at the

appropriate location based on

the length of your M.2 SSD.

30°

**3. **Insert your M.2 SSD into

the M.2 slot at a 30-degree

angle.

Supplied M.2

screw

**4. **Secure the M.2 SSDin place

with the supplied

M.2 screw.

23

**Chapter 2: Mechanical Specifications**

BCO-1000-ADLN l User’s Manual

**Expansion Slots**

**Expansion Slots**

**M2_B1: M.2 Slot \(B Key, 2242, 3042, 2280\)**

Please install the module card into the M.2

slot as shown below.

M2_B1

M2_E1

**3**

**1**

**2**

**Feature**

•

SupportsPCIex1signal.

•

SupportsB\+M keyPCIex1module.

24

**Chapter 2: Mechanical Specifications**

BCO-1000-ADLN l User’s Manual

**M2_E1: M.2 Slot \(E Key, 2230\)**

Please install the Wi-Fi/ Bluetooch card into the M.2 slot as shown below.

.

**3**

**4**

**2**

**1**

**Feature**

•

Supports PCIe x1 & USB 2.0 signal.

•

Supports Intel® Wi-Fi 6E AX210 \+ BT 5.2 wireless card.

**Important**

When adding or removing expansion cards, make sure that you unplug the power supply first. Meanwhile, read the documentation for the expansion card to configure any necessary hardware or software settings for the expansion card, such as jumpers, switches or BIOS configuration.

25

**Chapter 2: Mechanical Specifications**

BCO-1000-ADLN l User’s Manual

**Connectors**

**Power Connectors**

JPWR1

JPW1

**JPWR1: 4-Pin DC-In Main Power Connector**

This connector allows you to connect an power supply.

.

1

1

DC-IN

2

DC-IN

JPWR1

3

GND

4

GND

4

**JPW1: 4-Pin SATA Power Connector**

This connector is used to provide power to SATA devices.

.

1

5V

2

GND

JPW1 4

1

3

GND

4

12V

**Important**

Make sure that all the power cables are securely connected to a proper power supply to ensure stable operation of the system.

26

**Chapter 2: Mechanical Specifications**

BCO-1000-ADLN l User’s Manual

**Audio Connectors**

JAUD1

JAMP1

**JAUD1: Front Audio Header**

This connector allows you to connect front panel audio.

1

LINE_IN_RA

2

MIC1_RA

3

LINE_IN_LA

4

MIC1_LA

12

11

5

LOUT_RA

6

MIC1_JD

JAUD1

7

LOUT_LA

8

LINE_IN_JD

2

1

9

FRONT_JD

10

GND

11

GND

12

GND

**JAMP1: Audio Amplifier Header**

The connector is used to connect audio amplifiers to enhance audio performance..

1

1

AMP_L-

2

AMP_L\+

JAMP1

3

AMP_R-

4

AMP_R\+

4

27

**Chapter 2: Mechanical Specifications**

BCO-1000-ADLN l User’s Manual

**Graphics Connectors**

**JLVDS1: LVDS Wafer **

**Connector**

JLVDS1

This connector is designed for use

with LVDS interface flat panels.

When connecting your flat panel

JINVDD1

to this connector, be sure to check

the panel datasheet to ensure that

JEDP1

you set the LVDS power select

jumper \(JVDD1\) to the appropriate

power voltage.

1

12V

2

12V

3

LCD_VDD

4

12V

5

LCD_VDD

6

LCD_VDD

7

DDC_CLK

8

DDC_DATA

9

L_BKLT_CTRL\#

10

LCDEN

JLVDS1

11

INV_ON

12 LVDS_DETECT\#\_C

13

LVDSA_DATA1

14

LVDSA_DATA0

2

1

15

LVDSA_DATA\#1

16

LVDSA_DATA\#0

17

GND

18

GND

19

LVDSA_DATA3

20

LVDSA_DATA2

21

LVDSA_DATA\#3

22

LVDSA_DATA\#2

23

GND

24

GND

25

LVDSB_DATA1

26

LVDSB_DATA0

27

LVDSB_DATA\#1

28

LVDSB_DATA\#0

29

GND

30

GND

31

LVDSB_DATA3

32

LVDSB_DATA2

33

LVDSB_DATA\#3

34

LVDSB_DATA\#2

40

39

35

GND

36

GND

37

LVDSB_CLK

38

LVDSA_CLK

39

LVDSB_CLK\#

40

LVDSA_CLK\#

**Important**

Pin 12 is a detect pin. When using a customized LVDS cable, pin 12 should be a signal ground with a low impedance. Otherwise, LVDS will not function.

28

**Chapter 2: Mechanical Specifications** BCO-1000-ADLN l User’s Manual

**JINVDD1: LVDS Inverter Box Header**

The connector is provided for LCD backlight options, be sure to check the panel datasheet to ensure that you set the LVDS Inverter Power Select Jumper \(JINV1\) to the appropriate power voltage \(5V/12V\).

1

5V/12V

2

5V/12V

1

JINVDD1

3

BKLT_EN

4

BKLT_CTRL

6

5

GND

6

GND

**JEDP1: eDP Connector**

This connector is designed for use with eDP interface flat panels. When connecting your flat panel to this connector, be sure to check the panel datasheet to ensure that you set the eDP power select jumper \(JEDP_VDD1\) to the appropriate power voltage.

1

LCD_VDD1

2

LCD_VDD1

3

LCD_VDD1

4

LCD_VDD1

5

LCD_VDD1

6

VCC3

7

SMB_CLK

8

SMB_DATA

9

GND

10

HPD

11

N/C

12

N/C

13

GND

14

DPC_LINE3_DN

15

DPC_LINE3_DP

16

GND

1

17

DPC_LINE2_DN

18

DPC_LINE2_DP

19

GND

20

DPC_LINE1_DN

21

DPC_LINE1_DP

22

GND

23

DPC_LINE0_DN

24

DPC_LINE0_DP

JEDP1

25

GND

26 DSP_DDPC_AUXP

27 DSP_DDPC_AUXN 28

GND

29

VCC3

30

GND

31

\+12V

32

GND

40

33

GND

34

VCC5

35

GND

36

BKLTCTL

37

BKLT_EN

38

\+12V

39

VCC3

40

GND

29

**Chapter 2: Mechanical Specifications**

BCO-1000-ADLN l User’s Manual

**Other Connectors**

**SYSFAN1: PWM System Fan Box Header**

The fan power connector supports system cooling fans with \+12V. When connecting the wire to the connectors, always note that the red wire is the positive and should be connected to the \+12V; the black wire is Ground and should be connected to GND.

4 1

1

GND

2

FAN POWER

SYSFAN1

3

FAN SENSE

4

FAN_PWM

**Important**

Please refer to the recommended CPU fans at processor’s official website or consult the vendors for proper CPU cooling fan.

**JFP1: Front Panel Connector**

This front-panel connector is provided for electrical connection to the front panel switches

& LEDs and is compliant with Intel Front Panel I/O Connectivity Design Guide.

1

HDD LED\+

2

POWER LED

2

3

HDD LED-

4

SUS LED

JFP1

5

GND

6

POWER SWITCH\+

1

9

7

RESET SWITCH\+

8

POWER SWITCH-

9

NC

10

No pin

SYSFAN1

JFP1

30

**Chapter 2: Mechanical Specifications**

BCO-1000-ADLN l User’s Manual

**JCOM1, JCOM2: COM Port Box Headers**

This connector is a 16550A high speed communications port that sends/ receives 16 bytes FIFOs. You can attach a serial device to it.

1

DCD\#

2

SIN

1

2

3

SOUT

4

DTR

JCOM1

5

GND

6

DSR\#

JCOM2

7

RTS

8

CTS\#

9

VCC_COM\(**JCOM1**\)

9

NC \(**JCOM2**\)

10

No pin

•

**JCOM1**

- SupportsRS-232/422/485

JCOM2

- With0V/5V/12V

JCOM1

•

**JCOM2**

**- **Supports RS-232

**RS232**

**PIN**

**SIGNAL**

**DESCRIPTION**

1

NDCD

Data CarrierDetect

2

NSIN

Signal In

3

NSOUT

Signal Out

4

NDTR

DataTerminal Ready

5

GND

Signal Ground

6

NDSR

Data Set Ready

7

NRTS

Request To Send

8

NCTS

Clear To Send

9

VCC_COM/

VCC_COM/ No

NC

Connection

10

No Pin

No Pin

**RS422**

**RS485**

**PIN SIGNAL**

**DESCRIPTION**

**PIN SIGNAL**

**DESCRIPTION**

1

422 TXD-

TransmitData, Negative

1

TXD-

TransmitData, Negative

2

422 TXD\+ Receive Data, Positive

2

TXD\+

TransmitData, Positive

3

422 RXD\+ TransmitData, Positive

3

NC

No Connection

4

422 RXD-

Receive Data, Negative

4

NC

No Connection

5

GND

Signal Ground

5

GND

Signal Ground

6

NC

No Connection

6

NC

No Connection

7

NC

No Connection

7

NC

No Connection

8

NC

No Connection

8

NC

No Connection

9

NC

No Connection

9

NC

No Connection

10

NC

No Connection

10

NC

No Connection

31

**Chapter 2: Mechanical Specifications**

BCO-1000-ADLN l User’s Manual

**JGPIO1: GPIO \(DIO\) Box Header**

This connector is provided for the General-Purpose Input/Output \(GPIO\) peripheral module.

1

GND

2

VCC5

1

2

3

GPO0

4

GPI0

JGPIO1

5

GPO1

6

GPI1

9

10

7

GPO2

8

GPI2

9

GPO3

10

GPI3

**JUSB1~3: USB 2.0 Box Headers**

These connectors are ideal for connecting USB devices such as keyboard, mouse, or other USB-compatible devices.

2

8

1

5V

2

GND

JUSB1

3

USB_0-

4

USB_1\+

JUSB2

5

USB_0\+

6

USB_1-

JUSB3

1

7

7

GND

8

5V

**JSMB1: SMBus Box Header**

This connector, known as I2C, is for users to connect System Management Bus \(SMBus\) interface.

1

5VSB

2

SMBCLK

4

JSMB1

1

3

SMBDATA

4

GND

JSMB1

JGPIO1

JUSB3

JUSB2

JUSB1

32

**Chapter 2: Mechanical Specifications**

BCO-1000-ADLN l User’s Manual

**JRTC1: CMOS Battery Header**

If the CMOS battery is out of charge, the time in the BIOS will be reset and the data of system configuration will be lost. In this case, you need to replace the CMOS battery.

JRTC1

**Replacing CMOS battery**

•

Unplug the battery wire from the

JRTC1 connector and remove the

battery.

•

Connect the new CR2032 battery with

wire to the JRTC1 connector.

**WARNING**

**KEEP OUT OF REACH OF CHILDREN**

•

Swallowingcanleadtochemicalburns, perforationofsofttissue,can death.

•

Severe burns canoccur within2 hoursofingestion.

•

Ifyouthinkbatteries might have been swallowedorplaced insideany partof the body,seek immediate medical attention.

33

**Chapter 2: Mechanical Specifications**

BCO-1000-ADLN l User’s Manual

**Jumpers**

**Important**

Avoid adjusting jumpers when the system is on; it will damage the motherboard.

JVDD1

JINV1

JEDP_VDD1

JCOMP1

JCMOS1

JCSE_DIS1

JATX1

**Jumper Name**

**Default Setting**

**Description**

**COM Power Select Jumper**

**JCOMP1**

1

1-2:5VPower \(Default\)

2-3:12V Power

**Clear CMOS Jumper**

**JCMOS1**

1-2: Normal \(Default\)

1

2-3:ClearCMOS

**CSE Jumper**

**JCSE_DIS1**

1-2: Normal \(Default\)

1

2-3:M E disable

**AT/ ATX Mode Select Jumper**

**JATX1**

1-2:ATX \(Default\)

1

2-3:AT

**LVDS Power Select Jumper**

1

**JVDD1**

1-2:3V \(Default\)

2-3:5V

34

**Chapter 2: Mechanical Specifications** BCO-1000-ADLN l User’s Manual

**Jumper Name**

**Default Setting**

**Description**

**LVDS Inverter Power Select Jumper**

**JINV1**

1

1-2: 5V \(Default\)

2-3: 12V

**eDP Power Select Jumper**

**JEDP_VDD1**

1-2: 5V

1

2-3: 3V \(Default\)

35

**Chapter 3**

**System Setup**

**Chapter 3: System Setup**

BCO-1000-ADLN l User’s Manual

**3.1 Set torque force to 3.5 kgf-cm to screw or unscrew system parts. **

**3.2 Before installing the system, separate the top and the bottom** **covers**

To ensure safety and prevent system damage, before disassembly, please switch off the system and disconnect the unit from its power source.

**ARNING**W

1. Remove the 3 screws on the front and rear side of the system as highlighted in the pictures below.

37

**Chapter 3: System Setup**

BCO-1000-ADLN l User’s Manual

2. Remove the 2 screws on the left and right side of the system as highlighted in the pictures below

38

**Chapter 3: System Setup**

BCO-1000-ADLN l User’s Manual

3. After opening the bottom cover, remove the top and bottom cable covers to facilitate the installation of hard drives and memory.

39

**Chapter 3: System Setup**

BCO-1000-ADLN l User’s Manual

**3.3 Install RAM**

1. Insert at 45 degree angle

2. Press down lightly

40

**Chapter 3: System Setup**

BCO-1000-ADLN l User’s Manual

**3.4 Install M.2**

1. Loosen the screw

2. Insert M.2 at 45 degree angle

41

**Chapter 3: System Setup**

BCO-1000-ADLN l User’s Manual

3. After pressing M.2, lock the screw

42

**Chapter 3: System Setup**

BCO-1000-ADLN l User’s Manual

**3.5 Install 2.5-inch hard drive**

1. Remove the screws

2. Open the lid

43

**Chapter 3: System Setup**

BCO-1000-ADLN l User’s Manual

3. Install the 2.5-inch hard drive

44

**Chapter 3: System Setup**

BCO-1000-ADLN l User’s Manual

4. Lock the screws

45

**Chapter 3: System Setup**

BCO-1000-ADLN l User’s Manual

**3.6 Installing wall mount kit**

1. Wall mount kit is available for BCO-1000-ADLN included in the standard package.

2. Place the system upside down so you can see the bottom cover. The highlighted screw holes below will be used.

46

**Chapter 3: System Setup**

BCO-1000-ADLN l User’s Manual

3. Lock the wall mount kit with eight screws \(M3x5L, Nylok\).

47

**Chapter 3: System Setup**

BCO-1000-ADLN l User’s Manual

**3.7 Installing DIN rail holder**

1. Din rail holder is available for BCO-1000-ADLN series as optional accessories.

2. Place the system upside down so you can see the bottom cover. The highlighted screw holes below will be used.

3. Place the din rail holder on top of the bottom cover and lock it with two screws \(M4x5L, Nylok\).

48

**Chapter 4**

**BIOS Setup**

**Chapter 4: BIOS Setup**

BCO-1000-ADLN l User’s Manual

**4.1 BIOS Setup**

Thischapter provides information on the BIOS Setup program and allows users to configurethe system foroptimal use.

**Users may need to run the Setup program when:**

•

An errormessage appears on thescreen atsystemstartupand requests users to run SETUP.

•

Users want tochange the default settings forcustomized features.

**Important**

•

Please note thatBIOS update assumes technician-level experience.

•

As the system BIOS isunder continuous update forbettersystem performance, the il ustrationsinthischapter should be heldforreferenceonly.

**Entering Setup**

Power on the computer and the system wil startPOST \(Power On SelfTest\)process. When themessage belowappears onthescreen, press <DEL> or<F2>key toenter Setup, **<F11>** key toBootMenu, **<F12> **key toPXE Boot.

**Press <DEL> or <F2> to enter SETUP**

Ifthemessage disappears beforeyourespondand youstil wishtoenter Setup, restartthe system by turningit**OFF **and **On **or pressing the **RESET **button.You may alsorestartthe system by simultaneously pressing**<Ctrl>, <Alt>, and <Delete> **keys.

**Important**

The items under each BIOS category describedinthischapter are under continuous update forbettersystemperformance.Therefore,thedescriptionmay be slightly different from the latestBIOS and should be held forreference only.

50

**Chapter 4: BIOS Setup**

BCO-1000-ADLN l User’s Manual

**BIOS Introduction**

**Control Keys**

**🡪 🡪**

SelectScreen

**↑ ↓**

SelectItem

**Enter**

Select

**\+-**

Change Value

**Esc**

Exit

**F1**

GeneralHelp

**F7**

Previous Values

**F9**

Optimized Defaults

**F10**

Save& Reset\*

**F12**

Screenshotcapture

**<K> **

Scrol helpareaupwards

**<M> **

Scrol helparea downwards

\*When you press **<F10> **,a confirmation window appears and itprovides the modificationinformation.Selectbetween **Yes **or**No **toconfirm yourchoice.

**Getting Help**

Upon enteringsetup,youwil seetheMainMenu.

**Main Menu**

The main menu liststhe setup functionsyou can make changes to.You can use the **arrow** **keys \( ↑↓ \) **toselecttheitem.Theon-linedescriptionofthehighlightedsetup functionis displayedatthebottomofthescreen.

**Sub-Menu**

Ifyoufindarightpointersymbolappears totheleftofcertainfieldsthatmeans a sub-menu can be launched from thisfield.A sub-menu containsadditionaloptions forafieldparameter. Youcanuse**arrow keys \( ↑↓ \) **tohighlightthefieldandpress

**<Enter> **tocal up thesub-menu. Then you can use the**control keys **toenter values and move from fieldtofieldwithina sub-menu. Ifyouwant toreturn tothemain menu, justpress the **<Esc>. **

**General Help <F1> **

The BIOS setup program provides a General Help screen. You can cal up thisscreen fromany menu bysimply pressing**<F1> **.The Helpscreen liststheappropriate keys to useandthe possibleselectionsforthehighlighteditem.Press**<Esc> **toexittheHelp screen.

51

**Chapter 4: BIOS Setup**

BCO-1000-ADLN l User’s Manual

**4.2 The Menu Bar**

**Main**

Use thismenu forbasicsystem configurations, such as time,date,etc.

**Advanced**

Use thismenu tosetup theitems ofspecialenhanced features.

**Boot**

Use thismenu tospecifythepriorityofbootdevices.

**Security**

Use thismenu tosetsupervisor and userpasswords.

**Chipset**

Thismenu controlstheadvanced featuresofthe on-board chipsets.

**Power**

Use thismenu tospecifyyoursettings forpower management.

**Save & Exit**

Thismenu allowsyou toloadtheBIOSdefault values orfactorydefaultsettings intothe BIOS and exittheBIOS setup utilitywithorwithout changes.

52

**Chapter 4: BIOS Setup**

BCO-1000-ADLN l User’s Manual

**4.2.1 Menu**

HDD Information

•

RAID \(VMD\) Disabled: Display HDD information as plugging in status.

•

RAID \(VMD\) Enabled: Display "Empty" only.

\*SATA_2 is for M.2 B key \(SATA signal\)

**System Date**

This setting allows you to set the system date. Use <Tab> key to switch between date elements.

Format: <Day> <Month> <Date> <Year>.

**System Time**

This setting allows you to set the system time. Use <Tab> key to switch between time elements.

Format: <Hour> <Minute> <Second>.

**SATA Mode Selection**

This setting specifies SATA controller mode.

AHCI \(Advanced Host Controller Interface\), is a technical standard for an interface that allows the

\[AHCI\]

software to communicate with Serial ATA \(SATA\) devices. It offers advanced SATA features such as Native Command Queuing \(NCQ\) and hot-plugging.

\[RAID\]

RAID \(Redundant Array of Independent Disks\) is a virtual disk storage technology that combines multiple physical disks into one unit for data redundancy, performance improvement, or both.

53

**Chapter 4: BIOS Setup**

BCO-1000-ADLN l User’s Manual

**4.2.2 Advanced**

**Full Screen Logo Display**

This BIOS feature determines if the BIOS should hide the normal POST messages with the motherboard or system manufacturer’s full-screen logo.

BIOS will display the full-screen logo during the boot-up sequence, hiding

\[Enabled\]

normal POST messages.

\[Disabled\]

BIOS will display the normal POST messages, instead of the full- screen logo.

Please note that enabling this BIOS feature often adds 2-3 seconds to the booting sequence. This delay ensures that the logo is displayed for a sufficient amount of time.

Therefore, it is recommended to disable this BIOS feature for faster boot-up.

**Bootup NumLock State**

This setting is to set the state of the Num Lock key on the keyboard when the system is powered on.

\[On\]

Turn on the Num Lock key when the system is powered on.

\[Off\]

Allow users to use the arrow keys on the numeric keypad.

54

**Chapter 4: BIOS Setup**

BCO-1000-ADLN l User’s Manual

**CPU Configuration**

**Intel Virtualization Technology**

Enables ordisablesIntelVirtualizationtechnology.

\[Enabled\]

Enables IntelVirtualizationtechnologyand allowsa platformto run multipleoperating systems inindependent partitions. The system can functionas multiplesystems virtually.

\[Disabled\]

Disables thisfunction.

**Active Efficient-cores**

Selectthenumber ofactiveEfficient-cores\(E-cores\).

**Intel\(R\) SpeedStep\(TM\)**

Enhanced IntelSpeedStep® Technology enables the OS tocontroland activate performance states\(P-States\)ofthe processor.

When enabled, IntelSpeedStep® technologyisactivated. This

\[Enabled\]

technologyallowstheprocessortomanage itspower

consumption viaperformance state \(P-State\) transitions.

\[Disabled\]

Disables thisfunction.

55

**Chapter 4: BIOS Setup**

BCO-1000-ADLN l User’s Manual

**Intel\(R\) Speed Shift Technology**

Intel® Speed ShiftTechnology isan energy-efficient method that allows frequency control by hardware ratherthan theOS.

\[Enabled\]

When enabled, Intel®Speed ShiftTechnology isactivated. The technologyenables the management ofprocessor power consumption via hardware performance state \(P-State\) transitions.

\[Disabled\]

Disable thisfunction.

**C States**

Thissetting controls the C-States\(CPU Power states\).

Detects the idlestateofsystem and reduce CPU power

\[Enabled\]

consumption accordingly.

\[Disabled\]

Disable thisfunction.

56

**Chapter 4: BIOS Setup**

BCO-1000-ADLN l User’s Manual

**Super IO Configuration**

**Serial Port 1/ 2**

Thissettingenables ordisablesthe specifiedserialport.

» **Change Settings**

This setting isused tochange the address & IRQ settings ofthe specified serial port.

» **Mode Select**

Select an operationmode forSerialPort1/2.

**FIFO Mode**

ThissettingcontrolstheFIFO\(FirstInFirstOut\)datatransfermode.

**Shared IRQ Mode**

Thissettingprovides thesystemwiththeabilitytoshare interruptsamong its serial ports.

**Watch Dog Timer**

You can enable the system watchdog timer,a hardware timer that generates a reset when the softwarethatitmonitorsdoes not respond as expected each time the watchdog pol sit.

57

**Chapter 4: BIOS Setup**

BCO-1000-ADLN l User’s Manual

**H/W Monitor \(PC Health Status\)**

These items display the current status of all monitored hardware devices/ components such as voltages, temperatures and all fans’ speeds.

**Thermal Shutdown**

Thissettingdetermines thebehavior ofthesystemwhen theCPU temperature reachesapredefined threshold.

Initiatean automatic shutdown ofthe system toprotectfrom

\[Enabled\]

potentialdamage due tooverheating.

\[Disabled\]

Disable thisfunction.

**Smart Fan Configuration**

**SYSFAN**

This setting enables or disablesthe Smart Fan function.Smart Fan isan excel entfeature which wil adjustthe system fanspeed automaticallydepending on the current system temperature, avoiding theoverheating todamage your system. The fol owingitems wil displaywhen **SYSFAN **isenabled.

» **Min. Speed \(%\)**

The beginning speed ofthe System fan.

58

**Chapter 4: BIOS Setup**

BCO-1000-ADLN l User’s Manual

**PCI/PCIE Device Configuration**

**Audio Controller**

Thissettingenables ordisablesthe detection oftheonboard audiocontrol er.

**Network Stack Configuration**

Thismenu provides NetworkStack settings forusers toenable network boot \(PXE\) from BIOS.

**Network Stack**

Thismenu provides NetworkStack settings forusers toenable network boot \(PXE\)fromBIOS.The fol owingitems wil displaywhen **Network Stak **isenabled.

» **IPV4 PXE Support**

Enables ordisables IPv4PXE bootsupport.

» **IPV4 HTTP Support**

Enables ordisables Ipv4HTTP Support.

» **IPV6 PXE Support**

Enables ordisables Ipv6PXE Support.

» **IPV6 HTTP Support**

Enables ordisables Ipv6HTTP Support.

» **PXE boot wait time**

Use thisoptiontospecifythewaittime topress theESC key toabort the PXE

boot. Press “\+”or“-”on your keyboard tochange the value. The default setting is0.

» **Media detect count**

Use thisoptiontospecify the number oftimes media wil be checked. Press “\+”

or “-”on your keyboard tochange the value. The default setting is1.

59

**Chapter 4: BIOS Setup**

BCO-1000-ADLN l User’s Manual

**GPIO Group Configuration**

**GPO0 ~ GPO3**

These settings controlthe operationmode ofthe specifiedGPIO.

**PCIE ASPM settings**

Thismenu providesettings forPCIe ASPM \(ActiveStatePower Management\) level fordifferentinstal eddevices.

**M2_B1/ M2_E1**

Sets PCI Express ASPM \(Active StatePower Management\) state forpower saving.

Initiatean automatic shutdown ofthe system toprotectfrom

\[L0s\]

potentialdamage due tooverheating.

\[L1\]

Higher latency,lower power “standby”state **\(optional\)**.

\[L0sL1\]

Activate both L0s and L1 support.

\[Disabled\]

Disable thisfunction.

60

**Chapter 4: BIOS Setup**

BCO-1000-ADLN l User’s Manual

**4.3 Boot**

**Boot Option \#1-2**

Thissettingallows users tosetthe sequence ofboot devices where BIOS

attempts toloadthediskoperating system.

61

**Chapter 4: BIOS Setup**

BCO-1000-ADLN l User’s Manual

**4.4 Security**

**Administrator Password**

Administrator Password controls access tothe BIOS Setup utility.

**User Password**

User Password controls access tothe system atboot and tothe BIOS Setup utility.

62

**Chapter 4: BIOS Setup**

BCO-1000-ADLN l User’s Manual

**PCH-FW Configuration**

Thismenu allowsyoutoconfiguresettingsrelatedtothePCH firmware.

**Firmware Information**

These settingsshow the

M E Firmware Version M E

System IntegrityValue

firmwareinformationof the

Firmware Mode M E

M E Firmware Status 1-2

IntelM E \(Management

Engine\).

Firmware SKU

**ME State**

Thismenu controlstheIntel®Management Engine State\(ME state\)parameters, which provides variousmanagement and security capabilities.The following itemswil displaywhen **ME State **isenabled.

**Comms Hub Support**

Enables or disablesthe communications hub support.

**JHI Support**

Enables ordisablesJHI Support. JHI stands forIntel®Dynamic Application Loader Host Interface Service\(Intel®DAL HIS\)and isthe engineering name for thisfeature.

Enabling JHI Support inthe BIOS settings allowsthe systemto utilizethis interfacefor communication between trusted applications and host- based applications.

**Core BIOS Done Message**

Enables or disables Core BIOS Done Message sent toME.

63

**Chapter 4: BIOS Setup**

BCO-1000-ADLN l User’s Manual

**Firmware Update Configuration**

Thismenu wil displaywhen **ME State **isenabled.

» **ME FW Image Re-Flash**

Enables or disables the M E Firmware Image Re-flashing**. **

» **Local FW Update**

Enables ordisables thecapabilitytoperforma firmwareupdate ofthe M E locally.

**PTT Configuration**

Intel®PlatformTrust Technology \(PTT\)isa platformfunctionalityforcredential storageand key management used by MicrosoftWindows. Thismenu wil display when **ME State** isenabled.

» **TPM Device Selection**

Select TPM \(Trusted PlatformModule\) devices from PTT ordTPM \(DiscreteTPM\).

\[PTT\]

EnablesPTT inSkuMgr.

\[dTPM\]

DisablesPTT inSkuMgr. **Warning\! PTT/ dTPM will be disabled and all data** **saved on it will be lost. **

**ME Debug Configuration**

Thismenu allowsyou toconfiguredebug-related optionsfortheIntel®

Management Engine \(ME\).Thismenu wil displaywhen **ME State **isenabled.

» **HECI Timeouts**

This setting enables/ disables the HECI \(Host Embedded ControllerInterface\)send/

receivetimeouts.

» **Force ME DID Init Status**

ForcestheM E Device ID\(DID\)initializationstatusvalue.

64

**Chapter 4: BIOS Setup**

BCO-1000-ADLN l User’s Manual

» **CPU Replaced Polling Disable**

Settingthisoptiondisables the CPU replacement pol ingloop.

» **HECI Message Check Disable**

This setting disables message check forBIOSbootpath when sending messages.

» **MBP HOB Skip**

Setting thisoptionwil skipME’sMemory-Based Protection \(MBP\) H0B region.

» **HECI2 Interface Communication**

This setting Adds/ Removes HECI2 device from PCI space.

» **KT Device**

Enables ordisables Key Transfer\(KT\)Device.

» **End of Post Message**

Enables or disables End ofPost Message sent toME.

» **DOI3 Setting for HECI Disable**

Settingthisoptiondisables setting DOI3 bitforal HECI devices.

» **MCTP Broadcast Cycle**

Enables ordisablesManagement Component TransportProtocol\(MCTP\) Broadcast Cycle.

**Anti-Rollback SVN Configuration**

» **Automatic HW-Enforced Anti-Rollback SVN**

Settingthisitem enables wil automatically activatethe hardware-enforced anti-rol back protection based on the Secure Version Number \(SVN\).Once enabled, the hardware wil enforcethat onlyfirmware updates withan SVN equal toorhigher than the current SVN can be installed.

» **Set HW-Enforced Anti-Rollback for Current SVN**

Enable H W ERB mechanism forcurrent ARB SVN value.F W withlowerARB-SVN

wil be blocked from execution. The value wil be restoredtodisableafterthe command issent.This itemwil displaywhen **Automatic HW-Enforced Anti-Rollback SVN **isenabled.

65

**Chapter 4: BIOS Setup**

BCO-1000-ADLN l User’s Manual

**Trusted Computing**

**Security Device Support**

Thisitem enables ordisablesBIOSsupport forsecuritydevice.When setto \[Disable\],the OS wil notshow securitydevice.

**SHA256/ SHA384 PCR Bank**

These settings enables ordisablestheSHA256 PCR Bank and SHA384 PCR Bank.

**Pending Operation**

When **Security Device Support **issetto\[Enable\], **Pending Operation **wil appear. Itis advised thatusers should routinelyback up theirTPM secured data.

\[TPM Clear\]

Clearalldatasecured by TPM.

\[None\]

Discard theselection.

**Platform Hierarchy, Storage Hierarchy, Endorsement Hierarchy** These settings enables ordisablesthe Platform Hierarchy,Storage Hierarchy and Endorsement Hierarchy.

**Physical Presence Spec Version**

Thissettings show the PhysicalPresence Spec Version.

**TPM 2.0 Interface Type**

Thissetting shows the TPM 2.0Interface Type.

**PH Randomization**

Enables ordisablesPlatformHierarchy\(PH\)Randomization.

**Device Select**

SelectyourTPM devicethroughthissetting.

66

**Chapter 4: BIOS Setup**

BCO-1000-ADLN l User’s Manual

**Serial Port Console Redirection**

**Console Redirection**

Console Redirectionoperates inhostsystems thatdo not have a monitor and keyboard attached. Thissettingenables ordisablesthe operationofconsole redirection.When setto\[Enabled\],BIOS redirectsand sends al contents that should be displayedonthescreen tothe serialCO M portfordisplay onthe terminal screen.

Besides, al datareceivedfromthe serialportisinterpretedas keystrokes from a local keyboard.

67

**Chapter 4: BIOS Setup**

BCO-1000-ADLN l User’s Manual

**Console Redirection Settings \(COM1\)**

» **Terminal Type**

To operate the system’sconsole redirection,you need a terminal supporting ANSI terminal protocoland a RS-232 nul modem cable connected between the host system and terminal\(s\).You can selectemulation forthe terminal from thissetting.

\[ANSI\]

Extended ASCIIcharacter set.

\[VT100\]

ASCIIcharacter set.

\[VT100Plus\]

Extends VT100 tosupport color,functionkeys,etc.

\[VT-UTF8\]

Uses UTF8 encoding tomap Unicode characters onto one or more bytes.

» **Bits per second, Data Bits, Parity, Stop Bits** These setting specifiesthe transferrate\(bitsper second, data bits,parity,stopbits\) of Console Redirection.

» **Flow Control**

Flow controlisthe process ofmanaging the rateofdata transmissionbetween two nodes. It’sthe process ofadjusting the flowofdata from one device toanother toensure thatthe receivingdevice can handle al ofthe incoming data.This is particularlyimportant where the sending device iscapable ofsending data much fasterthan the receiving device can receiveit.

» **VT-UTF8 Combo Key Support**

This setting enables ordisables the VT-UTF8 combination key support forANSI/ VT100

terminals.

» **Recorder Mode, Resolution 100x31**

These settings enables ordisables the recorder mode and the resolution 100x31.

» **Putty KeyPad**

PuTTY isa terminal emulator forWindows. This setting controlsthe numeric keypad foruse inPuTTY.

68

**Chapter 4: BIOS Setup**

BCO-1000-ADLN l User’s Manual

**Secure Boot**

**Secure Boot**

Secure Bootfunctioncan be enabled onlywhen the **Platform Key \(PK\) **isenrolled and running accordingly.

**Secure Boot Mode**

Selectsthe secure bootmode. Thisitem appears when **Secure Boot **isenabled.

\[Standard\]

The system wil automaticallyload the secure keys from BIOS.

Allowsuser toconfigurethesecure bootsettings and manually

\[Custom\]

loadthesecurekeys.

**Restore Factory Keys**

Allowsyou torestoreal factorydefault keys.The settings wil be appliedafter rebootor atthenext reboot.Thisitemappears when **"Secure Boot Mode" **setsto **\[Custom\]**.

**Reset to setup Mode**

Allowsyou todeleteal the Secure Boot keys \(PK,KEK,db,dbt,dbx\). The settings wil be appliedafterrebootoratthenext reboot.Thisitemappears when “**Secure Boot** **Mode” **setsto**\[Custom\]**.

69

**Chapter 4: BIOS Setup**

BCO-1000-ADLN l User’s Manual

**Key Management**

Press **Enter **key toenter thesub-menu. Manage the secure bootkeys.Thisitem appears when **“Secure Boot Mode” **setsto**\[Custom\]**.

» **Platform Key \(PK\):**

The Platform Key \(PK\) can protect the firmware from any un-authenticated changes.

The system wil verifythe PK beforeyour system enters the OS. Platform Key \(PK\)isused forupdating KEK.

» **Set New Key**

Setsa new PK toyoursystem.

» **Delete Key**

Deletesthe PK fromyour system.

» **Key Exchange Keys \(KEK\):**

Key Exchange Key \(KEK\) isused forupdating DB or DBX.

» **Set New Key**

Setsa new KEK toyoursystem.

» **Append Key**

Loads an additional KEK from storagedevices toyour system.

» **Delete Key**

Deletesthe KEK fromyour system.

» **Authorized Signatures \(db\) :**

AuthorizedSignatures\(db\)liststhe signatures thatcan be loaded.

» **Set New Key**

Sets a new db toyoursystem.

70

**Chapter 4: BIOS Setup**

BCO-1000-ADLN l User’s Manual

» **Append Key**

Loads an additional db from storagedevices toyour system.

» **Delete Key**

Deletes the db from your system.

» **Forbidden Signatures \(dbx\):**

Forbidden Signatures\(dbx\)liststhe forbidden signatures thatare nottrustedand cannot be loaded.

» **Set New Key**

Setsa new dbx toyoursystem.

» **Append Key**

Loads an additional dbx from storagedevices toyour system.

» **Delete Key**

Deletes the dbx fromyour system.

» **Authorized TimeStamps \(dbt\):**

Authorized TimeStamps \(dbt\)lists the authentication signatures with authorization time stamps.

» **Set New Key**

Setsa new DBT toyoursystem.

» **Append Key**

Loads an additional DBT from storage devices toyour system.

» **OsRecovery Singnatures \(dbr\):**

Liststhe available signatures forOS recovery.

71

**Chapter 4: BIOS Setup**

BCO-1000-ADLN l User’s Manual

**4.5 Chipset**

**DVMT Total Gfx Mem**

Thissettingspecifiesthe totalgraphics memory sizeforDynamic Video Memory Technology\(DVMT\).

**LVDS Panel Type**

ThissettingspecifiestheLVDS Panel’sresolutionand distributionformats.

**Backlight Control**

ThissettingcontrolstheintensityoftheLED’sbacklightoutput.When lighting conditionsare brighter,setithigh fora clearerimage and lowwhen itisdarker.

**LED’s backlight output**

\[Level1\]

20%

\[Level2\]

40%

\[Level3\]

60%

\[Level4\]

80%

\[Level5\]

100%

72

**Chapter 4: BIOS Setup**

BCO-1000-ADLN l User’s Manual

**4.6 Power**

**Restore AC Power Loss**

Thissettingspecifieswhether your system wil reboot aftera power failureor interrupt occurs.Availablesettings are:

\[Power Off\]

Leaves the computer inthe power offstate. Leaves the

\[Power On\]

computer inthe power on state.

\[LastState\]

Restores the system tothe previous status before power failureor interruptoccurred.

**Deep Sleep Mode**

The setting enables or disablesthe Deep S5 power saving mode. S5 isalmost thesame asG3 Mechanical Off,exceptthatthePSU stil suppliespower,ata minimum, tothe powerbutton toallowreturn toS0.A ful rebootisrequired. No previous content is retained. Other components may remain powered so thecomputercan“wake”oninput fromthekeyboard,clock,modem, LAN,orUSB device.

**OnChip USB**

The item allowsthe activityoftheOnChip USB device towake up thesystem from S4/S5

sleep state.

**LAN/ PCIE PME**

Enables or disables the system tobe awakened from the power saving modes when activityorinputsignalofIntelLAN deviceand onboardPCIE PM E is detected.

**RTC**

When \[Enabled\],yourcan setthedateand time atwhich theRTC \(real-time clock\) alarm awakens the system from suspend mode.

73

**Chapter 4: BIOS Setup**

BCO-1000-ADLN l User’s Manual

**4.7 Save & Exit**

**Save Changes and Reset**

Save changes toCMOS and resetthe system.

**Discard Changes and Exit**

Abandon al changes and exit the Setup Utility.

**Discard Changes**

Abandon al changes.

**Load Optimized Defaults**

Use thismenu toload thedefaultvalues setby themotherboard manufacturer specifical yfor optimal performance ofthe motherboard.

**Save as User Defaults**

Save changes as the user’sdefault profile.

**Restore User Defaults**

Restore theuser’sdefaultprofile.

**Launch EFI Shell from filesystem device**

Thissettinghelps tolaunch theEFIShellapplication fromone ofthe availablefile system devices.

74

**Appendix**

**GPIO WDT BKL SMBus Access Programming**

**Appendix – WDT & GPIO**

BCO-1000-ADLN l User’s Manual

**GPIO WDT BKL SMBus Access Programming**

Thischapter provides GPIO \(General Purpose Input/Output\), W D T \(Watch Dog Timer\), LVDS Backlight and SMBus Access programming guide.

**Abstract**

In this section,code examples based on C programming language provided for customer interest. **Inportb, Outportb, Inportl **and **Outportl **are basicfunctions used foraccess IO

portsand definedas following.

**Inportb: **Read a single8-bitI/Oport. **Outportb: **Writeasinglebyte toan8-bitport. **Inportl: **Reads a single32-bitI/Oport.

**Outportl: **Writea singlelongtoa 32-bitport.
