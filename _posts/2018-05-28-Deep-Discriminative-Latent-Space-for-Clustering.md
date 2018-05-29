---
layout: post
title: "Deep Discriminative Latent Space for Clustering"
date: 2018-05-28 07:34:14
categories: arXiv_AI
tags: arXiv_AI
author: Elad Tzoreff, Olga Kogan, Yoni Choukroun
mathjax: true
---

* content
{:toc}

##### Abstract
Clustering is one of the most fundamental tasks in data analysis and machine learning. It is central to many data-driven applications that aim to separate the data into groups with similar patterns. Moreover, clustering is a complex procedure that is affected significantly by the choice of the data representation method. Recent research has demonstrated encouraging clustering results by learning effectively these representations. In most of these works a deep auto-encoder is initially pre-trained to minimize a reconstruction loss, and then jointly optimized with clustering centroids in order to improve the clustering objective. Those works focus mainly on the clustering phase of the procedure, while not utilizing the potential benefit out of the initial phase. In this paper we propose to optimize an auto-encoder with respect to a discriminative pairwise loss function during the auto-encoder pre-training phase. We demonstrate the high accuracy obtained by the proposed method as well as its rapid convergence (e.g. reaching above 92% accuracy on MNIST during the pre-training phase, in less than 50 epochs), even with small networks.

##### Abstract (translated by Google)
聚类是数据分析和机器学习中最基本的任务之一。许多数据驱动型应用程序的核心是旨在将数据分成具有相似模式的组。而且，聚类是一个复杂的过程，受数据表示方法的选择影响很大。最近的研究表明，通过有效地学习这些表示可以鼓励聚类结果。在大多数这些工作中，深度自动编码器最初被预先训练以最小化重建损失，然后与聚类质心一起进行联合优化以改进聚类目标。这些工作主要集中在程序的集群阶段，而没有利用初始阶段的潜在利益。在本文中，我们建议在自动编码器预训练阶段针对有差别的成对损失函数优化自动编码器。我们证明了由所提出的方法获得的高精度以及其快速收敛（例如，在训练前阶段，在小于50个时期内MNIST达到92％以上的准确度），甚至在小型网络中也是如此。

##### URL
[http://arxiv.org/abs/1805.10795](http://arxiv.org/abs/1805.10795)

##### PDF
[http://arxiv.org/pdf/1805.10795](http://arxiv.org/pdf/1805.10795)

