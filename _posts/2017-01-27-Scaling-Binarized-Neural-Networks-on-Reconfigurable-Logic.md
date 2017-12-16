---
layout: post
title: "Scaling Binarized Neural Networks on Reconfigurable Logic"
date: 2017-01-27 09:12:48
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Classification Deep_Learning
author: Nicholas J. Fraser, Yaman Umuroglu, Giulio Gambardella, Michaela Blott, Philip Leong, Magnus Jahre, Kees Vissers
mathjax: true
---

* content
{:toc}

##### Abstract
Binarized neural networks (BNNs) are gaining interest in the deep learning community due to their significantly lower computational and memory cost. They are particularly well suited to reconfigurable logic devices, which contain an abundance of fine-grained compute resources and can result in smaller, lower power implementations, or conversely in higher classification rates. Towards this end, the Finn framework was recently proposed for building fast and flexible field programmable gate array (FPGA) accelerators for BNNs. Finn utilized a novel set of optimizations that enable efficient mapping of BNNs to hardware and implemented fully connected, non-padded convolutional and pooling layers, with per-layer compute resources being tailored to user-provided throughput requirements. However, FINN was not evaluated on larger topologies due to the size of the chosen FPGA, and exhibited decreased accuracy due to lack of padding. In this paper, we improve upon Finn to show how padding can be employed on BNNs while still maintaining a 1-bit datapath and high accuracy. Based on this technique, we demonstrate numerous experiments to illustrate flexibility and scalability of the approach. In particular, we show that a large BNN requiring 1.2 billion operations per frame running on an ADM-PCIE-8K5 platform can classify images at 12 kFPS with 671 us latency while drawing less than 41 W board power and classifying CIFAR-10 images at 88.7% accuracy. Our implementation of this network achieves 14.8 trillion operations per second. We believe this is the fastest classification rate reported to date on this benchmark at this level of accuracy.

##### Abstract (translated by Google)
二值化神经网络（BNN）由于其显着较低的计算和存储成本而在深度学习社区中获得了兴趣。它们特别适合于可重构逻辑器件，这些器件包含大量细粒度的计算资源，可以实现更小，更低功耗的实现，或者相反可以实现更高的分类速率。为此，最近提出了Finn框架，用于为BNN构建快速灵活的现场可编程门阵列（FPGA）加速器。 Finn利用了一套新的优化方法，实现了BNN与硬件的高效映射，并实现了完全连接，无填充的卷积层和池层，每层计算资源都是根据用户提供的吞吐量要求量身定制的。然而，由于所选FPGA的尺寸，FINN未在较大的拓扑结构上进行评估，并且由于缺少填充而导致精度降低。在本文中，我们对Finn进行了改进，以说明如何在BNN上使用填充，同时保持1位数据通路和高精度。基于这种技术，我们展示了大量的实验来说明这种方法的灵活性和可扩展性。特别是，我们发现，在ADM-PCIE-8K5平台上运行的每帧需要12亿次运算的大型BNN可以以12 kFPS的速度对图像进行分类，处理时间为671 us，同时绘制的功耗低于41 W，并将CIFAR-10图像分类为88.7 ％ 准确性。我们实施这个网络达到每秒14.8万亿次。我们认为这是迄今为止在这个准确性水平上报告的最快的分类率。

##### URL
[https://arxiv.org/abs/1701.03400](https://arxiv.org/abs/1701.03400)

##### PDF
[https://arxiv.org/pdf/1701.03400](https://arxiv.org/pdf/1701.03400)

