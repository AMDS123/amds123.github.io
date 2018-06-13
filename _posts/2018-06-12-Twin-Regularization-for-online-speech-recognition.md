---
layout: post
title: "Twin Regularization for online speech recognition"
date: 2018-06-12 01:00:03
categories: arXiv_AI
tags: arXiv_AI Regularization Face Speech_Recognition Prediction Recognition
author: Mirco Ravanelli, Dmitriy Serdyuk, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
Online speech recognition is crucial for developing natural human-machine interfaces. This modality, however, is significantly more challenging than off-line ASR, since real-time/low-latency constraints inevitably hinder the use of future information, that is known to be very helpful to perform robust predictions. A popular solution to mitigate this issue consists of feeding neural acoustic models with context windows that gather some future frames. This introduces a latency which depends on the number of employed look-ahead features. This paper explores a different approach, based on estimating the future rather than waiting for it. Our technique encourages the hidden representations of a unidirectional recurrent network to embed some useful information about the future. Inspired by a recently proposed technique called Twin Networks, we add a regularization term that forces forward hidden states to be as close as possible to cotemporal backward ones, computed by a "twin" neural network running backwards in time. The experiments, conducted on a number of datasets, recurrent architectures, input features, and acoustic conditions, have shown the effectiveness of this approach. One important advantage is that our method does not introduce any additional computation at test time if compared to standard unidirectional recurrent networks.

##### Abstract (translated by Google)
在线语音识别对于开发自然人机界面至关重要。然而，这种模式比离线式ASR更具挑战性，因为实时/低延迟约束不可避免地妨碍未来信息的使用，这对于执行可靠预测是非常有用的。缓解这个问题的流行解决方案包括将神经声学模型与收集一些未来帧的上下文窗口相提供。这会引入延迟，这取决于所采用的预测功能的数量。本文基于对未来的估计而不是等待，探讨了一种不同的方法。我们的技术鼓励单向循环网络的隐藏表示嵌入一些关于未来的有用信息。受最近提出的称为双胞胎网络的技术的启发，我们增加了一个正则化术语，迫使前向隐藏状态尽可能接近于后向的状态，由时间倒退的“双胞胎”神经网络计算。在许多数据集，循环体系结构，输入特征和声学条件上进行的实验表明了这种方法的有效性。一个重要的优点是，与标准的单向循环网络相比，我们的方法在测试时间不会引入任何额外的计算。

##### URL
[http://arxiv.org/abs/1804.05374](http://arxiv.org/abs/1804.05374)

##### PDF
[http://arxiv.org/pdf/1804.05374](http://arxiv.org/pdf/1804.05374)

