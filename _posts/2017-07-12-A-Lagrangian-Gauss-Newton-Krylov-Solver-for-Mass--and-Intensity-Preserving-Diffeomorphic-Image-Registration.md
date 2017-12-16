---
layout: post
title: "A Lagrangian Gauss-Newton-Krylov Solver for Mass- and Intensity-Preserving Diffeomorphic Image Registration"
date: 2017-07-12 11:04:29
categories: arXiv_CV
tags: arXiv_CV Regularization Optimization
author: Andreas Mang, Lars Ruthotto
mathjax: true
---

* content
{:toc}

##### Abstract
We present an efficient solver for diffeomorphic image registration problems in the framework of Large Deformations Diffeomorphic Metric Mappings (LDDMM). We use an optimal control formulation, in which the velocity field of a hyperbolic PDE needs to be found such that the distance between the final state of the system (the transformed/transported template image) and the observation (the reference image) is minimized. Our solver supports both stationary and non-stationary (i.e., transient or time-dependent) velocity fields. As transformation models, we consider both the transport equation (assuming intensities are preserved during the deformation) and the continuity equation (assuming mass-preservation). We consider the reduced form of the optimal control problem and solve the resulting unconstrained optimization problem using a discretize-then-optimize approach. A key contribution is the elimination of the PDE constraint using a Lagrangian hyperbolic PDE solver. Lagrangian methods rely on the concept of characteristic curves that we approximate here using a fourth-order Runge-Kutta method. We also present an efficient algorithm for computing the derivatives of final state of the system with respect to the velocity field. This allows us to use fast Gauss-Newton based methods. We present quickly converging iterative linear solvers using spectral preconditioners that render the overall optimization efficient and scalable. Our method is embedded into the image registration framework FAIR and, thus, supports the most commonly used similarity measures and regularization functionals. We demonstrate the potential of our new approach using several synthetic and real world test problems with up to 14.7 million degrees of freedom.

##### Abstract (translated by Google)
我们提出了一个有效的求解大型变形差分度量映射（LDDMM）框架中的微分同胚图像配准问题。我们使用最优控制公式，其中双曲线PDE的速度场需要被找到，使得系统的最终状态（转换/运输的模板图像）和观察（参考图像）之间的距离被最小化。我们的求解器支持固定和非固定（即瞬态或时间相关）速度场。作为转换模型，我们考虑运输方程（假设在变形过程中保留强度）和连续性方程（假设质量保存）。我们考虑最优控制问题的简化形式，并使用离散 - 然后优化方法来解决由此产生的无约束优化问题。关键的贡献是使用拉格朗日双曲线PDE解算器消除PDE约束。拉格朗日方法依赖于我们使用四阶Runge-Kutta方法近似的特性曲线的概念。我们还提出了一个有效的算法来计算相对于速度场的系统的最终状态的导数。这使我们能够使用基于高斯 - 牛顿的快速方法。我们提出使用光谱预处理器快速收敛迭代线性求解器，使整体优化高效和可扩展。我们的方法被嵌入到图像配准框架FAIR中，从而支持最常用的相似性度量和正则化函数。我们使用多达1470万个自由度的合成和真实世界测试问题展示了我们新方法的潜力。

##### URL
[https://arxiv.org/abs/1703.04446](https://arxiv.org/abs/1703.04446)

##### PDF
[https://arxiv.org/pdf/1703.04446](https://arxiv.org/pdf/1703.04446)

