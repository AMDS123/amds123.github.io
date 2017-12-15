---
layout: post
title: "Seq2SQL: Generating Structured Queries from Natural Language using Reinforcement Learning"
date: 2017-11-09 23:06:14
categories: arXiv_CL
tags: arXiv_CL Knowledge Attention Reinforcement_Learning Optimization Relation
author: Victor Zhong, Caiming Xiong, Richard Socher
mathjax: true
---

* content
{:toc}

##### Abstract
A significant amount of the world's knowledge is stored in relational databases. However, the ability for users to retrieve facts from a database is limited due to a lack of understanding of query languages such as SQL. We propose Seq2SQL, a deep neural network for translating natural language questions to corresponding SQL queries. Our model leverages the structure of SQL queries to significantly reduce the output space of generated queries. Moreover, we use rewards from in-the-loop query execution over the database to learn a policy to generate unordered parts of the query, which we show are less suitable for optimization via cross entropy loss. In addition, we will publish WikiSQL, a dataset of 80654 hand-annotated examples of questions and SQL queries distributed across 24241 tables from Wikipedia. This dataset is required to train our model and is an order of magnitude larger than comparable datasets. By applying policy-based reinforcement learning with a query execution environment to WikiSQL, our model Seq2SQL outperforms attentional sequence to sequence models, improving execution accuracy from 35.9% to 59.4% and logical form accuracy from 23.4% to 48.3%.

##### Abstract (translated by Google)
大量的世界知识储存在关系数据库中。但是，由于缺乏对查询语言（如SQL）的理解，用户从数据库检索事实的能力是有限的。我们提出Seq2SQL，一个将自然语言问题翻译成相应的SQL查询的深层神经网络。我们的模型利用SQL查询的结构来显着减少生成查询的输出空间。此外，我们使用数据库中的循环查询执行中的奖励来学习一个策略来生成查询的无序部分，我们展示的策略不适合通过交叉熵损失进行优化。另外，我们还将发布维基百科（WikiSQL），这是一个由维基百科分布在24241个表格中的80654个手动注释的问题和SQL查询示例数据集。这个数据集是训练我们的模型所需的，并且比可比数据集大一个数量级。通过将基于策略的强化学习与查询执行环境应用于WikiSQL，我们的Seq2SQL模型比序列模型的注意序列更胜一筹，将执行精度从35.9％提高到59.4％，逻辑形式精度从23.4％提高到48.3％。

##### URL
[https://arxiv.org/abs/1709.00103](https://arxiv.org/abs/1709.00103)

##### PDF
[https://arxiv.org/pdf/1709.00103](https://arxiv.org/pdf/1709.00103)

