---
layout: page
title: Active Vision of Coordinated Ground Vehicle Systems
description: >
  Put some selected projects on this page.
hide_description: true
sitemap: false
permalink: /research/active_vision/
---
## Overview
<p align="justify">
This is the project for my Bachelor's dissertation. It was conducted in the laboratory of Cooperative Intelligence of
Unmanned Systems (CIUS) led by <a href="https://me.sjtu.edu.cn/teacher_directory1/dongwei2.html">Prof. Wei Dong</a>.
In this project, <strong>we deployed two ground vehicles (UGVs) to localize an aerial vehicle based on onboard cameras with
pan-tilt platforms. Meanwhile, the UGVs were capable of detecting surrounding obstacles for the aerial vehicle to
ensure safe navigation.</strong>

<br>
I was responsible for designing planning and control algorithms for the camera systems so that they could cooperatively adjust configurations
to fit the tasks of localization and obstacle detection simultaneously. My method consists of two modules. <strong>Task allocation</strong> module
plans task for each robot, and the <strong>MPC controller</strong> module generates control signals for camera pan-tilt platforms to conduct the assigned tasks.
</p>
<div class="video-container">
  <video width="600" controls style="display: block; margin: 0 auto;">
    <source src="/research/active_vision/active_vision_video_demo.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>
### Method
<p align="justify">
Tasks are modelled hierarchically into team and individual levels. The team level task is planned based on consensus among robots.
The individual level tasks is allocated based on auction method. The assigned tasks are sent into MPC controllers as objectives, and
In controller, UGV motion, pan-tilt platform motion, and UAV motion are modelled to capture major features that contributes to the
systems kinematics.
</p>
<img src="/research/active_vision/assets/img/active_vision_module.png" style="zoom:60%; display:block; margin:10px auto;"/>

### Implementation and Experiments
The algorithms wre implemented based on <strong>ROS</strong> and experiments were conducted in an indoor scenario.
Robust UAV localization is guaranteed for 96.6% of the experiment duration.

---
[Back to Research Page](/research/)
