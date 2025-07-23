## Product Introduction

### Overview

In today's connected world, maintaining seamless operations at the edge is more critical than ever. Out-of-Band (OOB) Remote Management technology ensures continuous monitoring and management of your systems, even during unforeseen disruptions. Whether it's for edge AI, IoT applications, or industrial automation, our solutions provide the reliability and control you need to prevent costly downtimes in 24/7 mission critical computing.

### Specification

| Specification              | Description                                                                                            |
| :------------------------- | :----------------------------------------------------------------------------------------------------- |
| MCU                        | Nuvoton NUC980DR63YC                                                                                   |
| SDRAM                      | Built-in 64MB DDR2 SDRAM Memory (16KB data cache)                                                      |
| **I/O**                    |                                                                                                        |
| LAN                        | 1x RJ45 (10/100 Mbps)                                                                                  |
| **Others**                 |                                                                                                        |
| On-board LED               | LED Indicator Light<br/>• Power LED (Color: Blue)<br/>• MCU Activated LED (Color: Green)               |
| DIP Switch                 | 4x2 DIP Switch for General Setting <br/> • USB or SPI Flash Switching <br/> • Wi-Fi or Debug Switching |
| **Environments**           |                                                                                                        |
| Operating Temp.            | -40°C to 85°C                                                                                          |
| Storage Temp.              | -40°C to 85°C                                                                                          |
| Relative Humidity          | 10% to 95% (non-condensing)                                                                            |
| Protection                 | 1.5KV                                                                                                  |
| Standards & Certifications | UL, CE, FCC                                                                                            |

## Mechanical Dimension

### EBIO-OOB

![EBIO-OOB Dimension](https://premio.blob.core.windows.net/premio-shared/datasheet-generator/RCO-3000-RPL/OOB_D.png)

### EBIO-OOB-J (JCO Series)

![EBIO-OOB-J dimension](https://premio.blob.core.windows.net/premio-shared/datasheet-generator/JCO-EDGEBoost-IO-Series/DTB-OOB_D.png)

## Mechanical Layout

### Top Side

![EBIO-OOB Top Side](https://premio.blob.core.windows.net/premio-shared/datasheet-generator/Modules/EBIO/EBIO-OOB/ebio-oob-top-side.png)

### Bottom Side

![EBIO-OOB Bottom Side](https://premio.blob.core.windows.net/premio-shared/datasheet-generator/Modules/EBIO/EBIO-OOB/ebio-oob-bottom-side.png)

## OOB Management Services Setup

### Overview

This section provides a complete guide for activating and configuring the Out-of-Band (OOB) management services on your device. Both In-Band and Out-of-Band (OOB) functions can be used together to achieve full remote access and control.

### Setup

#### Install the Allxon Agent

Begin by installing the Allxon Agent, which establishes secure communication between your device and the Allxon Portal.

- Access the device desktop.
- Launch the installation process using the supported method for your hardware model.
- For command-line installation, refer to: [Install Allxon Agent via Command Prompt](https://www.allxon.com/knowledge/install-allxon-agent-via-command-prompt)

#### Register Device to Allxon Portal

Once the Agent is installed, proceed to register your device.

- Retrieve Device Pairing Code:
  Instructions:
  [Get Device Pairing Code](https://www.allxon.com/knowledge/get-pairing-code)

- Add Device to Portal:
  After obtaining the pairing code, log in to the Allxon Portal and register your device following: [Add Your Device on Allxon Portal](https://www.allxon.com/knowledge/enable-out-of-band-control-on-device)

#### Activate Out-of-Band Features

After successful registration, enable the OOB Enabler to activate out-of-band management capabilities.

- Follow the activation guide here:
  [Enable Out-of-Band Management on Device](https://www.allxon.com/knowledge/enable-out-of-band-control-on-device)

### Configure Allxon swiftDR Power Management

The Allxon swiftDR suite offers advanced OOB power management for disaster recovery scenarios. After enabling OOB services, you can configure power cycling and recovery controls via the Allxon Portal.

- Full configuration steps available here:
  [Allxon swiftDR for Power Cycling](https://www.allxon.com/knowledge/allxon-swiftdr-for-power-cycling)

### OOB Enabler Troubleshooting

#### Network Connectivity Requirements

To ensure proper operation of Allxon services, a stable and reliable internet connection is required.

In environments with restricted network policies or firewall settings:

- Verify that all required network ports and protocols are accessible.
- For full network configuration details, refer to:
  [Allxon Service Port/Protocol and Whitelist Requirements](https://www.allxon.com/knowledge/internet-access-requirement-for-allxon-agent)
