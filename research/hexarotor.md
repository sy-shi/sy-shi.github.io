---
layout: page
title: An Integrated Quadruped-Hexarotor System
sitemap: false
permalink: /research/hexarotor/
---
<img src="assets/img/flight_1.png" style="zoom:100%; display:block; margin:10px auto;" />
This research was conducted in the laboratory of Cooperative Intelligence of
Unmanned Systems (CIUS) led by [Prof. Wei Dong](https://me.sjtu.edu.cn/teacher_directory1/dongwei2.html).
Aiming at exploraiton and rescue
tasks in flight-impeded areas, we designed an **integrated quadruped-hexarotor system**.
UAVs are flexible and efficient to transport the ground vehicle to the task spot,
and quadruped robots are of high-adaptiveness in complex environments. The
collaboration can combine the advantages of the aerial and quadruped vehicles.

---
### System Design
[Read our Paper](https://ieeexplore.ieee.org/abstract/document/9665137)
<img src="assets/img/dock.png" style="zoom:70%; display:block; margin:10px auto;" />
In transportation, the UAV and the quadruped robot are closely contacted. We exploited
this and developed an **adaptive docking system**, with which the quadruped can be
captured by the UAV without the requirement for high localization accuracy. And
this system enabled two vehicles to **share computing resources** with four electrodes
for serial communication.

We also implemented a **vision-based remote localization package** to enable the
quadruped finding the hexarotor quickly after the tasks finish. Details of the
system can be found in our published paper [in 2021 IEEE M2VIP](https://ieeexplore.ieee.org/abstract/document/9665137).

---
### Control
[Read our paper](http://arxiv.org/abs/2209.08209)

In the above collaborative system, the quadruped brings mass-inertia uncertainty
to the whole transportation system, because it might deploy sensors or carry samples
with it. Hence, the performance of flight is greatly affected. To tackle this
problem, we designed an **adaptive controller** for transportation. The proposed method
**rejects external disturbances** such as wind with compensation and **estimates uncertain**
**mass-inertia parameters**. It exceeds other methods in its smoothness and convergence
rate. The paper can be seen in [arXiv](http://arxiv.org/abs/2209.08209).

---
[Back to Research Page](/research/)