---
layout: post
title: "Hybrid Diffusion: Spectral-Temporal Graph Filtering for Manifold Ranking"
date: 2018-07-23 16:07:29
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Sparse
author: Ahmet Iscen, Yannis Avrithis, Giorgos Tolias, Teddy Furon, Ondrej Chum
mathjax: true
---

* content
{:toc}

##### Abstract
State of the art image retrieval performance is achieved with CNN features and manifold ranking using a k-NN similarity graph that is pre-computed off-line. The two most successful existing approaches are temporal filtering, where manifold ranking amounts to solving a sparse linear system online, and spectral filtering, where eigen-decomposition of the adjacency matrix is performed off-line and then manifold ranking amounts to dot-product search online. The former suffers from expensive queries and the latter from significant space overhead. Here we introduce a novel, theoretically well-founded hybrid filtering approach allowing full control of the space-time trade-off between these two extremes. Experimentally, we verify that our hybrid method delivers results on par with the state of the art, with lower memory demands compared to spectral filtering approaches and faster compared to temporal filtering.

##### Abstract (translated by Google)
利用CNN特征和使用离线预先计算的k-NN相似性图的流形排序来实现现有技术的图像检索性能。两种最成功的现有方法是时间滤波，其中流形排序相当于在线求解稀疏线性系统，以及频谱滤波，其中邻接矩阵的特征分解是离线执行的，然后流形排序相当于在线点积线搜索。前者遭受昂贵的查询，而后者则来自显着的空间开销。在这里，我们介绍一种新颖的，理论上有根据的混合滤波方法，允许完全控制这两个极端之间的时空权衡。在实验上，我们验证了我们的混合方法提供的结果与现有技术水平相当，与光谱过滤方法相比具有更低的内存需求，与时间过滤相比更快。

##### URL
[http://arxiv.org/abs/1807.08692](http://arxiv.org/abs/1807.08692)

##### PDF
[http://arxiv.org/pdf/1807.08692](http://arxiv.org/pdf/1807.08692)

