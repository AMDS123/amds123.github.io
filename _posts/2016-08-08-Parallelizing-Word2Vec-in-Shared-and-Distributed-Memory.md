---
layout: post
title: "Parallelizing Word2Vec in Shared and Distributed Memory"
date: 2016-08-08 17:45:00
categories: arXiv_CL
tags: arXiv_CL Sentiment Knowledge Language_Model Recognition
author: Shihao Ji, Nadathur Satish, Sheng Li, Pradeep Dubey
mathjax: true
---

* content
{:toc}

##### Abstract
Word2Vec is a widely used algorithm for extracting low-dimensional vector representations of words. It generated considerable excitement in the machine learning and natural language processing (NLP) communities recently due to its exceptional performance in many NLP applications such as named entity recognition, sentiment analysis, machine translation and question answering. State-of-the-art algorithms including those by Mikolov et al. have been parallelized for multi-core CPU architectures but are based on vector-vector operations that are memory-bandwidth intensive and do not efficiently use computational resources. In this paper, we improve reuse of various data structures in the algorithm through the use of minibatching, hence allowing us to express the problem using matrix multiply operations. We also explore different techniques to distribute word2vec computation across nodes in a compute cluster, and demonstrate good strong scalability up to 32 nodes. In combination, these techniques allow us to scale up the computation near linearly across cores and nodes, and process hundreds of millions of words per second, which is the fastest word2vec implementation to the best of our knowledge.

##### Abstract (translated by Google)
Word2Vec是一种广泛使用的提取词的低维向量表示的算法。它最近在机器学习和自然语言处理（NLP）社区中引起了相当的兴奋，因为它在诸如命名实体识别，情感分析，机器翻译和问题回答等许多NLP应用中表现出色。最先进的算法，包括Mikolov等人的算法。已被并行化为多核CPU架构，但基于向量向量操作，这是内存带宽密集型，并没有高效地使用计算资源。在本文中，我们通过使用minibatching来改进算法中各种数据结构的重用，从而使我们能够使用矩阵乘法运算来表达问题。我们还探索了不同的技术来在计算集群中的各个节点之间分配word2vec计算，并展现出高达32个节点的强大可扩展性。综合起来，这些技术使我们能够在核心和节点之间近乎线性地扩展计算，并且每秒处理数亿字，这是据我们所知最快的word2vec实现。

##### URL
[https://arxiv.org/abs/1604.04661](https://arxiv.org/abs/1604.04661)

##### PDF
[https://arxiv.org/pdf/1604.04661](https://arxiv.org/pdf/1604.04661)

