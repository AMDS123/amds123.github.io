---
layout: post
title: "An Optimality Proof for the PairDiff operator for Representing Relations between Words"
date: 2017-09-19 23:09:15
categories: arXiv_CL
tags: arXiv_CL Knowledge Embedding Relation
author: Huda Hakami, Kohei Hayashi, Danushka Bollegala
mathjax: true
---

* content
{:toc}

##### Abstract
Representing the semantic relations that exist between two given words (or entities) is an important first step in a wide-range of NLP applications such as analogical reasoning, knowledge base completion and relational information retrieval. A simple, yet surprisingly accurate method for representing a relation between two words is to compute the vector offset (\PairDiff) between the corresponding word embeddings. Despite its empirical success, it remains unclear whether \PairDiff is the best operator for obtaining a relational representation from word embeddings. In this paper, we conduct a theoretical analysis of the \PairDiff operator. In particular, we show that for word embeddings where cross-dimensional correlations are zero, \PairDiff is the only bilinear operator that can minimise the $\ell_{2}$ loss between analogous word-pairs. We experimentally show that for word embedding created using a broad range of methods, the cross-dimensional correlations in word embeddings are approximately zero, demonstrating the general applicability of our theoretical result. Moreover, we empirically verify the implications of the proven theoretical result in a series of experiments where we repeatedly discover \PairDiff as the best bilinear operator for representing semantic relations between words in several benchmark datasets.

##### Abstract (translated by Google)
表示两个给定单词（或实体）之间存在的语义关系是NLP应用程序的一个重要的第一步，如类推理，知识库完成和关系信息检索。用于表示两个单词之间的关系的一个简单但令人惊讶的精确方法是计算相应的单词嵌入之间的矢量偏移（\ PairDiff）。尽管其经验上的成功，但PairDiff是否是用于从词嵌入获得关系表示的最佳运算符仍不清楚。在本文中，我们对PairDiff算子进行了理论分析。特别是，我们表明，对于交叉维度相关性为零的字嵌入，\ PairDiff是唯一可以最小化类似字对之间的$ \ ell_ {2} $损失的双线性算子。我们通过实验表明，对于使用各种方法创建的词嵌入，词嵌入中的跨维相关近似为零，表明我们的理论结果的普遍适用性。此外，我们通过一系列的实验验证了理论结果的实际意义，我们反复发现\ PairDiff是表示几个基准数据集中词间语义关系的最佳双线性算子。

##### URL
[https://arxiv.org/abs/1709.06673](https://arxiv.org/abs/1709.06673)

##### PDF
[https://arxiv.org/pdf/1709.06673](https://arxiv.org/pdf/1709.06673)

