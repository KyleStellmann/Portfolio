---
layout: post
title: "Solar Tracking System |   In Progress"
author: "Kyle Stellmann"
categories: projects
image: SolarTracker.png
---
### Project Overview 
-
Designed and built a single-axis light tracking system using an Arduino and a custom 3D-printed frame. The system rotates automatically toward bright light sources, focusing on simple hardware integration and low-cost 3D fabrication.
---

### Technical Highlights & Analysis
- Sensor Logic: Used two Light Dependent Resistors (LDRs) to compare light readings and calculate which direction the frame should turn.

- 3D Printing & Assembly: Designed and printed a custom mounting stand to hold the servo motor, Arduino board, and sensors.

- Servo Motion Smoothing (In Progress): Writing embedded C++ code with deadbands and signal filtering to smooth out motor jitter and prevent rapid back-and-forth twitching.

- Cable Management (In Progress): Organizing and routing sensor wires through custom channels in the printed chassis to prevent tangling during rotation.
