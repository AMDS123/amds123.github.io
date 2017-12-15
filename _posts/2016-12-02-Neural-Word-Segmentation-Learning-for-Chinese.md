---
layout: post
title: "Neural Word Segmentation Learning for Chinese"
date: 2016-12-02 08:06:10
categories: arXiv_CL
tags: arXiv_CL Segmentation RNN
author: Deng Cai, Hai Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Most previous approaches to Chinese word segmentation formalize this problem as a character-based sequence labeling task where only contextual information within fixed sized local windows and simple interactions between adjacent tags can be captured. In this paper, we propose a novel neural framework which thoroughly eliminates context windows and can utilize complete segmentation history. Our model employs a gated combination neural network over characters to produce distributed representations of word candidates, which are then given to a long short-term memory (LSTM) language scoring model. Experiments on the benchmark datasets show that without the help of feature engineering as most existing approaches, our models achieve competitive or better performances with previous state-of-the-art methods.

##### Abstract (translated by Google)
大多数先前的中文分词方法将这个问题形式化为基于字符的序列标记任务，其中仅固定大小的本地窗口中的上下文信息以及相邻标签之间的简单交互可以被捕获。在本文中，我们提出了一个新的神经框架，彻底消除上下文窗口，可以利用完整的分割历史。我们的模型采用门控字符组合神经网络来产生候选单词的分布式表示，然后给出一个长期的短期记忆（LSTM）语言评分模型。在基准数据集上的实验表明，如果没有特征工程作为大多数现有方法的帮助，我们的模型通过先前的最新方法实现竞争性或更好的性能。

##### URL
[https://arxiv.org/abs/1606.04300](https://arxiv.org/abs/1606.04300)

##### PDF
[https://arxiv.org/pdf/1606.04300](https://arxiv.org/pdf/1606.04300)

