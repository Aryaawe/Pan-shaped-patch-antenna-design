# Pan-shaped-patch-antenna-design
Design and simulation of a microstrip inset-fed pan-shaped patch antenna using HFSS

# 🛰️ Pan-Shaped Inset-Fed Microstrip Patch Antenna for 2.4 GHz ISM Band Applications

<p align="center">
  <img src="Images/Pan_Patch_isometric_view.png" width="600">
</p>

## 📖 Overview

This project presents a **Pan-Shaped Inset-Fed Microstrip Patch Antenna** designed and simulated using **Ansys HFSS 2025 R2** for operation in the **2.4 GHz ISM band**.

Unlike a conventional rectangular microstrip patch antenna, the proposed design incorporates:

- A circular slot near the feed region
- Modified shoulder geometry
- Inset-feed excitation

These modifications alter the current distribution on the patch, resulting in excellent impedance matching and stable radiation performance around 2.4 GHz.

---

## 🎯 Design Objectives

- Operate in the 2.4 GHz ISM Band
- Achieve low return loss
- Obtain low VSWR
- Maintain broadside radiation
- Investigate the effect of shape modification on antenna performance

---

## 🛠 Software Used

- Ansys HFSS 2025 R2 Student Version
  
# 📊 Simulation Results

## Return Loss (S11)

The antenna resonates at approximately **2.424 GHz** with a return loss of **-24.03 dB**.

<p align="center">
  <img src="Pan_Patch Antenna/S11.png" width="700">
</p>

| Parameter | Value |
|------------|------------|
| Resonant Frequency | 2.424 GHz |
| S11 | -24.03 dB |

---

## VSWR

The antenna achieves a minimum VSWR of approximately **1.21**, indicating efficient power transfer.

<p align="center">
  <img src="Pan_Patch Antenna/VSWR.png" width="700">
</p>

| Parameter | Value |
|------------|------------|
| Minimum VSWR | 1.21 |

---

## 3D Radiation Pattern

The antenna radiates primarily in the broadside direction.

<p align="center">
  <img src="Pan_Patch Antenna/3D_Gain.png" width="550">
</p>

### Characteristics

- Broadside radiation
- Stable radiation pattern
- Low back radiation
- Suitable for wireless communication systems

---

## Polar Radiation Pattern

<p align="center">
  <img src="Pan_Patch Antenna/Radiation Pattern.png" width="550">
</p>

The E-plane and H-plane patterns show good directional behavior with a dominant main lobe.

---

# 📈 Performance Summary

| Parameter | Result |
|------------|------------|
| Operating Frequency | 2.424 GHz |
| Return Loss (S11) | -24.03 dB |
| VSWR | 1.21 |
| Maximum Gain | 3.12 dBi |
| Radiation Type | Broadside |
| Feed Type | Inset Feed |
| Antenna Category | Microstrip Patch |

---

# ✨ Novel Features

## Circular Slot Loading

The circular slot modifies the current path and introduces additional capacitive loading, helping improve impedance matching.

## Shape-Engineered Patch

The pan-shaped contour alters surface current distribution compared to conventional rectangular patches, providing opportunities for:

- Compact antenna design
- Better impedance matching
- Geometry-based optimization

## Inset Feed Matching

The inset feed allows direct tuning of the input impedance without external matching circuits.

---

# 🚀 Applications

This antenna is suitable for:

- Wi-Fi (IEEE 802.11 b/g/n)
- Bluetooth Devices
- ZigBee Networks
- IoT Systems
- Wireless Sensor Networks
- Embedded Communication Devices
- Academic Antenna Research



# 👨‍💻 Author

**Arya**


