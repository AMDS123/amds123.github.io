---
layout: post
title: "An ensemble diversity approach to supervised binary hashing"
date: 2016-02-04 04:59:54
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Optimization
author: Miguel Á. Carreira-Perpiñán, Ramin Raziperchikolaei
mathjax: true
---

* content
{:toc}

##### Abstract
Binary hashing is a well-known approach for fast approximate nearest-neighbor search in information retrieval. Much work has focused on affinity-based objective functions involving the hash functions or binary codes. These objective functions encode neighborhood information between data points and are often inspired by manifold learning algorithms. They ensure that the hash functions differ from each other through constraints or penalty terms that encourage codes to be orthogonal or dissimilar across bits, but this couples the binary variables and complicates the already difficult optimization. We propose a much simpler approach: we train each hash function (or bit) independently from each other, but introduce diversity among them using techniques from classifier ensembles. Surprisingly, we find that not only is this faster and trivially parallelizable, but it also improves over the more complex, coupled objective function, and achieves state-of-the-art precision and recall in experiments with image retrieval.

##### Abstract (translated by Google)
二进制哈希是信息检索中快速近似最近邻搜索的一种众所周知的方法。许多工作都集中在涉及散列函数或二进制代码的基于亲和性的目标函数上。这些目标函数对数据点之间的邻域信息进行编码，并且通常受到流形学习算法的启发它们通过约束或惩罚项来确保散列函数彼此不同，这些约束或惩罚项鼓励代码在各个位之间是正交或不相似的，但是这会耦合二进制变量并使已经困难的优化复杂化。我们提出一个更简单的方法：我们彼此独立地训练每个散列函数（或位），但是使用来自分类器集合的技术来引入它们之间的多样性。令人惊讶的是，我们发现，这不仅是快速和平凡的并行，而且还改善了更复杂，耦合的目标函数，并在图像检索实验中达到了最先进的精度和回忆。

##### URL
[https://arxiv.org/abs/1602.01557](https://arxiv.org/abs/1602.01557)

##### PDF
[https://arxiv.org/pdf/1602.01557](https://arxiv.org/pdf/1602.01557)

