---
layout: post
title: "An MPC Walking Framework With External Contact Forces"
date: 2018-02-27 20:14:46
categories: arXiv_RO
tags: arXiv_RO Tracking Optimization
author: Sean Mason, Nicholas Rotella, Stefan Schaal, Ludovic Righetti
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we present an extension to a linear Model Predictive Control (MPC) scheme that plans external contact forces for the robot when given multiple contact locations and their corresponding friction cone. To this end, we set up a two-step optimization problem. In the first optimization, we compute the Center of Mass (CoM) trajectory, foot step locations, and introduce slack variables to account for violating the imposed constraints on the Zero Moment Point (ZMP). We then use the slack variables to trigger the second optimization, in which we calculate the optimal external force that compensates for the ZMP tracking error. This optimization considers multiple contacts positions within the environment by formulating the problem as a Mixed Integer Quadratic Program (MIQP) that can be solved at a speed between 100-300 Hz. Once contact is created, the MIQP reduces to a single Quadratic Program (QP) that can be solved in real-time ($&lt;$ 1kHz). Simulations show that the presented walking control scheme can withstand disturbances 2-3x larger with the additional force provided by a hand contact.

##### Abstract (translated by Google)
在这项工作中，我们提出了一个线性模型预测控制（MPC）方案的扩展，该方案计划给定多个接触位置及其相应的摩擦锥时机器人的外部接触力。为此，我们建立了一个两步优化问题。在第一次优化中，我们计算质量中心（CoM）轨迹，脚步位置，并引入松弛变量来说明违反零点矩（ZMP）施加的约束。然后我们使用松弛变量来触发第二次优化，其中我们计算补偿ZMP跟踪误差的最佳外力。该优化考虑了环境中的多个触点位置，将问题表达为混合整数二次程序（MIQP），可以在100-300 Hz之间的速度下解决该问题。一旦建立联系，MIQP就会减少到一个可以实时解决的单个二次程序（QP）（$ <1kHz）。仿真表明，所提出的步行控制方案能够承受由手接触提供的附加力的2-3倍的干扰。

##### URL
[http://arxiv.org/abs/1712.09308](http://arxiv.org/abs/1712.09308)

##### PDF
[http://arxiv.org/pdf/1712.09308](http://arxiv.org/pdf/1712.09308)

