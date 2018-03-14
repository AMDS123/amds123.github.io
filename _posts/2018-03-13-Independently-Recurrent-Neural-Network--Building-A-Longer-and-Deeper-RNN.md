---
layout: post
title: "Independently Recurrent Neural Network : Building A Longer and Deeper RNN"
date: 2018-03-13 14:27:42
categories: arXiv_CV
tags: arXiv_CV RNN
author: Shuai Li, Wanqing Li, Chris Cook, Ce Zhu, Yanbo Gao
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural networks (RNNs) have been widely used for processing sequential data. However, RNNs are commonly difficult to train due to the well-known gradient vanishing and exploding problems and hard to learn long-term patterns. Long short-term memory (LSTM) and gated recurrent unit (GRU) were developed to address these problems, but the use of hyperbolic tangent and the sigmoid action functions results in gradient decay over layers. Consequently, construction of an efficiently trainable deep network is challenging. In addition, all the neurons in an RNN layer are entangled together and their behaviour is hard to interpret. To address these problems, a new type of RNN, referred to as independently recurrent neural network (IndRNN), is proposed in this paper, where neurons in the same layer are independent of each other and they are connected across layers. We have shown that an IndRNN can be easily regulated to prevent the gradient exploding and vanishing problems while allowing the network to learn long-term dependencies. Moreover, an IndRNN can work with non-saturated activation functions such as relu (rectified linear unit) and be still trained robustly. Multiple IndRNNs can be stacked to construct a network that is deeper than the existing RNNs. Experimental results have shown that the proposed IndRNN is able to process very long sequences (over 5000 time steps), can be used to construct very deep networks (21 layers used in the experiment) and still be trained robustly. Better performances have been achieved on various tasks by using IndRNNs compared with the traditional RNN and LSTM.

##### Abstract (translated by Google)
递归神经网络（RNN）已被广泛用于处理顺序数据。然而，由于众所周知的梯度消失和爆炸问题以及难以学习的长期模式，RNN通常难以训练。长期短期记忆（LSTM）和门控循环单元（GRU）是为解决这些问题而开发的，但双曲正切和S形动作函数的使用导致层间梯度衰减。因此，构建有效可训练的深度网络具有挑战性。另外，RNN层中的所有神经元都缠在一起，他们的行为很难解释。为解决这些问题，本文提出了一种新型的RNN，称为独立递归神经网络（IndRNN），其中同一层中的神经元彼此独立并且它们跨层连接。我们已经表明，IndRNN可以很容易地进行管理，以防止梯度爆炸和消失的问题，同时允许网络学习长期依赖性。此外，IndRNN可以使用非饱和激活功能，如relu（整流线性单元），并且仍然可以稳健地训练。可以堆叠多个IndRNN以构建比现有RNN更深的网络。实验结果表明，所提出的IndRNN能够处理非常长的序列（超过5000个时间步长），可以用来构建非常深的网络（在实验中使用21层）并且仍然能够被强健地训练。与传统的RNN和LSTM相比，使用IndRNN可以在各种任务中取得更好的性能。

##### URL
[http://arxiv.org/abs/1803.04831](http://arxiv.org/abs/1803.04831)

##### PDF
[http://arxiv.org/pdf/1803.04831](http://arxiv.org/pdf/1803.04831)

