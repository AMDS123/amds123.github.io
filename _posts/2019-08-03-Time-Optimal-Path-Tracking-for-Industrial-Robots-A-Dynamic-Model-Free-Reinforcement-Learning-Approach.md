---
layout: post
title: "Time-Optimal Path Tracking for Industrial Robots: A Dynamic Model-Free Reinforcement Learning Approach"
date: 2019-08-03 02:20:51
categories: arXiv_RO
tags: arXiv_RO Tracking Reinforcement_Learning
author: Jiadong Xiao, Lin Li, Tie Zhang, Yanbiao Zou
mathjax: true
---

* content
{:toc}

##### Abstract
In pursuit of the time-optimal path tracking (TOPT) trajectory of a robot manipulator along a preset path, a beforehand identified robot dynamic model is usually used to obtain the required optimal trajectory for perfect tracking. However, due to the inevitable model-plant mismatch, there may be a big error between the actually measured torques and the calculated torques by the dynamic model, which causes the obtained trajectory to be suboptimal or even be infeasible by exceeding given limits. This paper presents a TOPT-oriented SARSA algorithm (TOPTO-SARSA) and a two-step method for finding the time-optimal motion and ensuring the feasibility : Firstly, using TOPTO-SARSA to find a safe trajectory that satisfies the kinematic constraints through the interaction between reinforcement learning agent and kinematic model. Secondly, using TOPTO-SARSA to find the optimal trajectory through the interaction between the agent and the real world, and assure the actually measured torques satisfy the given limits at the last interaction. The effectiveness of the proposed algorithm has been verified through experiments on a 6-DOF robot manipulator.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.01348](http://arxiv.org/abs/1907.01348)

##### PDF
[http://arxiv.org/pdf/1907.01348](http://arxiv.org/pdf/1907.01348)

