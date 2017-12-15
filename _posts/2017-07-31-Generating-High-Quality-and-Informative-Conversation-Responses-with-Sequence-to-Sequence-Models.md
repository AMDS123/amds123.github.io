---
layout: post
title: "Generating High-Quality and Informative Conversation Responses with Sequence-to-Sequence Models"
date: 2017-07-31 16:53:33
categories: arXiv_SD
tags: arXiv_SD Attention
author: Louis Shao, Stephan Gouws, Denny Britz, Anna Goldie, Brian Strope, Ray Kurzweil
mathjax: true
---

* content
{:toc}

##### Abstract
Sequence-to-sequence models have been applied to the conversation response generation problem where the source sequence is the conversation history and the target sequence is the response. Unlike translation, conversation responding is inherently creative. The generation of long, informative, coherent, and diverse responses remains a hard task. In this work, we focus on the single turn setting. We add self-attention to the decoder to maintain coherence in longer responses, and we propose a practical approach, called the glimpse-model, for scaling to large datasets. We introduce a stochastic beam-search algorithm with segment-by-segment reranking which lets us inject diversity earlier in the generation process. We trained on a combined data set of over 2.3B conversation messages mined from the web. In human evaluation studies, our method produces longer responses overall, with a higher proportion rated as acceptable and excellent as length increases, compared to baseline sequence-to-sequence models with explicit length-promotion. A back-off strategy produces better responses overall, in the full spectrum of lengths.

##### Abstract (translated by Google)
序列到序列模型已经被应用于对话响应产生问题，其中源序列是对话历史，目标序列是响应。与翻译不同，对话反应本身就具有创造性。产生长期的，信息丰富的，连贯的，多样的反应仍然是一个艰巨的任务。在这项工作中，我们专注于单圈设置。我们增加对解码器的自我注意力，以保持更长的响应的一致性，并且我们提出了一种称为瞥一模型的实用方法来缩放大数据集。我们引入一个随机的波束搜索算法，逐段重排，让我们在生成过程中更早地注入多样性。我们训练了从网上挖掘的超过2.3B会话消息的组合数据集。在人体评估研究中，我们的方法总体上产生较长的反应，与具有明确长度促进的基线序列 - 序列模型相比，较高的比例被认为是可接受的，并且长度优良。退避策略在整个长度范围内产生更好的响应。

##### URL
[https://arxiv.org/abs/1701.03185](https://arxiv.org/abs/1701.03185)

##### PDF
[https://arxiv.org/pdf/1701.03185](https://arxiv.org/pdf/1701.03185)

