---
layout: post
title: "Clustering is Efficient for Approximate Maximum Inner Product Search"
date: 2015-11-30 02:26:44
categories: arXiv_CL
tags: arXiv_CL Embedding Classification Recommendation
author: Alex Auvolat, Sarath Chandar, Pascal Vincent, Hugo Larochelle, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
Efficient Maximum Inner Product Search (MIPS) is an important task that has a wide applicability in recommendation systems and classification with a large number of classes. Solutions based on locality-sensitive hashing (LSH) as well as tree-based solutions have been investigated in the recent literature, to perform approximate MIPS in sublinear time. In this paper, we compare these to another extremely simple approach for solving approximate MIPS, based on variants of the k-means clustering algorithm. Specifically, we propose to train a spherical k-means, after having reduced the MIPS problem to a Maximum Cosine Similarity Search (MCSS). Experiments on two standard recommendation system benchmarks as well as on large vocabulary word embeddings, show that this simple approach yields much higher speedups, for the same retrieval precision, than current state-of-the-art hashing-based and tree-based methods. This simple method also yields more robust retrievals when the query is corrupted by noise.

##### Abstract (translated by Google)
高效的最大内积搜索（MIPS）是推荐系统和大量类别分类推广应用的重要任务。最近的文献研究了基于局部敏感散列（LSH）和基于树的解决方案的解决方案，以在次线性时间执行近似MIPS。在本文中，我们将这些与基于k-means聚类算法的变体的另一个极其简单的求解近似MIPS的方法进行比较。具体而言，我们提出在将MIPS问题减少到最大余弦相似性搜索（MCSS）之后，训练球形k均值。在两个标准推荐系统基准以及大词汇量词嵌入上​​的实验表明，相对于当前的基于最新技术的基于散列和基于树的方法，相同的检索精度，这种简单的方法产生高得多的加速。当查询被噪声破坏时，这种简单的方法也可以产生更健壮的检索。

##### URL
[https://arxiv.org/abs/1507.05910](https://arxiv.org/abs/1507.05910)

##### PDF
[https://arxiv.org/pdf/1507.05910](https://arxiv.org/pdf/1507.05910)

