---
layout: post
title: "A Full End-to-End Semantic Role Labeler, Syntax-agnostic Over Syntax-aware?"
date: 2018-08-11 14:59:07
categories: arXiv_CL
tags: arXiv_CL Knowledge Attention RNN Classification
author: Jiaxun Cai, Shexia He, Zuchao Li, Hai Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic role labeling (SRL) is to recognize the predicate-argument structure of a sentence, including subtasks of predicate disambiguation and argument labeling. Previous studies usually formulate the entire SRL problem into two or more subtasks. For the first time, this paper introduces an end-to-end neural model which unifiedly tackles the predicate disambiguation and the argument labeling in one shot. Using a biaffine scorer, our model directly predicts all semantic role labels for all given word pairs in the sentence without relying on any syntactic parse information. Specifically, we augment the BiLSTM encoder with a non-linear transformation to further distinguish the predicate and the argument in a given sentence, and model the semantic role labeling process as a word pair classification task by employing the biaffine attentional mechanism. Though the proposed model is syntax-agnostic with local decoder, it outperforms the state-of-the-art syntax-aware SRL systems on the CoNLL-2008, 2009 benchmarks for both English and Chinese. To our best knowledge, we report the first syntax-agnostic SRL model that surpasses all known syntax-aware models.

##### Abstract (translated by Google)
语义角色标记（SRL）用于识别句子的谓词 - 参数结构，包括谓词消歧和参数标记的子任务。以前的研究通常将整个SRL问题制定为两个或更多子任务。本文首次介绍了一种端到端神经模型，该模型统一解决了谓词消歧和一次性参数标注。使用biaffine记分器，我们的模型直接预测句子中所有给定单词对的所有语义角色标签，而不依赖于任何语法分析信息。具体来说，我们使用非线性变换扩充BiLSTM编码器以进一步区分给定句子中的谓词和参数，并通过使用biaffine注意机制将语义角色标记过程建模为单词对分类任务。虽然所提出的模型与本地解码器是语法无关的，但它在CoNLL-2008,2009英语和中文基准测试中优于最先进的语法感知SRL系统。据我们所知，我们报告了第一个超出所有已知语法感知模型的语法无关SRL模型。

##### URL
[http://arxiv.org/abs/1808.03815](http://arxiv.org/abs/1808.03815)

##### PDF
[http://arxiv.org/pdf/1808.03815](http://arxiv.org/pdf/1808.03815)

