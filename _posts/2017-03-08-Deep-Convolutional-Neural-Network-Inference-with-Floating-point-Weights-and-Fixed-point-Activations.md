---
layout: post
title: "Deep Convolutional Neural Network Inference with Floating-point Weights and Fixed-point Activations"
date: 2017-03-08 23:49:20
categories: arXiv_CV
tags: arXiv_CV CNN Inference
author: Liangzhen Lai, Naveen Suda, Vikas Chandra
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural network (CNN) inference requires significant amount of memory and computation, which limits its deployment on embedded devices. To alleviate these problems to some extent, prior research utilize low precision fixed-point numbers to represent the CNN weights and activations. However, the minimum required data precision of fixed-point weights varies across different networks and also across different layers of the same network. In this work, we propose using floating-point numbers for representing the weights and fixed-point numbers for representing the activations. We show that using floating-point representation for weights is more efficient than fixed-point representation for the same bit-width and demonstrate it on popular large-scale CNNs such as AlexNet, SqueezeNet, GoogLeNet and VGG-16. We also show that such a representation scheme enables compact hardware multiply-and-accumulate (MAC) unit design. Experimental results show that the proposed scheme reduces the weight storage by up to 36% and power consumption of the hardware multiplier by up to 50%.

##### Abstract (translated by Google)
深度卷积神经网络（CNN）推理需要大量的存储器和计算，这限制了其在嵌入式设备上的部署。为了在一定程度上缓解这些问题，先前的研究利用低精度定点数来表示CNN的权重和激活。然而，定点权重所需的最小数据精度在不同网络之间以及同一网络的不同层之间是不同的。在这项工作中，我们建议使用浮点数来表示用于表示激活的权重和定点数。我们表明，使用浮点表示权重比相同位宽的定点表示更有效，并在流行的大规模CNN如AlexNet，SqueezeNet，GoogLeNet和VGG-16上进行演示。我们还表明，这样的表示方案能够实现紧凑的硬件乘法和累加（MAC）单元设计。实验结果表明，所提出的方案将重量存储减少高达36％，硬件乘法器的功耗降低高达50％。

##### URL
[https://arxiv.org/abs/1703.03073](https://arxiv.org/abs/1703.03073)

##### PDF
[https://arxiv.org/pdf/1703.03073](https://arxiv.org/pdf/1703.03073)

