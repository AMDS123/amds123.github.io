---
layout: post
title: "A new ADMM algorithm for the Euclidean median and its application to robust patch regression"
date: 2015-01-16 05:27:17
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Kunal N. Chaudhury, K. R. Ramakrishnan
mathjax: true
---

* content
{:toc}

##### Abstract
The Euclidean Median (EM) of a set of points $\Omega$ in an Euclidean space is the point x minimizing the (weighted) sum of the Euclidean distances of x to the points in $\Omega$. While there exits no closed-form expression for the EM, it can nevertheless be computed using iterative methods such as the Wieszfeld algorithm. The EM has classically been used as a robust estimator of centrality for multivariate data. It was recently demonstrated that the EM can be used to perform robust patch-based denoising of images by generalizing the popular Non-Local Means algorithm. In this paper, we propose a novel algorithm for computing the EM (and its box-constrained counterpart) using variable splitting and the method of augmented Lagrangian. The attractive feature of this approach is that the subproblems involved in the ADMM-based optimization of the augmented Lagrangian can be resolved using simple closed-form projections. The proposed ADMM solver is used for robust patch-based image denoising and is shown to exhibit faster convergence compared to an existing solver.

##### Abstract (translated by Google)
欧几里德空间中的一组点$ \欧米茄欧几里得中值（EM）是使x的欧几里得距离（加权）和$ \欧米加$中的点的（加权）和最小化的点。虽然不存在EM的闭式表达式，但仍然可以使用诸如Wieszfeld算法之类的迭代方法来计算。 EM经典被用作多变量数据中心性的稳健估计。最近证明，通过推广流行的非局部均值（Non-Local Means）算法，EM可用于执行鲁棒的基于斑块的图像去噪。在本文中，我们提出了一种新的算法来计算EM（及其盒子约束对应）使用可变分裂和增广拉格朗日的方法。这种方法的有吸引力的特点是在增广的拉格朗日的基于ADMM的优化中涉及的子问题可以使用简单的闭式投影来解决。所提出的ADMM求解器被用于鲁棒的基于斑块的图像去噪，并且与现有的求解器相比显示出显示出更快的收敛性。

##### URL
[https://arxiv.org/abs/1501.03879](https://arxiv.org/abs/1501.03879)

##### PDF
[https://arxiv.org/pdf/1501.03879](https://arxiv.org/pdf/1501.03879)

