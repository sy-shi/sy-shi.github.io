---
layout: page
title: Guided RL
description: >
  Put some selected projects on this page.
hide_description: true
sitemap: false
permalink: /project/guided_rl/
---
>Implemented and tested 3 intuitions for expert intervention during student learning.

## Overview
<img src="/project/guided_rl/ts2c.png" style="zoom:40%; display:block; margin:10px auto;" />
<p align="justify">
    Expert intervention and demonstration is an important scheme to kick-start reinforcement learning to improve learning efficiency as well as exploration safety. Based on the work <a href="https://arxiv.org/pdf/2303.01728">Guarded Policy Optimization With Imperfect Online Demonstrations</a> [1] illustrated in the figure above, we explored three intervention intuitions herein:
<ol>
    <li><strong>Confidence-Based Advising</strong>: Condition intervention probability on expert's confidence, which is defined as expert action distribution variance \( Var(\pi_t(\cdot \mid s)) \).</li>
    <li><strong>Importance-Based Advising</strong>: Condition intervention probability on state importance, defined as relative state-action value range \( \max_a Q(a,s) - \min_a Q(a,s) \).</li>
    <li><strong>Combined Decision Maker</strong>: Mix expert and student action distribution weighted by Q-value, to generate a potentially broader exploration.</li>
</ol>
</p>

<!-- Include MathJax script for rendering math equations -->
<script src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

## Results
<p align="justify">
We compared our modifications with the TS2C method proposed in [1]. The first two variations gain improvement against TS2C, verifying our intuition, while the third variation illustrated a worse performance.

<br>
The detailed results can be found here:
<div style="text-align: center;">
  <a href="https://docs.google.com/presentation/d/1lBRKngX34TddtSk2e2BscwjKf4b3XWWiue8bp08oV8o/edit?usp=sharing" target="_blank">
    <img src="/project/guided_rl/Guided RL results.png" alt="Google Slides Cover" style="max-width: 70%; height: auto; margin: 0 auto; display: block;">
  </a>
</div>
</p>

<br>
[1] Xue, Zhenghai, et al. "Guarded policy optimization with imperfect online demonstrations." arXiv preprint arXiv:2303.01728 (2023).

---
[Back to Project Page](/project/)
