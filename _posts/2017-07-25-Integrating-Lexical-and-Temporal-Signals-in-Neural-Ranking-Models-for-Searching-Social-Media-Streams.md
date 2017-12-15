---
layout: post
title: "Integrating Lexical and Temporal Signals in Neural Ranking Models for Searching Social Media Streams"
date: 2017-07-25 02:29:31
categories: arXiv_CL
tags: arXiv_CL Knowledge RNN
author: Jinfeng Rao, Hua He, Haotian Zhang, Ferhan Ture, Royal Sequiera, Salman Mohammed, Jimmy Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Time is an important relevance signal when searching streams of social media posts. The distribution of document timestamps from the results of an initial query can be leveraged to infer the distribution of relevant documents, which can then be used to rerank the initial results. Previous experiments have shown that kernel density estimation is a simple yet effective implementation of this idea. This paper explores an alternative approach to mining temporal signals with recurrent neural networks. Our intuition is that neural networks provide a more expressive framework to capture the temporal coherence of neighboring documents in time. To our knowledge, we are the first to integrate lexical and temporal signals in an end-to-end neural network architecture, in which existing neural ranking models are used to generate query-document similarity vectors that feed into a bidirectional LSTM layer for temporal modeling. Our results are mixed: existing neural models for document ranking alone yield limited improvements over simple baselines, but the integration of lexical and temporal signals yield significant improvements over competitive temporal baselines.

##### Abstract (translated by Google)
在搜索社交媒体帖子时，时间是一个重要的相关信号。从初始查询的结果中分配文档时间戳可以用来推断相关文档的分布，然后可以用它来重新排序初始结果。先前的实验已经表明，核密度估计是这个想法的简单而有效的实现。本文探讨了采用递归神经网络挖掘时间信号的另一种方法。我们的直觉是，神经网络提供了一个更具表现力的框架来及时捕捉邻近文档的时间连贯性。就我们所知，我们是第一个将词汇和时间信号整合到端到端的神经网络架构中，其中现有的神经排序模型被用来生成查询 - 文档相似度向量，馈送到双向LSTM层用于时间建模。我们的研究结果是不一样的：现有的文档排序神经模型比简单的基线产生有限的改进，但词汇和时间信号的整合比竞争时间基线产生显着的改善。

##### URL
[https://arxiv.org/abs/1707.07792](https://arxiv.org/abs/1707.07792)

##### PDF
[https://arxiv.org/pdf/1707.07792](https://arxiv.org/pdf/1707.07792)

