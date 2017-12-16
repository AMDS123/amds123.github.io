---
layout: post
title: "Ordinal Constrained Binary Code Learning for Nearest Neighbor Search"
date: 2016-11-19 13:24:10
categories: arXiv_CV
tags: arXiv_CV Attention Optimization Relation
author: Hong Liu, Rongrong Ji, Yongjian Wu, Feiyue Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Recent years have witnessed extensive attention in binary code learning, a.k.a. hashing, for nearest neighbor search problems. It has been seen that high-dimensional data points can be quantized into binary codes to give an efficient similarity approximation via Hamming distance. Among existing schemes, ranking-based hashing is recent promising that targets at preserving ordinal relations of ranking in the Hamming space to minimize retrieval loss. However, the size of the ranking tuples, which shows the ordinal relations, is quadratic or cubic to the size of training samples. By given a large-scale training data set, it is very expensive to embed such ranking tuples in binary code learning. Besides, it remains a dificulty to build ranking tuples efficiently for most ranking-preserving hashing, which are deployed over an ordinal graph-based setting. To handle these problems, we propose a novel ranking-preserving hashing method, dubbed Ordinal Constraint Hashing (OCH), which efficiently learns the optimal hashing functions with a graph-based approximation to embed the ordinal relations. The core idea is to reduce the size of ordinal graph with ordinal constraint projection, which preserves the ordinal relations through a small data set (such as clusters or random samples). In particular, to learn such hash functions effectively, we further relax the discrete constraints and design a specific stochastic gradient decent algorithm for optimization. Experimental results on three large-scale visual search benchmark datasets, i.e. LabelMe, Tiny100K and GIST1M, show that the proposed OCH method can achieve superior performance over the state-of-the-arts approaches.

##### Abstract (translated by Google)
近年来，在二进制代码学习方面得到了广泛的关注，也就是最近邻搜索问题。已经看到，可以将高维数据点量化为二进制码，以通过汉明距离给出有效的相似近似。在现有的方案中，基于排序的散列最近有前途，其目标是保持海明空间的序号关系，以最小化检索损失。然而，显示序数关系的排列元组的大小对于训练样本的大小是二次或三次的。通过给定一个大规模的训练数据集，在二进制代码学习中嵌入这样的排序元组是非常昂贵的。此外，对于大多数保持排序的散列，高效地构建排名元组仍然是一个难题，这些排列元素被部署在一个基于图形的有序设置上。为了解决这些问题，我们提出了一种新颖的保序哈希方法，称为序约束哈希（Ordinal Constraint Hashing，OCH），它利用基于图的近似来有效地学习最优哈希函数，以嵌入序数关系。其核心思想是通过序数约束投影来减少序图的大小，通过小数据集（如聚类或随机样本）保留序数关系。具体而言，为了有效地学习这些哈希函数，我们进一步放松离散约束，并设计一个特定的随机梯度下降算法进行优化。在三个大规模视觉搜索基准数据集（即LabelMe，Tiny100K和GIST1M）上的实验结果表明，所提出的OCH方法可以实现优于现有技术方法的优越性能。

##### URL
[https://arxiv.org/abs/1611.06362](https://arxiv.org/abs/1611.06362)

##### PDF
[https://arxiv.org/pdf/1611.06362](https://arxiv.org/pdf/1611.06362)

