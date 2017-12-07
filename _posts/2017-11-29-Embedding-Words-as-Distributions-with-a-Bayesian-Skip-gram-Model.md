---
layout: post
title: "Embedding Words as Distributions with a Bayesian Skip-gram Model"
date: 2017-11-29 18:55:48
categories: arXiv_CL
tags: arXiv_CL
author: Arthur Bražinskas, Serhii Havrylov, Ivan Titov
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a method for embedding words as probability densities in a low-dimensional space. Rather than assuming that a word embedding is fixed across the entire text collection, as in standard word embedding methods, in our Bayesian model we generate it from a word-specific prior density for each occurrence of a given word. Intuitively, for each word, the prior density encodes the distribution of its potential 'meanings'. These prior densities are conceptually similar to Gaussian embeddings. Interestingly, unlike the Gaussian embeddings, we can also obtain context-specific densities: they encode uncertainty about the sense of a word given its context and correspond to posterior distributions within our model. The context-dependent densities have many potential applications: for example, we show that they can be directly used in the lexical substitution task. We describe an effective estimation method based on the variational autoencoding framework. We also demonstrate that our embeddings achieve competitive results on standard benchmarks.

##### Abstract (translated by Google)
我们介绍一种将词作为概率密度嵌入到低维空间的方法。我们没有假设整个文本集合中的词语嵌入是固定的，就像在标准词语嵌入方法中那样，在我们的贝叶斯模型中，我们根据给定词语的每个出现的特定词先前密度来生成它。直观地说，对于每个单词，先验密度编码其潜在“含义”的分布。这些先前的密度在概念上类似于高斯嵌入。有趣的是，与高斯嵌入不同，我们还可以获得上下文特定的密度：它们根据上下文对单词的意义进行编码，并对应于我们模型中的后验分布。依赖于上下文的密度有许多潜在的应用：例如，我们表明它们可以直接用于词汇替换任务。我们描述了一个基于变分自动编码框架的有效估计方法。我们还证明了我们的嵌入在标准基准上取得了有竞争力的结果。

##### URL
[https://arxiv.org/abs/1711.11027](https://arxiv.org/abs/1711.11027)

##### PDF
[https://arxiv.org/pdf/1711.11027](https://arxiv.org/pdf/1711.11027)

