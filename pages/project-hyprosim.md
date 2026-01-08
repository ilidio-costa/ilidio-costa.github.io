---
layout: splash
title: "HyProSim: Hybrid Rocket Engine Propulsion Simulation, an Engineering Tool"
permalink: /pages/project-hyprosim/
toc: true
toc_label: "Role Overview"
mathjax: true
---

**Project:** HyProSim | **Tools:** Leadership, Python, Coolprop, RocketCEA  | **Authors:** Ilídio Costa, Rafael Lino & Pedro Gameiro

## 1. Introduction

Founded HyProSim to solve a critical resource bottleneck for the  [Porto Space Team's](https://www.portospaceteam.pt/en): the high cost and risk of physical testing for hybrid rocket engines. I designed the initial architecture and physics core for this modular engineering tool, which is now capable of predicting engine performance with high accuracy against experimental data.

HyProSim arose from project INVICTUS, which encompasses the development of a high-performance hybrid-propulsion rocket with a apogee of 3 km aimed at participating in the European Rocketry Challenge (EuRoC). In 2024, Porto Space Team marde history as the first Portuguese student-led team to produce and validate a hybrid rocket engine and first to compete in Euroc with a Portuguese hybrid chemical engine.

<div style="text-align: center; margin-bottom: 20px;">
  <img src="/assets/images/hyprosim.png" alt="defending the dissertation" style="max-width: 25%; height: auto;">
</div>

Hybrid rocket engines are of significant relevance to the future of space exploration, particularly for Portugal. This technology offers a compelling combination of safety and controllability, making it ideal for launching small satellites, a rapidly expanding market segment. Furthermore, hybrid engines present a more sustainable alternative, aligning with Portugal’s environmental objectives. Currently there's efforts to publish a stable version of the project.

## 2. Technical Experience

As the initial architect, I built the simulation's core modular infrastructure and programmed the fundamental fluid dynamic modules.

- Modular Design: Designed a decoupled architecture where specific engine components (Tank, Injector, Chamber) operate as independent modules. This allowed for easier maintenance and enabled the implementation of flexible simulation workflows.

- Oxidizer Tank Physics: Developed the thermodynamic models for Nitrous Oxide (N2O) storage. This included simulating "Auto-Pressurized" systems (reliant on vapor pressure and phase change) and "Externally Pressurized" systems (using inert gas regulation).

- Injector Dynamics: Implemented complex fluid flow models to account for the phase change of oxidizers across the injector plate. This involved coding Homogeneous Equilibrium Models (HEM) and Non-Homogeneous Non-Equilibrium (NHNE) models to accurately predict mass flow rates under varying pressure conditions.

- Early Simulations: Coupling every module including fuel grain geometry, fuel regression and combustion (which utilized RocketCEA) to produce the first simulation and validating with experimental data from previous hot fire tests.

<div style="text-align: center;">
  <iframe src="/assets/pdfs/hyprosim_intro.pdf" width="75%" height="600px" style="border: none;">
  </iframe>
</div>

Transitioning from primary developer to project lead, I managed the roadmap for future improvements, including architectural changes for the code, uniformization of , refinement of physic modules, interface. Curently the Project is manadge by Rafael Lino, pushing the boundering of HyProSim.

- <b>Award-Winning Scientific Poster:</b> The early architecture and simulation results earned the Best Poster Presentation Award at the 1st Space Education Summit.

<div style="text-align: center;">
  <iframe src="/assets/pdfs/1stSpaceEducationSummit.pdf" width="75%" height="600px" style="border: none;">
  </iframe>
</div>

- <b>Validation:</b> The simulator achieved high accuracy, with simulated chamber pressure and thrust curves closely matching experimental data trends.

<div style="text-align: center; margin-bottom: 20px;">
  <img src="/assets/images/advisor/advisor-hyprosim.png" style="max-width: 95%; height: auto;">
</div>

## 3. Key Takeaways

- <b>Full-Cycle Engineering:</b> Took a complex aerospace problem from theoretical physics equations to a deployed software tool used for real-hardware validation.

- <b>Scalable Architecture:</b> Built a codebase robust enough to be handed off and expanded by a new team of developers, proving the quality of the initial software design.

- <b>Domain Expertise:</b> Gained deep applied knowledge in thermodynamics, two-phase fluid flows, and propulsion system design.



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