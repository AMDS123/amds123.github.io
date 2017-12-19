---
layout: post
title: "Fast Spectral Unmixing based on Dykstra's Alternating Projection"
date: 2015-05-07 15:22:33
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Qi Wei, Jose Bioucas-Dias, Nicolas Dobigeon, Jean-Yves Tourneret
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a fast spectral unmixing algorithm based on Dykstra's alternating projection. The proposed algorithm formulates the fully constrained least squares optimization problem associated with the spectral unmixing task as an unconstrained regression problem followed by a projection onto the intersection of several closed convex sets. This projection is achieved by iteratively projecting onto each of the convex sets individually, following Dyktra's scheme. The sequence thus obtained is guaranteed to converge to the sought projection. Thanks to the preliminary matrix decomposition and variable substitution, the projection is implemented intrinsically in a subspace, whose dimension is very often much lower than the number of bands. A benefit of this strategy is that the order of the computational complexity for each projection is decreased from quadratic to linear time. Numerical experiments considering diverse spectral unmixing scenarios provide evidence that the proposed algorithm competes with the state-of-the-art, namely when the number of endmembers is relatively small, a circumstance often observed in real hyperspectral applications.

##### Abstract (translated by Google)
本文提出了一种基于Dykstra交替投影的快速光谱分解算法。该算法将与光谱解混任务相关的全约束最小二乘优化问题作为一个无约束的回归问题，并将其投影到几个闭凸集的交集上。按照Dyktra的方案，这个投影是通过迭代投影到每个凸集上来实现的。如此获得的序列被保证收敛到所寻求的投影。由于初步的矩阵分解和变量替换，投影是在一个子空间中实现的，其维数通常远低于频带数量。这个策略的一个好处是，每个投影的计算复杂度的顺序从二次到线性时间减少。考虑到多种光谱解混情景的数值实验证明，所提出的算法与现有技术竞争，即当端元数量相对较小时，在实际高光谱应用中经常观察到这种情况。

##### URL
[https://arxiv.org/abs/1505.01740](https://arxiv.org/abs/1505.01740)

##### PDF
[https://arxiv.org/pdf/1505.01740](https://arxiv.org/pdf/1505.01740)

