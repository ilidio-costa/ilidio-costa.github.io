---
layout: default
title: NiTi L-PBF Optimization
---

[← Back to Portfolio](./)

# Parameter Optimization of Laser Powder Bed Fusion of NiTi
**Role:** Master Researcher | **Timeline:** Feb 2025 - Oct 2025 | **Location:** FEUP & CATEC

## 1. The Engineering Challenge
Nitinol (NiTi) is a Shape Memory Alloy (SMA) highly valued in aerospace and biomedical fields for its superelasticity. However, processing it via Laser Powder Bed Fusion (L-PBF) is difficult due to:
* **Sensitivity to Thermal History:** Improper cooling rates destroy the shape memory effect.
* **Chemical Evaporation:** Nickel evaporation during melting can shift the transformation temperature.

**Objective:** Develop a robust L-PBF parameter set (Laser Power, Speed, Hatching) to minimize porosity and ensure correct phase formation.

## 2. Methodology: Design of Experiments (DoE)
To avoid efficient trial-and-error, I implemented a statistical approach:
* **Taguchi Method & Response Surface:** Designed a matrix to isolate the impact of energy density on part quality.
* **Feedstock Analysis:** Characterized powder morphology and particle size distribution (PSD) using **Python** and **ImageJ** to ensure consistent flowability during recoating.

## 3. Characterization & "The Process"
The core of this project was validating the internal structure of the printed parts.

### Microstructural Analysis
I utilized **Scanning Electron Microscopy (SEM)** with **EBSD** (Electron Backscatter Diffraction) to map grain orientation.
* *Observation:* Identified statistically significant variations in chemical composition across different thickness sections using XRF.
* *Action:* Adjusted scan strategies to homogenize heat input.

### Defect Reduction
Initial prints showed gas entrapment porosity.
* **Validation:** Used the Archimedes method and optical micrograph thresholding.
* **Result:** Tuned parameters reduced internal porosity to **< 0.07%**.

## 4. Outcome
The study successfully defined a processing window for NiTi on the Prima Sharp 150 system. This work allows for the direct manufacturing of complex functional actuators without post-assembly.

* **Key Achievement:** Minimized porosity to <0.07% while indicating future processing parameters.

---
[← Back to Portfolio](./)