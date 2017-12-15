---
layout: post
title: "Cross-Sentence N-ary Relation Extraction with Graph LSTMs"
date: 2017-08-12 04:33:52
categories: arXiv_CL
tags: arXiv_CL Knowledge Relation_Extraction RNN Relation Memory_Networks
author: Nanyun Peng, Hoifung Poon, Chris Quirk, Kristina Toutanova, Wen-tau Yih
mathjax: true
---

* content
{:toc}

##### Abstract
Past work in relation extraction has focused on binary relations in single sentences. Recent NLP inroads in high-value domains have sparked interest in the more general setting of extracting n-ary relations that span multiple sentences. In this paper, we explore a general relation extraction framework based on graph long short-term memory networks (graph LSTMs) that can be easily extended to cross-sentence n-ary relation extraction. The graph formulation provides a unified way of exploring different LSTM approaches and incorporating various intra-sentential and inter-sentential dependencies, such as sequential, syntactic, and discourse relations. A robust contextual representation is learned for the entities, which serves as input to the relation classifier. This simplifies handling of relations with arbitrary arity, and enables multi-task learning with related relations. We evaluate this framework in two important precision medicine settings, demonstrating its effectiveness with both conventional supervised learning and distant supervision. Cross-sentence extraction produced larger knowledge bases. and multi-task learning significantly improved extraction accuracy. A thorough analysis of various LSTM approaches yielded useful insight the impact of linguistic analysis on extraction accuracy.

##### Abstract (translated by Google)
过去在关系提取方面的工作集中在单个句子中的二元关系上。最近NLP进入高价值领域已经引起了对跨多个句子提取n元关系的更普遍设置的兴趣。在本文中，我们探索了一个基于图的长短期记忆网络（图LSTMs）的一般关系抽取框架，可以很容易地扩展到交叉句子n元关系抽取。图表公式提供了探索不同LSTM方法的统一方式，并且包含了顺序，句法和语篇关系等各种句子间和句间依赖关系。为实体学习稳健的上下文表示，作为关系分类器的输入。这简化了处理与任意元数据的关系，并使相关关系的多任务学习成为可能。我们在两个重要的精准医学环境中评估这个框架，证明其在常规监督学习和远程监督下的有效性。交叉句子提取产生了更大的知识库。多任务学习显着提高了提取精度。通过对各种LSTM方法的深入分析，对语言分析对提取精度的影响产生了有益的认识。

##### URL
[https://arxiv.org/abs/1708.03743](https://arxiv.org/abs/1708.03743)

##### PDF
[https://arxiv.org/pdf/1708.03743](https://arxiv.org/pdf/1708.03743)

