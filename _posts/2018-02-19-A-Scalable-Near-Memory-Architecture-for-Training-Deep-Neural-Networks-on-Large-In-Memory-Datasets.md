---
layout: post
title: "A Scalable Near-Memory Architecture for Training Deep Neural Networks on Large In-Memory Datasets"
date: 2018-02-19 09:28:22
categories: arXiv_CV
tags: arXiv_CV Attention CNN Inference Deep_Learning
author: Fabian Schuiki, Michael Schaffner, Frank K. Gürkaynak, Luca Benini
mathjax: true
---

* content
{:toc}

##### Abstract
Most investigations into near-memory hardware accelerators for deep neural networks have primarily focused on inference, while the potential of accelerating training has received relatively little attention so far. Based on an in-depth analysis of the key computational patterns in state-of-the-art gradient-based training methods, we propose an efficient near-memory acceleration engine called NTX that can be used to train state-of-the-art deep convolutional neural networks at scale. Our main contributions are: (i) identifying requirements for efficient data address generation and developing an efficient accelerator offloading scheme reducing overhead by 7x over previously published results; (ii) support a rich set of operations allowing for efficient calculation of the back-propagation phase. The low control overhead allows up to 8 NTX engines to be controlled by a simple processor. Evaluations in a near-memory computing scenario where the accelerator is placed on the logic base die of a Hybrid Memory Cube demonstrate a 2.6x energy efficiency improvement over contemporary GPUs at 4.4x less silicon area, and an average compute performance of 1.01 Tflop/s for training large state-of-the-art networks with full floating-point precision. The architecture is scalable and paves the way towards efficient deep learning in a distributed near-memory setting.

##### Abstract (translated by Google)
大多数关于深度神经网络的近存储硬件加速器的研究主要集中在推理上，而加速训练的潜力迄今尚未受到关注。基于对最先进的基于梯度的训练方法中的关键计算模式的深入分析，我们提出了一种高效的近存储器加速引擎NTX，可用于训练最先进的技术规模的深度卷积神经网络。我们的主要贡献是：（i）确定高效数据地址生成的要求，并开发高效的加速器卸载方案，比以前公布的结果减少7倍的开销; （ii）支持一组丰富的操作，以便有效地计算反向传播阶段。低控制开销允许最多8个NTX引擎由一个简单的处理器控制。在加速器放置在混合存储器立方体的逻辑基础芯片上的近存储器计算情况下的评估表明，与现代GPU相比，2.6倍的能量效率提高了4.4倍的硅面积，并且平均计算性能为1.01Tflop / s用于训练具有全浮点精度的大型现代化网络。该体系结构具有可扩展性，为分布式近存储设置中的高效深入学习铺平了道路。

##### URL
[https://arxiv.org/abs/1803.04783](https://arxiv.org/abs/1803.04783)

##### PDF
[https://arxiv.org/pdf/1803.04783](https://arxiv.org/pdf/1803.04783)

