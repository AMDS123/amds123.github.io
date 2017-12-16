---
layout: post
title: "Beyond Low-Rank Representations: Orthogonal Clustering Basis Reconstruction with Optimized Graph Structure for Multi-view Spectral Clustering"
date: 2017-10-16 01:46:52
categories: arXiv_CV
tags: arXiv_CV GAN
author: Yang Wang, Lin Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Low-Rank Representation (LRR) is arguably one of the most powerful paradigms for Multi-view spectral clustering, which elegantly encodes the multi-view local graph/manifold structures into an intrinsic low-rank self-expressive data similarity embedded in high-dimensional space, to yield a better graph partition than their single-view counterparts. In this paper we revisit it with a fundamentally different perspective by discovering LRR as essentially a latent clustered orthogonal projection based representation winged with an optimized local graph structure for spectral clustering; each column of the representation is fundamentally a cluster basis orthogonal to others to indicate its members, which intuitively projects the view-specific feature representation to be the one spanned by all orthogonal basis to characterize the cluster structures. Upon this finding, we propose our technique with the followings: (1) We decompose LRR into latent clustered orthogonal representation via low-rank matrix factorization, to encode the more flexible cluster structures than LRR over primal data objects; (2) We convert the problem of LRR into that of simultaneously learning orthogonal clustered representation and optimized local graph structure for each view; (3) The learned orthogonal clustered representations and local graph structures enjoy the same magnitude for multi-view, so that the ideal multi-view consensus can be readily achieved. The experiments over multi-view datasets validate its superiority.

##### Abstract (translated by Google)
低秩表示（Low-Rank Representation，LRR）可以说是Multi-view谱聚类中最强大的范式之一，它将多视图局部图/流形结构优雅地编码成高维嵌入的固有低秩自表达数据相似度空间，以产生比单视图更好的图分区。在本文中，我们通过发现LRR本质上是一个基于潜在聚类正交投影的表示方法，从根本上不同的角度重新审视它，表示的每一列基本上是与其他元素垂直的表示其成员的聚类基础，其直观地将视点特定的特征表示投影为由所有正交基础跨越的表征聚类结构的表示。在这个发现之后，我们提出了以下技术：（1）通过低秩矩阵分解，将LRR分解为潜在的聚类正交表示，对原始数据对象比LRR对更灵活的聚类结构进行编码; （2）将LRR问题转化为同时学习正交聚类表示和每个视图优化局部图结构的问题; （3）学习到的正交聚类表示和局部图结构在多视角下的幅度相同，可以很容易地实现理想的多视点共识。多视图数据集的实验验证了它的优越性。

##### URL
[https://arxiv.org/abs/1708.02288](https://arxiv.org/abs/1708.02288)

##### PDF
[https://arxiv.org/pdf/1708.02288](https://arxiv.org/pdf/1708.02288)

