---
layout: post
title: "Training RNNs as Fast as CNNs"
date: 2017-11-05 12:44:43
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition CNN RNN Classification Language_Model Recognition
author: Tao Lei, Yu Zhang, Yoav Artzi
mathjax: true
---

* content
{:toc}

##### Abstract
Common recurrent neural network architectures scale poorly due to the intrinsic difficulty in parallelizing their state computations. In this work, we propose the Simple Recurrent Unit (SRU) architecture, a recurrent unit that simplifies the computation and exposes more parallelism. In SRU, the majority of computation for each step is independent of the recurrence and can be easily parallelized. SRU is as fast as a convolutional layer and 5-10x faster than an optimized LSTM implementation. We study SRUs on a wide range of applications, including classification, question answering, language modeling, translation and speech recognition. Our experiments demonstrate the effectiveness of SRU and the trade-off it enables between speed and performance. We open source our implementation in PyTorch and CNTK.

##### Abstract (translated by Google)
常见的经常性神经网络结构由于并行化状态计算的内在困难而缩小。在这项工作中，我们提出了简单递归单元（SRU）架构，这是一个简化计算并展现更多并行性的递归单元。在SRU中，每个步骤的大部分计算与重现无关，并且可以很容易地并行化。 SRU与卷积层一样快，比优化的LSTM实现速度快5-10倍。我们在广泛的应用中研究SRU，包括分类，问题回答，语言建模，翻译和语音识别。我们的实验证明了SRU的有效性以及在速度和性能之间的权衡。我们在PyTorch和CNTK中开源实现。

##### URL
[https://arxiv.org/abs/1709.02755](https://arxiv.org/abs/1709.02755)

##### PDF
[https://arxiv.org/pdf/1709.02755](https://arxiv.org/pdf/1709.02755)

