---
layout: default
title: Research
permalink: /research.html
---

{% include nav.html %}

# Research

My research spans robot manipulation, whole-body teleoperation, distributed multi-robot control, and active visual perception.

<article class="research-project">
  <p class="meta">Human-robot interaction | 2024</p>
  <h2>Egocentric Control for Whole-Body Robot Teleoperation</h2>
  <p>Designed a real-time system that maps an operator's head and arm movements to a dual-arm TIAGo mobile manipulator. A fuzzy controller coordinates torso and base behavior using obstacle geometry and operator motion, while a VR interface provides live robot-camera and state feedback.</p>
  <ul>
    <li>Lower task-completion time with statistical significance (p &lt; 0.05).</li>
    <li>Lower NASA-TLX mental-workload scores (p &lt; 0.01).</li>
    <li>Collision-free operation in the evaluated tasks.</li>
  </ul>
</article>

<article class="research-project">
  <p class="meta">Multi-robot systems | 2021-2023</p>
  <h2>Trust Evaluation for Quadrotor Consensus Based on Behavior Prediction</h2>
  <p>Developed a fault-tolerant consensus method in which quadrotors exchange behavior predictions and update a distributed trust-weight matrix online.</p>
  <ul>
    <li>Implemented three-loop PID control for position, velocity, and attitude.</li>
    <li>Applied Kalman filtering for pose estimation in GPS-denied, single-IMU conditions.</li>
    <li>Achieved 100% successful convergence in simulation and physical experiments with a 50% drone failure rate.</li>
  </ul>
  <p><a href="https://doi.org/10.3390/drones6120371">Read the published paper</a></p>
</article>

<article class="research-project">
  <p class="meta">Active perception | 2022-2023</p>
  <h2>Active Visual Perception for Ground and Aerial Robotic Systems</h2>
  <p>Built a distributed perception system for cross-platform detection and localization using onboard cameras.</p>
  <ul>
    <li>Adapted the PyTorch-based NanoDet interface and communications stack for a ground vehicle, reaching 93% drone-detection confidence.</li>
    <li>Combined SIFT feature matching, the Hough transform, and triangulation for target-tower localization.</li>
    <li>Reached less than 2 degrees of angle error, less than 0.1 m of position error, and 90% tower-localization accuracy in physical experiments.</li>
  </ul>
</article>
