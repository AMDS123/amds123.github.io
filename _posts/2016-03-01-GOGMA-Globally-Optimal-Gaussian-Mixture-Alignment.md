---
layout: post
title: "GOGMA: Globally-Optimal Gaussian Mixture Alignment"
date: 2016-03-01 05:38:50
categories: arXiv_CV
tags: arXiv_CV
author: Dylan Campbell, Lars Petersson
mathjax: true
---

* content
{:toc}

##### Abstract
Gaussian mixture alignment is a family of approaches that are frequently used for robustly solving the point-set registration problem. However, since they use local optimisation, they are susceptible to local minima and can only guarantee local optimality. Consequently, their accuracy is strongly dependent on the quality of the initialisation. This paper presents the first globally-optimal solution to the 3D rigid Gaussian mixture alignment problem under the L2 distance between mixtures. The algorithm, named GOGMA, employs a branch-and-bound approach to search the space of 3D rigid motions SE(3), guaranteeing global optimality regardless of the initialisation. The geometry of SE(3) was used to find novel upper and lower bounds for the objective function and local optimisation was integrated into the scheme to accelerate convergence without voiding the optimality guarantee. The evaluation empirically supported the optimality proof and showed that the method performed much more robustly on two challenging datasets than an existing globally-optimal registration solution.

##### Abstract (translated by Google)
高斯混合对齐是经常用于稳健地解决点集注册问题的一类方法。然而，由于它们使用局部最优化，所以它们易受局部最小值的影响，只能保证局部最优。因此，它们的准确性强烈依赖于初始化的质量。本文首先给出了混合物间L2距离下的三维刚性高斯混合对准问题的第一个全局最优解。该算法被称为GOGMA，采用分支定界的方法搜索三维刚体运动的空间SE（3），保证全局最优性，而不管初始化。 SE（3）的几何被用来找到新的上下界的目标函数和局部优化被纳入方案加速收敛而不排除最优保证。评估经验支持最优性证明，并表明该方法比现有的全局最优配准解决方案在两个具有挑战性的数据集上表现得更强劲。

##### URL
[https://arxiv.org/abs/1603.00150](https://arxiv.org/abs/1603.00150)

##### PDF
[https://arxiv.org/pdf/1603.00150](https://arxiv.org/pdf/1603.00150)

