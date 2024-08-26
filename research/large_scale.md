---
layout: page
title: Efficient Large-Scale Team Behavior Manipulation
sitemap: false
permalink: /research/large_scale/
---
>How to control the collective behavior of large-scale agent teams so that they can achieve pre-designed human commands?

From June 2022 to February 2023, I remotely led this research project in the Cognitive Robotics and
AI [(CRAI)](https://ruiliurobotics.weebly.com/) lab, Kent State Unviersity, under the supervision
of [Prof. Rui Liu](https://www.kent.edu/cae/rui-liu-ph-d). Inspired by the **herding behavior**
in animals and the **opinion manipulation** in marketing, we believe large-scale robotic crowds can also be
efficiently manipulated via several **critical agents**.

---
### Method
<p align="justify">
We designed a distributed learning paradigm informed by social topology to <strong>elect</strong>
critical agents based on their ability and power, and collaboratively propagate
intended collective behaviors to other robots. Compared with other collective behavior
<ol>
    <li>Inspired by opinion propagation in marketing, we proposed an election paradigm to elect critical agents with large influence on the team.</li>
    <li>Based on GCN and observed states of their surrounding agents, critical agents manipulate the action of other agents via a learned policy.</li>
</ol>
manipulation methods, our method has better performance in scalability and efficiency.</p>


<img src="/research/large_scale/intuition.png" style="zoom:70%; display:block; margin:10px auto;" />

---
[Back to Research Page](/research/)
