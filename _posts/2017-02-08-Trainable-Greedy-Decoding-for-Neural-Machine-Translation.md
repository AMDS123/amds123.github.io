---
layout: post
title: "Trainable Greedy Decoding for Neural Machine Translation"
date: 2017-02-08 13:56:16
categories: arXiv_SD
tags: arXiv_SD Attention
author: Jiatao Gu, Kyunghyun Cho, Victor O.K. Li
mathjax: true
---

* content
{:toc}

##### Abstract
Recent research in neural machine translation has largely focused on two aspects; neural network architectures and end-to-end learning algorithms. The problem of decoding, however, has received relatively little attention from the research community. In this paper, we solely focus on the problem of decoding given a trained neural machine translation model. Instead of trying to build a new decoding algorithm for any specific decoding objective, we propose the idea of trainable decoding algorithm in which we train a decoding algorithm to find a translation that maximizes an arbitrary decoding objective. More specifically, we design an actor that observes and manipulates the hidden state of the neural machine translation decoder and propose to train it using a variant of deterministic policy gradient. We extensively evaluate the proposed algorithm using four language pairs and two decoding objectives and show that we can indeed train a trainable greedy decoder that generates a better translation (in terms of a target decoding objective) with minimal computational overhead.

##### Abstract (translated by Google)
最近的神经机器翻译研究主要集中在两个方面：神经网络架构和端到端的学习算法。然而，解码的问题却得不到研究界的关注。在本文中，我们只关注给定一个训练的神经机器翻译模型的解码问题。我们没有试图为任何特定的解码目标建立新的解码算法，而是提出了可训练的解码算法的思想，在这种算法中，我们训练一个解码算法来寻找一个最大化任意解码目标的翻译。更具体地说，我们设计一个观察和操纵神经机器翻译解码器的隐藏状态的演员，并提出使用确定性策略梯度的变体来训练它。我们广泛地使用四个语言对和两个解码目标来评估所提出的算法，并且显示我们确实可以训练可训练的贪婪解码器，其以最小的计算开销生成更好的翻译（根据目标解码目标）。

##### URL
[https://arxiv.org/abs/1702.02429](https://arxiv.org/abs/1702.02429)

##### PDF
[https://arxiv.org/pdf/1702.02429](https://arxiv.org/pdf/1702.02429)

