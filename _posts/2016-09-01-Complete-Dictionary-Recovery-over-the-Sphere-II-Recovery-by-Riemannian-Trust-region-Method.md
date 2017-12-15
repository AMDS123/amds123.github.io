---
layout: post
title: "Complete Dictionary Recovery over the Sphere II: Recovery by Riemannian Trust-region Method"
date: 2016-09-01 17:27:12
categories: arXiv_CV
tags: arXiv_CV Sparse Optimization
author: Ju Sun, Qing Qu, John Wright
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of recovering a complete (i.e., square and invertible) matrix $\mathbf A_0$, from $\mathbf Y \in \mathbb{R}^{n \times p}$ with $\mathbf Y = \mathbf A_0 \mathbf X_0$, provided $\mathbf X_0$ is sufficiently sparse. This recovery problem is central to theoretical understanding of dictionary learning, which seeks a sparse representation for a collection of input signals and finds numerous applications in modern signal processing and machine learning. We give the first efficient algorithm that provably recovers $\mathbf A_0$ when $\mathbf X_0$ has $O(n)$ nonzeros per column, under suitable probability model for $\mathbf X_0$. Our algorithmic pipeline centers around solving a certain nonconvex optimization problem with a spherical constraint, and hence is naturally phrased in the language of manifold optimization. In a companion paper (arXiv:1511.03607), we have showed that with high probability our nonconvex formulation has no "spurious" local minimizers and around any saddle point the objective function has a negative directional curvature. In this paper, we take advantage of the particular geometric structure, and describe a Riemannian trust region algorithm that provably converges to a local minimizer with from arbitrary initializations. Such minimizers give excellent approximations to rows of $\mathbf X_0$. The rows are then recovered by linear programming rounding and deflation.

##### Abstract (translated by Google)
我们考虑从$ \ mathbf Y \ in \ mathbb {R} ^ {n \ times p} $与$ \ mathbf Y = \ mathbf中恢复一个完整的（即正方形和可逆的）矩阵$ \ mathbf A_0 $的问题A_0 \ mathbf X_0 $，提供$ \ mathbf X_0 $足够稀疏。这个恢复问题是字典学习的理论理解的核心，字典学习寻求输入信号集合的稀疏表示，并在现代信号处理和机器学习中找到许多应用。当$ \ mathbf X_0 $具有$ O（n）$ nonzeros每列时，我们给出了第一个有效的算法，可以在$ \ mathbf X_0 $的合适概率模型下恢复$ \ mathbf A_0 $。我们的算法流程围绕解决球形约束条件下的某个非凸优化问题展开，因此在流形优化的语言中自然表达出来。在同伴论文（arXiv：1511.03607）中，我们已经证明，非凸表达式具有很高的概率，我们的非凸表达式没有“虚假的”局部极小值，并且在任何鞍点附近，目标函数都有一个负的方向曲率。在本文中，我们利用特定的几何结构，描述了一个黎曼信任域算法，证明了任意初始化后证明可以收敛到局部极小值。这样的最小值给出了$ \ mathbf X_0 $行的极好的近似值。然后通过线性编程舍入和放缩来恢复行。

##### URL
[https://arxiv.org/abs/1511.04777](https://arxiv.org/abs/1511.04777)

##### PDF
[https://arxiv.org/pdf/1511.04777](https://arxiv.org/pdf/1511.04777)

