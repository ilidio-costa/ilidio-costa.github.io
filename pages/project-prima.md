---
layout: splash
title: "Topological Optimization of Milling Head"
permalink: /pages/project-prima/
toc: true
toc_label: "Role Overview"
mathjax: true
---

**Project:** Prima Sharp 150 System Integration | **Tools:** L-PBF, Materialise Magics | **Authors:** Ilídio Costa, Prof. José Costa

## 1. Introduction

This project involved the end-to-end set up of a Laser Powder Bed Fusion (L-PBF) Prima Sharp 150 system within a research environment. The primary objective was to transition the equipment from installation to a high-precision production state, ensuring that all mechanical and software parameters were optimized for the fabrication of metal alloys.

<div style="text-align: center; margin-bottom: 20px;">
  <img src="/assets/images/prima/printsharp150.png" style="max-width: 50%; height: auto;">
</div>

## 2. Technical Experience

### Hardware Commissioning and System Calibration

My primary responsibility was the physical integration of the machine's internal components. This included the precise leveling of the build substrate and the calibration of the recoater mechanism to ensure uniform powder distribution. I monitored oxygen levels and inert gas flow to ensure material integrity during the fusion process. Additianlly I prepared the file in Materialise Magics

<div style="text-align: center; margin-bottom: 20px;">
  <img src="/assets/images/prima/oh_prima.png" style="max-width: 95%; height: auto;">
</div>

### Process Validation and First-Layer Analysis

A critical phase of the project focused on Initial Layer Adhesion. I established a rigorous verification protocol to inspect the first 100–500 microns of the build. By analyzing melt pool stability and track uniformity at the interface between the substrate and the part, I was able to mitigate the risks of delamination and thermal warping early in the process cycle.

<div style="text-align: center;">
  <video width="90%" controls style="text-align: center; margin-bottom: 20px;">
    <source src="/assets/images/prima/printing.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>

### Scaling to Complex Geometries

Upon achieving process stability with standard calibration specimens, I advanced the system’s operational envelope to include complex, thin-wall geometries and lattice structures. This required iterative adjustments to the scan strategy—specifically modulating laser power, hatch spacing, and point distance—to maintain high geometric fidelity and minimize porosity in intricate features.

<div style="text-align: center;">
  <video width="40%" controls style="text-align: center; margin-bottom: 20px;">
    <source src="/assets/images/prima/lifting.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>

<div style="text-align: center; margin-bottom: 20px;">
  <img src="/assets/images/prima/examples.jpg" style="max-width: 75%; height: auto;">
</div>

## 3. Takeaways

- <b>Systematic Troubleshooting:</b> Developed a high-level proficiency in identifying and resolving hardware-software discrepancies that affect part density and surface finish.

- <b>Precision Methodology:</b> Cultivated a disciplined approach to machine setup, recognizing that the reliability of a 20-hour build is contingent upon the accuracy of the first 20 minutes of preparation.

- <b>Operational Autonomy:</b> Gained the technical expertise required to manage the full lifecycle of a metal additive manufacturing build, from STL repair and support generation to post-process recovery.

[< Back to Portfolio](/)

<style>
  /* 1. FORCE FULL WIDTH LAYOUT */
  /* This breaks the default narrow column layout of the theme */
  .page__content {
    width: 100% !important;
    max-width: 100% !important;
    padding-right: 0 !important;
    float: none !important;
    margin-right: 0 !important;
  }

  /* 2. WIDEN THE PARENT CONTAINER */
  /* This controls the overall max width of the page body */
  .page__inner-wrap {
    width: 95% !important; /* Uses 95% of your screen */
    max-width: 95% !important;
    margin-left: auto;
    margin-right: auto;
  }
  
  /* 3. ENSURE TEXT IS READABLE */
  /* Justify text for a clean, academic look */
  p {
    text-align: justify;
    text-justify: inter-word;
  }
</style>