---
layout: post
title: "Efficient Large-scale Approximate Nearest Neighbor Search on the GPU"
date: 2017-02-20 09:57:11
categories: arXiv_CV
tags: arXiv_CV
author: Patrick Wieschollek, Oliver Wang, Alexander Sorkine-Hornung, Hendrik P.A. Lensch
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new approach for efficient approximate nearest neighbor (ANN) search in high dimensional spaces, extending the idea of Product Quantization. We propose a two-level product and vector quantization tree that reduces the number of vector comparisons required during tree traversal. Our approach also includes a novel highly parallelizable re-ranking method for candidate vectors by efficiently reusing already computed intermediate values. Due to its small memory footprint during traversal, the method lends itself to an efficient, parallel GPU implementation. This Product Quantization Tree (PQT) approach significantly outperforms recent state of the art methods for high dimensional nearest neighbor queries on standard reference datasets. Ours is the first work that demonstrates GPU performance superior to CPU performance on high dimensional, large scale ANN problems in time-critical real-world applications, like loop-closing in videos.

##### Abstract (translated by Google)
我们提出了一种新的高维近似（ANN）搜索方法，扩展了产品量化的思想。我们提出了一个两级产品和矢量量化树，减少树遍历期间所需的向量比较的数量。我们的方法还包括通过有效地重用已经计算的中间值，用于候选矢量的新颖的高度可并行重排序方法。由于在遍历过程中占用的内存很小，因此这种方法有助于实现高效，并行的GPU实现。该产品量化树（PQT）方法明显优于最近的标准参考数据集上的高维度最近邻查询的现有技术方法。我们的第一个工作是展现GPU性能优于CPU性能的高维，大规模人工神经网络在时间关键的真实应用程序中的问题，如视频闭环。

##### URL
[https://arxiv.org/abs/1702.05911](https://arxiv.org/abs/1702.05911)

##### PDF
[https://arxiv.org/pdf/1702.05911](https://arxiv.org/pdf/1702.05911)

