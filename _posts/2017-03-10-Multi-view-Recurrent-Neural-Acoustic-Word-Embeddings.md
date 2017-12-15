---
layout: post
title: "Multi-view Recurrent Neural Acoustic Word Embeddings"
date: 2017-03-10 23:57:57
categories: arXiv_CL
tags: arXiv_CL Embedding RNN Recognition
author: Wanjia He, Weiran Wang, Karen Livescu
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work has begun exploring neural acoustic word embeddings---fixed-dimensional vector representations of arbitrary-length speech segments corresponding to words. Such embeddings are applicable to speech retrieval and recognition tasks, where reasoning about whole words may make it possible to avoid ambiguous sub-word representations. The main idea is to map acoustic sequences to fixed-dimensional vectors such that examples of the same word are mapped to similar vectors, while different-word examples are mapped to very different vectors. In this work we take a multi-view approach to learning acoustic word embeddings, in which we jointly learn to embed acoustic sequences and their corresponding character sequences. We use deep bidirectional LSTM embedding models and multi-view contrastive losses. We study the effect of different loss variants, including fixed-margin and cost-sensitive losses. Our acoustic word embeddings improve over previous approaches for the task of word discrimination. We also present results on other tasks that are enabled by the multi-view approach, including cross-view word discrimination and word similarity.

##### Abstract (translated by Google)
最近的工作已经开始探索神经声学词汇嵌入 - 任意长度的与词相对应的语音段的固定维向量表示。这样的嵌入适用于语音检索和识别任务，其中对整个单词的推理可以避免模糊的子单词表示。主要想法是将声学序列映射到固定维度向量，使得相同的词的例子被映射到相似的向量，而不同的词例子被映射到非常不同的向量。在这项工作中，我们采取多视图的方法来学习声学词嵌入，其中我们共同学习嵌入声学序列及其相应的字符序列。我们使用深度双向LSTM嵌入模型和多视图对比损失。我们研究不同损失变量的影响，包括固定利润率和成本敏感性损失。我们的声学词汇嵌入改善了以前的方法来进行词汇歧视的任务。我们还展示了多视图方法所实现的其他任务的结果，包括交叉视图词识别和词相似性。

##### URL
[https://arxiv.org/abs/1611.04496](https://arxiv.org/abs/1611.04496)

##### PDF
[https://arxiv.org/pdf/1611.04496](https://arxiv.org/pdf/1611.04496)

