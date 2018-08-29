---
layout: post
title: "N-ary Relation Extraction using Graph State LSTM"
date: 2018-08-28 03:37:39
categories: arXiv_CL
tags: arXiv_CL Knowledge Relation_Extraction RNN Relation
author: Linfeng Song, Yue Zhang, Zhiguo Wang, Daniel Gildea
mathjax: true
---

* content
{:toc}

##### Abstract
Cross-sentence $n$-ary relation extraction detects relations among $n$ entities across multiple sentences. Typical methods formulate an input as a \textit{document graph}, integrating various intra-sentential and inter-sentential dependencies. The current state-of-the-art method splits the input graph into two DAGs, adopting a DAG-structured LSTM for each. Though being able to model rich linguistic knowledge by leveraging graph edges, important information can be lost in the splitting procedure. We propose a graph-state LSTM model, which uses a parallel state to model each word, recurrently enriching state values via message passing. Compared with DAG LSTMs, our graph LSTM keeps the original graph structure, and speeds up computation by allowing more parallelization. On a standard benchmark, our model shows the best result in the literature.

##### Abstract (translated by Google)
交叉句$ n $ -ary关系提取检测多个句子中$ n $个实体之间的关系。典型的方法将输入表示为\ textit {document graph}，集成了各种句内和句子间依赖关系。当前最先进的方法将输入图分成两个DAG，每个DAG采用DAG结构的LSTM。虽然能够通过利用图形边缘来模拟丰富的语言知识，但是在分割过程中可能会丢失重要信息。我们提出了一个图形状态LSTM模型，它使用并行状态来模拟每个单词，通过消息传递反复丰富状态值。与DAG LSTM相比，我们的图形LSTM保留了原始图形结构，并通过允许更多并行化来加速计算。在标准基准测试中，我们的模型显示了文献中的最佳结果。

##### URL
[http://arxiv.org/abs/1808.09101](http://arxiv.org/abs/1808.09101)

##### PDF
[http://arxiv.org/pdf/1808.09101](http://arxiv.org/pdf/1808.09101)

