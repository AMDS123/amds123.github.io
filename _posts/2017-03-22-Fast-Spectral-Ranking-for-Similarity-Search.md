---
layout: post
title: "Fast Spectral Ranking for Similarity Search"
date: 2017-03-22 12:55:21
categories: arXiv_CV
tags: arXiv_CV Sparse Embedding Deep_Learning
author: Ahmet Iscen, Yannis Avrithis, Giorgos Tolias, Teddy Furon, Ondrej Chum
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the success of deep learning on representing images for particular object retrieval, recent studies show that the learned representations still lie on manifolds in a high dimensional space. Therefore, nearest neighbor search cannot be expected to be optimal for this task. Even if a nearest neighbor graph is computed offline, exploring the manifolds online remains expensive. This work introduces an explicit embedding reducing manifold search to Euclidean search followed by dot product similarity search. We show this is equivalent to linear graph filtering of a sparse signal in the frequency domain, and we introduce a scalable offline computation of an approximate Fourier basis of the graph. We improve the state of art on standard particular object retrieval datasets including a challenging one containing small objects. At a scale of $10^5$ images, the offline cost is only a few hours, while query time is comparable to standard similarity search.

##### Abstract (translated by Google)
尽管深度学习在表示特定对象检索的图像方面取得了成功，但最近的研究表明，学习表示仍然位于高维空间的流形上。因此，最近邻搜索对于这个任务不可能是最佳的。即使离线计算最近的邻居图，在线浏览歧管仍然是昂贵的。这项工作引入了显式嵌入减少流形搜索到欧几里得搜索，然后点产品相似性搜索。我们证明这相当于频域中的稀疏信号的线性图滤波，并且引入了图的近似傅立叶基的可扩展离线计算。我们改进了标准特定对象检索数据集的艺术状态，包括一个包含小对象的具有挑战性的数据集。在10 ^ 5美元的图像尺度下，离线成本仅为几个小时，而查询时间与标准相似性搜索相当。

##### URL
[https://arxiv.org/abs/1703.06935](https://arxiv.org/abs/1703.06935)

##### PDF
[https://arxiv.org/pdf/1703.06935](https://arxiv.org/pdf/1703.06935)

