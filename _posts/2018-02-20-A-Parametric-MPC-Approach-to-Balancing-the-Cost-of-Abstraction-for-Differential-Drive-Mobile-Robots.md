---
layout: post
title: "A Parametric MPC Approach to Balancing the Cost of Abstraction for Differential-Drive Mobile Robots"
date: 2018-02-20 16:58:09
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Paul Glotfelter, Magnus Egerstedt
mathjax: true
---

* content
{:toc}

##### Abstract
When designing control strategies for differential-drive mobile robots, one standard tool is the consideration of a point at a fixed distance along a line orthogonal to the wheel axis instead of the full pose of the vehicle. This abstraction supports replacing the non-holonomic, three-state unicycle model with a much simpler two-state single-integrator model (i.e., a velocity-controlled point). Yet this transformation comes at a performance cost, through the robot's precision and maneuverability. This work contains derivations for expressions of these precision and maneuverability costs in terms of the transformation's parameters. Furthermore, these costs show that only selecting the parameter once over the course of an application may cause an undue loss of precision. Model Predictive Control (MPC) represents one such method to ameliorate this condition. However, MPC typically realizes a control signal, rather than a parameter, so this work also proposes a Parametric Model Predictive Control (PMPC) method for parameter and sampling horizon optimization. Experimental results are presented that demonstrate the effects of the parameterization on the deployment of algorithms developed for the single-integrator model on actual differential-drive mobile robots.

##### Abstract (translated by Google)
在设计差速驱动移动机器人的控制策略时，一种标准工​​具是考虑沿着与车轮轴线正交的直线的固定距离处的点，而不是车辆的全部姿态。该抽象支持用非常简单的双状态单积分模型（即速度控制点）替代非完整的三态独轮车模型。然而，通过机器人的精确性和可操作性，这种转变的性能成本。这项工作包含了根据转换参数表达这些精度和可操作性成本的推导。此外，这些成本表明，只有在应用程序的过程中选择参数才会导致精确度的不必要的损失。模型预测控制（MPC）代表了一种改善这种情况的方法。然而，MPC通常实现控制信号而不是参数，所以本文还提出了参数模型预测控制（PMPC）方法，用于参数和采样时域优化。展示了实验结果，这些结果证明了参数化对于为实际差分驱动移动机器人上的单积分器模型开发的算法的部署的影响。

##### URL
[http://arxiv.org/abs/1802.07199](http://arxiv.org/abs/1802.07199)

##### PDF
[http://arxiv.org/pdf/1802.07199](http://arxiv.org/pdf/1802.07199)

