---
layout: post
title: "SQL-to-Text Generation with Graph-to-Sequence Model"
date: 2018-09-14 05:00:40
categories: arXiv_CL
tags: arXiv_CL Text_Generation Embedding Relation
author: Kun Xu, Lingfei Wu, Zhiguo Wang, Mo Yu, Liwei Chen, Vadim Sheinin
mathjax: true
---

* content
{:toc}

##### Abstract
Previous work approaches the SQL-to-text generation task using vanilla Seq2Seq models, which may not fully capture the inherent graph-structured information in SQL query. In this paper, we first introduce a strategy to represent the SQL query as a directed graph and then employ a graph-to-sequence model to encode the global structure information into node embeddings. This model can effectively learn the correlation between the SQL query pattern and its interpretation. Experimental results on the WikiSQL dataset and Stackoverflow dataset show that our model significantly outperforms the Seq2Seq and Tree2Seq baselines, achieving the state-of-the-art performance.

##### Abstract (translated by Google)
以前的工作使用vanilla Seq2Seq模型来处理SQL到文本生成任务，这可能无法完全捕获SQL查询中固有的图形结构信息。在本文中，我们首先介绍一种策略，将SQL查询表示为有向图，然后使用图到序列模型将全局结构信息编码为节点嵌入。该模型可以有效地学习SQL查询模式与其解释之间的相关性。 WikiSQL数据集和Stackoverflow数据集的实验结果表明，我们的模型明显优于Seq2Seq和Tree2Seq基线，从而实现了最先进的性能。

##### URL
[http://arxiv.org/abs/1809.05255](http://arxiv.org/abs/1809.05255)

##### PDF
[http://arxiv.org/pdf/1809.05255](http://arxiv.org/pdf/1809.05255)

