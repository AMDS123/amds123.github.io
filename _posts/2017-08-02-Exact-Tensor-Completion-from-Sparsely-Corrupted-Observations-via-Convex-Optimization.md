---
layout: post
title: "Exact Tensor Completion from Sparsely Corrupted Observations via Convex Optimization"
date: 2017-08-02 04:45:42
categories: arXiv_CV
tags: arXiv_CV Sparse Optimization
author: Jonathan Q. Jiang, Michael K. Ng
mathjax: true
---

* content
{:toc}

##### Abstract
This paper conducts a rigorous analysis for provable estimation of multidimensional arrays, in particular third-order tensors, from a random subset of its corrupted entries. Our study rests heavily on a recently proposed tensor algebraic framework in which we can obtain tensor singular value decomposition (t-SVD) that is similar to the SVD for matrices, and define a new notion of tensor rank referred to as the tubal rank. We prove that by simply solving a convex program, which minimizes a weighted combination of tubal nuclear norm, a convex surrogate for the tubal rank, and the $\ell_1$-norm, one can recover an incoherent tensor exactly with overwhelming probability, provided that its tubal rank is not too large and that the corruptions are reasonably sparse. Interestingly, our result includes the recovery guarantees for the problems of tensor completion (TC) and tensor principal component analysis (TRPCA) under the same algebraic setup as special cases. An alternating direction method of multipliers (ADMM) algorithm is presented to solve this optimization problem. Numerical experiments verify our theory and real-world applications demonstrate the effectiveness of our algorithm.

##### Abstract (translated by Google)
本文进行了一个严格的分析可证明的多维阵列，特别是三阶张量的估计，从其损坏的条目的随机子集。我们的研究严重依赖于最近提出的张量代数框架，其中我们可以获得类似于矩阵SVD的张量奇异值分解（t-SVD），并且定义了称为输卵管等级的新的张量概念。我们证明了，通过简单地求解一个凸函数来最小化输卵管核范数，一个输卵管等级的凸代理和$ \ ell_1 $范数的加权组合，可以精确地以非常大的概率恢复一个非相干张量，其输卵管级别不算太大，腐败相当稀少。有趣的是，我们的结果包括在与特殊情况相同的代数设置下对张量完成（TC）和张量主成分分析（TRPCA）问题的恢复保证。提出了交替方向的乘法器（ADMM）算法来解决这个优化问题。数值实验验证了我们的理论和实际应用证明了我们算法的有效性。

##### URL
[https://arxiv.org/abs/1708.00601](https://arxiv.org/abs/1708.00601)

##### PDF
[https://arxiv.org/pdf/1708.00601](https://arxiv.org/pdf/1708.00601)

