---
layout: post
title: "Semi-tied Units for Efficient Gating in LSTM and Highway Networks"
date: 2018-06-18 06:49:00
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition RNN Recognition
author: Chao Zhang, Philip Woodland
mathjax: true
---

* content
{:toc}

##### Abstract
Gating is a key technique used for integrating information from multiple sources by long short-term memory (LSTM) models and has recently also been applied to other models such as the highway network. Although gating is powerful, it is rather expensive in terms of both computation and storage as each gating unit uses a separate full weight matrix. This issue can be severe since several gates can be used together in e.g. an LSTM cell. This paper proposes a semi-tied unit (STU) approach to solve this efficiency issue, which uses one shared weight matrix to replace those in all the units in the same layer. The approach is termed "semi-tied" since extra parameters are used to separately scale each of the shared output values. These extra scaling factors are associated with the network activation functions and result in the use of parameterised sigmoid, hyperbolic tangent, and rectified linear unit functions. Speech recognition experiments using British English multi-genre broadcast data showed that using STUs can reduce the calculation and storage cost by a factor of three for highway networks and four for LSTMs, while giving similar word error rates to the original models.

##### Abstract (translated by Google)
门控是用于通过长期短期记忆（LSTM）模型整合来自多个来源的信息的关键技术，并且最近还被应用于其他模型，例如高速公路网络。尽管门控功能强大，但在计算和存储方面都相当昂贵，因为每个门控单元都使用单独的完整权重矩阵。这个问题可能很严重，因为几个门可以一起用于例如一个LSTM单元。本文提出了一个半连接单元（STU）方法来解决这个效率问题，它使用一个共享权重矩阵来替换同一层中所有单元中的那些。该方法被称为“半绑定”，因为额外的参数用于分别缩放每个共享输出值。这些额外的比例因子与网络激活函数相关联，并导致使用参数化的S形，双曲正切和整流后的线性单位函数。使用英国英语多类型广播数据的语音识别实验表明，使用STU可以将公路网络的计算和存储成本减少三倍，LSTM的计算和存储成本减少四倍，同时给原始模型提供类似的字错误率。

##### URL
[http://arxiv.org/abs/1806.06513](http://arxiv.org/abs/1806.06513)

##### PDF
[http://arxiv.org/pdf/1806.06513](http://arxiv.org/pdf/1806.06513)

