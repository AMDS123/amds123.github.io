---
layout: post
title: "Link and code: Fast indexing with graphs and compact regression codes"
date: 2018-04-27 10:01:51
categories: arXiv_CV
tags: arXiv_CV
author: Matthijs Douze, Alexandre Sablayrolles, Herv&#xe9; J&#xe9;gou
mathjax: true
---

* content
{:toc}

##### Abstract
Similarity search approaches based on graph walks have recently attained outstanding speed-accuracy trade-offs, taking aside the memory requirements. In this paper, we revisit these approaches by considering, additionally, the memory constraint required to index billions of images on a single server. This leads us to propose a method based both on graph traversal and compact representations. We encode the indexed vectors using quantization and exploit the graph structure to refine the similarity estimation. 
 In essence, our method takes the best of these two worlds: the search strategy is based on nested graphs, thereby providing high precision with a relatively small set of comparisons. At the same time it offers a significant memory compression. As a result, our approach outperforms the state of the art on operating points considering 64-128 bytes per vector, as demonstrated by our results on two billion-scale public benchmarks.

##### Abstract (translated by Google)
基于图形散步的相似性搜索方法最近取得了出色的速度 - 精度折衷，撇开内存要求。在本文中，我们重新考虑这些方法，另外还考虑了在单个服务器上索引数十亿图像所需的内存约束。这导致我们提出一种基于图遍历和紧凑表示的方法。我们使用量化对索引向量进行编码并利用图结构来改进相似性估计。
 实质上，我们的方法利用了这两个世界中最好的一个：搜索策略基于嵌套图，从而以相对较小的一组比较提供高精度。同时它提供了显着的内存压缩。因此，我们的方法在考虑每个矢量64-128个字节的操作点上优于现有技术的最新状态，正如我们在20亿规模的公共基准测试中的结果所证明的。

##### URL
[http://arxiv.org/abs/1804.09996](http://arxiv.org/abs/1804.09996)

##### PDF
[http://arxiv.org/pdf/1804.09996](http://arxiv.org/pdf/1804.09996)

