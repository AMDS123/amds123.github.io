---
layout: post
title: "Visual Processing by a Unified Schatten-$p$ Norm and $ell_q$ Norm Regularized Principal Component Pursuit"
date: 2016-08-20 18:18:39
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Jing Wang, Meng Wang, Xuegang Hu, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a non-convex formulation to recover the authentic structure from the corrupted real data. Typically, the specific structure is assumed to be low rank, which holds for a wide range of data, such as images and videos. Meanwhile, the corruption is assumed to be sparse. In the literature, such a problem is known as Robust Principal Component Analysis (RPCA), which usually recovers the low rank structure by approximating the rank function with a nuclear norm and penalizing the error by an $\ell_1$-norm. Although RPCA is a convex formulation and can be solved effectively, the introduced norms are not tight approximations, which may cause the solution to deviate from the authentic one. Therefore, we consider here a non-convex relaxation, consisting of a Schatten-$p$ norm and an $\ell_q$-norm that promote low rank and sparsity respectively. We derive a proximal iteratively reweighted algorithm (PIRA) to solve the problem. Our algorithm is based on an alternating direction method of multipliers, where in each iteration we linearize the underlying objective function that allows us to have a closed form solution. We demonstrate that solutions produced by the linearized approximation always converge and have a tighter approximation than the convex counterpart. Experimental results on benchmarks show encouraging results of our approach.

##### Abstract (translated by Google)
在本文中，我们提出了一个非凸公式来从损坏的实际数据中恢复真实的结构。通常情况下，特定的结构被认为是低级的，这适用于广泛的数据，如图像和视频。同时，腐败被认为是稀疏的。在文献中，这样的问题被称为鲁棒主成分分析（RPCA），其通常通过用核准则逼近秩函数并通过$ \ ell_1 $ -norm惩罚误差来恢复低秩结构。虽然RPCA是一种凸规则，可以有效地解决，但引入的规范并不是严格的近似，这可能会导致解决方案偏离真正的规范。因此，我们在这里考虑一个非凸松弛，它由一个Schatten- $ p $范数和一个$ \ ell_q $ -norm组成，分别促进了低秩和稀疏性。我们得到一个近端迭代重新加权算法（PIRA）来解决这个问题。我们的算法基于乘法器的交替方向方法，其中在每次迭代中我们使得基础目标函数线性化，使得我们能够具有封闭形式的解决方案。我们证明了由线性化逼近产生的解决方案总是收敛，并且比凸对称更紧密的近似。基准的实验结果显示我们的方法令人鼓舞的结果。

##### URL
[https://arxiv.org/abs/1608.05856](https://arxiv.org/abs/1608.05856)

##### PDF
[https://arxiv.org/pdf/1608.05856](https://arxiv.org/pdf/1608.05856)

