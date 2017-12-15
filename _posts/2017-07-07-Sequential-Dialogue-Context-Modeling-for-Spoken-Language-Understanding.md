---
layout: post
title: "Sequential Dialogue Context Modeling for Spoken Language Understanding"
date: 2017-07-07 21:35:02
categories: arXiv_CL
tags: arXiv_CL RNN
author: Ankur Bapna, Gokhan Tur, Dilek Hakkani-Tur, Larry Heck
mathjax: true
---

* content
{:toc}

##### Abstract
Spoken Language Understanding (SLU) is a key component of goal oriented dialogue systems that would parse user utterances into semantic frame representations. Traditionally SLU does not utilize the dialogue history beyond the previous system turn and contextual ambiguities are resolved by the downstream components. In this paper, we explore novel approaches for modeling dialogue context in a recurrent neural network (RNN) based language understanding system. We propose the Sequential Dialogue Encoder Network, that allows encoding context from the dialogue history in chronological order. We compare the performance of our proposed architecture with two context models, one that uses just the previous turn context and another that encodes dialogue context in a memory network, but loses the order of utterances in the dialogue history. Experiments with a multi-domain dialogue dataset demonstrate that the proposed architecture results in reduced semantic frame error rates.

##### Abstract (translated by Google)
口语语言理解（SLU）是面向目标的对话系统的关键组件，其将用户话语解析为语义框架表示。传统上SLU不利用超出先前系统转向的对话历史，并且下游组件解决了上下文歧义。在本文中，我们探索了一种基于递归神经网络（RNN）的语言理解系统中对话情境建模的新方法。我们提出了Sequential Dialogue Encoder Network，它允许按时间顺序从对话历史中编码上下文。我们将我们提出的架构的性能与两个上下文模型进行比较，一个只使用前一个上下文，另一个模拟内存网络中的对话上下文，但丢失对话历史中的话语顺序。多域对话数据集的实验表明，所提出的体系结构导致语义帧错误率降低。

##### URL
[https://arxiv.org/abs/1705.03455](https://arxiv.org/abs/1705.03455)

##### PDF
[https://arxiv.org/pdf/1705.03455](https://arxiv.org/pdf/1705.03455)

