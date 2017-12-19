---
layout: post
title: "Nonconvex Nonsmooth Low-Rank Minimization via Iteratively Reweighted Nuclear Norm"
date: 2015-10-23 11:28:06
categories: arXiv_CV
tags: arXiv_CV RNN
author: Canyi Lu, Jinhui Tang, Shuicheng Yan, Zhouchen Lin
mathjax: true
---

* content
{:toc}

##### Abstract
The nuclear norm is widely used as a convex surrogate of the rank function in compressive sensing for low rank matrix recovery with its applications in image recovery and signal processing. However, solving the nuclear norm based relaxed convex problem usually leads to a suboptimal solution of the original rank minimization problem. In this paper, we propose to perform a family of nonconvex surrogates of $L_0$-norm on the singular values of a matrix to approximate the rank function. This leads to a nonconvex nonsmooth minimization problem. Then we propose to solve the problem by Iteratively Reweighted Nuclear Norm (IRNN) algorithm. IRNN iteratively solves a Weighted Singular Value Thresholding (WSVT) problem, which has a closed form solution due to the special properties of the nonconvex surrogate functions. We also extend IRNN to solve the nonconvex problem with two or more blocks of variables. In theory, we prove that IRNN decreases the objective function value monotonically, and any limit point is a stationary point. Extensive experiments on both synthesized data and real images demonstrate that IRNN enhances the low-rank matrix recovery compared with state-of-the-art convex algorithms.

##### Abstract (translated by Google)
核范数在压缩感知中被广泛用作低秩矩阵恢复中的秩函数的凸代替，并且在图像恢复和信号处理中被应用。但是，解决基于核范数的松弛凸问题通常会导致原始秩最小化问题的次优解。在本文中，我们提出对矩阵的奇异值执行$ L_0 $范数的非凸代理族来逼近秩函数。这导致非凸非光滑最小化问题。然后我们提出用迭代加权核范数（IRNN）算法来解决这个问题。 IRNN迭代求解了一个加权奇异值阈值（WSVT）问题，由于非凸代理函数的特殊性质，该问题具有封闭形式的解。我们还扩展IRNN以解决两个或更多变量块的非凸问题。理论上，我们证明了IRNN单调减小目标函数值，任何极限点都是一个平稳点。综合数据和实际图像的大量实验表明，与最先进的凸算法相比，IRNN增强了低秩矩阵恢复。

##### URL
[https://arxiv.org/abs/1510.06895](https://arxiv.org/abs/1510.06895)

##### PDF
[https://arxiv.org/pdf/1510.06895](https://arxiv.org/pdf/1510.06895)

