---
layout: post
title: "Entity Commonsense Representation for Neural Abstractive Summarization"
date: 2018-06-14 12:41:50
categories: arXiv_CL
tags: arXiv_CL Knowledge Attention Summarization
author: Reinald Kim Amplayo, Seonjae Lim, Seung-won Hwang
mathjax: true
---

* content
{:toc}

##### Abstract
A major proportion of a text summary includes important entities found in the original text. These entities build up the topic of the summary. Moreover, they hold commonsense information once they are linked to a knowledge base. Based on these observations, this paper investigates the usage of linked entities to guide the decoder of a neural text summarizer to generate concise and better summaries. To this end, we leverage on an off-the-shelf entity linking system (ELS) to extract linked entities and propose Entity2Topic (E2T), a module easily attachable to a sequence-to-sequence model that transforms a list of entities into a vector representation of the topic of the summary. Current available ELS's are still not sufficiently effective, possibly introducing unresolved ambiguities and irrelevant entities. We resolve the imperfections of the ELS by (a) encoding entities with selective disambiguation, and (b) pooling entity vectors using firm attention. By applying E2T to a simple sequence-to-sequence model with attention mechanism as base model, we see significant improvements of the performance in the Gigaword (sentence to title) and CNN (long document to multi-sentence highlights) summarization datasets by at least 2 ROUGE points.

##### Abstract (translated by Google)
文本摘要的主要部分包括原始文本中的重要实体。这些实体构建了摘要的主题。而且，一旦他们与知识库联系在一起，他们就拥有常识信息。基于这些观察，本文调查了链接实体的用法，以指导神经文本汇总器的解码器生成简洁和更好的摘要。为此，我们利用现成的实体链接系统（ELS）提取链接的实体并提出Entity2Topic（E2T）模块，该模块可轻松连接到序列到序列模型，将实体列表转换为摘要的主题的矢量表示。目前可用的ELS仍然不够有效，可能引入未解决的含糊和不相关的实体。我们通过以下方式来解决ELS的不完善性：（a）使用选择性消除歧义的方式对实体进行编码，以及（b）使用公司的注意力来合并实体向量。通过将E2T应用于以注意机制为基础模型的简单序列 - 序列模型，我们看到Gigaword（句子标题）和CNN（长文档到多句高亮）摘要数据集的性能显着提高2个ROUGE点。

##### URL
[http://arxiv.org/abs/1806.05504](http://arxiv.org/abs/1806.05504)

##### PDF
[http://arxiv.org/pdf/1806.05504](http://arxiv.org/pdf/1806.05504)

