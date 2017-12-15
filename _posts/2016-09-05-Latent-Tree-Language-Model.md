---
layout: post
title: "Latent Tree Language Model"
date: 2016-09-05 14:47:18
categories: arXiv_CL
tags: arXiv_CL Language_Model
author: Tomas Brychcin
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we introduce Latent Tree Language Model (LTLM), a novel approach to language modeling that encodes syntax and semantics of a given sentence as a tree of word roles. The learning phase iteratively updates the trees by moving nodes according to Gibbs sampling. We introduce two algorithms to infer a tree for a given sentence. The first one is based on Gibbs sampling. It is fast, but does not guarantee to find the most probable tree. The second one is based on dynamic programming. It is slower, but guarantees to find the most probable tree. We provide comparison of both algorithms. We combine LTLM with 4-gram Modified Kneser-Ney language model via linear interpolation. Our experiments with English and Czech corpora show significant perplexity reductions (up to 46% for English and 49% for Czech) compared with standalone 4-gram Modified Kneser-Ney language model.

##### Abstract (translated by Google)
在本文中，我们将介绍潜在树语言模型（LTLM），这是一种新的语言建模方法，它将给定句子的语法和语义编码为词角树。学习阶段通过根据吉布斯采样移动节点来迭代地更新树。我们引入两个算法来推断给定句子的树。第一个是基于吉布斯抽样。它速度快，但不能保证找到最可能的树。第二个是基于动态编程。这是慢，但保证找到最可能的树。我们提供了两种算法的比较。我们将LTLM与4克改进的Kneser-Ney语言模型通过线性插值相结合。我们对英语和捷克语语料库的实验显示，与独立的4克修改的Kneser-Ney语言模型相比，显着的困惑度降低（英语高达46％，捷克语高达49％）。

##### URL
[https://arxiv.org/abs/1607.07057](https://arxiv.org/abs/1607.07057)

##### PDF
[https://arxiv.org/pdf/1607.07057](https://arxiv.org/pdf/1607.07057)

