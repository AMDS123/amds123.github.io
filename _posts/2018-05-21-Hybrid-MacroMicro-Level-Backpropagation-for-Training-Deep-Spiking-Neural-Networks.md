---
layout: post
title: "Hybrid Macro/Micro Level Backpropagation for Training Deep Spiking Neural Networks"
date: 2018-05-21 02:04:30
categories: arXiv_AI
tags: arXiv_AI CNN Deep_Learning
author: Yingyezhe Jin, Peng Li, Wenrui Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Spiking neural networks (SNNs) are positioned to enable spatio-temporal information processing and ultra-low power event-driven neuromorphic hardware. However, SNNs are yet to reach the same performances of conventional deep artificial neural networks (ANNs), a long-standing challenge due to complex dynamics and non-differentiable spike events encountered in training. The existing SNN error backpropagation (BP) methods are limited in terms of scalability, lack of proper handling of spiking discontinuities, and/or mismatch between the rate-coded loss function and computed gradient. We present a hybrid macro/micro level backpropagation algorithm (HM2-BP) for training multi-layer SNNs. The temporal effects are precisely captured by the proposed spike-train level post-synaptic potential (S-PSP) at the microscopic level. The rate-coded errors are defined at the macroscopic level, computed and back-propagated across both macroscopic and microscopic levels. Different from existing BP methods, HM2-BP directly computes the gradient of the rate-coded loss function w.r.t tunable parameters. We evaluate the proposed HM2-BP algorithm by training deep fully connected and convolutional SNNs based on the static MNIST [13] and dynamic neuromorphic N-MNIST [22] datasets. HM2-BP achieves an accuracy level of 99.49% and $98.88% for MNIST and N-MNIST, respectively, outperforming the best reported performances obtained from the existing SNN BP algorithms. It also achieves competitive performances surpassing those of conventional deep learning models when dealing with asynchronous spiking streams.

##### Abstract (translated by Google)
Spiking神经网络（SNN）的定位是为了实现时空信息处理和超低功耗事件驱动神经形态硬件。然而，SNN尚未达到常规深层人工神经网络（ANN）的相同性能，这是由于复杂的动力学和训练中遇到的不可区分的尖峰事件所带来的长期挑战。现有的SNN误差反向传播（BP）方法在可扩展性，缺少适当处理尖峰不连续性和/或速率编码损失函数与计算梯度之间的不匹配方面受到限制。我们提出了一种用于训练多层SNN的混合宏观/微观层次反向传播算法（HM2-BP）。在微观层面上，所提出的尖峰训练水平突触后电位（S-PSP）可准确捕获时间效应。速率编码误差在宏观水平上定义，在宏观和微观水平上计算和反向传播。与现有的BP方法不同，HM2-BP直接计算速率编码损失函数w.r.t可调参数的梯度。我们通过基于静态MNIST [13]和动态神经形态N-MNIST [22]数据集训练深度完全连接和卷积SNN来评估HM2-BP算法。对于MNIST和N-MNIST，HM2-BP分别达到99.49％和98.88％的精确度，优于现有SNN BP算法获得的最佳报告性能。在处理异步尖峰流时，它还实现了超越传统深度学习模型的竞争性能。

##### URL
[https://arxiv.org/abs/1805.07866](https://arxiv.org/abs/1805.07866)

##### PDF
[https://arxiv.org/pdf/1805.07866](https://arxiv.org/pdf/1805.07866)

