---
layout: post
title: "Attentive Memory Networks: Efficient Machine Reading for Conversational Search"
date: 2017-12-19 21:43:59
categories: arXiv_CL
tags: arXiv_CL Knowledge Memory_Networks
author: Tom Kenter, Maarten de Rijke
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in conversational systems have changed the search paradigm. Traditionally, a user poses a query to a search engine that returns an answer based on its index, possibly leveraging external knowledge bases and conditioning the response on earlier interactions in the search session. In a natural conversation, there is an additional source of information to take into account: utterances produced earlier in a conversation can also be referred to and a conversational IR system has to keep track of information conveyed by the user during the conversation, even if it is implicit. We argue that the process of building a representation of the conversation can be framed as a machine reading task, where an automated system is presented with a number of statements about which it should answer questions. The questions should be answered solely by referring to the statements provided, without consulting external knowledge. The time is right for the information retrieval community to embrace this task, both as a stand-alone task and integrated in a broader conversational search setting. In this paper, we focus on machine reading as a stand-alone task and present the Attentive Memory Network (AMN), an end-to-end trainable machine reading algorithm. Its key contribution is in efficiency, achieved by having an hierarchical input encoder, iterating over the input only once. Speed is an important requirement in the setting of conversational search, as gaps between conversational turns have a detrimental effect on naturalness. On 20 datasets commonly used for evaluating machine reading algorithms we show that the AMN achieves performance comparable to the state-of-the-art models, while using considerably fewer computations.

##### Abstract (translated by Google)
会话系统的最新进展改变了搜索模式。传统上，用户向搜索引擎提出查询，该搜索引擎基于其索引返回答案，可能利用外部知识库并在搜索会话的早期交互中调节响应。在自然对话中，有一个额外的信息来源需要考虑：对话中早先产生的话语也可以被引用，而对话式IR系统必须跟踪用户在对话期间传达的信息，即使它是隐含的。我们认为，建立对话表示的过程可以被定义为一个机器阅读任务，在这个过程中，一个自动化系统被提供了一些关于它应该回答问题的陈述。这些问题只能通过参考所提供的陈述来回答，而不需要咨询外部的知识。信息检索社区接受这一任务的时机是正确的，既是一个独立的任务，也是整合在一个更广泛的对话式搜索环境中。在本文中，我们专注于机器阅读作为一项独立的任务，并提出细致记忆网络（AMN），一种端到端的可训练机器阅读算法。它的主要贡献在于效率，通过使用分层输入编码器实现，只对输入迭代一次。速度是对话式搜索设置的重要要求，因为会话轮回之间的差距对自然度有不利影响。在通常用于评估机器读取算法的20个数据集上，我们展示了AMN达到与最先进的模型相当的性能，同时使用更少的计算。

##### URL
[https://arxiv.org/abs/1712.07229](https://arxiv.org/abs/1712.07229)

##### PDF
[https://arxiv.org/pdf/1712.07229](https://arxiv.org/pdf/1712.07229)

