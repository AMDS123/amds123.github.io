---
layout: post
title: "Biconvex Relaxation for Semidefinite Programming in Computer Vision"
date: 2016-08-08 23:23:28
categories: arXiv_CV
tags: arXiv_CV Segmentation Optimization
author: Sohil Shah, Abhay Kumar, Carlos Castillo, David Jacobs, Christoph Studer, Tom Goldstein
mathjax: true
---

* content
{:toc}

##### Abstract
Semidefinite programming is an indispensable tool in computer vision, but general-purpose solvers for semidefinite programs are often too slow and memory intensive for large-scale problems. We propose a general framework to approximately solve large-scale semidefinite problems (SDPs) at low complexity. Our approach, referred to as biconvex relaxation (BCR), transforms a general SDP into a specific biconvex optimization problem, which can then be solved in the original, low-dimensional variable space at low complexity. The resulting biconvex problem is solved using an efficient alternating minimization (AM) procedure. Since AM has the potential to get stuck in local minima, we propose a general initialization scheme that enables BCR to start close to a global optimum - this is key for our algorithm to quickly converge to optimal or near-optimal solutions. We showcase the efficacy of our approach on three applications in computer vision, namely segmentation, co-segmentation, and manifold metric learning. BCR achieves solution quality comparable to state-of-the-art SDP methods with speedups between 4X and 35X. At the same time, BCR handles a more general set of SDPs than previous approaches, which are more specialized.

##### Abstract (translated by Google)
半定规划是计算机视觉中不可或缺的工具，但是对于半定规划的通用求解器往往太慢，需要大量的内存来解决大规模的问题。我们提出了一个通用框架来近似求解低复杂度的大规模半定规划问题（SDP）。我们的方法被称为双凸松弛（BCR），将一般的SDP转换成一个特定的双凸优化问题，然后可以在低复杂度的原始低维变量空间中求解。使用有效的交替最小化（AM）程序来解决所得到的双凸问题。由于AM有可能陷入局部极小值，所以我们提出了一个通用的初始化方案，使BCR能够接近全局最优 - 这对于我们的算法能够快速收敛到最优或者接近最优的解决方案至关重要。我们展示了我们的方法在计算机视觉中的三个应用，即分割，协同分割和流形度量学习的功效。 BCR实现了与最先进的SDP方法相媲美的解决方案质量，速度在4X和35X之间。与此同时，BCR比之前更专业的方法处理更一般的SDP集合。

##### URL
[https://arxiv.org/abs/1605.09527](https://arxiv.org/abs/1605.09527)

##### PDF
[https://arxiv.org/pdf/1605.09527](https://arxiv.org/pdf/1605.09527)

