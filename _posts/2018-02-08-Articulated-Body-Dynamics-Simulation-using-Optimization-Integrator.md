---
layout: post
title: "Articulated Body Dynamics Simulation using Optimization Integrator"
date: 2018-02-08 22:10:55
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Zherong Pan, Dinesh Manocha
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel optimization-based algorithm for articulated body dynamics simulation. We formulate the governing equations of rigid body dynamics using only the position variables and recast the position-based articulated dynamics as an optimization problem. We also extend our framework to handle joint limits, control forces/torques, fluid drag forces, and frictional contact forces. Our reformulation allows us to use an off-the-shelf optimization algorithm to time integrate the articulated body with an arbitrarily large timestep size and analyze the stability. Our algorithm can efficiently perform each iteration of optimization within $\mathcal{O}(N)$ time using Quasi-Newton method and $\mathcal{O}(N^2)$ time using Newton's method, where $N$ is the number of links. We highlight the performance on different benchmarks and compare the performance with prior articulated body dynamics simulators.

##### Abstract (translated by Google)
我们提出了一种新颖的基于优化的算法用于铰接人体动力学仿真。我们仅使用位置变量来制定刚体动力学的控制方程，并将基于位置的铰接动力学重新设计为优化问题。我们还扩展我们的框架来处理关节限制，控制力/扭矩，流体阻力和摩擦接触力。我们的重新配置允许我们使用现成的优化算法来将关节的物体与任意大的时间步长整合，并分析稳定性。我们的算法可以使用牛顿法和$ \ mathcal {O}（N ^ 2）$ time在Newton方法中有效执行$ \ mathcal {O}（N）$ time中的每次优化迭代，其中$ N $是链接数量。我们强调不同基准下的性能，并将性能与以前的铰接式车身动力学仿真器进行比较。

##### URL
[http://arxiv.org/abs/1709.04145](http://arxiv.org/abs/1709.04145)

##### PDF
[http://arxiv.org/pdf/1709.04145](http://arxiv.org/pdf/1709.04145)

