---
layout: post
title: "Sim-to-Real Transfer for Biped Locomotion"
date: 2019-03-04 17:37:43
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Wenhao Yu, Visak CV Kumar, Greg Turk, C. Karen Liu
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new approach for transfer of dynamic robot control policies such as biped locomotion from simulation to real hardware. Key to our approach is to perform system identification of the model parameters {\mu} of the hardware (e.g. friction, center-of-mass) in two distinct stages, before policy learning (pre-sysID) and after policy learning (post-sysID). Pre-sysID begins by collecting trajectories from the physical hardware based on a set of generic motion sequences. Because the trajectories may not be related to the task of interest, presysID does not attempt to accurately identify the true value of {\mu}, but only to approximate the range of {\mu} to guide the policy learning. Next, a Projected Universal Policy (PUP) is created by simultaneously training a network that projects {\mu} to a low-dimensional latent variable {\eta} and a family of policies that are conditioned on {\eta}. The second round of system identification (post-sysID) is then carried out by deploying the PUP on the robot hardware using task-relevant trajectories. We use Bayesian Optimization to determine the values for {\eta} that optimizes the performance of PUP on the real hardware. We have used this approach to create three successful biped locomotion controllers (walk forward, walk backwards, walk sideways) on the Darwin OP2 robot.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.01390](http://arxiv.org/abs/1903.01390)

##### PDF
[http://arxiv.org/pdf/1903.01390](http://arxiv.org/pdf/1903.01390)

