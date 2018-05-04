---
layout: post
title: "Accelerating Neural Transformer via an Average Attention Network"
date: 2018-05-03 05:44:38
categories: arXiv_CL
tags: arXiv_CL Attention
author: Biao Zhang, Deyi Xiong, Jinsong Su
mathjax: true
---

* content
{:toc}

##### Abstract
With parallelizable attention networks, the neural Transformer is very fast to train. However, due to the auto-regressive architecture and self-attention in the decoder, the decoding procedure becomes slow. To alleviate this issue, we propose an average attention network as an alternative to the self-attention network in the decoder of the neural Transformer. The average attention network consists of two layers, with an average layer that models dependencies on previous positions and a gating layer that is stacked over the average layer to enhance the expressiveness of the proposed attention network. We apply this network on the decoder part of the neural Transformer to replace the original target-side self-attention model. With masking tricks and dynamic programming, our model enables the neural Transformer to decode sentences over four times faster than its original version with almost no loss in training time and translation performance. We conduct a series of experiments on WMT17 translation tasks, where on 6 different language pairs, we obtain robust and consistent speed-ups in decoding.

##### Abstract (translated by Google)
借助可并行化的注意力网络，神经变压器的训练速度非常快。然而，由于解码器中的自回归结构和自我关注，解码过程变得缓慢。为了缓解这个问题，我们提出了一个平均关注网络作为神经变压器解码器中自我关注网络的替代方案。平均关注网络由两层组成，其中平均层模拟对先前位置的依赖性以及叠加在平均层上的门控层以增强所提出的关注网络的表达性。我们将这个网络应用于神经变压器的解码器部分，以取代原始的目标侧自我关注模型。通过屏蔽技巧和动态编程，我们的模型使神经变压器能够比原始版本更快地解码句子四倍，而且几乎不会损失训练时间和翻译表现。我们对WMT17翻译任务进行了一系列的实验，在6种不同的语言对中，我们获得了强大且一致的解码速度。

##### URL
[http://arxiv.org/abs/1805.00631](http://arxiv.org/abs/1805.00631)

##### PDF
[http://arxiv.org/pdf/1805.00631](http://arxiv.org/pdf/1805.00631)

