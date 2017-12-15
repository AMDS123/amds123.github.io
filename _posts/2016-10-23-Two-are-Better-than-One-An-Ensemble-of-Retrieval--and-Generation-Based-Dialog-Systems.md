---
layout: post
title: "Two are Better than One: An Ensemble of Retrieval- and Generation-Based Dialog Systems"
date: 2016-10-23 11:22:40
categories: arXiv_CL
tags: arXiv_CL Attention RNN
author: Yiping Song, Rui Yan, Xiang Li, Dongyan Zhao, Ming Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Open-domain human-computer conversation has attracted much attention in the field of NLP. Contrary to rule- or template-based domain-specific dialog systems, open-domain conversation usually requires data-driven approaches, which can be roughly divided into two categories: retrieval-based and generation-based systems. Retrieval systems search a user-issued utterance (called a query) in a large database, and return a reply that best matches the query. Generative approaches, typically based on recurrent neural networks (RNNs), can synthesize new replies, but they suffer from the problem of generating short, meaningless utterances. In this paper, we propose a novel ensemble of retrieval-based and generation-based dialog systems in the open domain. In our approach, the retrieved candidate, in addition to the original query, is fed to an RNN-based reply generator, so that the neural model is aware of more information. The generated reply is then fed back as a new candidate for post-reranking. Experimental results show that such ensemble outperforms each single part of it by a large margin.

##### Abstract (translated by Google)
开放领域的人机对话在NLP领域备受瞩目。与基于规则或模板的特定于域的对话系统相反，开放域对话通常需要数据驱动的方法，大致可以分为两类：基于检索的系统和基于生成的系统。检索系统在大型数据库中搜索用户发出的话语（称为查询），并返回与查询最匹配的答复。通常基于递归神经网络（RNN）的生成方法可以合成新的答复，但是它们遭受产生短而无意义的话语的问题。在本文中，我们提出了一个新颖的基于检索和基于生成的对话系统在开放领域的集合。在我们的方法中，除了原始的查询之外，所检索的候选者被馈送到基于RNN的应答生成器，使得神经模型意识到更多的信息。生成的答复然后反馈作为一个新的候选人后重新排名。实验结果表明，这样的集成大大优于其单个部分。

##### URL
[https://arxiv.org/abs/1610.07149](https://arxiv.org/abs/1610.07149)

##### PDF
[https://arxiv.org/pdf/1610.07149](https://arxiv.org/pdf/1610.07149)

