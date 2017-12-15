---
layout: post
title: "GIFT: A Real-time and Scalable 3D Shape Search Engine"
date: 2017-03-31 07:30:06
categories: arXiv_CV
tags: arXiv_CV
author: Song Bai, Xiang Bai, Zhichao Zhou, Zhaoxiang Zhang, Longin Jan Latecki
mathjax: true
---

* content
{:toc}

##### Abstract
Projective analysis is an important solution for 3D shape retrieval, since human visual perceptions of 3D shapes rely on various 2D observations from different view points. Although multiple informative and discriminative views are utilized, most projection-based retrieval systems suffer from heavy computational cost, thus cannot satisfy the basic requirement of scalability for search engines. In this paper, we present a real-time 3D shape search engine based on the projective images of 3D shapes. The real-time property of our search engine results from the following aspects: (1) efficient projection and view feature extraction using GPU acceleration; (2) the first inverted file, referred as F-IF, is utilized to speed up the procedure of multi-view matching; (3) the second inverted file (S-IF), which captures a local distribution of 3D shapes in the feature manifold, is adopted for efficient context-based re-ranking. As a result, for each query the retrieval task can be finished within one second despite the necessary cost of IO overhead. We name the proposed 3D shape search engine, which combines GPU acceleration and Inverted File Twice, as GIFT. Besides its high efficiency, GIFT also outperforms the state-of-the-art methods significantly in retrieval accuracy on various shape benchmarks and competitions.

##### Abstract (translated by Google)
投影分析是三维形状检索的重要解决方案，因为人类对三维形状的视觉感受依赖于来自不同视点的各种二维观察。尽管利用了多种信息和判别性视图，但大多数基于投影的检索系统的计算成本很高，不能满足搜索引擎可扩展性的基本要求。在本文中，我们提出了一个基于三维形状投影图像的实时三维形状搜索引擎。我们的搜索引擎的实时性来自于以下几个方面：（1）使用GPU加速的高效投影和视图特征提取; （2）利用第一个倒排文件，即F-IF来加快多视图匹配的过程; （3）在特征流形中捕获3D形状的局部分布的第二倒排文件（S-IF）被用于有效的基于上下文的重新排序。因此，对于每个查询，尽管需要IO开销的成本，检索任务可以在一秒内完成。我们将所提出的3D形状搜索引擎命名为GIFT，其将GPU加速和倒置文件两次结合起来。除了高效率之外，GIFT还在各种形状的基准和竞赛中的检索精度上超越了最先进的方法。

##### URL
[https://arxiv.org/abs/1604.01879](https://arxiv.org/abs/1604.01879)

##### PDF
[https://arxiv.org/pdf/1604.01879](https://arxiv.org/pdf/1604.01879)

