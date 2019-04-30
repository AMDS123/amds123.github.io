---
layout: post
title: "Efficient Computation of Higher-Order Variational Integrators in Robotic Simulation and Trajectory Optimization"
date: 2019-04-29 14:53:32
categories: arXiv_RO
tags: arXiv_RO Knowledge Optimization
author: Taosha Fan, Jarvis Schultz, Todd Murphey
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of efficiently computing higher-order variational integrators in simulation and trajectory optimization of mechanical systems as those often found in robotic applications. We develop $O(n)$ algorithms to evaluate the discrete Euler-Lagrange (DEL) equations and compute the Newton direction for solving the DEL equations, which results in linear-time variational integrators of arbitrarily high order. To our knowledge, no linear-time higher-order variational or even implicit integrators have been developed before. Moreover, an $O(n^2)$ algorithm to linearize the DEL equations is presented, which is useful for trajectory optimization. These proposed algorithms eliminate the bottleneck of implementing higher-order variational integrators in simulation and trajectory optimization of complex robotic systems. The efficacy of this paper is validated through comparison with existing methods, and implementation on various robotic systems---including trajectory optimization of the Spring Flamingo robot, the LittleDog robot and the Atlas robot. The results illustrate that the same integrator can be used for simulation and trajectory optimization in robotics, preserving mechanical properties while achieving good scalability and accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.12756](http://arxiv.org/abs/1904.12756)

##### PDF
[http://arxiv.org/pdf/1904.12756](http://arxiv.org/pdf/1904.12756)

