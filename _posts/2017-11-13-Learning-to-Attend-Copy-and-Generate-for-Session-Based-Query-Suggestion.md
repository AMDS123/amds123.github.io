---
layout: post
title: "Learning to Attend, Copy, and Generate for Session-Based Query Suggestion"
date: 2017-11-13 11:29:43
categories: arXiv_CL
tags: arXiv_CL Attention
author: Mostafa Dehghani, Sascha Rothe, Enrique Alfonseca, Pascal Fleury
mathjax: true
---

* content
{:toc}

##### Abstract
Users try to articulate their complex information needs during search sessions by reformulating their queries. To make this process more effective, search engines provide related queries to help users in specifying the information need in their search process. In this paper, we propose a customized sequence-to-sequence model for session-based query suggestion. In our model, we employ a query-aware attention mechanism to capture the structure of the session context. is enables us to control the scope of the session from which we infer the suggested next query, which helps not only handle the noisy data but also automatically detect session boundaries. Furthermore, we observe that, based on the user query reformulation behavior, within a single session a large portion of query terms is retained from the previously submitted queries and consists of mostly infrequent or unseen terms that are usually not included in the vocabulary. We therefore empower the decoder of our model to access the source words from the session context during decoding by incorporating a copy mechanism. Moreover, we propose evaluation metrics to assess the quality of the generative models for query suggestion. We conduct an extensive set of experiments and analysis. e results suggest that our model outperforms the baselines both in terms of the generating queries and scoring candidate queries for the task of query suggestion.

##### Abstract (translated by Google)
用户尝试在搜索会话中通过重新表达他们的疑问来表达他们复杂的信息需求。为了使这个过程更加有效，搜索引擎提供相关的查询来帮助用户在他们的搜索过程中指定信息需求。在本文中，我们提出了一种基于会话的查询建议的定制序列到序列模型。在我们的模型中，我们使用了查询感知的注意机制来捕获会话上下文的结构。使我们能够控制会话的范围，从中推断出下一个查询，这不仅有助于处理有噪声的数据，还能自动检测会话边界。此外，我们观察到，基于用户查询重构行为，在单个会话中，从先前提交的查询中保留大部分查询词语，并且大多数是偶尔或不可见的词语，通常不包括在词汇表中。因此，我们使得我们的模型的解码器能够通过合并复制机制来在解码期间从会话上下文访问源语言。此外，我们提出评估指标来评估查询建议的生成模型的质量。我们进行了大量的实验和分析。 e结果表明，我们的模型在查询建议任务的生成查询和评分候选查询方面都优于基线。

##### URL
[https://arxiv.org/abs/1708.03418](https://arxiv.org/abs/1708.03418)

##### PDF
[https://arxiv.org/pdf/1708.03418](https://arxiv.org/pdf/1708.03418)

