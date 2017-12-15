---
layout: post
title: "Go-ICP: A Globally Optimal Solution to 3D ICP Point-Set Registration"
date: 2016-05-11 09:15:11
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Jiaolong Yang, Hongdong Li, Dylan Campbell, Yunde Jia
mathjax: true
---

* content
{:toc}

##### Abstract
The Iterative Closest Point (ICP) algorithm is one of the most widely used methods for point-set registration. However, being based on local iterative optimization, ICP is known to be susceptible to local minima. Its performance critically relies on the quality of the initialization and only local optimality is guaranteed. This paper presents the first globally optimal algorithm, named Go-ICP, for Euclidean (rigid) registration of two 3D point-sets under the L2 error metric defined in ICP. The Go-ICP method is based on a branch-and-bound (BnB) scheme that searches the entire 3D motion space SE(3). By exploiting the special structure of SE(3) geometry, we derive novel upper and lower bounds for the registration error function. Local ICP is integrated into the BnB scheme, which speeds up the new method while guaranteeing global optimality. We also discuss extensions, addressing the issue of outlier robustness. The evaluation demonstrates that the proposed method is able to produce reliable registration results regardless of the initialization. Go-ICP can be applied in scenarios where an optimal solution is desirable or where a good initialization is not always available.

##### Abstract (translated by Google)
迭代最近点（ICP）算法是点集注册中使用最广泛的方法之一。然而，基于局部迭代优化，已知ICP易受局部最小值的影响。其性能严格依赖于初始化的质量，只保证局部最优性。本文提出了第一个全局优化算法Go-ICP，用于在ICP中定义的L2误差度量下的两个三维点集的欧几里得（刚性）配准。 Go-ICP方法基于搜索整个3D运动空间SE（3）的分支定界（BnB）方案。通过利用SE（3）几何的特殊结构，我们得到了配准误差函数的新颖上下界。本地ICP被集成到BnB方案中，在保证全局最优性的同时加快了新方法的速度。我们也讨论扩展，解决异常健壮性的问题。评估表明，无论初始化如何，所提出的方法都能够产生可靠的配准结果。 Go-ICP可以应用于需要最佳解决方案的情况下，或者初始化并不总是可用的情况。

##### URL
[https://arxiv.org/abs/1605.03344](https://arxiv.org/abs/1605.03344)

##### PDF
[https://arxiv.org/pdf/1605.03344](https://arxiv.org/pdf/1605.03344)

