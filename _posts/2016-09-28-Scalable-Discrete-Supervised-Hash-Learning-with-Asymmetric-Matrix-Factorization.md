---
layout: post
title: "Scalable Discrete Supervised Hash Learning with Asymmetric Matrix Factorization"
date: 2016-09-28 02:37:23
categories: arXiv_CV
tags: arXiv_CV Attention
author: Shifeng Zhang, Jianmin Li, Jinma Guo, Bo Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Hashing method maps similar data to binary hashcodes with smaller hamming distance, and it has received a broad attention due to its low storage cost and fast retrieval speed. However, the existing limitations make the present algorithms difficult to deal with large-scale datasets: (1) discrete constraints are involved in the learning of the hash function; (2) pairwise or triplet similarity is adopted to generate efficient hashcodes, resulting both time and space complexity are greater than O(n^2). To address these issues, we propose a novel discrete supervised hash learning framework which can be scalable to large-scale datasets. First, the discrete learning procedure is decomposed into a binary classifier learning scheme and binary codes learning scheme, which makes the learning procedure more efficient. Second, we adopt the Asymmetric Low-rank Matrix Factorization and propose the Fast Clustering-based Batch Coordinate Descent method, such that the time and space complexity is reduced to O(n). The proposed framework also provides a flexible paradigm to incorporate with arbitrary hash function, including deep neural networks and kernel methods. Experiments on large-scale datasets demonstrate that the proposed method is superior or comparable with state-of-the-art hashing algorithms.

##### Abstract (translated by Google)
散列方法将相似的数据映射为汉明距离较小的二元码，由于其存储成本低，检索速度快，受到了广泛的关注。然而，现有的局限性使得目前的算法难以处理大规模的数据集：（1）哈希函数学习中涉及到离散约束; （2）采用两两相似或相似的方法生成高效的哈希码，使得时间和空间复杂度都大于O（n ^ 2）。为了解决这些问题，我们提出了一个新的离散监督散列学习框架，可以扩展到大规模的数据集。首先将离散学习过程分解为二元分类器学习方案和二进制编码学习方案，使学习过程更加高效。其次，采用非对称低秩矩阵分解方法，提出了基于快速聚类的批处理坐标下降方法，使得时间和空间复杂度降低到O（n）。所提出的框架还提供了一种灵活的范式，以便与任意散列函数结合，包括深度神经网络和内核方法。在大规模数据集上的实验表明，所提出的方法与先进的哈希算法相比是优越的或可比的。

##### URL
[https://arxiv.org/abs/1609.08740](https://arxiv.org/abs/1609.08740)

##### PDF
[https://arxiv.org/pdf/1609.08740](https://arxiv.org/pdf/1609.08740)

