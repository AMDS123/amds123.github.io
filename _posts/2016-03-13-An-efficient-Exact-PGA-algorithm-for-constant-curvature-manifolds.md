---
layout: post
title: "An efficient Exact-PGA algorithm for constant curvature manifolds"
date: 2016-03-13 02:57:34
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Rudrasis Chakraborty, Dohyung Seo, Baba C. Vemuri
mathjax: true
---

* content
{:toc}

##### Abstract
Manifold-valued datasets are widely encountered in many computer vision tasks. A non-linear analog of the PCA, called the Principal Geodesic Analysis (PGA) suited for data lying on Riemannian manifolds was reported in literature a decade ago. Since the objective function in PGA is highly non-linear and hard to solve efficiently in general, researchers have proposed a linear approximation. Though this linear approximation is easy to compute, it lacks accuracy especially when the data exhibits a large variance. Recently, an alternative called exact PGA was proposed which tries to solve the optimization without any linearization. For general Riemannian manifolds, though it gives better accuracy than the original (linearized) PGA, for data that exhibit large variance, the optimization is not computationally efficient. In this paper, we propose an efficient exact PGA for constant curvature Riemannian manifolds (CCM-EPGA). CCM-EPGA differs significantly from existing PGA algorithms in two aspects, (i) the distance between a given manifold-valued data point and the principal submanifold is computed analytically and thus no optimization is required as in existing methods. (ii) Unlike the existing PGA algorithms, the descent into codimension-1 submanifolds does not require any optimization but is accomplished through the use of the Rimeannian inverse Exponential map and the parallel transport operations. We present theoretical and experimental results for constant curvature Riemannian manifolds depicting favorable performance of CCM-EPGA compared to existing PGA algorithms. We also present data reconstruction from principal components and directions which has not been presented in literature in this setting.

##### Abstract (translated by Google)
在许多计算机视觉任务中广泛遇到流形值数据集。 PCA的非线性模拟，被称为适用于黎曼流形上的数据的主要测地分析（PGA），在十年前的文献中被报道。由于PGA中的目标函数具有高度非线性，一般难以有效求解，因此研究人员提出了一种线性逼近。虽然这种线性逼近很容易计算，但是它缺乏准确性，特别是当数据表现出很大的变化时。最近，提出了一种称为精确PGA的替代方案，它试图在没有任何线性化的情况下解决优化问题。对于一般的黎曼流形，虽然它比原始（线性化的）PGA具有更好的精度，但对于表现出较大方差的数据来说，优化在计算上并不高效。在本文中，我们提出了一个高效的精确的PGA等曲率黎曼流形（CCM-EPGA）。 CCM-EPGA与现有的PGA算法在两个方面存在显着差异，（i）给定的流形值数据点与主子流形之间的距离是分析计算的，因此不需要像现有方法那样进行优化。 （ii）与现有的PGA算法不同，下降到codimension-1子流形不需要任何优化，而是通过使用Rimeannian逆指数映射和并行传输操作来完成。我们给出了与现有的PGA算法相比，描述CCM-EPGA的良好性能的常曲率黎曼流形的理论和实验结果。我们还提供了主要组成部分和方向的数据重构，这在文献中没有提到。

##### URL
[https://arxiv.org/abs/1603.03984](https://arxiv.org/abs/1603.03984)

##### PDF
[https://arxiv.org/pdf/1603.03984](https://arxiv.org/pdf/1603.03984)

