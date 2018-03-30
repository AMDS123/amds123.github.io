---
layout: post
title: "Fast Spectral Ranking for Similarity Search"
date: 2018-03-29 14:00:49
categories: arXiv_CV
tags: arXiv_CV Sparse Embedding Deep_Learning
author: Ahmet Iscen, Yannis Avrithis, Giorgos Tolias, Teddy Furon, Ondrej Chum
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the success of deep learning on representing images for particular object retrieval, recent studies show that the learned representations still lie on manifolds in a high dimensional space. This makes the Euclidean nearest neighbor search biased for this task. Exploring the manifolds online remains expensive even if a nearest neighbor graph has been computed offline. This work introduces an explicit embedding reducing manifold search to Euclidean search followed by dot product similarity search. This is equivalent to linear graph filtering of a sparse signal in the frequency domain. To speed up online search, we compute an approximate Fourier basis of the graph offline. We improve the state of art on particular object retrieval datasets including the challenging Instre dataset containing small objects. At a scale of 10^5 images, the offline cost is only a few hours, while query time is comparable to standard similarity search.

##### Abstract (translated by Google)
尽管对于特定对象检索表示图像的深度学习取得了成功，但最近的研究表明，所学的表示仍然位于高维空间中的流形上。这使得欧几里得最近邻搜索偏向于这个任务。即使最近的邻居图已经离线计算，探索在线歧管仍然很昂贵。这项工作引入了显式嵌入减少流形搜索到欧几里得搜索，然后是点积相似搜索。这相当于频域中稀疏信号的线性图滤波。为了加速在线搜索，我们计算离线图的近似傅里叶基。我们改进了特定对象检索数据集的艺术状态，包括具有挑战性的包含小对象的Instre数据集。在10 ^ 5图像的尺度下，离线成本仅为几个小时，而查询时间与标准相似性搜索相当。

##### URL
[http://arxiv.org/abs/1703.06935](http://arxiv.org/abs/1703.06935)

##### PDF
[http://arxiv.org/pdf/1703.06935](http://arxiv.org/pdf/1703.06935)

