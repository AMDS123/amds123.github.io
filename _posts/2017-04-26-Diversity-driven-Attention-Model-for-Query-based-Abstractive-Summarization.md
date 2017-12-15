---
layout: post
title: "Diversity driven Attention Model for Query-based Abstractive Summarization"
date: 2017-04-26 19:06:37
categories: arXiv_CL
tags: arXiv_CL Salient Attention Summarization
author: Preksha Nema, Mitesh Khapra, Anirban Laha, Balaraman Ravindran
mathjax: true
---

* content
{:toc}

##### Abstract
Abstractive summarization aims to generate a shorter version of the document covering all the salient points in a compact and coherent fashion. On the other hand, query-based summarization highlights those points that are relevant in the context of a given query. The encode-attend-decode paradigm has achieved notable success in machine translation, extractive summarization, dialog systems, etc. But it suffers from the drawback of generation of repeated phrases. In this work we propose a model for the query-based summarization task based on the encode-attend-decode paradigm with two key additions (i) a query attention model (in addition to document attention model) which learns to focus on different portions of the query at different time steps (instead of using a static representation for the query) and (ii) a new diversity based attention model which aims to alleviate the problem of repeating phrases in the summary. In order to enable the testing of this model we introduce a new query-based summarization dataset building on debatepedia. Our experiments show that with these two additions the proposed model clearly outperforms vanilla encode-attend-decode models with a gain of 28\% (absolute) in ROUGE-L scores.

##### Abstract (translated by Google)
抽象概括旨在以紧凑和一致的方式生成一个覆盖所有要点的简短版本的文档。另一方面，基于查询的摘要将突出显示在给定查询的上下文中相关的那些点。编码参与解码范例在机器翻译，抽取摘要，对话系统等方面取得了显着的成功，但却遭受了重复短语产生的弊端。在这项工作中，我们提出了一个基于查询的摘要任务模型，基于编码参与解码范例，其中有两个关键的附加（i）查询关注模型（除了文档关注模型），学习关注不同部分在不同时间步骤的查询（而不是使用查询的静态表示）和（ii）基于新的基于多样性的注意模型，其目的在于减轻概要中重复短语的问题。为了能够对这个模型进行测试，我们引入了一个基于查询的摘要数据集，并在辩论百科上构建。我们的实验显示，通过这两个增加，所提出的模型明显优于在ROUGE-L得分中增益为28％（绝对值）的vanilla编码参与解码模型。

##### URL
[https://arxiv.org/abs/1704.08300](https://arxiv.org/abs/1704.08300)

##### PDF
[https://arxiv.org/pdf/1704.08300](https://arxiv.org/pdf/1704.08300)

