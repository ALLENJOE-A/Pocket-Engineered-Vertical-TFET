<div align="center">

# Double Gate Source-Pocket Engineered Heterogeneous Gate Dielectric Vertical TFET
### *Optimized for Ultra-Low Power VLSI Applications*

![Research](https://img.shields.io/badge/Research-Semiconductor-blue)
![Technology](https://img.shields.io/badge/Technology-Synopsys%20Sentaurus%20TCAD-green)
![Device](https://img.shields.io/badge/Device-DG--TFET-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

**Electronics & VLSI Engineering**  
**VIT Chennai**

</div>

---

#  Project Overview

As CMOS technology approaches its physical scaling limits, **Tunnel Field-Effect Transistors (TFETs)** have emerged as one of the most promising candidates for next-generation ultra-low-power electronics.

This project presents the design and simulation of a **Double Gate Source-Pocket Engineered Heterogeneous Gate Dielectric Vertical TFET (DG-TFET)** using **Synopsys Sentaurus TCAD**. The proposed device integrates:

- Vertical Double-Gate Architecture
- Source-Pocket Engineering
- GaSb/GaAsSb/GaAs Heterojunction
- HfO₂ High-k Gate Dielectric

to improve electrostatic control, enhance Band-to-Band Tunneling (BTBT), and significantly increase ON-state current while maintaining extremely low leakage current.


#  Objectives

- Design a Vertical Double-Gate TFET architecture.
- Improve ON-current through Source-Pocket Engineering.
- Reduce OFF-state leakage.
- Optimize threshold voltage.
- Study the impact of heterogeneous materials.
- Analyze electrical characteristics using TCAD simulations.


#  Device Architecture

| Region | Material |
|----------|-----------|
| Source | GaSb (P⁺) |
| Pocket | GaAs₀.₅Sb₀.₅ (N⁺) |
| Channel | GaAs |
| Drain | GaAs (N⁺) |
| Gate Dielectric | HfO₂ + SiO₂ |
| Gate Structure | Double Gate |


#  Software & Tools

- Synopsys Sentaurus TCAD
- Sentaurus Structure Editor (SDE)
- Sentaurus Device (SDevice)
- Sentaurus Visual


#  Physics Models

The following physical models were implemented during simulation:

- Non-Local Hurkx Band-to-Band Tunneling
- Shockley-Read-Hall Recombination
- Auger Recombination
- Bandgap Narrowing
- High Field Saturation
- Fermi Statistics
- Extended Precision Solver


#  Performance Summary

| Parameter | Value |
|-----------|-------|
| ON Current (ION) | **7.4 × 10⁻⁷ A** |
| Threshold Voltage | **0.527 V** |
| Ion/Ioff Ratio | **>10⁸** |
| OFF Current | **Sub-femtoampere** |


#  Simulation Results

The project includes analysis of:

- Transfer Characteristics (ID–VG)
- Output Characteristics (ID–VD)
- Electric Field Distribution
- Energy Band Diagram
- Electrostatic Potential
- Bandgap Narrowing
- Carrier Concentration


#  Repository Structure

```text
DG-Source-Pocket-Engineered-Vertical-TFET
│
├── README.md
├── images/
├── results/
├── docs/
└── references/
```


#  Applications

- Ultra-Low Power VLSI
- IoT Devices
- Edge Computing
- Biomedical Electronics
- Wearable Systems
- Beyond CMOS Technology


#  Future Improvements

- Gate-All-Around (GAA) TFET
- Multi-Gate Architectures
- Strain Engineering
- Trap-Assisted Tunneling Analysis
- Process Variation Analysis
- Technology Scaling below 10 nm


#  Authors

**Allen Joe A**  
B.Tech Electronics & VLSI Engineering  
VIT Chennai



#  Acknowledgement

This project was carried out as part of the **Semiconductor Device Modelling** course under the guidance of the faculty of the **School of Electronics Engineering (SENSE), VIT Chennai**.


# 📜 License

This repository is intended solely for **academic, educational, and research purposes**.
