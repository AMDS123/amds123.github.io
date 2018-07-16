---
layout: post
title: "Diversity driven Attention Model for Query-based Abstractive Summarization"
date: 2018-07-13 05:44:05
categories: arXiv_CL
tags: arXiv_CL Salient Attention Summarization
author: Preksha Nema, Mitesh Khapra, Anirban Laha, Balaraman Ravindran
mathjax: true
---

* content
{:toc}

##### Abstract
Abstractive summarization aims to generate a shorter version of the document covering all the salient points in a compact and coherent fashion. On the other hand, query-based summarization highlights those points that are relevant in the context of a given query. The encode-attend-decode paradigm has achieved notable success in machine translation, extractive summarization, dialog systems, etc. But it suffers from the drawback of generation of repeated phrases. In this work we propose a model for the query-based summarization task based on the encode-attend-decode paradigm with two key additions (i) a query attention model (in addition to document attention model) which learns to focus on different portions of the query at different time steps (instead of using a static representation for the query) and (ii) a new diversity based attention model which aims to alleviate the problem of repeating phrases in the summary. In order to enable the testing of this model we introduce a new query-based summarization dataset building on debatepedia. Our experiments show that with these two additions the proposed model clearly outperforms vanilla encode-attend-decode models with a gain of 28% (absolute) in ROUGE-L scores.

##### Abstract (translated by Google)
抽象概括旨在以紧凑和连贯的方式生成涵盖所有突出点的文档的较短版本。另一方面，基于查询的摘要突出显示在给定查询的上下文中相关的那些点。编码参与解码范例在机器翻译，提取摘要，对话系统等方面取得了显着的成功。但是它存在产生重复短语的缺点。在这项工作中，我们提出了一个基于编码参与解码范例的基于查询的摘要任务的模型，该模型具有两个关键的附加功能（i）查询注意模型（除文档注意模型之外），它学习专注于不同的部分。在不同时间步骤的查询（而不是使用查询的静态表示）和（ii）新的基于多样性的注意模型，其旨在减轻在摘要中重复短语的问题。为了能够测试这个模型，我们在辩论的基础上引入了一个新的基于查询的摘要数据集。我们的实验表明，通过这两个加法，所提出的模型明显优于香草编码 - 参与 - 解码模型，ROUGE-L得分增益为28％（绝对值）。

##### URL
[http://arxiv.org/abs/1704.08300](http://arxiv.org/abs/1704.08300)

##### PDF
[http://arxiv.org/pdf/1704.08300](http://arxiv.org/pdf/1704.08300)

