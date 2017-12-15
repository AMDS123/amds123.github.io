---
layout: post
title: "Complete Dictionary Recovery over the Sphere"
date: 2015-11-17 21:56:30
categories: arXiv_CV
tags: arXiv_CV Sparse Optimization
author: Ju Sun, Qing Qu, John Wright
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of recovering a complete (i.e., square and invertible) matrix $\mathbf A_0$, from $\mathbf Y \in \mathbb R^{n \times p}$ with $\mathbf Y = \mathbf A_0 \mathbf X_0$, provided $\mathbf X_0$ is sufficiently sparse. This recovery problem is central to the theoretical understanding of dictionary learning, which seeks a sparse representation for a collection of input signals, and finds numerous applications in modern signal processing and machine learning. We give the first efficient algorithm that provably recovers $\mathbf A_0$ when $\mathbf X_0$ has $O(n)$ nonzeros per column, under suitable probability model for $\mathbf X_0$. In contrast, prior results based on efficient algorithms provide recovery guarantees when $\mathbf X_0$ has only $O(n^{1-\delta})$ nonzeros per column for any constant $\delta \in (0, 1)$. Our algorithmic pipeline centers around solving a certain nonconvex optimization problem with a spherical constraint, and hence is naturally phrased in the language of manifold optimization. To show this apparently hard problem is tractable, we first provide a geometric characterization of the high-dimensional objective landscape, which shows that with high probability there are no "spurious" local minima. This particular geometric structure allows us to design a Riemannian trust region algorithm over the sphere that provably converges to one local minimizer with an arbitrary initialization, despite the presence of saddle points. The geometric approach we develop here may also shed light on other problems arising from nonconvex recovery of structured signals.

##### Abstract (translated by Google)
我们考虑从$ \ mathbf Y \ in \ mathbb R \ {n \ times p} $与$ \ mathbf Y中恢复一个完整的（即正方形和可逆的）矩阵$ \ mathbf A_0 $的问题Y = \ mathbf A_0 \ mathbf X_0 $，提供$ \ mathbf X_0 $足够稀疏。这个恢复问题是字典学习的理论理解的核心，字典学习寻求输入信号集合的稀疏表示，并在现代信号处理和机器学习中找到许多应用。当$ \ mathbf X_0 $具有$ O（n）$ nonzeros每列时，我们给出了第一个有效的算法，可以在$ \ mathbf X_0 $的合适概率模型下恢复$ \ mathbf A_0 $。相比之下，基于高效算法的先前结果在$ \ mathbf X_0 $对于任何常量$ \ delta \ in（0，1）$而言每列只有$ O（n ^ {1- \ delta}）$ nonzeros时提供了恢复保证。我们的算法流程围绕解决球形约束条件下的某个非凸优化问题展开，因此在流形优化的语言中自然表达出来。为了表明这个显然难以解决的问题是容易处理的，我们首先提供高维度客观景观的几何特征，这表明高概率不存在“假”局部最小值。这种特殊的几何结构使我们能够在球面上设计一个黎曼信赖域算法，尽管存在鞍点，但它可以任意初始化地收敛到一个局部极小值。我们在这里开发的几何方法也可以阐明由结构化信号的非凸回收引起的其他问题。

##### URL
[https://arxiv.org/abs/1504.06785](https://arxiv.org/abs/1504.06785)

##### PDF
[https://arxiv.org/pdf/1504.06785](https://arxiv.org/pdf/1504.06785)

