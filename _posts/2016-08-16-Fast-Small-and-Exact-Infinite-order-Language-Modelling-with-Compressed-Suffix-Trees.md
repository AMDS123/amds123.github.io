---
layout: post
title: "Fast, Small and Exact: Infinite-order Language Modelling with Compressed Suffix Trees"
date: 2016-08-16 02:33:21
categories: arXiv_CL
tags: arXiv_CL Language_Model
author: Ehsan Shareghi, Matthias Petri, Gholamreza Haffari, Trevor Cohn
mathjax: true
---

* content
{:toc}

##### Abstract
Efficient methods for storing and querying are critical for scaling high-order n-gram language models to large corpora. We propose a language model based on compressed suffix trees, a representation that is highly compact and can be easily held in memory, while supporting queries needed in computing language model probabilities on-the-fly. We present several optimisations which improve query runtimes up to 2500x, despite only incurring a modest increase in construction time and memory usage. For large corpora and high Markov orders, our method is highly competitive with the state-of-the-art KenLM package. It imposes much lower memory requirements, often by orders of magnitude, and has runtimes that are either similar (for training) or comparable (for querying).

##### Abstract (translated by Google)
存储和查询的高效方法对于将高阶n元语言模型扩展到大型语料库至关重要。我们提出了一种基于压缩后缀树的语言模型，这种语言模型非常紧凑，可以很容易地保存在内存中，同时支持在计算语言模型概率时所需的查询。我们提出了一些优化，可以将查询运行时间提高到2500x，尽管只会造成建设时间和内存使用量的适度增加。对于大型语料库和高马尔可夫订单，我们的方法与最先进的KenLM软件包竞争非常激烈。它要求的内存要求要低得多，通常是数量级的，运行时间要么相似（要么是训练），要么是可比较的（用于查询）。

##### URL
[https://arxiv.org/abs/1608.04465](https://arxiv.org/abs/1608.04465)

##### PDF
[https://arxiv.org/pdf/1608.04465](https://arxiv.org/pdf/1608.04465)

