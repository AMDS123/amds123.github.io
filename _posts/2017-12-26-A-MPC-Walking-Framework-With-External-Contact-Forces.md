---
layout: post
title: "A MPC Walking Framework With External Contact Forces"
date: 2017-12-26 17:03:39
categories: arXiv_RO
tags: arXiv_RO Tracking Optimization
author: Sean Mason, Nicholas Rotella, Stefan Schaal, Ludovic Righetti
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we present an extension to a linear Model Predictive Control (MPC) scheme that plans external contact forces for the robot when given multiple contact locations and their corresponding friction cone. To accomplish this we set up a two step optimization problem. In the first optimization, we compute the Center of Mass (CoM) trajectory, foot step locations, and introduce slack variables to account for violating the imposed constraints on the Center of Pressure (CoP). We then use the slack variables to trigger the second optimization, in which we calculate the optimal external force that compensates for the CoP tracking error. This optimization considers multiple contacts with the environment by formulating the problem as a Mixed Integer Quadratic Program (MIQP) that can be solved at the order of 100 Hz. Once contact is created, the MIQP collapses to a single Quadratic Program (QP) that can be solved in real time $&lt;$ 1kHz. Simulations show that the presented control scheme can withstand disturbances 2-5x larger with the additional force provide by a hand contact when considering delays and 3-6x larger when contact is already made.

##### Abstract (translated by Google)
在这项工作中，我们提出了一个线性模型预测控制（MPC）方案的扩展，该方案计划给定多个接触位置及其相应摩擦圆锥的机器人的外部接触力。为了做到这一点，我们建立了一个两步优化问题。在第一次优化中，我们计算质量中心（CoM）轨迹，脚步位置，并引入松弛变量来解释违反压力中心（CoP）施加的约束。然后我们使用松弛变量触发第二次优化，其中我们计算补偿CoP跟踪误差的最佳外力。这种优化考虑到与环境的多个接触，通过将问题公式化为混合整数二次程序（MIQP），其可以在100Hz的数量级解决。一旦建立联系，MIQP就会崩溃到可以实时解决的单个二次程序（QP）$ <1kHz。仿真表明，所提出的控制方案能够承受比考虑延迟时由手接触提供的附加力大2-5倍的干扰，而在已经接触时可以承受3-6倍的更大的干扰。

##### URL
[http://arxiv.org/abs/1712.09308](http://arxiv.org/abs/1712.09308)

##### PDF
[http://arxiv.org/pdf/1712.09308](http://arxiv.org/pdf/1712.09308)

