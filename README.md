# Boardoza TPA3111 Mono Audio Amplifier Breakout Board

The **Boardoza TPA3111 Mono Audio Amplifier Module** is a compact and efficient Class-D audio amplifier built around the **Texas Instruments TPA3111D1** chip. Designed to deliver up to **10W mono output power**, this board provides high-quality audio performance with minimal heat generation thanks to its high-efficiency architecture.

With a wide **8V to 28V DC input voltage range**, this amplifier module is compatible with a variety of power sources including DC adapters and battery systems. Screw terminal connections for power, audio input, and speaker output make installation quick and reliable. It is ideal for **DIY speaker builds, portable audio systems, embedded audio solutions, and custom sound projects** requiring compact and efficient amplification.

## [Click here to purchase!](https://www.ozdisan.com/ureticiler/boardoza)

| Front Side | Back Side |
|:---:|:---:|
| ![TPA3111 Front](./assets/TPA3111%20Front.png) | ![TPA3111 Back](./assets/TPA3111%20Back.png) |

---

## Key Features

- **High-Efficiency Class-D Amplifier:** 310 khz Switching frequency provides clear and powerful mono audio output with minimal heat generation.
- **Wide Input Voltage Range:** Operates from 8V to 28V DC, compatible with various power sources.
- **Easy Connectivity:** Screw terminals for audio input, speaker output, and power connections.
- **Clean Audio Performance:** Integrated pop and click suppression for smooth startup and shutdown.
- **Built-in Protection Features:** Includes thermal shutdown and short-circuit protection for reliable operation.

---

## Technical Specifications

**Model:** TPA3111D1  
**Manufacturer:** Boardoza   
**Manufacturer IC:** Texas Instruments   
**Input Voltage:** 8V – 28V DC  
**Functions:** Mono Audio Amplifier  
**Amplifier Type:** Class-D  
**Output Power:** Up to 10W  
**Efficiency:** Up to 90%  
**Audio Output:** Mono (H-Bridge)  
**Gain Setting:** Configurable via JP2 / JP3 (Default: 36 dB)  
**Protection Features:** Thermal protection, short-circuit protection  
**Operating Temperature:** -40 °C to +85 °C  
**Board Dimensions:** 40 mm x 40 mm  

---

## Board Pinout

### **( JP2 & JP3 ) Gain Configuration (GAIN1 / GAIN0)**

| Pin / Jumper | Pin Name | Description |
|:---:|:---:|---|
| JP2 | GAIN1 | Gain select input (logic level via jumper) |
| JP3 | GAIN0 | Gain select input (logic level via jumper) |

> Default configuration is typically **36 dB** (GAIN1=1, GAIN0=1).

#### **Gain / Input Impedance Selection Table**

| GAIN1 | GAIN0 | Amplifier Gain (dB) (Typical) | Input Impedance (kΩ) (Typical) |
|:---:|:---:|:---:|:---:|
| 0 | 0 | 20 | 60 |
| 0 | 1 | 26 | 30 |
| 1 | 0 | 32 | 15 |
| 1 | 1 | 36 | 9 |

---

### **( JP5 ) Control Pins**

| Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 1 | SD | Shutdown pin (Active Low). Connect to FAULT for auto-recovery |
| 2 | FAULT | Fault indicator pin (Active Low). Connect to SD for auto-recovery |

---

### **( J3 ) Power Connector**

| Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 1 | 8V–28V | DC Voltage Input |
| 2 | GND | Ground |

---

### **( J1 ) Audio Input**

| Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 1 | IN+ | Positive audio input |
| 2 | IN- | Negative audio input |

---

### **( J2 ) Speaker Output**

| Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 1 | OUT+ | Class-D H-Bridge positive output |
| 2 | OUT- | Class-D H-Bridge negative output |

---

## Board Dimensions

<img src="./assets/TPA3111 Dimensions.png" alt="TPA3111 Board Dimensions" width="450"/>

---

## Step Files

[Boardoza TPA3111.step](./assets/TPA3111%20Step.step)

---

## Datasheet

[TPA3111D1 Datasheet](./assets/TPA3111%20Datasheet.pdf)

---

## Version History

- **V1.0.0** – Initial Release

---

## Support

- If you have any questions or need support, please contact **support@boardoza.com**

---

## **License**
### **Hardware Design**

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

All hardware design files are licensed under [Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
