# 📘 Photonic Crystal-Based Binary-to-Gray Code Converter

## 👩‍🔬 Authors

- **Mohammad Reza Eslami**, Clemson University  
- **Mir Hamid Rezaei**, Shiraz University  
- **Abdolah Amirany**, The George Washington University  
- **Yaser M. Banad**, University of Oklahoma  
- **Sarah S. Sharif**, University of Oklahoma *(Corresponding Author: s.sh@ou.edu)*

## 🧠 Abstract

This repository contains the simulation files, configurations, and instructions for implementing an ultra-compact two-bit binary-to-Gray code converter based on two-dimensional photonic crystal (PhC) waveguides. Designed for high-performance optical logic systems, this device achieves a compact 100 µm² footprint, high extinction ratios (up to 10.11 dB), and low power operation. The converter supports reversible computing (Feynman gate behavior) and is optimized for integration into photonic neural networks. Simulations are conducted using **Lumerical FDTD Solutions (2020 R2.4)** in both frequency and time domains.

## 🔬 Simulation Instructions

### Frequency Domain
1. For Two Bit-B2G-Frequency Domain, Lunch B1B0_01.fsp
2. Use monitors `G0` and `G1` to plot the transmission spectrum.
3. Use the `monitor` object to visualize electric, magnetic, or power fields at 1.55 µm.

### Time Domain
1. For Two Bit-B2G-Time Domain, Launch Time.fsp
2. For 3Bits B2G_1, lunch B2B1B0_001.fsp
3. Use time-domain monitors (`B0`, `B1`, `G0`, and `G1`) to analyze the temporal behavior of electric and magnetic fields.

### Band Structure
1- For Band Structure, see the folder Band Structure-Rsoft 

## 📜 License

This project is licensed under the **MIT License**. See the [LICENSE](./LICENSE) file for details.

## 🧩 Applications

- Optical Feynman gate for reversible logic
- Binary neural network accelerators
- Photonic integrated circuits
- Low-power, high-speed optical computing
