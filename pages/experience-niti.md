---
layout: single
title: "Parameter Optimisation for Laser Powder Bed Fusion of NiTi"
permalink: /pages/experience-niti/
sidebar:
  nav: "docs"
toc: true
toc_label: "Role Overview"
mathjax: true
---

**Organization:** FEUP & CATEC | **Role:** Research AM Engineer | **Timeline:** February 2025 - October 2025

![Logos](/assets/images/niti-thumb.jpg)

{: .notice--danger}
**Restricted Access:** This work contains protected results and thus cannot be fully shared.


## 1. Introdution

#### Context

Had the oppurtunity to conclude my Master’s in Material Engineering with a specialisation in Metallurgy with this work. It is a collaboration with FEUP (Faculdade de Engenharia da Universidade do Porto) and CATEC (Fundación Andaluza para el Desarrollo Aeroespacial), supervised by Prof. Elsa W. Sequeiros and co-supervised by Pof. Jorgue Lino. Titled “Parameter Optimisation for Laser Powder Bed Fusion of NiTi”, it obtained a of 18 out of 20 final grade (which is the highest without any scientific publication as stated by internal faculty rules).

![defending the dissertation](/assets/images/niti/presenting.jpg)

The transformative potential of additively manufactured Nickel-Titanium (NiTi) is driving innovation across the aerospace and biomedical sectors. In biomedical engineering, Laser Powder Bed Fusion (L-PBF) enables the creation of patient-specific orthopedic implants with porous structures that mimic bone stiffness, alongside superelastic stents and heart valves for minimally invasive procedures. Simultaneously, the aerospace industry leverages NiTi’s high power-to-weight ratio for lightweight actuators used in morphing aircraft wings, satellite deployment mechanisms, and shock-absorption systems. With significant backing from organizations like the European Space Agency, research continues to expand into smart superelastic joints, damping components and elastocaloric cooling systems, highlighting NiTi as a critical material for the next generation of intelligent, high-performance engineering solutions.

#### Engineering Challenge

NiTi is a shape memory alloy with exceptional superelasticity and shape memory effects, making it highly desirable for advanced applications. However, its full potential is limited by significant conventional manufacturing difficulties. L-PBF offers a transformative path to produce geometrically complex NiTi parts, but the process itself introduces challenges, including controlling chemical composition, defect formation, and microstructure. This work aims to establish a foundational understanding of these variables by optimising the bulk processing parameters for NiTi.

Manufacturing of NiTi components by L-PBF poses challenges, as expressed by some authors. Despite its potential, the implementation of L-PBF in the context of NiTi components manufacturing faces numerous challenges that must be surmounted to ensure the production of reliable, high-performance components. These challenges are regarded as the primary technical hurdles that current research seeks to address:

- Compositional Control: The intense, localised energy from the laser has been shown to cause the preferential evaporation of nickel, which has a higher vapour pressure than titanium. This results in alterations to the Ni/Ti ratio in the final component, which frequently leads to substantial and often unpredictable shifts in the phase transformation temperatures that govern the material’s functional properties.

- Defect Formation: Like many alloys processed via L-PBF, NiTi is susceptible to defects that can compromise its structural integrity. Porosity, formed by gas entrapment or lack of fusion between powder layers, is a common problem that can cause fatigue failure. High thermal gradients and rapid solidification can lead to solidification cracking, severely degrading the component’s mechanical properties.

- Microstructural & Phase Control: The highly dynamic and non-equilibrium thermal conditions of L-PBF result in complex microstructures. Therefore, achieving the desired austenitic or martensitic phase composition in the as-built state is challenging.

## 2. Technical Experties Utilized

#### Powder Feedstock Characterization

The research involved a rigorous assessment of Nickel-Titanium (NiTi) powder feedstock to ensure build quality. Key techniques included:

- Morphological and Chemical Analysis: Utilized Scanning Electron Microscopy (SEM) in Backscatter Electron (BSE) mode and Energy-Dispersive X-ray Spectroscopy (EDS) to evaluate powder morphology and detect potential contaminants.

- Particle Size Distribution (PSD): Implemented an automated data processing pipeline using image analysis software and Python to characterize particle diameters and distribution statistics (span, skewness, and kurtosis).

- Internal Porosity: Conducted cross-sectional analysis via Optical Microscopy (OM), involving resin mounting, precision metallographic polishing, and chemical etching to reveal internal structures.

#### Process Optimization (L-PBF)

The manufacturing phase focused on the optimization of Laser Powder Bed Fusion (L-PBF) parameters to minimize porosity:

- Experimental Design: Employed Taguchi orthogonal arrays to systematically explore the impact of laser power and scanning speed on part density.

- Density and Porosity Quantification: Evaluated build quality through Archimedes' method for bulk density and digital image analysis of polished cross-sections.

- Mathematical Modeling: Developed Response Surface Methodology (RSM) models using regression analysis to visualize the relationship between input parameters and porosity outcomes.

- Chemical Stability: Monitored elemental composition changes across varying part geometries using X-ray Fluorescence (XRF) and EDS.

#### Microstructure & Phase Analysis

Advanced characterization was performed to understand the material's structural evolution:

- Multi-Scale Imaging: Used OM and digital microscopy under polarized light to examine melt pools and grain structures, alongside high-resolution SEM for precipitate detection.

- Crystallographic Texture: Performed Electron Backscatter Diffraction (EBSD) to generate orientation imaging maps and pole figures, facilitating a deep understanding of material texture.

- Phase Identification: Conducted X-ray Diffraction (XRD) in transmission mode, utilizing computational databases and API-driven diffraction theory (pymatgen) to verify phase indexation.

#### Thermal Post-Processing

To refine material properties, controlled thermal treatments were applied:

- Heat Treatment: Executed solubilization treatments in a vertical furnace under inert gas flow to ensure environmental control.

- Post-Treatment Validation: Re-examined the samples through metallographic preparation and SEM/EDS to assess the effect of thermal history on precipitates and microstructure.

## 3. Conclusion

The successful optimization of L-PBF parameters culminated in the production of NiTi components reaching a relative density of $> 99.9\%$. This achievement represents a critical milestone in regards to defect formation and structural integrity. By virtually eliminating porosity, which is often the precursor to fatigue failure in additive-manufacured alloys, this work demonstrates that L-PBF can produce NiTi parts with the mechanical reliability required for high-stakes environments.

Achieving such high density through systematic methodologies like Taguchi orthogonal arrays and Response Surface Methodology ensures that the material's unique superelastic and shape memory properties can be fully realized without the interference of internal voids. For the aerospace industry, this paves the way for reliable, lightweight actuators and morphing structures. In the biomedical field, it ensures that patient-specific implants and cardiovascular stents possess the fatigue resistance necessary for long-term integration within the human body. Ultimately, this research validates a robust pathway for transitioning NiTi from a difficult-to-manufacture alloy into a cornerstone of next-generation, high-performance engineering solutions.


[< Back to Portfolio](/)

<style>
/* 1. JUSTIFY PARAGRAPH TEXT */
p {
  text-align: justify;
  text-justify: inter-word;
}

/* 2. FIX TABLE OF CONTENTS (SIDEBAR) */
/* This fixes the "squashed" text in the red box */
.sidebar .nav__list a, .toc__menu a {
  white-space: normal !important;   /* Allows text to wrap naturally */
  display: block;                   /* Fills the width of the box */
  padding: 4px 0;                   /* Adds space between items */
  font-size: 0.85em;                /* Slightly smaller font fits better */
  line-height: 1.4;                 /* Better spacing between lines */
  color: #444;                      /* Dark Grey instead of Bright Blue */
  text-decoration: none;            /* Removes underline */
}

/* Hover Effect for Sidebar Links */
.sidebar .nav__list a:hover, .toc__menu a:hover {
  color: #d9230f; /* Highlights red on hover */
  text-decoration: underline;
}
</style>