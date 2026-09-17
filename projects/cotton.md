---
layout: project
type: project
image: img/cotton/cotton-square.png
title: "Introductory Light Scanner"
date: 2024
published: true
labels:
  - Matlab
  - Arduino
summary: "A text adventure game that I developed for ICS 313."
---

During my first year studying Mechanical Engineering, I was introduced to programming with Arduino and MATLAB. Throughout the course, we built several projects that combined coding with physical parts to complete different tasks. For our final project, my partner and I developed a light scanner using an Arduino, sensors, servo motors, and 3D-printed parts. The goal of the project was to scan the surrounding area and determine where the brightest light in the room was located.

The scanner was built around an Arduino Uno and used two servo motors to control its movement in two directions. One servo controlled the horizontal rotation while the other controlled the vertical angle, allowing the light sensor to scan across a hemisphere. Using MATLAB, we programmed the servos to move through a 45-by-45 grid of positions and record the voltage from the light sensor at each point. The program then converted the voltage readings into estimated lux values and calculated the corresponding X, Y, and Z coordinates. Once the scan was complete, MATLAB generated 3D surface plots that visually displayed the brightness levels across the scanned area, making it possible to identify the direction of the strongest light source.

This project taught me how software and hardware can work together to solve a real-world problem. I gained experience programming an Arduino through MATLAB, controlling servo motors, collecting sensor data, and transforming raw data into useful visualizations. I also learned how important testing and troubleshooting are when working with physical systems, since small changes in the hardware, sensor readings, or code could affect the final results.

