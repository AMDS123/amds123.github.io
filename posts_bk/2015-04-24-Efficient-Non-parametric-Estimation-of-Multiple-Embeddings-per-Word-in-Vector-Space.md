---
layout: post
title: "Efficient Non-parametric Estimation of Multiple Embeddings per Word in Vector Space"
date: 2015-04-24 22:12:14
categories: arXiv_SD
tags: arXiv_SD Embedding
author: Arvind Neelakantan, Jeevan Shankar, Alexandre Passos, Andrew McCallum
mathjax: true
---

* content
{:toc}

##### Abstract
There is rising interest in vector-space word embeddings and their use in NLP, especially given recent methods for their fast estimation at very large scale. Nearly all this work, however, assumes a single vector per word type ignoring polysemy and thus jeopardizing their usefulness for downstream tasks. We present an extension to the Skip-gram model that efficiently learns multiple embeddings per word type. It differs from recent related work by jointly performing word sense discrimination and embedding learning, by non-parametrically estimating the number of senses per word type, and by its efficiency and scalability. We present new state-of-the-art results in the word similarity in context task and demonstrate its scalability by training with one machine on a corpus of nearly 1 billion tokens in less than 6 hours.

##### Abstract (translated by Google)
对矢量空间的词嵌入和它们在NLP中的使用有着越来越大的兴趣，特别是鉴于最近用于快速估计的大规模的方法。但是，几乎所有这些工作都假设每个单词类型的单个向量忽略多义性，从而危害了它们对下游任务的有用性。我们提出了跳跃克模型的扩展，有效地学习每个单词类型的多个嵌入。与通过联合执行词义辨别和嵌入学习的近期相关工作不同，通过非参数估计每个词类型的意义数量，以及其效率和可伸缩性。我们在上下文任务相似性的单词中提出了最新的最新结果，并通过在不到6个小时的时间内用一台机器对近10亿个代币的语料进行训练来展示其可扩展性。

##### URL
[https://arxiv.org/abs/1504.06654](https://arxiv.org/abs/1504.06654)

##### PDF
[https://arxiv.org/pdf/1504.06654](https://arxiv.org/pdf/1504.06654)

