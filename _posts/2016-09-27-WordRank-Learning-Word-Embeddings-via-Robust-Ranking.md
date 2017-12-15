---
layout: post
title: "WordRank: Learning Word Embeddings via Robust Ranking"
date: 2016-09-27 21:11:56
categories: arXiv_CL
tags: arXiv_CL Sparse Attention Embedding
author: Shihao Ji, Hyokun Yun, Pinar Yanardag, Shin Matsushima, S. V. N. Vishwanathan
mathjax: true
---

* content
{:toc}

##### Abstract
Embedding words in a vector space has gained a lot of attention in recent years. While state-of-the-art methods provide efficient computation of word similarities via a low-dimensional matrix embedding, their motivation is often left unclear. In this paper, we argue that word embedding can be naturally viewed as a ranking problem due to the ranking nature of the evaluation metrics. Then, based on this insight, we propose a novel framework WordRank that efficiently estimates word representations via robust ranking, in which the attention mechanism and robustness to noise are readily achieved via the DCG-like ranking losses. The performance of WordRank is measured in word similarity and word analogy benchmarks, and the results are compared to the state-of-the-art word embedding techniques. Our algorithm is very competitive to the state-of-the- arts on large corpora, while outperforms them by a significant margin when the training set is limited (i.e., sparse and noisy). With 17 million tokens, WordRank performs almost as well as existing methods using 7.2 billion tokens on a popular word similarity benchmark. Our multi-node distributed implementation of WordRank is publicly available for general usage.

##### Abstract (translated by Google)
在一个向量空间中嵌入单词近年来受到了很多关注。虽然最先进的方法通过低维矩阵嵌入来提供有效的字词相似性计算，但是他们的动机往往不清楚。在本文中，我们认为，由于评估指标的排序性质，词嵌入可以自然地被视为排名问题。然后，基于这种认识，我们提出了一个新的框架WordRank，通过强大的排名有效地估计词的表示，其中注意机制和噪声的稳健性很容易通过DCG类排名损失实现。 WordRank的表现是在词相似性和词类比基准测量，并将结果与​​最先进的词嵌入技术进行比较。我们的算法对于大型语料库的现状非常有竞争力，但是当训练集是有限的（即稀疏和嘈杂）时，它们的表现优于它们。 WordRank拥有1700万令牌，与现有的方法相比，其性能几乎与使用热门词语相似性基准的72亿令牌相当。我们的WordRank的多节点分布式实现是公开可用的。

##### URL
[https://arxiv.org/abs/1506.02761](https://arxiv.org/abs/1506.02761)

##### PDF
[https://arxiv.org/pdf/1506.02761](https://arxiv.org/pdf/1506.02761)

