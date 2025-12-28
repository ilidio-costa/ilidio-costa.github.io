---
layout: splash
title: "Home"
author_profile: false

experience_gallery:
  - image_path: /assets/images/pst-thumb.png
    title: "Propulsion Lead @ Porto Space Team"
    excerpt: "**(2024 - Present)**<br>Leading the INVICTUS II hybrid rocket engine development."
    url: "/pages/experience-invictus/"
    btn_label: "View Role"
    btn_class: "btn--inverse"

  - image_path: /assets/images/niti-thumb.jpg
    title: "NiTi L-PBF Optimization"
    excerpt: "**Master's Thesis**<br>Minimizing porosity to <0.07% in Shape Memory Alloys."
    url: "/pages/project-niti/"
    btn_label: "View Role"
    btn_class: "btn--inverse"

    
projects_gallery:
  - image_path: /assets/images/fem-thumb.jpg
    title: "Topology Optimization"
    excerpt: "**Research Project**<br>FEA analysis of cutting heads."
    url: "/pages/project-niti/"
    btn_label: "View Case Study"
    btn_class: "btn--primary"
---

<div style="
    background-image: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('/assets/images/banner.png');
    background-size: cover;
    background-position: center;
    border-radius: 8px;
    padding: 60px 40px;
    margin-bottom: 40px;
    color: white;
    box-shadow: 0 4px 10px rgba(0,0,0,0.3);
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    gap: 40px;">

    <img src="/assets/images/profile.png" alt="Profile" style="
        width: 250px;
        height: 250px;
        border-radius: 50%;
        border: 4px solid white;
        object-fit: cover;
        box-shadow: 0 0 20px rgba(0,0,0,0.5);">

    <div style="flex: 1; min-width: 300px;">
        <h1 style="color: white; margin: 0; font-size: 3em; line-height: 1.1; text-transform: none;">Ilídio Costa</h1>
        <p style="font-size: 1.4em; color: #aabccd; margin: 10px 0 0 0; font-weight: 300;">Materials Engineer | Additive Manufacturing & Propulsion</p>
        
        <p style="font-size: 1.1em; color: #eee; margin-top: 20px; max-width: 600px;">
            Bridging the gap between metallurgy and aerospace systems. Currently optimizing <b>NiTi L-PBF parameters</b> and leading propulsion at <b>Porto Space Team</b>.
        </p>

        <div style="margin-top: 25px; display: flex; gap: 15px; flex-wrap: wrap;">
            <a href="/assets/pdfs/CV_Ilidio_Costa.pdf" style="background: white; color: #1a1a1a; padding: 10px 20px; border-radius: 4px; text-decoration: none; font-weight: bold;">Download CV</a>
            <a href="mailto:ilidiomibritocosta@gmail.com" style="border: 2px solid white; color: white; padding: 8px 20px; border-radius: 4px; text-decoration: none;">Email Me</a>
            <a href="https://linkedin.com" style="border: 2px solid #0077b5; background: #0077b5; color: white; padding: 8px 20px; border-radius: 4px; text-decoration: none;">LinkedIn</a>
        </div>
    </div>
</div>

## 🛠️ Skills & Stack

<div class="marquee-container">
  <div class="marquee-content">
    <span class="skill-pill">L-PBF (EOS M290)</span>
    <span class="skill-pill">Design for AM (DfAM)</span>
    <span class="skill-pill">Parameter Optimization</span>
    <span class="skill-pill">SEM / EDS / EBSD</span>
    <span class="skill-pill">XRD & XRF</span>
    <span class="skill-pill">Optical Microscopy</span>
    <span class="skill-pill">Python (Pandas/Matplotlib)</span>
    <span class="skill-pill">nTop (Topology Opt)</span>
    <span class="skill-pill">Abaqus (FEA)</span>
    
    <span class="skill-pill">L-PBF (EOS M290)</span>
    <span class="skill-pill">Design for AM (DfAM)</span>
    <span class="skill-pill">Parameter Optimization</span>
    <span class="skill-pill">SEM / EDS / EBSD</span>
    <span class="skill-pill">XRD & XRF</span>
    <span class="skill-pill">Optical Microscopy</span>
    <span class="skill-pill">Python (Pandas/Matplotlib)</span>
    <span class="skill-pill">nTop (Topology Opt)</span>
    <span class="skill-pill">Abaqus (FEA)</span>
  </div>
</div>

<br>

## 🚀 Experience
{% include feature_row id="experience_gallery" type="center" %}

<br>

## 🎓 Education

**MSc Materials Engineering** | *FEUP, Porto (2025)*
* **Thesis:** Parameter Optimization of Laser Powder Bed Fusion of NiTi.
* **Focus:** Metallurgy, Thermodynamics, and AM Process Development.

**Powder Metallurgy Summer School** | *EPMA, Sweden (June 2025)*
* Intensive 5-day training on Sintering, MIM, and HIP technologies.

**BSc Materials Engineering** | *FEUP, Porto (2023)*
* **Capstone:** Topological Optimization of Avionic Bay Support.

<br>

## 🧪 Technical Projects

{% include feature_row id="projects_gallery" type="center" %}

<script>
// This is a trick to render the feature rows without complex YAML
</script>

---

## 📬 Contact
Ready to build? [**Email Me**](mailto:ilidiomibritocosta@gmail.com).

<style>
  /* 1. Hide Top Title */
  .masthead__branding {
    display: none !important;
  }

  /* 2. THE IMAGE BOX (The Alignment Fix) */
  .archive__item-teaser {
    height: 80px;          /* FIXED HEIGHT: Text will always start below this line */
    display: flex;          /* Enables centering */
    align-items: center;    /* Vertically centers the logo in the box */
    justify-content: center;/* Horizontally centers the logo */
    margin-bottom: 20px;    /* Standard space between Image and Text */
    padding: 10px;          /* Breathing room */
  }

  /* 3. THE LOGO ITSELF */
  .archive__item-teaser img {
    max-height: 100%;       /* Ensure it fits in the 160px box */
    max-width: 100%;        /* Ensure wide logos don't overflow */
    width: auto;            /* Maintain aspect ratio */
    object-fit: contain;    /* Keep sharp */
  }

  /* 4. THE TEXT (Force Left Alignment) */
  .archive__item-body {
    text-align: left !important; /* Forces the title and description to the left */
    padding-left: 10px;          /* Aligns slightly with the image box */
  }

  /* 5. MAKE CARDS UNIFORM */
  .feature__item {
    margin-bottom: 40px;    /* Space between rows */
  }


  /* Container for the marquee */
  .marquee-container {
    width: 100%;
    overflow: hidden;
    padding: 20px 0;
    position: relative;
    background: transparent;
    /* Optional: Adds a fade effect at the edges */
    -webkit-mask-image: linear-gradient(to right, transparent, black 10%, black 90%, transparent);
    mask-image: linear-gradient(to right, transparent, black 10%, black 90%, transparent);
  }

  /* The moving track */
  .marquee-content {
    display: flex;
    gap: 20px;
    width: max-content;
    animation: scroll-left 30s linear infinite;
  }

  /* Style for each individual skill "pill" */
  .skill-pill {
    padding: 10px 20px;
    background: #f0f0f0;
    color: #333;
    border: 1px solid #ddd;
    border-radius: 50px;
    font-weight: 600;
    font-size: 0.9em;
    white-space: nowrap;
    box-shadow: 0 2px 5px rgba(0,0,0,0.05);
  }

  /* Dark mode adjustment for Contrast skin */
  .skill-pill {
    background: #252a34;
    color: #eee;
    border-color: #454d5d;
  }

  /* Animation keyframes */
  @keyframes scroll-left {
    0% { transform: translateX(0); }
    100% { transform: translateX(-50%); } /* Moves halfway through the double list */
  }

  /* Pause on hover so people can read */
  .marquee-container:hover .marquee-content {
    animation-play-state: paused;
  }
</style>