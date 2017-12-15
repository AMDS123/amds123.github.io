---
layout: post
title: "Automatic Synonym Discovery with Knowledge Bases"
date: 2017-06-25 23:10:26
categories: arXiv_CL
tags: arXiv_CL Knowledge Inference
author: Meng Qu, Xiang Ren, Jiawei Han
mathjax: true
---

* content
{:toc}

##### Abstract
Recognizing entity synonyms from text has become a crucial task in many entity-leveraging applications. However, discovering entity synonyms from domain-specific text corpora (e.g., news articles, scientific papers) is rather challenging. Current systems take an entity name string as input to find out other names that are synonymous, ignoring the fact that often times a name string can refer to multiple entities (e.g., "apple" could refer to both Apple Inc and the fruit apple). Moreover, most existing methods require training data manually created by domain experts to construct supervised-learning systems. In this paper, we study the problem of automatic synonym discovery with knowledge bases, that is, identifying synonyms for knowledge base entities in a given domain-specific corpus. The manually-curated synonyms for each entity stored in a knowledge base not only form a set of name strings to disambiguate the meaning for each other, but also can serve as "distant" supervision to help determine important features for the task. We propose a novel framework, called DPE, to integrate two kinds of mutually-complementing signals for synonym discovery, i.e., distributional features based on corpus-level statistics and textual patterns based on local contexts. In particular, DPE jointly optimizes the two kinds of signals in conjunction with distant supervision, so that they can mutually enhance each other in the training stage. At the inference stage, both signals will be utilized to discover synonyms for the given entities. Experimental results prove the effectiveness of the proposed framework.

##### Abstract (translated by Google)
从文本中识别实体同义词已成为许多实体利用应用程序中的关键任务。然而，从领域特定的文本语料库（例如新闻文章，科学论文）发现实体同义词是相当具有挑战性的。目前的系统采用实体名称字符串作为输入来查找其他同义名称，忽略了名称字符串通常可以引用多个实体的事实（例如，“苹果”可能指Apple Inc和苹果水果）。而且，大多数现有的方法都需要由领域专家手动创建的训练数据来构建监督学习系统。在本文中，我们研究了知识库的自动同义词发现问题，即在给定的领域特定语料库中识别知识库实体的同义词。存储在知识库中的每个实体的手动策划的同义词不仅形成一组名称字符串以消除彼此的含义，还可以作为“远程”监督来帮助确定任务的重要特征。我们提出了一个新的框架，称为DPE，以整合两种互补信号用于同义词发现，即基于语料库统计的分布特征和基于本地语境的文本模式。特别是DPE在结合远程监督的基础上，共同优化这两种信号，使其在训练阶段相互加强。在推理阶段，两个信号将被用来发现给定实体的同义词。实验结果证明了该框架的有效性。

##### URL
[https://arxiv.org/abs/1706.08186](https://arxiv.org/abs/1706.08186)

##### PDF
[https://arxiv.org/pdf/1706.08186](https://arxiv.org/pdf/1706.08186)

