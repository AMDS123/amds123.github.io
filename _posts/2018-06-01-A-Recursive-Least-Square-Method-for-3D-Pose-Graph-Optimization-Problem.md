---
layout: post
title: "A Recursive Least Square Method for 3D Pose Graph Optimization Problem"
date: 2018-06-01 10:52:39
categories: arXiv_RO
tags: arXiv_RO Optimization SLAM
author: S.M. Nasiri, Reshad Hosseini, Hadi Moradi
mathjax: true
---

* content
{:toc}

##### Abstract
Pose Graph Optimization (PGO) is an important non-convex optimization problem and is the state-of-the-art formulation for SLAM in robotics. It also has applications like camera motion estimation, structure from motion and 3D reconstruction in machine vision. Recent researches have shown the importance of good initialization to bootstrap well-known iterative PGO solvers to converge to good solutions. The state-of-the-art initialization methods, however, works in low noise or eventually moderate noise problems, and they fail in challenging problems with high measurement noise. Consequently, iterative methods may get entangled in local minima in high noise scenarios. In this paper we present an initialization method which uses orientation measurements and then present a convergence analysis of our iterative algorithm. We show how the algorithm converges to global optima in noise-free cases and also obtain a bound for the difference between our result and the optimum solution in scenarios with noisy measurements. We then present our second algorithm that uses both relative orientation and position measurements to obtain a more accurate least squares approximation of the problem that is again solved iteratively. In the convergence proof, a structural coefficient arises that has important influence on the basin of convergence. Interestingly, simulation results show that this coefficient also affects the performance of other solvers and so it can indicate the complexity of the problem. Experimental results show the excellent performance of the proposed initialization algorithm, specially in high noise scenarios.

##### Abstract (translated by Google)
姿态图优化（PGO）是一个重要的非凸优化问题，并且是机器人技术中最先进的SLAM公式。它还具有相机运动估计，运动结构和机器视觉三维重建等应用。最近的研究表明，良好的初始化对引导着名的迭代PGO求解器收敛到良好解决方案非常重要。然而，最先进的初始化方法在低噪声或最终适度噪声问题中起作用，并且它们在高测量噪声的挑战性问题上失败。因此，在高噪声情况下，迭代方法可能会纠缠在局部最小值。在本文中，我们提出了一种初始化方法，它使用方位测量，然后对我们的迭代算法进行收敛分析。我们展示了该算法如何在无噪声情况下收敛到全局最优解，并且还获得了我们的结果与具有噪声测量的情况下的最优解之间差异的界限。然后，我们介绍我们的第二种算法，它使用相对方向和位置测量来获得迭代求解的更精确的最小二乘逼近问题。在收敛性证明中，出现了对收敛盆地有重要影响的结构系数。有趣的是，仿真结果表明，这个系数也影响其他解算器的性能，因此它可以指示问题的复杂性。实验结果表明了所提出的初始化算法的出色性能，特别是在高噪声情况下。

##### URL
[http://arxiv.org/abs/1806.00281](http://arxiv.org/abs/1806.00281)

##### PDF
[http://arxiv.org/pdf/1806.00281](http://arxiv.org/pdf/1806.00281)

