---
layout: post
title: "Baseline Needs More Love: On Simple Word-Embedding-Based Models and Associated Pooling Mechanisms"
date: 2018-05-24 18:27:21
categories: arXiv_AI
tags: arXiv_AI Embedding RNN Classification Deep_Learning
author: Dinghan Shen, Guoyin Wang, Wenlin Wang, Martin Renqiang Min, Qinliang Su, Yizhe Zhang, Chunyuan Li, Ricardo Henao, Lawrence Carin
mathjax: true
---

* content
{:toc}

##### Abstract
Many deep learning architectures have been proposed to model the compositionality in text sequences, requiring a substantial number of parameters and expensive computations. However, there has not been a rigorous evaluation regarding the added value of sophisticated compositional functions. In this paper, we conduct a point-by-point comparative study between Simple Word-Embedding-based Models (SWEMs), consisting of parameter-free pooling operations, relative to word-embedding-based RNN/CNN models. Surprisingly, SWEMs exhibit comparable or even superior performance in the majority of cases considered. Based upon this understanding, we propose two additional pooling strategies over learned word embeddings: (i) a max-pooling operation for improved interpretability; and (ii) a hierarchical pooling operation, which preserves spatial (n-gram) information within text sequences. We present experiments on 17 datasets encompassing three tasks: (i) (long) document classification; (ii) text sequence matching; and (iii) short text tasks, including classification and tagging. The source code and datasets can be obtained from https:// github.com/dinghanshen/SWEM.

##### Abstract (translated by Google)
已经提出许多深度学习体系结构来对文本序列中的组合性进行建模，这需要大量的参数和昂贵的计算。但是，对复杂的组合函数的附加价值没有进行严格的评估。在本文中，我们对基于单词嵌入的模型（SWEM）进行了逐点比较研究，该模型由无参数池操作组成，与基于单词嵌入的RNN / CNN模型相关。令人惊讶的是，在大多数情况下，SWEMs表现出可比的甚至更优越的表现。基于这种理解，我们提出了两种额外的学习词汇嵌入策略：（i）最大化池操作以提高可解释性;和（ii）分层汇集操作，其保留文本序列内的空间（n-gram）信息。我们对包含三项任务的17个数据集进行实验：（i）（长）文档分类; （ii）文本序列匹配;和（iii）短文本任务，包括分类和标签。源代码和数据集可以从https：// github.com/dinghanshen/SWEM获取。

##### URL
[http://arxiv.org/abs/1805.09843](http://arxiv.org/abs/1805.09843)

##### PDF
[http://arxiv.org/pdf/1805.09843](http://arxiv.org/pdf/1805.09843)

