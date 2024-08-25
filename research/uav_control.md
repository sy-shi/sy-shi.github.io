---
layout: page
title: Adaptive Control of UAVs with Parameter Estimation
sitemap: false
permalink: /research/uav_control/
---

The project was conducted in the laboratory of Cooperative Intelligence of
Unmanned Systems (CIUS) led by <a href="https://me.sjtu.edu.cn/teacher_directory1/dongwei2.html">Prof. Wei Dong</a>.

In recent years, unmanned aerial vehicles (UAVs), es-
pecially multi-rotor UAVs, have been widely applied to
military/civil transportation tasks such as parcel delivery,
equipment deployment, and rescue missions. These
tasks share common characteristics that the mass-inertia
parameters of UAVs vary from flight to flight, and a fine-tune
of controllers to retain good tracking performances between
missions is time-consuming.
<!-- In the above collaborative system, the quadruped brings mass-inertia uncertainty
to the whole transportation system, because it might deploy sensors or carry samples
with it. Hence, the performance of flight is greatly affected.  -->
To tackle this problem, we designed an **adaptive controller** for transportation. The proposed method
**rejects external disturbances** such as wind with compensation and **estimates uncertain**
**mass-inertia parameters**. It exceeds other methods in its smoothness and convergence
rate. It is able to achieve 2% estimation error bound in less than 4 seconds for an UAV with mass over 3kg.

<img src="/research/uav_control/assets/img/attitude_e.png" style="zoom:90%; float:center; padding:37px;" />

---
[Back to Research Page](/research/)
