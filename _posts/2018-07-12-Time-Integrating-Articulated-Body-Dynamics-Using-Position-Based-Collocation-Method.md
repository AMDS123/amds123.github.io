---
layout: post
title: "Time Integrating Articulated Body Dynamics Using Position-Based Collocation Method"
date: 2018-07-12 21:11:59
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Zherong Pan, Dinesh Manocha
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new time integrator for articulated body dynamics. We formulate the governing equations of the dynamics using only the position variables and recast the position-based articulated dynamics as an optimization problem. Our reformulation allows us to integrate the dynamics in a fully implicit manner without computing high-order derivatives. Therefore, under arbitrarily large timestep sizes, the stability of our time integration scheme is guaranteed using an off-the-shelf numerical optimizer. In addition to stability, we show that, similar to the Runge-Kutta method, the accuracy of our time integrator can also be increased arbitrarily by using a high-order collocation method. We provide efficient algorithms to perform time integration using our position-based formulation. We show that each iteration of optimization has a complexity of O(N) using Quasi-Newton method or O(N^2) using Newton's method, where N is the number of links. Finally, our method is highly parallelizable and can be accelerated using a Graphics Processing Unit (GPU). We highlight the efficiency and stability of our method on different benchmarks and compare the performance with prior articulated body dynamics simulation methods based on the Newton-Euler's equation. Our method is stable under a timestep size as large as 0.1s. Using a larger timestep size and less timesteps, our method achieves up to 4 times speedup on a single-core CPU. With GPU acceleration, we observe an additional 3-6 times speedup over a 4-core CPU.

##### Abstract (translated by Google)
我们提出了一种新的关节体动力学时间积分器。我们仅使用位置变量来表示动力学的控制方程，并将基于位置的关节动力学重新设计为优化问题。我们的重构使我们能够以完全隐式的方式整合动态，而无需计算高阶导数。因此，在任意大的时间步长下，使用现成的数值优化器可以保证时间积分方案的稳定性。除了稳定性之外，我们还表明，与Runge-Kutta方法类似，我们的时间积分器的精度也可以通过使用高阶配置方法任意增加。我们使用基于位置的公式提供有效的算法来执行时间积分。我们证明了每次迭代的优化都使用Quasi-Newton方法的O（N）或使用Newton方法的O（N ^ 2），其中N是链​​接数。最后，我们的方法是高度可并行化的，可以使用图形处理单元（GPU）加速。我们强调了我们的方法在不同基准测试中的效率和稳定性，并将性能与基于牛顿 - 欧拉方程的先前铰接式人体动力学模拟方法进行了比较。我们的方法在0.1s的时间尺寸下是稳定的。使用更大的时间步长和更少的时间步长，我们的方法在单核CPU上实现了高达4倍的加速。通过GPU加速，我们观察到比4核CPU多出3-6倍的加速。

##### URL
[http://arxiv.org/abs/1709.04145](http://arxiv.org/abs/1709.04145)

##### PDF
[http://arxiv.org/pdf/1709.04145](http://arxiv.org/pdf/1709.04145)

