---
layout: post
title: "When Are Tree Structures Necessary for Deep Learning of Representations?"
date: 2015-08-18 05:59:18
categories: arXiv_SD
tags: arXiv_SD Sentiment Relation_Extraction Sentiment_Classification RNN Classification Deep_Learning Relation
author: Jiwei Li, Minh-Thang Luong, Dan Jurafsky, Eudard Hovy
mathjax: true
---

* content
{:toc}

##### Abstract
Recursive neural models, which use syntactic parse trees to recursively generate representations bottom-up, are a popular architecture. But there have not been rigorous evaluations showing for exactly which tasks this syntax-based method is appropriate. In this paper we benchmark {\bf recursive} neural models against sequential {\bf recurrent} neural models (simple recurrent and LSTM models), enforcing apples-to-apples comparison as much as possible. We investigate 4 tasks: (1) sentiment classification at the sentence level and phrase level; (2) matching questions to answer-phrases; (3) discourse parsing; (4) semantic relation extraction (e.g., {\em component-whole} between nouns). Our goal is to understand better when, and why, recursive models can outperform simpler models. We find that recursive models help mainly on tasks (like semantic relation extraction) that require associating headwords across a long distance, particularly on very long sequences. We then introduce a method for allowing recurrent models to achieve similar performance: breaking long sentences into clause-like units at punctuation and processing them separately before combining. Our results thus help understand the limitations of both classes of models, and suggest directions for improving recurrent models.

##### Abstract (translated by Google)
递归神经模型是一种流行的体系结构，它使用句法分析树以递归方式自下而上地生成表示。但是没有严格的评估显示这个基于语法的方法是合适的。在本文中，我们将{\ bf递归}神经模型与顺序{\ bf recurrent}神经模型（简单递归和LSTM模型）进行比较，尽可能强化苹果与苹果之间的比较。我们调查4个任务：（1）在句子层面和短语层面的情感分类; （2）将问题与答案进行匹配; （3）话语解析; （4）名词之间的语义关系提取（例如名词之间的{\ em分量 - 整体}）。我们的目标是更好地理解何时以及为什么递归模型可以超越简单的模型。我们发现递归模型主要有助于长距离（特别是非常长的序列）需要关联词目的任务（如语义关系提取）。然后，我们介绍一种允许经常性模型达到类似性能的方法：在标点符号上将长句子拆分成子句单元，并在合并之前单独处理它们。因此，我们的结果有助于理解这两类模型的局限性，并提出改善复发模型的方向。

##### URL
[https://arxiv.org/abs/1503.00185](https://arxiv.org/abs/1503.00185)

##### PDF
[https://arxiv.org/pdf/1503.00185](https://arxiv.org/pdf/1503.00185)

