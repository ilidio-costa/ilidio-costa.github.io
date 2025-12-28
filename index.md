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
    btn_label: "View Case Study"
    btn_class: "btn--primary"

    
projects_gallery:
  - image_path: /assets/images/fem-thumb.jpg
    title: "Topology Optimization"
    excerpt: "**Research Project**<br>FEA analysis of cutting heads."
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
        width: 160px;
        height: 160px;
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

| **Additive Mfg.** | **Characterization** | **Software** |
| :--- | :--- | :--- |
| L-PBF (EOS M290) | SEM / EDS / EBSD | Python (Pandas/Matplotlib) |
| Design for AM (DfAM) | XRD & XRF | nTop (Topology Opt) |
| Parameter Optimization | Optical Microscopy | Abaqus (FEA) |

<br>

## 🚀 Experience
{% include feature_row id="experience_gallery" type="left" %}

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

{% include feature_row id="projects_gallery" type="left" %}

{% assign experience_gallery = site.empty_array %}
{% assign projects_gallery = site.empty_array %}

{% capture exp_1_title %}Propulsion Lead @ Porto Space Team{% endcapture %}
{% capture exp_1_excerpt %}**(2024 - Present)**<br>Leading the INVICTUS II hybrid rocket engine development. Managed hot-fire testing, safety protocols, and team budget.{% endcapture %}
{% capture exp_1_url %}/pages/experience-invictus/{% endcapture %}

{% capture exp_2_title %}R&D Intern @ Palbit{% endcapture %}
{% capture exp_2_excerpt %}**(2024 - 2025)**<br>Topology optimization of machining heads using nTop to reduce mass while maintaining structural stiffness.{% endcapture %}

{% capture proj_1_title %}NiTi L-PBF Optimization{% endcapture %}
{% capture proj_1_excerpt %}**Master's Thesis**<br>Minimizing porosity to <0.07% in Shape Memory Alloys using Taguchi DoE.{% endcapture %}
{% capture proj_1_url %}/pages/project-niti/{% endcapture %}

{% capture proj_2_title %}Topology Optimization Study{% endcapture %}
{% capture proj_2_excerpt %}**Research Project**<br>FEA analysis of cutting heads to reduce inertia in high-speed machining.{% endcapture %}

<script>
// This is a trick to render the feature rows without complex YAML
</script>

---

## 📬 Contact
Ready to build? [**Email Me**](mailto:ilidiomibritocosta@gmail.com).

<style>
  /* Hides the default top title ONLY on this page */
  .masthead__branding {
    display: none !important;
  }
</style>