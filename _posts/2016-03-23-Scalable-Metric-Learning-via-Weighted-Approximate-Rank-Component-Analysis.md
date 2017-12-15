---
layout: post
title: "Scalable Metric Learning via Weighted Approximate Rank Component Analysis"
date: 2016-03-23 14:56:19
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification Embedding Optimization
author: Cijo Jose, Francois Fleuret
mathjax: true
---

* content
{:toc}

##### Abstract
We are interested in the large-scale learning of Mahalanobis distances, with a particular focus on person re-identification. We propose a metric learning formulation called Weighted Approximate Rank Component Analysis (WARCA). WARCA optimizes the precision at top ranks by combining the WARP loss with a regularizer that favors orthonormal linear mappings, and avoids rank-deficient embeddings. Using this new regularizer allows us to adapt the large-scale WSABIE procedure and to leverage the Adam stochastic optimization algorithm, which results in an algorithm that scales gracefully to very large data-sets. Also, we derive a kernelized version which allows to take advantage of state-of-the-art features for re-identification when data-set size permits kernel computation. Benchmarks on recent and standard re-identification data-sets show that our method beats existing state-of-the-art techniques both in term of accuracy and speed. We also provide experimental analysis to shade lights on the properties of the regularizer we use, and how it improves performance.

##### Abstract (translated by Google)
我们对Mahalanobis距离的大规模学习感兴趣，特别关注重新识别人。我们提出了称为加权近似秩分量分析（WARCA）的度量学习公式。 WARCA通过将WARP损失与有利于正交线性映射的调节器相结合来优化顶级精度，并且避免了等级不足的嵌入。使用这个新的正规化器，我们可以调整大规模的WSABIE程序，并利用Adam随机优化算法，这样可以得到一个可以适度地扩展到非常大的数据集的算法。而且，我们推导出一个核心版本，当数据集大小允许内核计算时，它允许利用最先进的特征来重新识别。最近的和标准的重新识别数据集的基准表明，我们的方法在准确性和速度方面都超过了现有的最新技术。我们还提供实验分析，以对我们使用的正规化剂的性质进行灯光照明，以及它如何提高性能。

##### URL
[https://arxiv.org/abs/1603.00370](https://arxiv.org/abs/1603.00370)

##### PDF
[https://arxiv.org/pdf/1603.00370](https://arxiv.org/pdf/1603.00370)

