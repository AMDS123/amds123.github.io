---
layout: post
title: "Query2Vec: An Evaluation of NLP Techniques for Generalized Workload Analytics"
date: 2018-02-02 22:07:06
categories: arXiv_CL
tags: arXiv_CL Summarization Transfer_Learning Prediction Recommendation
author: Shrainik Jain, Bill Howe, Jiaqi Yan, Thierry Cruanes
mathjax: true
---

* content
{:toc}

##### Abstract
We consider methods for learning vector representations of SQL queries to support generalized workload analytics tasks, including workload summarization for index selection and predicting queries that will trigger memory errors. We consider vector representations of both raw SQL text and optimized query plans, and evaluate these methods on synthetic and real SQL workloads. We find that general algorithms based on vector representations can outperform existing approaches that rely on specialized features. For index recommendation, we cluster the vector representations to compress large workloads with no loss in performance from the recommended index. For error prediction, we train a classifier over learned vectors that can automatically relate subtle syntactic patterns with specific errors raised during query execution. Surprisingly, we also find that these methods enable transfer learning, where a model trained on one SQL corpus can be applied to an unrelated corpus and still enable good performance. We find that these general approaches, when trained on a large corpus of SQL queries, provides a robust foundation for a variety of workload analysis tasks and database features, without requiring application-specific feature engineering.

##### Abstract (translated by Google)
我们考虑用于学习SQL查询的矢量表示的方法，以支持广义的工作负载分析任务，包括索引选择的工作负载汇总和预测将引发内存错误的查询。我们考虑原始SQL文本和优化查询计划的矢量表示，并对合成和实际SQL工作负载评估这些方法。我们发现基于向量表示的通用算法可以超越现有的依赖于特定功能的方法。对于索引推荐，我们将向量表示集中在一起，以压缩大量的工作负载，而不会影响性能。对于错误预测，我们训练一个分类器，学习向量可以自动将微妙的语法模式与查询执行过程中引发的特定错误联系起来。令人惊讶的是，我们还发现这些方法可以实现转移学习，在一个SQL语料库上训练的模型可以应用于不相关的语料库，并且仍然可以实现良好的性能。我们发现，这些通用方法在大量SQL查询语言上进行培训时，为各种工作负载分析任务和数据库功能提供了坚实的基础，而无需特定于应用程序的特征工程。

##### URL
[http://arxiv.org/abs/1801.05613](http://arxiv.org/abs/1801.05613)

##### PDF
[http://arxiv.org/pdf/1801.05613](http://arxiv.org/pdf/1801.05613)

