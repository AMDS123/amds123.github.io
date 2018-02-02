---
layout: post
title: "Indexing of CNN Features for Large Scale Image Search"
date: 2018-02-01 09:39:54
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Embedding CNN
author: Ruoyu Liu, Yao Zhao, Shikui Wei, Yi Yang
mathjax: true
---

* content
{:toc}

##### Abstract
The convolutional neural network (CNN) features can give a good description of image content, which usually represent images with unique global vectors. Although they are compact compared to local descriptors, they still cannot efficiently deal with large-scale image retrieval due to the cost of the linear incremental computation and storage. To address this issue, we build a simple but effective indexing framework based on inverted table, which significantly decreases both the search time and memory usage. In addition, several strategies are fully investigated under an indexing framework to adapt it to CNN features and compensate for quantization errors. First, we use multiple assignment for the query and database images to increase the probability of relevant images' co-existing in the same Voronoi cells obtained via the clustering algorithm. Then, we introduce embedding codes to further improve precision by removing false matches during a search. We demonstrate that by using hashing schemes to calculate the embedding codes and by changing the ranking rule, indexing framework speeds can be greatly improved. Extensive experiments conducted on several unsupervised and supervised benchmarks support these results and the superiority of the proposed indexing framework. We also provide a fair comparison between the popular CNN features.

##### Abstract (translated by Google)
卷积神经网络（CNN）特征可以很好地描述图像内容，通常表示具有唯一全局向量的图像。虽然它们与局部描述符相比是紧凑的，但是由于线性增量计算和存储的成本，它们仍然不能有效地处理大规模的图像检索。为了解决这个问题，我们构建了一个基于倒排表的简单而有效的索引框架，它显着减少了搜索时间和内存使用量。另外，在索引框架下对几种策略进行了充分研究，以使其适应CNN特征并补偿量化误差。首先，对查询和数据库图像使用多个赋值，以增加相关图像在通过聚类算法获得的相同Voronoi单元中共存的概率。然后，我们引入嵌入代码，以通过在搜索期间去除错误匹配来进一步提高精度。我们证明，通过使用哈希方案来计算嵌入代码，并通过改变排名规则，索引框架的速度可以大大提高。在几个无监督和监督的基准上进行的大量实验支持这些结果和所提出的索引框架的优越性。我们还提供了流行的CNN功能之间的公平比较。

##### URL
[http://arxiv.org/abs/1508.00217](http://arxiv.org/abs/1508.00217)

##### PDF
[http://arxiv.org/pdf/1508.00217](http://arxiv.org/pdf/1508.00217)

