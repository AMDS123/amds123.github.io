---
layout: post
title: "More is Less: A More Complicated Network with Less Inference Complexity"
date: 2017-05-15 07:56:20
categories: arXiv_CV
tags: arXiv_CV CNN Inference
author: Xuanyi Dong, Junshi Huang, Yi Yang, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a novel and general network structure towards accelerating the inference process of convolutional neural networks, which is more complicated in network structure yet with less inference complexity. The core idea is to equip each original convolutional layer with another low-cost collaborative layer (LCCL), and the element-wise multiplication of the ReLU outputs of these two parallel layers produces the layer-wise output. The combined layer is potentially more discriminative than the original convolutional layer, and its inference is faster for two reasons: 1) the zero cells of the LCCL feature maps will remain zero after element-wise multiplication, and thus it is safe to skip the calculation of the corresponding high-cost convolution in the original convolutional layer, 2) LCCL is very fast if it is implemented as a 1*1 convolution or only a single filter shared by all channels. Extensive experiments on the CIFAR-10, CIFAR-100 and ILSCRC-2012 benchmarks show that our proposed network structure can accelerate the inference process by 32\% on average with negligible performance drop.

##### Abstract (translated by Google)
本文提出了一种加速卷积神经网络推理过程的新颖的通用网络结构，网络结构复杂，推理复杂度较低。其核心思想是将每个原始的卷积层与另一个低成本的协作层（LCCL）相配合，并且这两个并行层的ReLU输出的元素乘法产生分层输出。组合层可能比原始卷积层更有区别性，其推理速度更快，原因有两个：1）LCCL特征映射的零单元在元素乘法之后保持为零，因此跳过计算是安全的在原始卷积层中相应的高成本卷积，2）如果作为1 * 1卷积或仅由所有通道共享的单个滤波器实现，则LCCL非常快。在CIFAR-10，CIFAR-100和ILSCRC-2012基准上的大量实验表明，我们提出的网络结构可以使推理过程平均加速32％，性能下降可以忽略不计。

##### URL
[https://arxiv.org/abs/1703.08651](https://arxiv.org/abs/1703.08651)

##### PDF
[https://arxiv.org/pdf/1703.08651](https://arxiv.org/pdf/1703.08651)

