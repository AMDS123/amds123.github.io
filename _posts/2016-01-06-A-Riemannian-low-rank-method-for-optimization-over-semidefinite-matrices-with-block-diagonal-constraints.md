---
layout: post
title: "A Riemannian low-rank method for optimization over semidefinite matrices with block-diagonal constraints"
date: 2016-01-06 15:01:39
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Nicolas Boumal
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new algorithm to solve optimization problems of the form $\min f(X)$ for a smooth function $f$ under the constraints that $X$ is positive semidefinite and the diagonal blocks of $X$ are small identity matrices. Such problems often arise as the result of relaxing a rank constraint (lifting). In particular, many estimation tasks involving phases, rotations, orthonormal bases or permutations fit in this framework, and so do certain relaxations of combinatorial problems such as Max-Cut. The proposed algorithm exploits the facts that (1) such formulations admit low-rank solutions, and (2) their rank-restricted versions are smooth optimization problems on a Riemannian manifold. Combining insights from both the Riemannian and the convex geometries of the problem, we characterize when second-order critical points of the smooth problem reveal KKT points of the semidefinite problem. We compare against state of the art, mature software and find that, on certain interesting problem instances, what we call the staircase method is orders of magnitude faster, is more accurate and scales better. Code is available.

##### Abstract (translated by Google)
我们提出了一个新的算法来求解一个光滑函数$ f $的$ \ min f（X）$形式的优化问题，其中$ X $是正半定的，$ X $的对角块是小的单位矩阵。这种问题常常是由于放松排名限制（提升）而产生的。特别是涉及到阶段，旋转，正交基或置换的许多估计任务都适合于这个框架，所以Max-Cut等组合问题的某些放松也是如此。所提出的算法利用了以下事实：（1）这些公式允许低秩解;（2）它们的秩限制版本是黎曼流形上的光滑优化问题。结合黎曼问题和凸问题的见解，我们刻画了光滑问题的二阶临界点揭示了半定问题的KKT点。我们和最先进的成熟的软件进行比较，发现在某些有趣的问题实例中，我们所说的阶梯方法快了几个数量级，更精确和更好。代码是可用的。

##### URL
[https://arxiv.org/abs/1506.00575](https://arxiv.org/abs/1506.00575)

##### PDF
[https://arxiv.org/pdf/1506.00575](https://arxiv.org/pdf/1506.00575)

