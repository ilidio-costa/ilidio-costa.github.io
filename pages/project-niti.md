---
layout: single
title: "NiTi L-PBF Parameter Optimization"
permalink: /pages/project-niti/
sidebar:
  nav: "docs"
toc: true
mathjax: true
---

**Project:** Master's Dissertation | **Tools:** Python, ImageJ, SEM, EBSD | **Material:** Nitinol (NiTi)

## 1. The Engineering Challenge
Processing Nitinol (NiTi) via Laser Powder Bed Fusion (L-PBF) is challenging due to its sensitivity to thermal history. The goal was to minimize porosity while preserving the shape memory effect.

## 2. Methodology: Taguchi DoE
[cite_start]I utilized a **Taguchi Design of Experiments** to minimize the number of print jobs required to find the optimal window[cite: 8].

$$E = \frac{P}{v \cdot h \cdot t}$$

* **Variable 1:** Laser Power (W)
* **Variable 2:** Scanning Speed (mm/s)
* **Variable 3:** Hatch Spacing (μm)

## 3. Characterization Results
### Powder Analysis
[cite_start]Using custom **Python scripts** and **ImageJ**, I analyzed the particle size distribution (PSD) of the feedstock to predict flowability issues[cite: 9].

![Placeholder for PSD Graph](/assets/images/niti-thumb.jpg)

### Microstructure & Defects
I used **SEM (Scanning Electron Microscopy)** to detect lack-of-fusion defects.
* **Initial Results:** High porosity (>1%) due to insufficient energy density.
* **Optimization:** Adjusted parameters based on the Response Surface Model.
* [cite_start]**Final Result:** Achieved **< 0.07% porosity** (measured via Archimedes method)[cite: 17].

## 4. Conclusion
The study defined a stable processing window for NiTi on the Prima Sharp 150 machine, allowing for the manufacturing of complex biomedical actuators.

[< Back to Portfolio](/)