---
layout: post
title: "MEDRoP: Memory-Efficient Dynamic Robust PCA"
date: 2017-12-17 06:14:58
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Praneeth Narayanamurthy, Namrata Vaswani
mathjax: true
---

* content
{:toc}

##### Abstract
Robust PCA (RPCA) is the problem of separating a given data matrix into the sum of a sparse matrix and a low-rank matrix. The column span of the low-rank matrix gives the PCA solution. Dynamic RPCA is the time-varying extension of RPCA. It assumes that the true data vectors lie in a low-dimensional subspace that can change with time, albeit slowly. The goal is to track this changing subspace over time in the presence of sparse outliers. We propose an algorithm that we call Memory-Efficient Dynamic Robust PCA (MEDRoP). This relies on the recently studied recursive projected compressive sensing (ReProCS) framework for solving dynamic RPCA problems, however, the actual algorithm is significantly different from, and simpler than, previous ReProCS-based methods. The main contribution of this work is a theoretical guarantee that MEDRoP provably solves dynamic RPCA under weakened versions of standard RPCA assumptions, a mild assumption on slow subspace change, and two simple assumptions (a lower bound on most outlier magnitudes and mutual independence of the true data vectors). Our result is important because (i) it removes the strong assumptions needed by the three previous complete guarantees for ReProCS-based algorithms; (ii) it shows that, it is possible to achieve significantly improved outlier tolerance compared to static RPCA solutions by exploiting slow subspace change and a lower bound on most outlier magnitudes; (iii) it is able to track a changed subspace within a delay that is more than the subspace dimension by only logarithmic factors and thus is near-optimal; and (iv) it studies an algorithm that is online (after initialization), fast, and, memory-efficient (its memory complexity is within logarithmic factors of the optimal).

##### Abstract (translated by Google)
稳健的PCA（RPCA）是将给定的数据矩阵分成稀疏矩阵和低秩矩阵之和的问题。低秩矩阵的列跨度给出了PCA解决方案。动态RPCA是RPCA的时变扩展。它假定真实的数据向量位于可以随时间变化的低维子空间中，尽管是缓慢的。目标是在存在稀疏异常值的情况下跟踪这个不断变化的子空间。我们提出了一个算法，我们称之为Memory-Efficient Dynamic Robust PCA（MEDRoP）。这依赖于最近研究的递归投影压缩感知（ReProCS）框架来解决动态RPCA问题，然而，实际的算法与以前的基于ReProCS的方法有显着的不同，并且比以前更简单。这项工作的主要贡献是一个理论上的保证，MEDRoP证明了在RPCA假设的弱版本下，缓慢子空间变化的一个温和假设，以及两个简单的假设（大多数离群值的下界和真正的相互独立性数据向量）。我们的结果是非常重要的，因为（i）它消除了先前对基于ReProCS算法的三个完整保证所需的强烈假设; （ii）表明，与静态RPCA解决方案相比，通过利用缓慢的子空间变化和大多数异常值幅度的下限，有可能实现显着提高的异常容忍度; （iii）能够仅以对数因子跟踪比子空间维度更大的延迟内的变化子空间，因此是接近最优的;和（iv）它研究一种在线（在初始化之后），快速和高效的存储器（其存储器复杂度在最佳的对数因子内）的算法。

##### URL
[http://arxiv.org/abs/1712.06061](http://arxiv.org/abs/1712.06061)

##### PDF
[http://arxiv.org/pdf/1712.06061](http://arxiv.org/pdf/1712.06061)

