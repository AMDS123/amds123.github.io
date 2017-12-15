---
layout: post
title: "Flexible End-to-End Dialogue System for Knowledge Grounded Conversation"
date: 2017-09-13 11:59:06
categories: arXiv_CL
tags: arXiv_CL Knowledge QA
author: Wenya Zhu, Kaixiang Mo, Yu Zhang, Zhangbin Zhu, Xuezheng Peng, Qiang Yang
mathjax: true
---

* content
{:toc}

##### Abstract
In knowledge grounded conversation, domain knowledge plays an important role in a special domain such as Music. The response of knowledge grounded conversation might contain multiple answer entities or no entity at all. Although existing generative question answering (QA) systems can be applied to knowledge grounded conversation, they either have at most one entity in a response or cannot deal with out-of-vocabulary entities. We propose a fully data-driven generative dialogue system GenDS that is capable of generating responses based on input message and related knowledge base (KB). To generate arbitrary number of answer entities even when these entities never appear in the training set, we design a dynamic knowledge enquirer which selects different answer entities at different positions in a single response, according to different local context. It does not rely on the representations of entities, enabling our model deal with out-of-vocabulary entities. We collect a human-human conversation data (ConversMusic) with knowledge annotations. The proposed method is evaluated on CoversMusic and a public question answering dataset. Our proposed GenDS system outperforms baseline methods significantly in terms of the BLEU, entity accuracy, entity recall and human evaluation. Moreover,the experiments also demonstrate that GenDS works better even on small datasets.

##### Abstract (translated by Google)
在基于知识的对话中，领域知识在诸如音乐这样的特殊领域中起着重要的作用。基于知识的对话的响应可能包含多个答案实体，或者根本不包含实体。虽然现有的生成性问答系统（QA）可以应用于基于知识的对话，但是它们最多只能有一个实体作为响应，或者不能处理超出实际的词汇实体。我们提出一个全面的数据驱动的生成对话系统GenDS，能够根据输入消息和相关知识库（KB）产生响应。为了生成任意数量的答案实体，即使这些实体从未出现在训练集中，我们设计了一个动态知识查询器，根据不同的本地情境，在单个响应中选择不同位置的不同答案实体。它不依赖于实体的表示，使我们的模型能够处理超出词汇的实体。我们收集带有知识注释的人际交谈数据（ConversMusic）。所提出的方法在封面音乐和公共问答数据集上进行评估。我们提出的GenDS系统在BLEU，实体准确性，实体召回和人类评估方面均优于基准方法。此外，实验还表明，GenDS即使在小数据集上也能更好地工作。

##### URL
[https://arxiv.org/abs/1709.04264](https://arxiv.org/abs/1709.04264)

##### PDF
[https://arxiv.org/pdf/1709.04264](https://arxiv.org/pdf/1709.04264)

