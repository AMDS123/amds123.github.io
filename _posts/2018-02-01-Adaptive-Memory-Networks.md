---
layout: post
title: "Adaptive Memory Networks"
date: 2018-02-01 22:33:56
categories: arXiv_AI
tags: arXiv_AI QA Inference Memory_Networks
author: Daniel Li, Asim Kadav
mathjax: true
---

* content
{:toc}

##### Abstract
We present Adaptive Memory Networks (AMN) that processes input-question pairs to dynamically construct a network architecture optimized for lower inference times for Question Answering (QA) tasks. AMN processes the input story to extract entities and stores them in memory banks. Starting from a single bank, as the number of input entities increases, AMN learns to create new banks as the entropy in a single bank becomes too high. Hence, after processing an input-question(s) pair, the resulting network represents a hierarchical structure where entities are stored in different banks, distanced by question relevance. At inference, one or few banks are used, creating a tradeoff between accuracy and performance. AMN is enabled by dynamic networks that allow input dependent network creation and efficiency in dynamic mini-batching as well as our novel bank controller that allows learning discrete decision making with high accuracy. In our results, we demonstrate that AMN learns to create variable depth networks depending on task complexity and reduces inference times for QA tasks.

##### Abstract (translated by Google)
我们提出了自适应内存网络（AMN），它处理输入 - 问题对，以动态地构建针对问题回答（QA）任务的较低推断时间而优化的网络体系结构。 AMN处理输入故事以提取实体并将其存储在存储体中。从单一银行开始，随着投入实体数量的增加，AMN学习创建新的银行，因为单一银行的熵过高。因此，在处理一个或多个输入问题对之后，所得到的网络表示一个分层结构，其中实体被存储在不同的存储库中，通过问题的相关性来隔开。推断时，使用一个或几个银行，在准确性和性能之间进行权衡。 AMN由动态网络启用，允许输入相关的网络创建和动态小批量生产效率，以及我们新颖的银行控制器，允许高精度地学习离散决策。在我们的研究结果中，我们证明AMN学习根据任务的复杂性创建可变深度网络，并减少QA任务的推理时间。

##### URL
[https://arxiv.org/abs/1802.00510](https://arxiv.org/abs/1802.00510)

##### PDF
[https://arxiv.org/pdf/1802.00510](https://arxiv.org/pdf/1802.00510)

