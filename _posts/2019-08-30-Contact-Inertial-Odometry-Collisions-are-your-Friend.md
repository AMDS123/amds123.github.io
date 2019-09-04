---
layout: post
title: "Contact Inertial Odometry: Collisions are your Friend"
date: 2019-08-30 22:09:45
categories: arXiv_RO
tags: arXiv_RO Drone
author: Thomas Lew, Tomoki Emmei, David D. Fan, Tara Bartlett, Angel Santamaria-Navarro, Rohan Thakker, Ali-akbar Agha-mohammadi
mathjax: true
---

* content
{:toc}

##### Abstract
Autonomous exploration of unknown environments with aerial vehicles remains a challenging problem, especially in perceptually degraded conditions. Dust, smoke, fog, and a lack of visual or LiDAR-based features result in severe difficulties for state estimation and planning. The absence of measurement updates from visual or LiDAR odometry can cause large drifts in velocity estimates while propagating measurements from an IMU. Furthermore, it is not possible to construct a map for collision checking in absence of pose updates. In this work, we show that it is indeed possible to navigate without any exteroceptive sensing by exploiting collisions instead of treating them as constraints. To this end, we first perform modeling and system identification for a hybrid ground and aerial vehicle which can withstand collisions. Next, we develop a novel external wrench estimation algorithm for this class of vehicles. We then present a novel contact-based inertial odometry (CIO) algorithm: it uses estimated external forces to detect collisions and to generate pseudo-measurements of the robot velocity, fused in an Extended Kalman Filter. Finally, we implement a reactive planner and control law which encourage exploration by bouncing off obstacles. We validate our framework in hardware experiments and show that a quadrotor can traverse a cluttered environment using an IMU only. This work can be used on drones to recover from visual inertial odometry failure or on micro-drones that do not have the payload capacity to carry cameras, LiDARs or powerful computers.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00079](http://arxiv.org/abs/1909.00079)

##### PDF
[http://arxiv.org/pdf/1909.00079](http://arxiv.org/pdf/1909.00079)

