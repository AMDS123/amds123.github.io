---
layout: post
title: "Certifiably Globally Optimal Extrinsic Calibration from Per-Sensor Egomotion"
date: 2018-09-10 19:13:01
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Matthew Giamou, Ziye Ma, Valentin Peretroukhin, Jonathan Kelly
mathjax: true
---

* content
{:toc}

##### Abstract
We present a certifiably globally optimal algorithm for determining the extrinsic calibration between two sensors that are capable of producing independent egomotion estimates. This problem has been previously solved using a variety of techniques, including local optimization approaches that have no formal global optimality guarantees. We use a quadratic objective function to formulate calibration as a quadratically constrained quadratic program (QCQP). By leveraging recent advances in the optimization of QCQPs, we are able to use existing semidefinite program (SDP) solvers to obtain a certifiably global optimum via the Lagrangian dual problem. Our problem formulation can be globally optimized by existing general-purpose solvers in less than a second, regardless of the number of measurements available and the noise level. This enables a variety of robotic platforms to rapidly and robustly compute and certify a globally optimal set of calibration parameters without a prior estimate or operator intervention. We compare the performance of our approach with a local solver on extensive simulations and a real dataset. Finally, we present necessary observability conditions that connect our approach to recent theoretical results and analytically support the empirical performance of our system.

##### Abstract (translated by Google)
我们提出了一种可认证的全局最优算法，用于确定能够产生独立运动估计的两个传感器之间的外部校准。先前已经使用各种技术解决了该问题，包括没有正式全局最优性保证的局部优化方法。我们使用二次目标函数将校准公式化为二次约束二次规划（QCQP）。通过利用QCQP优化的最新进展，我们能够使用现有的半定规划（SDP）求解器通过拉格朗日对偶问题获得可证明的全局最优。无论可用的测量数量和噪声水平如何，我们的问题公式都可以在不到一秒的时间内通过现有的通用求解器进行全局优化。这使得各种机器人平台能够快速且稳健地计算和认证全局最佳校准参数集，而无需事先估计或操作员干预。我们在广泛的模拟和真实的数据集上比较了我们的方法与局部求解器的性能。最后，我们提出了必要的可观察性条件，将我们的方法与最近的理论结果联系起来，并在分析上支持我们系统的经验性能。

##### URL
[http://arxiv.org/abs/1809.03554](http://arxiv.org/abs/1809.03554)

##### PDF
[http://arxiv.org/pdf/1809.03554](http://arxiv.org/pdf/1809.03554)

