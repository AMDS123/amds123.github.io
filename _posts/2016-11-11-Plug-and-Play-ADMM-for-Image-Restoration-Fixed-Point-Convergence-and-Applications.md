---
layout: post
title: "Plug-and-Play ADMM for Image Restoration: Fixed Point Convergence and Applications"
date: 2016-11-11 18:12:48
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Optimization
author: Stanley H. Chan, Xiran Wang, Omar A. Elgendy
mathjax: true
---

* content
{:toc}

##### Abstract
Alternating direction method of multiplier (ADMM) is a widely used algorithm for solving constrained optimization problems in image restoration. Among many useful features, one critical feature of the ADMM algorithm is its modular structure which allows one to plug in any off-the-shelf image denoising algorithm for a subproblem in the ADMM algorithm. Because of the plug-in nature, this type of ADMM algorithms is coined the name "Plug-and-Play ADMM". Plug-and-Play ADMM has demonstrated promising empirical results in a number of recent papers. However, it is unclear under what conditions and by using what denoising algorithms would it guarantee convergence. Also, since Plug-and-Play ADMM uses a specific way to split the variables, it is unclear if fast implementation can be made for common Gaussian and Poissonian image restoration problems. In this paper, we propose a Plug-and-Play ADMM algorithm with provable fixed point convergence. We show that for any denoising algorithm satisfying an asymptotic criteria, called bounded denoisers, Plug-and-Play ADMM converges to a fixed point under a continuation scheme. We also present fast implementations for two image restoration problems on super-resolution and single-photon imaging. We compare Plug-and-Play ADMM with state-of-the-art algorithms in each problem type, and demonstrate promising experimental results of the algorithm.

##### Abstract (translated by Google)
乘法器的交替方向法（ADMM）是一种用于解决图像恢复中的约束优化问题的广泛使用的算法。在许多有用的功能中，ADMM算法的一个关键特征是它的模块化结构，允许在ADMM算法中插入任何现成的图像去噪算法来处理子问题。由于插入特性，这种类型的ADMM算法被命名为“即插即用ADMM”。即插即用的ADMM在最近的一些论文中展示了有前景的实证结果。但是，在什么条件下，通过使用什么样的去噪算法来保证收敛还不清楚。另外，由于即插即用ADMM使用特定的方式来分割变量，因此对于普通的高斯和泊松图像恢复问题是否能够快速实现尚不清楚。在本文中，我们提出了一个可证明的不动点收敛的即插即用ADMM算法。我们证明，对于任何满足渐近标准的去噪算法，称为有界denoisers，即插即用的ADMM收敛到一个固定点下的延续计划。我们还介绍了超分辨率和单光子成像的两个图像恢复问题的快速实现。我们比较了即插即用ADMM和每种问题类型中最先进的算法，并证明了该算法的有前景的实验结果。

##### URL
[https://arxiv.org/abs/1605.01710](https://arxiv.org/abs/1605.01710)

##### PDF
[https://arxiv.org/pdf/1605.01710](https://arxiv.org/pdf/1605.01710)

