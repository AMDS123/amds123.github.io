---
layout: post
title: "Simple and Accurate Dependency Parsing Using Bidirectional LSTM Feature Representations"
date: 2016-07-20 15:17:29
categories: arXiv_SD
tags: arXiv_SD RNN
author: Eliyahu Kiperwasser, Yoav Goldberg
mathjax: true
---

* content
{:toc}

##### Abstract
We present a simple and effective scheme for dependency parsing which is based on bidirectional-LSTMs (BiLSTMs). Each sentence token is associated with a BiLSTM vector representing the token in its sentential context, and feature vectors are constructed by concatenating a few BiLSTM vectors. The BiLSTM is trained jointly with the parser objective, resulting in very effective feature extractors for parsing. We demonstrate the effectiveness of the approach by applying it to a greedy transition-based parser as well as to a globally optimized graph-based parser. The resulting parsers have very simple architectures, and match or surpass the state-of-the-art accuracies on English and Chinese.

##### Abstract (translated by Google)
我们提出了一种基于双向LSTM（BiLSTMs）的依赖分析的简单而有效的方案。每个句子标记与表示其句子上下文中的标记的BiLSTM向量相关联，并且通过级联几个BiLSTM向量来构造特征向量。 BiLSTM与解析器目标一起训练，导致非常有效的解析特征提取器。我们通过将其应用于贪婪的基于转换的解析器以及全局优化的基于图形的解析器来演示该方法的有效性。由此产生的解析器具有非常简单的架构，并匹配或超过英文和中文的最新精度。

##### URL
[https://arxiv.org/abs/1603.04351](https://arxiv.org/abs/1603.04351)

##### PDF
[https://arxiv.org/pdf/1603.04351](https://arxiv.org/pdf/1603.04351)

