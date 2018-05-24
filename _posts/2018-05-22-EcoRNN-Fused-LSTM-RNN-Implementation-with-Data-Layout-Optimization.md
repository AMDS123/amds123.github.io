---
layout: post
title: "EcoRNN: Fused LSTM RNN Implementation with Data Layout Optimization"
date: 2018-05-22 23:01:25
categories: arXiv_AI
tags: arXiv_AI Optimization RNN Deep_Learning
author: Bojian Zheng, Akshay Nair, Qiongsi Wu, Nandita Vijaykumar, Gennady Pekhimenko
mathjax: true
---

* content
{:toc}

##### Abstract
Long-Short-Term-Memory Recurrent Neural Network (LSTM RNN) is a state-of-the-art (SOTA) model for analyzing sequential data. Current implementations of LSTM RNN in machine learning frameworks usually either lack performance or flexibility. For example, default implementations in Tensorflow and MXNet invoke many tiny GPU kernels, leading to excessive overhead in launching GPU threads. Although cuDNN, NVIDIA's deep learning library, can accelerate performance by around 2x, it is closed-source and inflexible, hampering further research and performance improvements in frameworks, such as PyTorch, that use cuDNN as their backend. In this paper, we introduce a new RNN implementation called EcoRNN that is significantly faster than the SOTA open-source implementation in MXNet and is competitive with the closed-source cuDNN. We show that (1) fusing tiny GPU kernels and (2) applying data layout optimization can give us a maximum performance boost of 3x over MXNet default and 1.5x over cuDNN implementations. Our optimizations also apply to other RNN cell types such as LSTM variants and Gated Recurrent Units (GRUs). We integrate EcoRNN into MXNet Python library and open-source it to benefit machine learning practitioners.

##### Abstract (translated by Google)
长期短期记忆递归神经网络（LSTM RNN）是用于分析顺序数据的最先进的（SOTA）模型。目前机器学习框架中的LSTM RNN实现通常缺乏性能或灵活性。例如，Tensorflow和MXNet中的默认实现会调用许多微小的GPU内核，导致启动GPU线程的开销过大。虽然NVIDIA的深度学习库cuDNN可以将性能提高2倍左右，但是它是封闭源代码和不灵活的，阻碍了在使用cuDNN作为后端的PyTorch等框架中的进一步研究和性能改进。在本文中，我们介绍了一种名为EcoRNN的新RNN实现，它比MXNet中的SOTA开源实现快得多，并且与闭源cuDNN相比具有竞争力。我们展示（1）融合微型GPU内核和（2）应用数据布局优化可以使MXNet默认性能提升3倍，而cuDNN实现提升1.5倍。我们的优化还适用于其他RNN小区类型，例如LSTM变体和门控循环单元（GRU）。我们将EcoRNN整合到MXNet Python库中，并将其开源，以使机器学习从业人员受益。

##### URL
[http://arxiv.org/abs/1805.08899](http://arxiv.org/abs/1805.08899)

##### PDF
[http://arxiv.org/pdf/1805.08899](http://arxiv.org/pdf/1805.08899)

