---
layout: post
title: "Trajectory Tracking for Quadrotors with Attitude Control on $mathcal{S}^2 times mathcal{S}^1$"
date: 2019-06-17 09:59:53
categories: arXiv_RO
tags: arXiv_RO Tracking
author: Dave Kooijman, Angela P. Schoellig, Duarte J. Antunes
mathjax: true
---

* content
{:toc}

##### Abstract
The control of a quadrotor is typically split into two subsequent problems: finding desired accelerations to control its position, and controlling its attitude and the total thrust to track these accelerations and to track a yaw angle reference. While the thrust vector, generating accelerations, and the angle of rotation about the thrust vector, determining the yaw angle, can be controlled independently, most attitude control strategies in the literature, relying on representations in terms of quaternions, rotation matrices or Euler angles, result in an unnecessary coupling between the control of the thrust vector and of the angle about this vector. This leads, for instance, to undesired position tracking errors due to yaw tracking errors. In this paper we propose to tackle the attitude control problem using an attitude representation in the Cartesian product of the 2-sphere and the 1-sphere, denoted by $\mathcal{S}^2\times \mathcal{S}^1$. We propose a non-linear tracking control law on $\mathcal{S}^2\times \mathcal{S}^1$ that decouples the control of the thrust vector and of the angle of rotation about the thrust vector, and guarantees almost global asymptotic stability. Simulation results highlight the advantages of the proposed approach over previous approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.06926](http://arxiv.org/abs/1906.06926)

##### PDF
[http://arxiv.org/pdf/1906.06926](http://arxiv.org/pdf/1906.06926)

