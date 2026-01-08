---
layout: splash
title: "Topological Optimization of Milling Head"
permalink: /pages/project-palbit/
toc: true
toc_label: "Role Overview"
mathjax: true
---

**Project:** Topological Optimization of a Milling Head for Additive Manufacturing | **Tools:** nTop, TopOp, FEA  | **Authors:** Ilídio Brito Costa, Bruno Rafael Cunha, João Marouvo, Daniel Figueiredo, Bruno Miguel Guimarães, Manuel Fernando Vieira & José Manuel Costa

## 1. Introduction

The global machining market is shifting toward high-end materials and digitalization, demanding tools that are lighter, more efficient, and capable of higher cutting speeds. In collaboration with Palbit S.A. and FEUP, this project aimed to redesign a standard 8-cutting-face milling head to leverage the design freedom of Additive Manufacturing (specifically Laser Powder Bed Fusion).

<div style="text-align: center; margin-bottom: 20px;">
  <img src="/assets/images/palbit/palbit_banner.png" style="max-width: 90%; height: auto;">
</div>

My primary role focused on the structural redesign using nTop. By moving away from traditional subtractive manufacturing constraints, we utilized topological optimization (SIMP) to create a tool that was not only lighter but also mechanically superior to the original solid steel component.

## 2. Technical Experience

Topological Optimization in nTop To ensure computational efficiency and geometric symmetry, I defined the design space by isolating a 1/8th section of the milling head (representing one insert seat). This segment was optimized and then patterned to reconstruct the full component.

- <b>Design Constraints:</b> I configured the optimization logic to strictly adhere to LPBF manufacturing limitations, specifically enforcing a minimum overhang angle of 45° to minimize the need for internal support structures.

- <b>Structural Targets:</b> The optimization objective was volume minimization while strictly capping maximum displacement at 200 µm under load.

- <b>Result:</b> The final topology achieved a 10% weight reduction compared to the original solid part.
Finite Element Analysis (FEA) & Validation A critical aspect of my work was proving that a lighter, "hollowed" tool could withstand the harsh environment of metal cutting.

- <b>Load Case:</b> We simulated the cutting forces exerted on the inserts while milling a steel block. Incorporating a safety factor of 1.5, the validation load was set to 13,500 N applied to the insert mounting faces.

- <b>Comparative Analysis:</b> I performed static structural simulations on both the original subtractive design and our new additive design.

- <b>Performance Gain:</b> The analysis revealed a counter-intuitive improvement: despite being 10% lighter, the topologically optimized head exhibited less displacement (increased stiffness). The original head showed a maximum displacement of 160 µm, while our optimized design reduced this to 151 µm.

3. Key Takeaways

- <b>Design for Additive Manufacturing (DfAM):</b> Successfully balanced mass reduction with strict manufacturing constraints (overhangs and powder removal) to ensure the part was printable.

- <b>Performance Enhancement:</b> Proved that mass reduction does not require a compromise in stiffness; the optimized geometry outperformed the solid legacy part in structural rigidity.

- <b>Industry-Academia Success:</b> The project bridged theoretical optimization with practical industrial application, culminating in a poster presentation at the HiRev Conference and a peer-reviewed publication in [MDPI Metals](https://doi.org/10.3390/met15070729).

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