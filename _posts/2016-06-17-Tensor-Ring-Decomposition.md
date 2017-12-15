---
layout: post
title: "Tensor Ring Decomposition"
date: 2016-06-17 14:40:18
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Qibin Zhao, Guoxu Zhou, Shengli Xie, Liqing Zhang, Andrzej Cichocki
mathjax: true
---

* content
{:toc}

##### Abstract
Tensor networks have in recent years emerged as the powerful tools for solving the large-scale optimization problems. One of the most popular tensor network is tensor train (TT) decomposition that acts as the building blocks for the complicated tensor networks. However, the TT decomposition highly depends on permutations of tensor dimensions, due to its strictly sequential multilinear products over latent cores, which leads to difficulties in finding the optimal TT representation. In this paper, we introduce a fundamental tensor decomposition model to represent a large dimensional tensor by a circular multilinear products over a sequence of low dimensional cores, which can be graphically interpreted as a cyclic interconnection of 3rd-order tensors, and thus termed as tensor ring (TR) decomposition. The key advantage of TR model is the circular dimensional permutation invariance which is gained by employing the trace operation and treating the latent cores equivalently. TR model can be viewed as a linear combination of TT decompositions, thus obtaining the powerful and generalized representation abilities. For optimization of latent cores, we present four different algorithms based on the sequential SVDs, ALS scheme, and block-wise ALS techniques. Furthermore, the mathematical properties of TR model are investigated, which shows that the basic multilinear algebra can be performed efficiently by using TR representaions and the classical tensor decompositions can be conveniently transformed into the TR representation. Finally, the experiments on both synthetic signals and real-world datasets were conducted to evaluate the performance of different algorithms.

##### Abstract (translated by Google)
张量网络近年来成为解决大规模优化问题的有力工具。最流行的张量网络之一是作为复杂张量网络构件的张量分解。然而，TT分解高度依赖于张量维数的排列，这是由于其严格的序列多线性产物超过潜在的核心，导致难以找到最佳的TT表示。在本文中，我们引入了一个基本的张量分解模型来表示一个圆的多重线性产物在一维低维核上的一个大维张量，它可以被图形化地解释为一个三阶张量的循环互连，从而被称为张量环（TR）分解。 TR模型的关键优点是通过使用跟踪操作和等价地处理潜在的核心得到的圆形维数置换不变性。 TR模型可以视为TT分解的线性组合，从而获得强大而广义的表示能力。为了优化潜在的核心，我们提出了四种基于顺序SVD，ALS方案和分块ALS技术的算法。此外，还研究了TR模型的数学特性，表明利用TR表示可以有效地实现基本多线性代数，将经典张量分解方便地转化为TR表示。最后，对合成信号和真实世界数据集进行实验，评估不同算法的性能。

##### URL
[https://arxiv.org/abs/1606.05535](https://arxiv.org/abs/1606.05535)

##### PDF
[https://arxiv.org/pdf/1606.05535](https://arxiv.org/pdf/1606.05535)

