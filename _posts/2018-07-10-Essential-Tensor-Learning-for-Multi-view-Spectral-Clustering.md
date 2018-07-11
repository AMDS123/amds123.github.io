---
layout: post
title: "Essential Tensor Learning for Multi-view Spectral Clustering"
date: 2018-07-10 13:01:48
categories: arXiv_CV
tags: arXiv_CV Attention Relation
author: Jianlong Wu, Zhouchen Lin, Hongbin Zha
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-view clustering attracts much attention recently, which aims to take advantage of multi-view information to improve the performance of clustering. However, most recent work mainly focus on self-representation based subspace clustering, which is of high computation complexity. In this paper, we focus on the Markov chain based spectral clustering method and propose a novel essential tensor learning method to explore the high order correlations for multi-view representation. We first construct a tensor based on multi-view transition probability matrices of the Markov chain. By incorporating the idea from robust principle component analysis, tensor singular value decomposition (t-SVD) based tensor nuclear norm is imposed to preserve the low-rank property of the essential tensor, which can well capture the principle information from multiple views. We also employ the tensor rotation operator for this task to better investigate the relationship among views as well as reduce the computation complexity. The proposed method can be efficiently optimized by the alternating direction method of multipliers~(ADMM). Extensive experiments on six real world datasets corresponding to five different applications show that our method achieves superior performance over other state-of-the-art methods.

##### Abstract (translated by Google)
多视图聚类最近引起了很多关注，其目的是利用多视图信息来提高聚类的性能。然而，最近的工作主要集中在基于自代表的子空间聚类上，其具有高计算复杂度。在本文中，我们重点研究基于马尔可夫链的谱聚类方法，并提出一种新的基本张量学习方法，以探索多视图表示的高阶相关性。我们首先构造基于马尔可夫链的多视图转移概率矩阵的张量。通过结合鲁棒主成分分析的思想，采用基于张量奇异值分解（t-SVD）的张量核范数来保持基本张量的低秩性质，从而可以很好地从多个视图中捕获原理信息。我们还使用张量旋转运算符来完成此任务，以更好地研究视图之间的关系以及降低计算复杂性。通过乘法器的交替方向〜（ADMM）可以有效地优化所提出的方法。对与五种不同应用相对应的六个真实世界数据集进行的大量实验表明，我们的方法比其他最先进的方法具有更好的性能。

##### URL
[http://arxiv.org/abs/1807.03602](http://arxiv.org/abs/1807.03602)

##### PDF
[http://arxiv.org/pdf/1807.03602](http://arxiv.org/pdf/1807.03602)

