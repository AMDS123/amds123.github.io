---
layout: post
title: "COBRA: A Fast and Simple Method for Active Clustering with Pairwise Constraints"
date: 2018-01-30 12:30:50
categories: arXiv_AI
tags: arXiv_AI
author: Toon Van Craenendonck, Sebastijan Dumancic, Hendrik Blockeel
mathjax: true
---

* content
{:toc}

##### Abstract
Clustering is inherently ill-posed: there often exist multiple valid clusterings of a single dataset, and without any additional information a clustering system has no way of knowing which clustering it should produce. This motivates the use of constraints in clustering, as they allow users to communicate their interests to the clustering system. Active constraint-based clustering algorithms select the most useful constraints to query, aiming to produce a good clustering using as few constraints as possible. We propose COBRA, an active method that first over-clusters the data by running K-means with a $K$ that is intended to be too large, and subsequently merges the resulting small clusters into larger ones based on pairwise constraints. In its merging step, COBRA is able to keep the number of pairwise queries low by maximally exploiting constraint transitivity and entailment. We experimentally show that COBRA outperforms the state of the art in terms of clustering quality and runtime, without requiring the number of clusters in advance.

##### Abstract (translated by Google)
聚类本质上是不适当的：一个数据集经常存在多个有效的聚类，没有任何额外的信息，聚类系统无法知道应该产生哪个聚类。这激发了在聚类中使用约束，因为它们允许用户将他们的兴趣传达给聚类系统。基于主动约束的聚类算法选择最有用的约束进行查询，旨在使用尽可能少的约束产生良好的聚类。我们提出了COBRA，一种主动的方法，首先通过运行带有$ K $的K-means来过度聚集数据，然后根据成对的约束将产生的小群集合成更大的群集。在其合并步骤中，COBRA能够通过最大限度地利用约束传递性和包含性来保持配对查询的数量低。我们通过实验证明COBRA在集群质量和运行时间方面优于现有技术，而不需要提前预测集群的数量。

##### URL
[http://arxiv.org/abs/1801.09955](http://arxiv.org/abs/1801.09955)

##### PDF
[http://arxiv.org/pdf/1801.09955](http://arxiv.org/pdf/1801.09955)

