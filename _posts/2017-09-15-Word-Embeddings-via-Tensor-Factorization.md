---
layout: post
title: "Word Embeddings via Tensor Factorization"
date: 2017-09-15 18:56:30
categories: arXiv_CL
tags: arXiv_CL Embedding Detection Relation
author: Eric Bailey, Shuchin Aeron
mathjax: true
---

* content
{:toc}

##### Abstract
Most popular word embedding techniques involve implicit or explicit factorization of a word co-occurrence based matrix into low rank factors. In this paper, we aim to generalize this trend by using numerical methods to factor higher-order word co-occurrence based arrays, or \textit{tensors}. We present four word embeddings using tensor factorization and analyze their advantages and disadvantages. One of our main contributions is a novel joint symmetric tensor factorization technique related to the idea of coupled tensor factorization. We show that embeddings based on tensor factorization can be used to discern the various meanings of polysemous words without being explicitly trained to do so, and motivate the intuition behind why this works in a way that doesn't with existing methods. We also modify an existing word embedding evaluation metric known as Outlier Detection [Camacho-Collados and Navigli, 2016] to evaluate the quality of the order-$N$ relations that a word embedding captures, and show that tensor-based methods outperform existing matrix-based methods at this task. Experimentally, we show that all of our word embeddings either outperform or are competitive with state-of-the-art baselines commonly used today on a variety of recent datasets. Suggested applications of tensor factorization-based word embeddings are given, and all source code and pre-trained vectors are publicly available online.

##### Abstract (translated by Google)
最流行的词嵌入技术涉及将基于词共现的矩阵的隐式或显式因式分解为低级别因子。在本文中，我们的目标是通过使用数字方法来推广这个趋势，以便将基于高级词语共现的数组或者\ textit {张量}分解。我们用张量分解的方法给出了四个单词的嵌入，并分析了它们的优缺点。我们的主要贡献之一是与张量因式分解有关的新颖的联合对称张量分解技术。我们表明，基于张量因式分解的嵌入可以用来辨别多义词的各种含义，而不需要经过明确的训练，并且为什么这种方法的工作原理与现有的方法不一致。我们还修改了一个名为Outlier Detection [Camacho-Collados and Navigli，2016]的现有词嵌入评估指标来评估单词嵌入捕获的顺序$ N $关系的质量，并显示基于张量的方法优于现有矩阵在这个任务的基础上的方法。在实验上，我们表明，我们所有的单词嵌入或者超越目前最先进的基线，或者与目前在各种最新数据集上使用的最新基线竞争。给出了基于张量分解的词嵌入的建议应用，并且所有的源代码和预先训练好的向量都可以在线公开获得。

##### URL
[https://arxiv.org/abs/1704.02686](https://arxiv.org/abs/1704.02686)

##### PDF
[https://arxiv.org/pdf/1704.02686](https://arxiv.org/pdf/1704.02686)

