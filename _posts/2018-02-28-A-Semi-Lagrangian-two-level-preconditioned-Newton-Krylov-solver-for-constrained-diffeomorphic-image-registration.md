---
layout: post
title: "A Semi-Lagrangian two-level preconditioned Newton-Krylov solver for constrained diffeomorphic image registration"
date: 2018-02-28 20:16:09
categories: arXiv_CV
tags: arXiv_CV
author: Andreas Mang, George Biros
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an efficient numerical algorithm for the solution of diffeomorphic image registration problems. We use a variational formulation constrained by a partial differential equation (PDE), where the constraints are a scalar transport equation. 
 We use a pseudospectral discretization in space and second-order accurate semi-Lagrangian time stepping scheme for the transport equations. We solve for a stationary velocity field using a preconditioned, globalized, matrix-free Newton-Krylov scheme. We propose and test a two-level Hessian preconditioner. We consider two strategies for inverting the preconditioner on the coarse grid: a nested preconditioned conjugate gradient method (exact solve) and a nested Chebyshev iterative method (inexact solve) with a fixed number of iterations. 
 We test the performance of our solver in different synthetic and real-world two-dimensional application scenarios. We study grid convergence and computational efficiency of our new scheme. We compare the performance of our solver against our initial implementation that uses the same spatial discretization but a standard, explicit, second-order Runge-Kutta scheme for the numerical time integration of the transport equations and a single-level preconditioner. Our improved scheme delivers significant speedups over our original implementation. As a highlight, we observe a 20$\times$ speedup for a two dimensional, real world multi-subject medical image registration problem.

##### Abstract (translated by Google)
我们提出了一种求解微分同胚图像配准问题的高效数值算法。我们使用由偏微分方程（PDE）约束的变分公式，其中约束是标量输运方程。
 我们使用空间伪谱离散化和运输方程的二阶准确半拉格朗日时间步进方案。我们使用预条件的全球化的无矩阵Newton-Krylov方案求解一个平稳速度场。我们提出并测试一个两级Hessian预处理器。我们考虑在粗网格上反演预处理器的两种策略：嵌套预处理共轭梯度法（精确求解）和嵌套Chebyshev迭代法（不精确求解），并且具有固定次数的迭代。
 我们在不同的合成和现实世界的二维应用场景中测试解算器的性能。我们研究了我们新方案的网格收敛和计算效率。我们将求解器的性能与我们初始实现的性能进行了比较，该算法使用相同的空间离散化，但使用标准的显式二阶龙格库塔方案对输运方程和单级预处理器进行数值时间积分。我们的改进方案在原始实施方面提供了显着的加速。作为一个亮点，我们观察到二维，现实世界多主体医学图像配准问题的20美元/倍加速。

##### URL
[http://arxiv.org/abs/1604.02153](http://arxiv.org/abs/1604.02153)

##### PDF
[http://arxiv.org/pdf/1604.02153](http://arxiv.org/pdf/1604.02153)

