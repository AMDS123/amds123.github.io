---
layout: post
title: "Nonparametric Spherical Topic Modeling with Word Embeddings"
date: 2016-04-01 04:36:58
categories: arXiv_SD
tags: arXiv_SD Embedding Inference Relation
author: Kayhan Batmanghelich, Ardavan Saeedi, Karthik Narasimhan, Sam Gershman
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional topic models do not account for semantic regularities in language. Recent distributional representations of words exhibit semantic consistency over directional metrics such as cosine similarity. However, neither categorical nor Gaussian observational distributions used in existing topic models are appropriate to leverage such correlations. In this paper, we propose to use the von Mises-Fisher distribution to model the density of words over a unit sphere. Such a representation is well-suited for directional data. We use a Hierarchical Dirichlet Process for our base topic model and propose an efficient inference algorithm based on Stochastic Variational Inference. This model enables us to naturally exploit the semantic structures of word embeddings while flexibly discovering the number of topics. Experiments demonstrate that our method outperforms competitive approaches in terms of topic coherence on two different text corpora while offering efficient inference.

##### Abstract (translated by Google)
传统的主题模型并没有考虑到语言的语义规律。最近的词语分布表示展示了诸如余弦相似度之类的方向度量的语义一致性。然而，既有的主题模型中使用的分类和高斯观测分布都不适合于利用这种相关性。在本文中，我们建议使用von Mises-Fisher分布来模拟单位球面上的单词密度。这样的表示非常适合定向数据。基于主题模型的分层Dirichlet过程，提出了一种基于随机变分推理的高效推理算法。这个模型使我们能够自然地利用词嵌入的语义结构，同时灵活地发现主题的数量。实验证明，我们的方法在两个不同文本语料上的主题一致性方面优于竞争方法，同时提供有效的推理。

##### URL
[https://arxiv.org/abs/1604.00126](https://arxiv.org/abs/1604.00126)

##### PDF
[https://arxiv.org/pdf/1604.00126](https://arxiv.org/pdf/1604.00126)

