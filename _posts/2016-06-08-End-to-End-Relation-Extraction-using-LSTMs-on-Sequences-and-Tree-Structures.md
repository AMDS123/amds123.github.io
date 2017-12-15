---
layout: post
title: "End-to-End Relation Extraction using LSTMs on Sequences and Tree Structures"
date: 2016-06-08 01:08:08
categories: arXiv_SD
tags: arXiv_SD Relation_Extraction RNN Classification Detection Relation
author: Makoto Miwa, Mohit Bansal
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel end-to-end neural model to extract entities and relations between them. Our recurrent neural network based model captures both word sequence and dependency tree substructure information by stacking bidirectional tree-structured LSTM-RNNs on bidirectional sequential LSTM-RNNs. This allows our model to jointly represent both entities and relations with shared parameters in a single model. We further encourage detection of entities during training and use of entity information in relation extraction via entity pretraining and scheduled sampling. Our model improves over the state-of-the-art feature-based model on end-to-end relation extraction, achieving 12.1% and 5.7% relative error reductions in F1-score on ACE2005 and ACE2004, respectively. We also show that our LSTM-RNN based model compares favorably to the state-of-the-art CNN based model (in F1-score) on nominal relation classification (SemEval-2010 Task 8). Finally, we present an extensive ablation analysis of several model components.

##### Abstract (translated by Google)
我们提出了一种新颖的端到端神经模型来提取它们之间的实体和关系。我们的基于循环神经网络的模型通过在双向顺序LSTM-RNN上堆叠双向树状结构的LSTM-RNN来捕获词序列和依赖树子结构信息。这允许我们的模型在单个模型中共同表示实体和具有共享参数的关系。进一步鼓励在实训期间对实体进行检测，并通过实体预训练和计划抽样在关系提取中使用实体信息。我们的模型在端到端关系抽取方面改进了先进的基于特征的模型，分别在ACE2005和ACE2004上分别实现了12.1％和5.7％的F1分数相对误差减少。我们还表明，我们的基于LSTM-RNN的模型与名义关系分类（SemEval-2010 Task 8）中的最新CNN模型（在F1分数中）相比是有利的。最后，我们提出了几个模型组件的广泛消融分析。

##### URL
[https://arxiv.org/abs/1601.00770](https://arxiv.org/abs/1601.00770)

##### PDF
[https://arxiv.org/pdf/1601.00770](https://arxiv.org/pdf/1601.00770)

