---
layout: post
title: "Context-aware Path Ranking for Knowledge Base Completion"
date: 2017-12-20 23:10:21
categories: arXiv_CL
tags: arXiv_CL Knowledge Attention Embedding Prediction
author: Sahisnu Mazumder, Bing Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Knowledge base (KB) completion aims to infer missing facts from existing ones in a KB. Among various approaches, path ranking (PR) algorithms have received increasing attention in recent years. PR algorithms enumerate paths between entity pairs in a KB and use those paths as features to train a model for missing fact prediction. Due to their good performances and high model interpretability, several methods have been proposed. However, most existing methods suffer from scalability (high RAM consumption) and feature explosion (trains on an exponentially large number of features) problems. This paper proposes a Context-aware Path Ranking (C-PR) algorithm to solve these problems by introducing a selective path exploration strategy. C-PR learns global semantics of entities in the KB using word embedding and leverages the knowledge of entity semantics to enumerate contextually relevant paths using bidirectional random walk. Experimental results on three large KBs show that the path features (fewer in number) discovered by C-PR not only improve predictive performance but also are more interpretable than existing baselines.

##### Abstract (translated by Google)
知识库（KB）完成旨在从KB中的现有知识库中推断缺少的事实。在各种方法中，路径排序（PR）算法近年来受到越来越多的关注。 PR算法枚举KB中实体对之间的路径，并将这些路径用作特征来训练缺少事实预测的模型。由于其良好的性能和较高的模型可解释性，已经提出了几种方法。然而，大多数现有的方法都受到可扩展性（高RAM消耗）和特征爆炸（在指数级大量特征上训练）的困扰。本文提出了一种上下文感知路径排序（C-PR）算法，通过引入选择性路径探索策略来解决这些问题。 C-PR使用词嵌入来学习KB中的实体的全局语义，并利用实体语义的知识来使用双向随机游走来枚举上下文相关的路径。在三个大型KB上的实验结果表明，C-PR发现的路径特征（数量较少）不仅提高了预测性能，而且比现有基线更具可解释性。

##### URL
[http://arxiv.org/abs/1712.07745](http://arxiv.org/abs/1712.07745)

##### PDF
[http://arxiv.org/pdf/1712.07745](http://arxiv.org/pdf/1712.07745)

