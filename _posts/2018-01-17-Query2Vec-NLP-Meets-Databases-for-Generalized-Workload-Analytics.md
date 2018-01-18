---
layout: post
title: "Query2Vec: NLP Meets Databases for Generalized Workload Analytics"
date: 2018-01-17 10:21:49
categories: arXiv_CL
tags: arXiv_CL Summarization Embedding RNN Recommendation
author: Shrainik Jain, Bill Howe
mathjax: true
---

* content
{:toc}

##### Abstract
We propose methods for learning vector representations of SQL workloads to support a variety of administration tasks and application features, including query recommendation, workload summarization, index selection, identifying expensive queries, and predicting query reuse. We consider vector representations of both raw SQL text and optimized query plans under various assumptions and pre-processing strategies, and evaluate these methods on multiple real SQL workloads by comparing with results of task and application feature metrics in the literature. We find that simple algorithms based on these generic vector representations compete favorably with previous approaches that require a number of assumptions and task-specific heuristics. We then present a new embedding strategy specialized for queries based on tree-structured Long Short Term Memory (LSTM) network architectures that improves on the text-oriented embeddings for some tasks. We find that the general approach, when trained on a large corpus of SQL queries, provides a robust foundation for a variety of workload analysis tasks. We conclude by considering how workload embeddings can be deployed as a core database system feature to support database maintenance and novel applications.

##### Abstract (translated by Google)
我们提出了学习SQL工作负载的矢量表示的方法，以支持各种管理任务和应用程序功能，包括查询推荐，工作负载汇总，索引选择，识别昂贵查询以及预测查询重用。我们考虑在各种假设和预处理策略下的原始SQL文本和优化查询计划的矢量表示，并通过与文献中的任务和应用程序特征度量的结果进行比较来对这些方法在多个实际SQL工作负载上进行评估。我们发现，基于这些通用向量表示的简单算法与以前需要大量假设和任务特定启发式的方法相比，具有良好的竞争力。然后，我们提出了一种专门针对基于树状结构的长短期记忆（LSTM）网络体系结构的查询的新的嵌入策略，该策略改进了针对某些任务的面向文本的嵌入。我们发现，在大型SQL查询语言上进行训练时，通用方法为各种工作负载分析任务提供了坚实的基础。我们通过考虑如何将工作负载嵌入作为核心数据库系统功能部署来支持数据库维护和新应用程序来结束。

##### URL
[http://arxiv.org/abs/1801.05613](http://arxiv.org/abs/1801.05613)

##### PDF
[http://arxiv.org/pdf/1801.05613](http://arxiv.org/pdf/1801.05613)

