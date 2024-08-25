---
layout: page
title: Robot Painting
description: >
  Put some selected projects on this page.
hide_description: true
sitemap: false
permalink: /project/painting/
---
>We implemented a hierarchical planning and control framework which is able to create a stylish painting given an input image.

## System architecture
<p align="justify">
Given a target image, high-level stroke points are produced from an <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10160702&casa_token=RrD0Abg3uBwAAAAA:nmpR6ak2dzhuswPm9VHG1bYNXr9Iu0BlxUAwHDTD92qYkqKTFwDnEpiWpmqoV8g47Mbqcgdj&tag=1">FRIDA planner</a> [1], which exploits pre-trained VLMs for image to image mapping. The stroke points are further converted into executable Bezier curve points, and sent to a low-level motion controller for execution. The mobile manipulator is localized by running an ArUco Tag detection program with visual servo.
</p>
<img src="/project/painting/framework.png" style="zoom:50%; display:block; margin:10px auto;" />

<br>
[1] Schaldenbrand, Peter, James McCann, and Jean Oh. "Frida: A collaborative robot painter with a differentiable, real2sim2real planning environment." 2023 IEEE International Conference on Robotics and Automation (ICRA). IEEE, 2023.

## Demo
<div class="video-container">
  <video width="600" controls style="display: block; margin: 0 auto;">
    <source src="/project/painting/painting demo.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>

---
[Back to Project Page](/project/)
