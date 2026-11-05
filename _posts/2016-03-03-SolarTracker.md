---
layout: post
title: "Light Tracking System | In Progress"
author: "Kyle Stellmann"
categories: projects
image: SolarTracker.jpg
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
Designed and built a single-axis light tracking system using an Arduino and a custom 3D-printed frame. The system rotates automatically toward bright light sources, focusing on simple hardware integration and low-cost 3D fabrication.

### Technical Highlights & Analysis
- **Sensor Logic:** Used two Light Dependent Resistors (LDRs) in a voltage divider setup to compare light readings and determine optimal rotation direction.
- **3D Printing & Assembly:** Designed and printed a custom mounting stand to hold the servo motor, Arduino board, and sensor array.
- **Servo Motion Smoothing (In Progress):** Writing embedded C++ code with deadbands and signal filtering to smooth out motor jitter and prevent rapid back-and-forth twitching.
- **Cable Management (In Progress):** Organizing and routing sensor wires through custom channels in the printed chassis to prevent tangling during rotation.

---

### Prototype Demonstration
*Check out the early prototype test below:*

<div style="text-align: center; margin: 20px 0;">
  <iframe 
    width="315" 
    height="560" 
    src="https://www.youtube.com/embed/MRSSKDdbY6E" 
    title="Arduino Light Tracker Prototype Demo" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
    allowfullscreen>
  </iframe>
</div>
