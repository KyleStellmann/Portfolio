---
layout: post
title: "Stirling Engine Design & Prototyping"
date: 2016-09-09
categories: projects
image: Stirling_Engine.jpg
author: "Kyle Stellmann"
---

<style>
  /* Limits only the top featured image rendered on THIS specific page */
  .featured-image img {
    max-height: 380px !important;
    width: auto !important;
    object-fit: contain;
  }
</style>

### Project Overview
Engineered and fabricated a functional Stirling engine designed to convert thermal energy into mechanical work, focusing on optimizing the relationship between thermal expansion and mechanical friction.

---

### Technical Highlights & Analysis
- **CAD Modeling & Dynamics:** Modeled the complete assembly in SolidWorks and calculated the flywheel's moment of inertia to ensure sufficient kinetic energy to carry the piston through its compression stroke.
- **Kinematics & Timing:** Designed the custom crankshaft and connecting rod linkages in SolidWorks to establish precise mechanical timing between the displacer and power cylinder.
- **Tolerance & Seal Optimization:** Iterated interference fits between the 3D-printed PLA piston and PVC cylinder to achieve a near airtight seal with minimal sliding friction.
- **System Validation:** Successfully achieved a consistent idle speed using a standard heat lamp, leveraging precision tolerances and flywheel inertia to smooth out power strokes and prevent stalling.

<div style="text-align: center; margin: 25px 0;">
  <img src="{{ site.github.url }}/assets/img/Animation.gif" alt="Stirling Engine Motion Demo" style="max-height: 400px; width: auto; max-width: 100%; border-radius: 4px;">
</div>
