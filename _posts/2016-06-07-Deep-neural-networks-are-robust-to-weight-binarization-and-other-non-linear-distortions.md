---
layout: post
title: "Deep neural networks are robust to weight binarization and other non-linear distortions"
date: 2016-06-07 00:28:42
categories: arXiv_CV
tags: arXiv_CV
author: Paul Merolla, Rathinakumar Appuswamy, John Arthur, Steve K. Esser, Dharmendra Modha
mathjax: true
---

* content
{:toc}

##### Abstract
Recent results show that deep neural networks achieve excellent performance even when, during training, weights are quantized and projected to a binary representation. Here, we show that this is just the tip of the iceberg: these same networks, during testing, also exhibit a remarkable robustness to distortions beyond quantization, including additive and multiplicative noise, and a class of non-linear projections where binarization is just a special case. To quantify this robustness, we show that one such network achieves 11% test error on CIFAR-10 even with 0.68 effective bits per weight. Furthermore, we find that a common training heuristic--namely, projecting quantized weights during backpropagation--can be altered (or even removed) and networks still achieve a base level of robustness during testing. Specifically, training with weight projections other than quantization also works, as does simply clipping the weights, both of which have never been reported before. We confirm our results for CIFAR-10 and ImageNet datasets. Finally, drawing from these ideas, we propose a stochastic projection rule that leads to a new state of the art network with 7.64% test error on CIFAR-10 using no data augmentation.

##### Abstract (translated by Google)
最近的结果表明，即使在训练期间，权重被量化并被投影到二进制表示，深度神经网络也能获得优异的性能。在这里，我们表明这只是冰山一角：这些相同的网络，在测试过程中，也表现出超越量化的失真，包括加性和乘性噪声，以及一类非线性投影，二值化只是一个非常强大的鲁棒性特例。为了量化这种鲁棒性，我们证明了一个这样的网络在CIFAR-10上实现了11％的测试误差，即使是每个权重有0.68个有效位。此外，我们发现一个共同的训练启发式 - 即反向传播期间投射量化权重 - 可以被改变（或甚至被删除），并且网络在测试期间仍然达到基本水平的鲁棒性。具体地说，除量化之外的权重投影的训练也是有效的，就像简单地裁剪权重一样，两者之前从未被报告过。我们确认了CIFAR-10和ImageNet数据集的结果。最后，从这些观点出发，我们提出了一个随机投影规则，导致了在没有数据增强的情况下CIFAR-10的测试误差为7.64％的新的网络状态。

##### URL
[https://arxiv.org/abs/1606.01981](https://arxiv.org/abs/1606.01981)

##### PDF
[https://arxiv.org/pdf/1606.01981](https://arxiv.org/pdf/1606.01981)

