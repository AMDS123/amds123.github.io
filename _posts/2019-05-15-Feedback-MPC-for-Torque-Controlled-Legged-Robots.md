---
layout: post
title: "Feedback MPC for Torque-Controlled Legged Robots"
date: 2019-05-15 12:50:37
categories: arXiv_RO
tags: arXiv_RO Tracking
author: Ruben Grandia, Farbod Farshidian, Ren&#xe9; Ranftl, Marco Hutter
mathjax: true
---

* content
{:toc}

##### Abstract
The computational power of mobile robots is currently insufficient to achieve torque level whole-body Model Predictive Control (MPC) at the update rates required for complex dynamic systems such as legged robots. This problem is commonly circumvented by using a fast tracking controller to compensate for model errors between updates. In this work, we show that the feedback policy from a Differential Dynamic Programming (DDP) based MPC algorithm is a viable alternative to bridge the gap between the low MPC update rate and the actuation command rate. We propose to augment the DDP approach with a relaxed barrier function to address inequality constraints arising from the friction cone. A frequency-dependent cost function is used to reduce the sensitivity to high-frequency model errors and actuator bandwidth limits. We demonstrate that our approach can find stable locomotion policies for the torque-controlled quadruped, ANYmal, both in simulation and on hardware.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.06144](http://arxiv.org/abs/1905.06144)

##### PDF
[http://arxiv.org/pdf/1905.06144](http://arxiv.org/pdf/1905.06144)

