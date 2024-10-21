---
layout: page
title: Action Advising in Ad Hoc Teaming
description: >
  Put some selected projects on this page.
hide_description: true
sitemap: false
permalink: /research/action_advise/
---

## Overview

<img src="/research/action_advise/overview.pdf" style="zoom:90%; display:block; margin:10px auto;" />

<p align="justify">
Efficiency in multi-agent teamwork has been extensively studied where agents are equally experienced. %or novice. 
However, the problem when agents have varying levels of experience remains under-explored.
In such a heterogeneous knowledge setting, experienced agents can transfer their knowledge to less experienced agents to accelerate their learning, while leveraging the students' initial expertise to inform what knowledge to transfer. 
Inspired by this idea, this work explores how a teacher agent can efficiently utilize these knowledge priors to effectively improve the overall team's training by performing experience-based action advising for each student agent. 
We propose a novel teaching approach that leverages the teacher's policy to identify a student's pre-existing skill and subsequently assigns appropriate sub-tasks to each student based on a bandit formulation.
As a result, student teammates are assigned to and advised through sub-tasks that enable them to leverage their skills and thus improve overall task convergence.
We empirically evaluate our method on Grid World tasks with two and three agents, and in an Overcooked-AI task with three agents. 
Our method outperforms existing teacher-student approaches that do not consider prior knowledge, and achieves faster convergence than teaming without knowledge transfer, demonstrating that tailored action advising accelerates team learning and improves overall performance, particularly as student agents may have accrued prior experience in particular sub-tasks.
</p>

---
[Back to Research Page](/research/)