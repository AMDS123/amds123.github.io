---
layout: post
title: "Semantic Cluster Unary Loss for Efficient Deep Hashing"
date: 2018-05-15 08:59:45
categories: arXiv_CV
tags: arXiv_CV Attention Classification Deep_Learning
author: Shifeng Zhang, Jianmin Li, Bo Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Hashing method maps similar data to binary hashcodes with smaller hamming distance, which has received a broad attention due to its low storage cost and fast retrieval speed. With the rapid development of deep learning, deep hashing methods have achieved promising results in efficient information retrieval. Most of the existing deep hashing methods adopt pairwise or triplet losses to deal with similarities underlying the data, but the training is difficult and less efficient because $O(n^2)$ data pairs and $O(n^3)$ triplets are involved. To address these issues, we propose a novel deep hashing algorithm with unary loss which can be trained very efficiently. We first of all introduce a Unary Upper Bound of the traditional triplet loss, thus reducing the complexity to $O(n)$ and bridging the classification-based unary loss and the triplet loss. Second, we propose a novel Semantic Cluster Deep Hashing (SCDH) algorithm by introducing a modified Unary Upper Bound loss, named Semantic Cluster Unary Loss (SCUL). The resultant hashcodes form several compact clusters, which means hashcodes in the same cluster have similar semantic information. We also demonstrate that the proposed SCDH is easy to be extended to semi-supervised settings by incorporating the state-of-the-art semi-supervised learning algorithms. Experiments on large-scale datasets show that the proposed method is superior to state-of-the-art hashing algorithms.

##### Abstract (translated by Google)
哈希方法将类似的数据映射到汉宁距离较小的二进制哈希码，由于其低存储成本和快速检索速度而受到广泛关注。随着深度学习的快速发展，深度哈希方法在高效的信息检索方面取得了可喜的成果。大多数现有的深度哈希方法采用成对或三重损失来处理数据背后的相似性，但由于$ O（n ^ 2）$数据对和$ O（n ^ 3）$三元组是相当困难且效率较低的，参与其中。为了解决这些问题，我们提出了一种具有一元损失的新型深度哈希算法，可以非常有效地进行训练。我们首先引入传统三元组损失的一元上界，从而将复杂性降低到$ O（n）$，并弥补了基于分类的一元损失和三元组损失。其次，我们通过引入修正的一元上限损失（Semantic Cluster Unary Loss，SCUL），提出了一种新的语义集群深度散列（SCDH）算法。由此产生的哈希码形成几个紧凑的集群，这意味着同一集群中的哈希码具有相似的语义信息。我们还证明，通过整合最先进的半监督学习算法，提议的SCDH很容易扩展到半监督设置。在大规模数据集上的实验表明，所提出的方法优于最先进的哈希算法。

##### URL
[https://arxiv.org/abs/1805.08705](https://arxiv.org/abs/1805.08705)

##### PDF
[https://arxiv.org/pdf/1805.08705](https://arxiv.org/pdf/1805.08705)

