---
layout: post
title: "Robust PCA via Nonconvex Rank Approximation"
date: 2015-11-17 03:00:30
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Zhao Kang, Chong Peng, Qiang Cheng
mathjax: true
---

* content
{:toc}

##### Abstract
Numerous applications in data mining and machine learning require recovering a matrix of minimal rank. Robust principal component analysis (RPCA) is a general framework for handling this kind of problems. Nuclear norm based convex surrogate of the rank function in RPCA is widely investigated. Under certain assumptions, it can recover the underlying true low rank matrix with high probability. However, those assumptions may not hold in real-world applications. Since the nuclear norm approximates the rank by adding all singular values together, which is essentially a $\ell_1$-norm of the singular values, the resulting approximation error is not trivial and thus the resulting matrix estimator can be significantly biased. To seek a closer approximation and to alleviate the above-mentioned limitations of the nuclear norm, we propose a nonconvex rank approximation. This approximation to the matrix rank is tighter than the nuclear norm. To solve the associated nonconvex minimization problem, we develop an efficient augmented Lagrange multiplier based optimization algorithm. Experimental results demonstrate that our method outperforms current state-of-the-art algorithms in both accuracy and efficiency.

##### Abstract (translated by Google)
数据挖掘和机器学习中的许多应用程序需要恢复最小等级的矩阵。稳健的主成分分析（RPCA）是处理这类问题的一般框架。 RPCA中基于核范数的等级函数的凸代理被广泛研究。在一定的假设下，它可以很有可能地恢复潜在的真正的低秩矩阵。但是，这些假设可能不适用于现实世界的应用程序。由于核范数通过将所有奇异值加在一起来逼近秩，这基本上是奇异值的$ \ ell_1 $范数，所得到的逼近误差并不是微不足道的，因此得到的矩阵估计量可能显着偏差。为了寻求更接近的近似值并缓解上面提到的核范数的局限性，我们提出一个非凸的近似。矩阵秩的近似比核常数更紧密。为了解决相关的非凸最小化问题，我们开发了一个高效的基于拉格朗日乘子的优化算法。实验结果表明，我们的方法在精度和效率上均优于目前最先进的算法。

##### URL
[https://arxiv.org/abs/1511.05261](https://arxiv.org/abs/1511.05261)

##### PDF
[https://arxiv.org/pdf/1511.05261](https://arxiv.org/pdf/1511.05261)

