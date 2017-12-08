---
layout: post
title: "Multi-View Spectral Clustering via Structured Low-Rank Matrix Factorization"
date: 2017-12-07 00:33:05
categories: arXiv_CV
tags: arXiv_CV Attention Optimization Relation
author: Yang Wang, Lin Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-view data clustering attracts more attention than their single view counterparts due to the fact that leveraging multiple independent and complementary information from multi-view feature spaces outperforms the single one. Multi-view Spectral Clustering aims at yielding the data partition agreement over their local manifold structures by seeking eigenvalue-eigenvector decompositions. However, as we observed, such classical paradigm still suffers from (1) overlooking the flexible local manifold structure, caused by (2) enforcing the low-rank data correlation agreement among all views; worse still, (3) LRR is not intuitively flexible to capture the latent data clustering structures. In this paper, we present the structured LRR by factorizing into the latent low-dimensional data-cluster representations, which characterize the data clustering structure for each view. Upon such representation, (b) the laplacian regularizer is imposed to be capable of preserving the flexible local manifold structure for each view. (c) We present an iterative multi-view agreement strategy by minimizing the divergence objective among all factorized latent data-cluster representations during each iteration of optimization process, where such latent representation from each view serves to regulate those from other views, such intuitive process iteratively coordinates all views to be agreeable. (d) We remark that such data-cluster representation can flexibly encode the data clustering structure from any view with adaptive input cluster number. To this end, (e) a novel non-convex objective function is proposed via the efficient alternating minimization strategy. The complexity analysis are also presented. The extensive experiments conducted against the real-world multi-view datasets demonstrate the superiority over state-of-the-arts.

##### Abstract (translated by Google)
由于利用来自多视点特征空间的多个独立和补充信息优于单视点特征空间，所以多视点数据聚类比单视点对等物引起更多关注。多视图谱聚类旨在通过寻找特征值 - 特征向量分解来产生其局部流形结构上的数据分割协议。然而，正如我们所观察到的，这样的经典范式仍然存在：（1）忽视了由于（2）在所有视图之间执行低秩数据相关性协议而引起的灵活的局部流形结构; （3）LRR捕捉潜在的数据聚类结构并不直观。在本文中，我们通过分解潜在的低维数据聚类表示来呈现结构化的LRR，其表征每个视图的数据聚类结构。根据这种表示，（b）拉普拉斯正规化者被强加为能够为每个视图保留灵活的局部流形结构。 （c）我们提出了一个迭代的多视图协议策略，通过最小化所有因子化潜在数据集群表示在每次迭代优化过程期间的分歧目标，其中来自每个视图的这种潜在表示用来调节来自其他视图的这些潜在表示，这样的直观过程迭代地协调所有的视图是合意的。 （d）我们注意到，这样的数据聚类表示可以灵活地从具有自适应输入聚类数的任何视图对数据聚类结构进行编码。为此，（e）通过有效的交替最小化策略提出了一种新的非凸目标函数。还介绍了复杂性分析。针对真实世界的多视图数据集进行的大量实验证明了其优于现有技术的优势。

##### URL
[http://arxiv.org/abs/1709.01212](http://arxiv.org/abs/1709.01212)

##### PDF
[http://arxiv.org/pdf/1709.01212](http://arxiv.org/pdf/1709.01212)

