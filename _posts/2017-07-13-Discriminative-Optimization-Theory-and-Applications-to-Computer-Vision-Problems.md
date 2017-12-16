---
layout: post
title: "Discriminative Optimization: Theory and Applications to Computer Vision Problems"
date: 2017-07-13 20:58:32
categories: arXiv_CV
tags: arXiv_CV Face Pose_Estimation Optimization
author: Jayakorn Vongkulbhisal, Fernando De la Torre, João P. Costeira
mathjax: true
---

* content
{:toc}

##### Abstract
Many computer vision problems are formulated as the optimization of a cost function. This approach faces two main challenges: (i) designing a cost function with a local optimum at an acceptable solution, and (ii) developing an efficient numerical method to search for one (or multiple) of these local optima. While designing such functions is feasible in the noiseless case, the stability and location of local optima are mostly unknown under noise, occlusion, or missing data. In practice, this can result in undesirable local optima or not having a local optimum in the expected place. On the other hand, numerical optimization algorithms in high-dimensional spaces are typically local and often rely on expensive first or second order information to guide the search. To overcome these limitations, this paper proposes Discriminative Optimization (DO), a method that learns search directions from data without the need of a cost function. Specifically, DO explicitly learns a sequence of updates in the search space that leads to stationary points that correspond to desired solutions. We provide a formal analysis of DO and illustrate its benefits in the problem of 3D point cloud registration, camera pose estimation, and image denoising. We show that DO performed comparably or outperformed state-of-the-art algorithms in terms of accuracy, robustness to perturbations, and computational efficiency.

##### Abstract (translated by Google)
许多计算机视觉问题被制定为成本函数的优化。这种方法面临两个主要的挑战：（i）设计一个具有局部最优的成本函数在一个可接受的解决方案，和（ii）开发一个有效的数值方法来搜索一个（或多个）这些局部最优。虽然在无噪声情况下设计这样的函数是可行的，但在噪声，遮挡或缺失数据下，局部最优的稳定性和位置几乎是未知的。在实践中，这可能会导致不希望的局部最佳或在预期的地方没有局部最佳。另一方面，高维空间中的数值优化算法通常是局部的，并且通常依靠昂贵的一阶或二阶信息来指导搜索。为了克服这些限制，本文提出了判别优化（Discriminative Optimization，DO），这种方法从数据中学习搜索方向，而不需要成本函数。具体而言，DO明确地学习搜索空间中的更新序列，其导致与期望的解决方案相对应的静止点。我们提供了DO的正式分析，并说明了它在3D点云配准，相机姿态估计和图像去噪等方面的优势。我们表明DO在精度，对扰动的鲁棒性和计算效率方面表现出了可比的或者超越最先进的算法。

##### URL
[https://arxiv.org/abs/1707.04318](https://arxiv.org/abs/1707.04318)

##### PDF
[https://arxiv.org/pdf/1707.04318](https://arxiv.org/pdf/1707.04318)

