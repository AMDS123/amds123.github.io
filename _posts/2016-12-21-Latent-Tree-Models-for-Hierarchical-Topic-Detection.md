---
layout: post
title: "Latent Tree Models for Hierarchical Topic Detection"
date: 2016-12-21 08:59:14
categories: arXiv_CL
tags: arXiv_CL Detection Relation
author: Peixian Chen, Nevin L. Zhang, Tengfei Liu, Leonard K.M. Poon, Zhourong Chen, Farhan Khawar
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel method for hierarchical topic detection where topics are obtained by clustering documents in multiple ways. Specifically, we model document collections using a class of graphical models called hierarchical latent tree models (HLTMs). The variables at the bottom level of an HLTM are observed binary variables that represent the presence/absence of words in a document. The variables at other levels are binary latent variables, with those at the lowest latent level representing word co-occurrence patterns and those at higher levels representing co-occurrence of patterns at the level below. Each latent variable gives a soft partition of the documents, and document clusters in the partitions are interpreted as topics. Latent variables at high levels of the hierarchy capture long-range word co-occurrence patterns and hence give thematically more general topics, while those at low levels of the hierarchy capture short-range word co-occurrence patterns and give thematically more specific topics. Unlike LDA-based topic models, HLTMs do not refer to a document generation process and use word variables instead of token variables. They use a tree structure to model the relationships between topics and words, which is conducive to the discovery of meaningful topics and topic hierarchies.

##### Abstract (translated by Google)
我们提出了一种分层主题检测的新方法，其中的主题是通过多种方式对文档进行聚类而获得的。具体而言，我们使用一类称为分层潜在树模型（HLTM）的图形模型对文档集进行建模。 HLTM底层的变量是观察到的二进制变量，表示文档中单词的存在/不存在。其他层次的变量是二元潜变量，最低潜在水平的变量表示词汇共现模式，而较高层次上的变量代表下面层次模式的共现。每个潜在变量给出文​​档的软分区，分区中的文档集群被解释为主题。高层次的潜在变量捕捉远距离字词共现模式，从而给出主题更一般的主题，而低层次的潜在变量捕捉短程字词共现模式，并给出更具体的主题。与基于LDA的主题模型不同，HLTM不引用文档生成过程，而是使用单词变量而不是令牌变量。他们使用树状结构来模拟主题和单词之间的关系，有利于发现有意义的主题和主题层次。

##### URL
[https://arxiv.org/abs/1605.06650](https://arxiv.org/abs/1605.06650)

##### PDF
[https://arxiv.org/pdf/1605.06650](https://arxiv.org/pdf/1605.06650)

