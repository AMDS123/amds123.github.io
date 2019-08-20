---
layout: post
title: "Inverse Kinematics with Forward Dynamics Solvers for Sampled Motion Tracking"
date: 2019-08-17 07:08:54
categories: arXiv_RO
tags: arXiv_RO Tracking
author: Stefan Scherzinger, Arne Roennau, R&#xfc;diger Dillmann
mathjax: true
---

* content
{:toc}

##### Abstract
Tracking Cartesian trajectories with end-effectors is a fundamental task in robot control. For motion that is not known a priori, the solvers must find fast solutions to the inverse kinematics (IK) problem for discretely sampled target poses. On joint control level, however, the robot's actuators operate in a continuous domain, requiring smooth transitions between individual states. In this work we present a boost to the well-known Jacobian transpose method to address this goal, using the mass matrix of a virtually conditioned twin of the manipulator. Results on the UR10 show superior convergence and quality of our dynamics-based solver against the plain Jacobian method. Our algorithm is straightforward to implement as a controller, using present robotics libraries.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.06252](http://arxiv.org/abs/1908.06252)

##### PDF
[http://arxiv.org/pdf/1908.06252](http://arxiv.org/pdf/1908.06252)

