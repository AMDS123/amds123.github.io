---
layout: post
title: "The Projected Power Method: An Efficient Algorithm for Joint Alignment from Pairwise Differences"
date: 2017-12-07 20:30:54
categories: arXiv_CV
tags: arXiv_CV
author: Yuxin Chen, Emmanuel Candes
mathjax: true
---

* content
{:toc}

##### Abstract
Various applications involve assigning discrete label values to a collection of objects based on some pairwise noisy data. Due to the discrete---and hence nonconvex---structure of the problem, computing the optimal assignment (e.g.~maximum likelihood assignment) becomes intractable at first sight. This paper makes progress towards efficient computation by focusing on a concrete joint alignment problem---that is, the problem of recovering $n$ discrete variables $x_i \in \{1,\cdots, m\}$, $1\leq i\leq n$ given noisy observations of their modulo differences $\{x_i - x_j~\mathsf{mod}~m\}$. We propose a low-complexity and model-free procedure, which operates in a lifted space by representing distinct label values in orthogonal directions, and which attempts to optimize quadratic functions over hypercubes. Starting with a first guess computed via a spectral method, the algorithm successively refines the iterates via projected power iterations. We prove that for a broad class of statistical models, the proposed projected power method makes no error---and hence converges to the maximum likelihood estimate---in a suitable regime. Numerical experiments have been carried out on both synthetic and real data to demonstrate the practicality of our algorithm. We expect this algorithmic framework to be effective for a broad range of discrete assignment problems.

##### Abstract (translated by Google)
各种应用涉及基于一些成对噪声数据将离散标签值分配给对象集合。由于问题的离散的，因此是非凸的结构，计算最佳分配（例如〜最大似然分配）一见成为棘手的问题。本文将重点放在一个具体的联合对准问题上，即有效计算方面取得进展，即在{1，\ cdots，m \} $，$ 1 \ leq i中恢复$ n $离散变量$ x_i \ \ leq n $给出它们的模差分的噪音观察。\ \ {x_i  -  x_j〜\ mathsf {mod}〜m \} $。我们提出了一个低复杂度和无模型的过程，它通过在正交方向上表示不同的标签值而在提升的空间中运行，并试图在超立方体上优化二次函数。从通过频谱方法计算的第一次猜测开始，算法通过投影功率迭代不断地改进迭代。我们证明，对于一个广泛的统计模型类别，所提出的投影幂方法不会产生任何错误，因此会收敛到最大似然估计。已经对合成和实际数据进行了数值实验，以证明我们算法的实用性。我们期望这个算法框架对于广泛的离散分配问题是有效的。

##### URL
[http://arxiv.org/abs/1609.05820](http://arxiv.org/abs/1609.05820)

##### PDF
[http://arxiv.org/pdf/1609.05820](http://arxiv.org/pdf/1609.05820)

