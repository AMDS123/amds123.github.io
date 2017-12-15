---
layout: post
title: "Complete Dictionary Recovery over the Sphere I: Overview and the Geometric Picture"
date: 2016-09-01 17:19:08
categories: arXiv_CV
tags: arXiv_CV Sparse Optimization
author: Ju Sun, Qing Qu, John Wright
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of recovering a complete (i.e., square and invertible) matrix $\mathbf A_0$, from $\mathbf Y \in \mathbb{R}^{n \times p}$ with $\mathbf Y = \mathbf A_0 \mathbf X_0$, provided $\mathbf X_0$ is sufficiently sparse. This recovery problem is central to theoretical understanding of dictionary learning, which seeks a sparse representation for a collection of input signals and finds numerous applications in modern signal processing and machine learning. We give the first efficient algorithm that provably recovers $\mathbf A_0$ when $\mathbf X_0$ has $O(n)$ nonzeros per column, under suitable probability model for $\mathbf X_0$. In contrast, prior results based on efficient algorithms either only guarantee recovery when $\mathbf X_0$ has $O(\sqrt{n})$ zeros per column, or require multiple rounds of SDP relaxation to work when $\mathbf X_0$ has $O(n^{1-\delta})$ nonzeros per column (for any constant $\delta \in (0, 1)$). } Our algorithmic pipeline centers around solving a certain nonconvex optimization problem with a spherical constraint. In this paper, we provide a geometric characterization of the objective landscape. In particular, we show that the problem is highly structured: with high probability, (1) there are no "spurious" local minimizers; and (2) around all saddle points the objective has a negative directional curvature. This distinctive structure makes the problem amenable to efficient optimization algorithms. In a companion paper (arXiv:1511.04777), we design a second-order trust-region algorithm over the sphere that provably converges to a local minimizer from arbitrary initializations, despite the presence of saddle points.

##### Abstract (translated by Google)
我们考虑从$ \ mathbf Y \ in \ mathbb {R} ^ {n \ times p} $与$ \ mathbf Y = \ mathbf中恢复一个完整的（即正方形和可逆的）矩阵$ \ mathbf A_0 $的问题A_0 \ mathbf X_0 $，提供$ \ mathbf X_0 $足够稀疏。这个恢复问题是字典学习的理论理解的核心，字典学习寻求输入信号集合的稀疏表示，并在现代信号处理和机器学习中找到许多应用。当$ \ mathbf X_0 $具有$ O（n）$ nonzeros每列时，我们给出了第一个有效的算法，可以在$ \ mathbf X_0 $的合适概率模型下恢复$ \ mathbf A_0 $。相比之下，基于高效算法的先前结果要么仅当$ \ mathbf X_0 $每列具有$ O（\ sqrt {n}）$零时保证恢复，要么在$ \ mathbf X_0 $具有多个SDP松弛时才保证恢复$ O（n ^ {1 \ delta}）$ nonzeros每列（对于任何常量$ \ delta \ in（0，1）$）。 }我们的算法流水线围绕着解决球形约束的某个非凸优化问题。在本文中，我们提供了客观景观的几何特征。特别是，我们证明这个问题是高度结构化的：很有可能：（1）没有“虚假的”局部极小值; （2）在所有鞍点周围，物镜具有负方向曲率。这种独特的结构使问题适用于有效的优化算法。在同伴论文（arXiv：1511.04777）中，我们设计了一个球面上的二阶可信区域算法，尽管存在鞍点，但它可以从任意初始化收敛到局部最小值。

##### URL
[https://arxiv.org/abs/1511.03607](https://arxiv.org/abs/1511.03607)

##### PDF
[https://arxiv.org/pdf/1511.03607](https://arxiv.org/pdf/1511.03607)

