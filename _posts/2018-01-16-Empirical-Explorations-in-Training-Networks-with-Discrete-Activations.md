---
layout: post
title: "Empirical Explorations in Training Networks with Discrete Activations"
date: 2018-01-16 08:47:18
categories: arXiv_AI
tags: arXiv_AI Classification
author: Shumeet Baluja
mathjax: true
---

* content
{:toc}

##### Abstract
We present extensive experiments training and testing hidden units in deep networks that emit only a predefined, static, number of discretized values. These units provide benefits in real-world deployment in systems in which memory and/or computation may be limited. Additionally, they are particularly well suited for use in large recurrent network models that require the maintenance of large amounts of internal state in memory. Surprisingly, we find that despite reducing the number of values that can be represented in the output activations from $2^{32}-2^{64}$ to between 64 and 256, there is little to no degradation in network performance across a variety of different settings. We investigate simple classification and regression tasks, as well as memorization and compression problems. We compare the results with more standard activations, such as tanh and relu. Unlike previous discretization studies which often concentrate only on binary units, we examine the effects of varying the number of allowed activation levels. Compared to existing approaches for discretization, the approach presented here is both conceptually and programatically simple, has no stochastic component, and allows the training, testing, and usage phases to be treated in exactly the same manner.

##### Abstract (translated by Google)
我们提出了广泛的实验来训练和测试深层网络中的隐藏单元，它们只发出预定义的静态数量的离散值。这些单元在存储器和/或计算可能受限的系统中为现实世界的部署提供了好处。此外，它们特别适合用于需要在内存中维护大量内部状态的大型经常性网络模型。令人惊讶的是，我们发现，尽管将输出激活中可以表示的值从$ 2 ^ {32} -2 ^ {64} $减少到64和256之间，那么各个网络的网络性能几乎没有降低不同的设置。我们调查简单的分类和回归任务，以及记忆和压缩问题。我们比较结果与更多标准的激活，例如tanh和relu。不同于以往的离散化研究往往只集中在二元单位，我们研究了不同的允许激活水平的数量的影响。与现有的离散化方法相比，这里介绍的方法在概念和程序上都很简单，没有随机组件，并且可以以完全相同的方式处理训练，测试和使用阶段。

##### URL
[http://arxiv.org/abs/1801.05156](http://arxiv.org/abs/1801.05156)

##### PDF
[http://arxiv.org/pdf/1801.05156](http://arxiv.org/pdf/1801.05156)

