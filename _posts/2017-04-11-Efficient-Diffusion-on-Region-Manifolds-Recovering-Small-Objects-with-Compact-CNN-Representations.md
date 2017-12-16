---
layout: post
title: "Efficient Diffusion on Region Manifolds: Recovering Small Objects with Compact CNN Representations"
date: 2017-04-11 11:05:41
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Sparse
author: Ahmet Iscen, Giorgos Tolias, Yannis Avrithis, Teddy Furon, Ondrej Chum
mathjax: true
---

* content
{:toc}

##### Abstract
Query expansion is a popular method to improve the quality of image retrieval with both conventional and CNN representations. It has been so far limited to global image similarity. This work focuses on diffusion, a mechanism that captures the image manifold in the feature space. The diffusion is carried out on descriptors of overlapping image regions rather than on a global image descriptor like in previous approaches. An efficient off-line stage allows optional reduction in the number of stored regions. In the on-line stage, the proposed handling of unseen queries in the indexing stage removes additional computation to adjust the precomputed data. We perform diffusion through a sparse linear system solver, yielding practical query times well below one second. Experimentally, we observe a significant boost in performance of image retrieval with compact CNN descriptors on standard benchmarks, especially when the query object covers only a small part of the image. Small objects have been a common failure case of CNN-based retrieval.

##### Abstract (translated by Google)
查询扩展是提高传统和CNN表示的图像检索质量的常用方法。迄今为止，仅限于全球图像相似性。这项工作的重点是扩散，一个机制，捕获特征空间中的图像流形。扩散是在重叠图像区域的描述符上进行的，而不是像以前的方法那样在全局图像描述符上进行。一个有效的离线阶段允许可选地减少存储区域的数量。在在线阶段，建议在索引阶段处理未见的查询消除了额外的计算以调整预先计算的数据。我们通过一个稀疏线性系统解算器执行扩散，产生实际的查询时间远低于一秒。在实验上，我们观察到在标准基准测试中使用紧凑CNN描述符进行图像检索的性能显着提高，特别是当查询对象仅覆盖图像的一小部分时。小对象是基于CNN检索的常见失败案例。

##### URL
[https://arxiv.org/abs/1611.05113](https://arxiv.org/abs/1611.05113)

##### PDF
[https://arxiv.org/pdf/1611.05113](https://arxiv.org/pdf/1611.05113)

