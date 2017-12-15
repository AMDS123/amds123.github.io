---
layout: post
title: "Span-Based Constituency Parsing with a Structure-Label System and Provably Optimal Dynamic Oracles"
date: 2016-12-20 01:23:00
categories: arXiv_CL
tags: arXiv_CL RNN
author: James Cross, Liang Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Parsing accuracy using efficient greedy transition systems has improved dramatically in recent years thanks to neural networks. Despite striking results in dependency parsing, however, neural models have not surpassed state-of-the-art approaches in constituency parsing. To remedy this, we introduce a new shift-reduce system whose stack contains merely sentence spans, represented by a bare minimum of LSTM features. We also design the first provably optimal dynamic oracle for constituency parsing, which runs in amortized O(1) time, compared to O(n^3) oracles for standard dependency parsing. Training with this oracle, we achieve the best F1 scores on both English and French of any parser that does not use reranking or external data.

##### Abstract (translated by Google)
近年来，由于神经网络的原因，使用高效的贪婪过渡系统的解析精度得到了显着的提高。尽管在依赖分析方面有惊人的结果，但是，在选区分析中，神经模型并没有超越最先进的方法。为了解决这个问题，我们引入了一个新的移位 - 缩减系统，它的栈只包含句子跨度，用最少的LSTM特征来表示。我们还设计了第一个可证明的用于选区解析的动态预言器，与O（n ^ 3）标准依赖解析器相比，O（1）时间分期运行。使用这个oracle进行培训，我们可以在任何不使用重新编码或外部数据的解析器上获得英文和法文的最佳F1分数。

##### URL
[https://arxiv.org/abs/1612.06475](https://arxiv.org/abs/1612.06475)

##### PDF
[https://arxiv.org/pdf/1612.06475](https://arxiv.org/pdf/1612.06475)

