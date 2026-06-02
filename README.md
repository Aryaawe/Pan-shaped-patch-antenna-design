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

---

# 📐 Antenna Geometry

## Top View

<p align="center">
  <img src="Images/Top_view.png" width="450">
</p>

### Key Features

- Inset-fed microstrip patch
- Circular slot loading
- Modified pan-shaped contour
- Ground plane backed substrate

The circular slot increases the effective current path length while providing additional reactive loading, enabling resonance tuning and improved impedance matching.

---

# 📊 Simulation Results

## Return Loss (S11)

The antenna resonates at approximately **2.424 GHz** with a return loss of **-24.03 dB**.

<p align="center">
  <img src="Images/S11.png" width="700">
</p>

| Parameter | Value |
|------------|------------|
| Resonant Frequency | 2.424 GHz |
| S11 | -24.03 dB |

---

## VSWR

The antenna achieves a minimum VSWR of approximately **1.21**, indicating efficient power transfer.

<p align="center">
  <img src="Images/VSWR.png" width="700">
</p>

| Parameter | Value |
|------------|------------|
| Minimum VSWR | 1.21 |

---

## Gain vs Frequency

The antenna exhibits a maximum gain of approximately **3.12 dBi** around the operating frequency.

<p align="center">
  <img src="Images/gain_vs_frequency.png" width="700">
</p>

| Parameter | Value |
|------------|------------|
| Maximum Gain | 3.12 dBi |

---

## 3D Radiation Pattern

The antenna radiates primarily in the broadside direction.

<p align="center">
  <img src="Images/3D_Gain.png" width="550">
</p>

### Characteristics

- Broadside radiation
- Stable radiation pattern
- Low back radiation
- Suitable for wireless communication systems

---

## Polar Radiation Pattern

<p align="center">
  <img src="Images/Radiation_Pattern.png" width="550">
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

---

# 🔬 Future Improvements

Potential enhancements include:

- Bandwidth improvement
- Defected Ground Structures (DGS)
- Metamaterial loading
- Circular polarization
- MIMO implementation
- Gain enhancement techniques

---

# 📁 Repository Structure

```text
Pan-Shaped-Patch-Antenna/
│
├── HFSS_Project/
│   └── PanPatch.aedt
│
├── Images/
│   ├── Top_view.png
│   ├── Pan_Patch_isometric_view.png
│   ├── S11.png
│   ├── VSWR.png
│   ├── gain_vs_frequency.png
│   ├── 3D_Gain.png
│   └── Radiation_Pattern.png
│
├── Results/
│   └── Simulation_Data
│
└── README.md
```

# 👨‍💻 Author

**Arya**

Electronics and Communication Engineering Student

### Interests

- Antenna Design
- RF Engineering
- Electromagnetics
- HFSS Simulation
- Wireless Communication

---

# 📜 License

This project is released for academic and research purposes.

---

## ⭐ If you found this project useful, consider giving it a star.
