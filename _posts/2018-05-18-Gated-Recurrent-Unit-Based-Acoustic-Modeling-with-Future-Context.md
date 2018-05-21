---
layout: post
title: "Gated Recurrent Unit Based Acoustic Modeling with Future Context"
date: 2018-05-18 02:33:53
categories: arXiv_CL
tags: arXiv_CL RNN
author: Jie Li, Xiaorui Wang, Yuanyuan Zhao, Yan Li
mathjax: true
---

* content
{:toc}

##### Abstract
The use of future contextual information is typically shown to be helpful for acoustic modeling. However, for the recurrent neural network (RNN), it's not so easy to model the future temporal context effectively, meanwhile keep lower model latency. In this paper, we attempt to design a RNN acoustic model that being capable of utilizing the future context effectively and directly, with the model latency and computation cost as low as possible. The proposed model is based on the minimal gated recurrent unit (mGRU) with an input projection layer inserted in it. Two context modules, temporal encoding and temporal convolution, are specifically designed for this architecture to model the future context. Experimental results on the Switchboard task and an internal Mandarin ASR task show that, the proposed model performs much better than long short-term memory (LSTM) and mGRU models, whereas enables online decoding with a maximum latency of 170 ms. This model even outperforms a very strong baseline, TDNN-LSTM, with smaller model latency and almost half less parameters.

##### Abstract (translated by Google)
通常表明对未来上下文信息的使用有助于声学建模。然而，对于递归神经网络（RNN）来说，对未来时间上下文进行有效建模并不容易，同时保持较低的模型延迟。在本文中，我们试图设计一种能够有效和直接地利用未来上下文的RNN声学模型，其模型延迟和计算成本尽可能低。所提出的模型基于最小门控循环单元（mGRU），其中插入了输入投影层。两种上下文模块，即时间编码和时间卷积，都是专门为此架构设计的，以对未来上下文进行建模。在交换机任务和内部普通话ASR任务上的实验结果表明，所提出的模型比长期短期存储器（LSTM）和mGRU模型执行得好得多，而在线解码能够实现170毫秒的最大延迟。该模型甚至胜过非常强大的基准TDNN-LSTM，具有较小的模型延迟和几乎一半的参数。

##### URL
[http://arxiv.org/abs/1805.07024](http://arxiv.org/abs/1805.07024)

##### PDF
[http://arxiv.org/pdf/1805.07024](http://arxiv.org/pdf/1805.07024)

