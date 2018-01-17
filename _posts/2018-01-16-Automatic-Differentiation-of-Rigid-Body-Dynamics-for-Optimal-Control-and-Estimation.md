---
layout: post
title: "Automatic Differentiation of Rigid Body Dynamics for Optimal Control and Estimation"
date: 2018-01-16 10:44:39
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Markus Giftthaler, Michael Neunert, Markus St&#xe4;uble, Marco Frigerio, Claudio Semini, Jonas Buchli
mathjax: true
---

* content
{:toc}

##### Abstract
Many algorithms for control, optimization and estimation in robotics depend on derivatives of the underlying system dynamics, e.g. to compute linearizations, sensitivities or gradient directions. However, we show that when dealing with Rigid Body Dynamics, these derivatives are difficult to derive analytically and to implement efficiently. To overcome this issue, we extend the modelling tool `RobCoGen' to be compatible with Automatic Differentiation. Additionally, we propose how to automatically obtain the derivatives and generate highly efficient source code. We highlight the flexibility and performance of the approach in two application examples. First, we show a Trajectory Optimization example for the quadrupedal robot HyQ, which employs auto-differentiation on the dynamics including a contact model. Second, we present a hardware experiment in which a 6 DoF robotic arm avoids a randomly moving obstacle in a go-to task by fast, dynamic replanning.

##### Abstract (translated by Google)
用于机器人中的控制，优化和估计的许多算法取决于底层系统动态的导数，例如，计算线性化，灵敏度或梯度方向。然而，我们表明，当处理刚体动力学时，这些衍生物很难得到分析和有效实施。为了克服这个问题，我们扩展了建模工具“RobCoGen”以与自动微分兼容。此外，我们还提出了如何自动获得衍生品并生成高效的源代码。我们在两个应用实例中强调了这种方法的灵活性和性能。首先，我们展示了四足机器人HyQ的一个轨迹优化实例，该实例使用包括接触模型在内的动态自动微分。其次，我们展示了一个硬件实验，其中6个DoF机器人手臂通过快速，动态的重新规划避开了随意移动的障碍。

##### URL
[http://arxiv.org/abs/1709.03799](http://arxiv.org/abs/1709.03799)

##### PDF
[http://arxiv.org/pdf/1709.03799](http://arxiv.org/pdf/1709.03799)

