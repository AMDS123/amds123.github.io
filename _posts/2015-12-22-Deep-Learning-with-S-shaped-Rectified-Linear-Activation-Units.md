---
layout: post
title: "Deep Learning with S-shaped Rectified Linear Activation Units"
date: 2015-12-22 10:54:26
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Xiaojie Jin, Chunyan Xu, Jiashi Feng, Yunchao Wei, Junjun Xiong, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Rectified linear activation units are important components for state-of-the-art deep convolutional networks. In this paper, we propose a novel S-shaped rectified linear activation unit (SReLU) to learn both convex and non-convex functions, imitating the multiple function forms given by the two fundamental laws, namely the Webner-Fechner law and the Stevens law, in psychophysics and neural sciences. Specifically, SReLU consists of three piecewise linear functions, which are formulated by four learnable parameters. The SReLU is learned jointly with the training of the whole deep network through back propagation. During the training phase, to initialize SReLU in different layers, we propose a "freezing" method to degenerate SReLU into a predefined leaky rectified linear unit in the initial several training epochs and then adaptively learn the good initial values. SReLU can be universally used in the existing deep networks with negligible additional parameters and computation cost. Experiments with two popular CNN architectures, Network in Network and GoogLeNet on scale-various benchmarks including CIFAR10, CIFAR100, MNIST and ImageNet demonstrate that SReLU achieves remarkable improvement compared to other activation functions.

##### Abstract (translated by Google)
整流式线性激活单元是最先进的深度卷积网络的重要组成部分。在本文中，我们提出了一种新型的S型整形线性激励单元（SReLU）来学习凸函数和非凸函数，模拟由Webner-Fechner定律和Stevens定律这两个基本定律给出的多重函数形式，在心理物理学和神经科学。具体来说，SReLU由三个分段线性函数组成，由四个可学习的参数表示。 SRELU通过反向传播与整个深度网络的训练共同学习。在训练阶段，为了初始化不同层次的SReLU，我们提出了一种“冻结”的方法，在最初的几个训练时期将SReLU退化为一个预定义的漏整型线性单元，然后自适应地学习良好的初始值。 SRELU可以广泛应用于现有的深度网络中，其附加参数和计算成本可以忽略不计。两个流行的CNN架构，网络中的网络和GoogLeNet在包括CIFAR10，CIFAR100，MNIST和ImageNet在内的各种基准的实验表明，与其他激活功能相比，SReLU取得了显着的改进。

##### URL
[https://arxiv.org/abs/1512.07030](https://arxiv.org/abs/1512.07030)

##### PDF
[https://arxiv.org/pdf/1512.07030](https://arxiv.org/pdf/1512.07030)

