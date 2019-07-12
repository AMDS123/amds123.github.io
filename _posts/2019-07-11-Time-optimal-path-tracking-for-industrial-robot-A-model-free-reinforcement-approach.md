---
layout: post
title: "Time-optimal path tracking for industrial robot: A model-free reinforcement approach"
date: 2019-07-11 12:10:52
categories: arXiv_RO
tags: arXiv_RO Tracking
author: Jiadong Xiao, Lin Li, Tie Zhang, Yanbiao Zou
mathjax: true
---

* content
{:toc}

##### Abstract
In pursuit of the time-optimal motion of a robot manipulator along a preset path, a previously identified dynamic model is typically used to calculate the required optimal trajectory for perfect tracking. However, due to the inevitable model-plant mismatch, there may be a big error between the calculated torque of the planned trajectory and the actually measured torque, which causes the obtained trajectory to be suboptimal or even be infeasible by exceeding given limits. This paper presents a two-step improved SARSA approach for finding the time-optimal motion and ensuring the feasibility. Firstly, using the improved SARSA algorithm to find a safe trajectory that satisfies the kinematic constraints through the interaction between reinforcement agent and kinematic model. Secondly, using the improved SARSA algorithm to find the optimal trajectory that the actually measured torque satisfied the given constraints through the interaction between the agent and the real world. Simulations and experiments on a 6-DOF robot manipulator verify the effectiveness of the proposed algorithm.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.01348](http://arxiv.org/abs/1907.01348)

##### PDF
[http://arxiv.org/pdf/1907.01348](http://arxiv.org/pdf/1907.01348)

