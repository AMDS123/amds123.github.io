---
layout: post
title: "Jerk Control of Floating Base Systems with Contact-Stable Parametrised Force Feedback"
date: 2019-07-27 13:28:04
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Ahmad Gazar, Gabriele Nava, Francisco Javier Andrade Chavez, Daniele Pucci
mathjax: true
---

* content
{:toc}

##### Abstract
Nonlinear controllers for floating base systems in contact with the environment are often framed as quadratic programming (QP) optimization problems. Common drawbacks of such QP based controllers are: the friction cone constraints are approximated with a set of linear inequalities; the control input often experiences discontinuities; no force feedback from Force/Torque (FT) sensors installed on the robot is taken into account. This paper attempts at addressing these limitations through the design of jerk controllers. These controllers assume the rate-of-change of the joint torques as control input, and exploit the system position, velocity, accelerations, and contact wrenches as measurable quantities. The key ingredient of the presented approach is a one-to-one correspondence between free variables and the manifold defined by the contact stability constraints. This parametrisation allows us to transform the underlying constrained optimisation problems into one that is unconstrained. Then, we propose a jerk control framework that exploits the proposed parametrisation and uses FT measurements in the control loop. Furthermore, we present Lyapunov stable controllers for the system momentum in the jerk control framework. The approach is validated with simulations and experiments using the iCub humanoid robot.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.11906](http://arxiv.org/abs/1907.11906)

##### PDF
[http://arxiv.org/pdf/1907.11906](http://arxiv.org/pdf/1907.11906)

