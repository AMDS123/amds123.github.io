---
layout: post
title: "How to evaluate sentiment classifiers for Twitter time-ordered data?"
date: 2018-03-14 08:16:48
categories: arXiv_CL
tags: arXiv_CL Sentiment Sentiment_Classification Classification
author: Igor Mozetič, Luis Torgo, Vitor Cerqueira, Jasmina Smailović
mathjax: true
---

* content
{:toc}

##### Abstract
Social media are becoming an increasingly important source of information about the public mood regarding issues such as elections, Brexit, stock market, etc. In this paper we focus on sentiment classification of Twitter data. Construction of sentiment classifiers is a standard text mining task, but here we address the question of how to properly evaluate them as there is no settled way to do so. Sentiment classes are ordered and unbalanced, and Twitter produces a stream of time-ordered data. The problem we address concerns the procedures used to obtain reliable estimates of performance measures, and whether the temporal ordering of the training and test data matters. We collected a large set of 1.5 million tweets in 13 European languages. We created 138 sentiment models and out-of-sample datasets, which are used as a gold standard for evaluations. The corresponding 138 in-sample datasets are used to empirically compare six different estimation procedures: three variants of cross-validation, and three variants of sequential validation (where test set always follows the training set). We find no significant difference between the best cross-validation and sequential validation. However, we observe that all cross-validation variants tend to overestimate the performance, while the sequential methods tend to underestimate it. Standard cross-validation with random selection of examples is significantly worse than the blocked cross-validation, and should not be used to evaluate classifiers in time-ordered data scenarios.

##### Abstract (translated by Google)
社交媒体正在成为越来越多关于公众情绪的信息来源，例如选举，英国脱欧，股市等。本文主要关注Twitter数据的情感分类。情感分类器的构建是一项标准的文本挖掘任务，但我们在这里讨论如何正确评估它们的问题，因为没有确定的方式来实现。情绪类是有序的和不平衡的，Twitter产生一系列时间排序的数据。我们解决的问题涉及用于获得绩效度量的可靠估计的程序，以及训练和测试数据的时间顺序是否重要。我们以13种欧洲语言收集了大量150万条推文。我们创建了138个情感模型和样本外数据集，这些数据集被用作评估的黄金标准。相应的138个样本内数据集用于根据经验对六种不同的估计程序进行比较：交叉验证的三种变体和连续验证的三种变体（其中测试集总是遵循训练集）。我们发现最好的交叉验证和顺序验证没有显着差异。然而，我们观察到，所有交叉验证变体倾向于高估性能，而顺序方法倾向于低估它。随机选择示例的标准交叉验证比阻塞交叉验证要差得多，并且不应该用于在时间排序的数据场景中评估分类器。

##### URL
[https://arxiv.org/abs/1803.05160](https://arxiv.org/abs/1803.05160)

##### PDF
[https://arxiv.org/pdf/1803.05160](https://arxiv.org/pdf/1803.05160)

