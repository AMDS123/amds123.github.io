---
layout: post
title: "A network approach to topic models"
date: 2018-07-19 13:14:31
categories: arXiv_CL
tags: arXiv_CL Detection
author: Martin Gerlach, Tiago P. Peixoto, Eduardo G. Altmann
mathjax: true
---

* content
{:toc}

##### Abstract
One of the main computational and scientific challenges in the modern age is to extract useful information from unstructured texts. Topic models are one popular machine-learning approach which infers the latent topical structure of a collection of documents. Despite their success --- in particular of its most widely used variant called Latent Dirichlet Allocation (LDA) --- and numerous applications in sociology, history, and linguistics, topic models are known to suffer from severe conceptual and practical problems, e.g. a lack of justification for the Bayesian priors, discrepancies with statistical properties of real texts, and the inability to properly choose the number of topics. Here we obtain a fresh view on the problem of identifying topical structures by relating it to the problem of finding communities in complex networks. This is achieved by representing text corpora as bipartite networks of documents and words. By adapting existing community-detection methods -- using a stochastic block model (SBM) with non-parametric priors -- we obtain a more versatile and principled framework for topic modeling (e.g., it automatically detects the number of topics and hierarchically clusters both the words and documents). The analysis of artificial and real corpora demonstrates that our SBM approach leads to better topic models than LDA in terms of statistical model selection. More importantly, our work shows how to formally relate methods from community detection and topic modeling, opening the possibility of cross-fertilization between these two fields.

##### Abstract (translated by Google)
现代时代的主要计算和科学挑战之一是从非结构化文本中提取有用信息。主题模型是一种流行的机器学习方法，它推断出文档集合的潜在主题结构。尽管它们的成功 - 特别是其最广泛使用的称为潜在Dirichlet分配（LDA）的变体 - 以及社会学，历史和语言学中的众多应用，已知主题模型遭受严重的概念和实际问题，例如，缺乏对贝叶斯先验的理由，与实际文本的统计属性的差异，以及无法正确选择主题的数量。在这里，我们通过将主题结构与在复杂网络中寻找社区的问题联系起来，获得了对主题结构识别问题的全新观点。这是通过将文本语料库表示为文档和单词的二分网络来实现的。通过使用现有的社区检测方法 - 使用具有非参数先验的随机块模型（SBM） - 我们获得了用于主题建模的更通用且有原则的框架（例如，它自动检测主题的数量并且分层地集群两者文字和文件）。对人工和真实语料库的分析表明，在统计模型选择方面，我们的SBM方法导致比LDA更好的主题模型。更重要的是，我们的工作展示了如何正式地将社区检测和主题建模方法联系起来，从而开启了这两个领域之间相互促进的可能性。

##### URL
[http://arxiv.org/abs/1708.01677](http://arxiv.org/abs/1708.01677)

##### PDF
[http://arxiv.org/pdf/1708.01677](http://arxiv.org/pdf/1708.01677)

