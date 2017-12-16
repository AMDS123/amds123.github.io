---
layout: post
title: "Learning long-term dependencies for action recognition with a biologically-inspired deep network"
date: 2017-03-19 08:27:24
categories: arXiv_CV
tags: arXiv_CV Attention Action_Recognition Embedding RNN Recognition
author: Yemin Shi, Yonghong Tian, Yaowei Wang, Tiejun Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Despite a lot of research efforts devoted in recent years, how to efficiently learn long-term dependencies from sequences still remains a pretty challenging task. As one of the key models for sequence learning, recurrent neural network (RNN) and its variants such as long short term memory (LSTM) and gated recurrent unit (GRU) are still not powerful enough in practice. One possible reason is that they have only feedforward connections, which is different from the biological neural system that is typically composed of both feedforward and feedback connections. To address this problem, this paper proposes a biologically-inspired deep network, called shuttleNet\footnote{Our code is available at \url{this https URL}}. Technologically, the shuttleNet consists of several processors, each of which is a GRU while associated with multiple groups of cells and states. Unlike traditional RNNs, all processors inside shuttleNet are loop connected to mimic the brain's feedforward and feedback connections, in which they are shared across multiple pathways in the loop connection. Attention mechanism is then employed to select the best information flow pathway. Extensive experiments conducted on two benchmark datasets (i.e UCF101 and HMDB51) show that we can beat state-of-the-art methods by simply embedding shuttleNet into a CNN-RNN framework.

##### Abstract (translated by Google)
尽管近年来有很多的研究工作，但是如何从序列中有效地学习长期依赖关系仍然是一个相当具有挑战性的任务。作为序列学习的重要模型之一，在实践中，递归神经网络（RNN）及其长期短期记忆（LSTM）和门控循环单元（GRU）等变体仍然不够强大。一个可能的原因是它们只有前馈连接，这与通常由前馈和反馈连接组成的生物神经系统不同。为了解决这个问题，本文提出了一个生物启发式的深层网络，称为shuttleNet \ footnote {我们的代码可以在\ url {this https URL}中找到。在技​​术上，ShuttleNet由多个处理器组成，每个处理器都是一个GRU，同时与多组单元和状态相关联。与传统的RNN不同，ShuttleNet内部的所有处理器都是环形连接的，以模拟大脑的前馈和反馈连接，在连接中它们在多个路径上共享。然后使用注意机制选择最佳的信息流通路。在两个基准数据集（即UCF101和HMDB51）上进行的大量实验表明，只需将shuttleNet嵌入到CNN-RNN框架中，就可以击败最先进的方法。

##### URL
[https://arxiv.org/abs/1611.05216](https://arxiv.org/abs/1611.05216)

##### PDF
[https://arxiv.org/pdf/1611.05216](https://arxiv.org/pdf/1611.05216)

