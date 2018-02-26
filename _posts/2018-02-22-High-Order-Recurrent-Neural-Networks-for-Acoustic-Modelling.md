---
layout: post
title: "High Order Recurrent Neural Networks for Acoustic Modelling"
date: 2018-02-22 22:01:05
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition RNN Recognition
author: Chao Zhang, Philip Woodland
mathjax: true
---

* content
{:toc}

##### Abstract
Vanishing long-term gradients are a major issue in training standard recurrent neural networks (RNNs), which can be alleviated by long short-term memory (LSTM) models with memory cells. However, the extra parameters associated with the memory cells mean an LSTM layer has four times as many parameters as an RNN with the same hidden vector size. This paper addresses the vanishing gradient problem using a high order RNN (HORNN) which has additional connections from multiple previous time steps. Speech recognition experiments using British English multi-genre broadcast (MGB3) data showed that the proposed HORNN architectures for rectified linear unit and sigmoid activation functions reduced word error rates (WER) by 4.2% and 6.3% over the corresponding RNNs, and gave similar WERs to a (projected) LSTM while using only 20%--50% of the recurrent layer parameters and computation.

##### Abstract (translated by Google)
消除长期梯度是训练标准递归神经网络（RNN）中的主要问题，其可以通过具有记忆细胞的长期短期记忆（LSTM）模型来缓解。然而，与存储器单元相关联的额外参数意味着LSTM层具有四倍于具有相同隐藏矢量大小的RNN的参数。本文讨论使用高阶RNN（HORNN）的消失梯度问题，该问题具有来自多个先前时间步骤的附加连接。使用英国英语多类型广播（MGB3）数据的语音识别实验表明，所提出的用于校正线性单位和S形激活函数的HORNN架构比相应的RNN减少了4.2％和6.3％的误字率（WER），并给出了类似的WER到（投影）LSTM，而只使用20％-50％的递归层参数和计算。

##### URL
[https://arxiv.org/abs/1802.08314](https://arxiv.org/abs/1802.08314)

##### PDF
[https://arxiv.org/pdf/1802.08314](https://arxiv.org/pdf/1802.08314)

