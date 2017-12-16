---
layout: post
title: "SC-DCNN: Highly-Scalable Deep Convolutional Neural Network using Stochastic Computing"
date: 2017-01-31 16:19:46
categories: arXiv_CV
tags: arXiv_CV CNN Optimization
author: Ao Ren, Ji Li, Zhe Li, Caiwen Ding, Xuehai Qian, Qinru Qiu, Bo Yuan, Yanzhi Wang
mathjax: true
---

* content
{:toc}

##### Abstract
With recent advancing of Internet of Things (IoTs), it becomes very attractive to implement the deep convolutional neural networks (DCNNs) onto embedded/portable systems. Presently, executing the software-based DCNNs requires high-performance server clusters in practice, restricting their widespread deployment on the mobile devices. To overcome this issue, considerable research efforts have been conducted in the context of developing highly-parallel and specific DCNN hardware, utilizing GPGPUs, FPGAs, and ASICs. Stochastic Computing (SC), which uses bit-stream to represent a number within [-1, 1] by counting the number of ones in the bit-stream, has a high potential for implementing DCNNs with high scalability and ultra-low hardware footprint. Since multiplications and additions can be calculated using AND gates and multiplexers in SC, significant reductions in power/energy and hardware footprint can be achieved compared to the conventional binary arithmetic implementations. The tremendous savings in power (energy) and hardware resources bring about immense design space for enhancing scalability and robustness for hardware DCNNs. This paper presents the first comprehensive design and optimization framework of SC-based DCNNs (SC-DCNNs). We first present the optimal designs of function blocks that perform the basic operations, i.e., inner product, pooling, and activation function. Then we propose the optimal design of four types of combinations of basic function blocks, named feature extraction blocks, which are in charge of extracting features from input feature maps. Besides, weight storage methods are investigated to reduce the area and power/energy consumption for storing weights. Finally, the whole SC-DCNN implementation is optimized, with feature extraction blocks carefully selected, to minimize area and power/energy consumption while maintaining a high network accuracy level.

##### Abstract (translated by Google)
随着物联网（IoTs）近来的发展，将深度卷积神经网络（DCNN）应用于嵌入式/便携式系统变得非常有吸引力。目前，执行基于软件的DCNN实际上需要高性能的服务器集群，限制了它们在移动设备上的广泛部署。为了克服这个问题，在利用GPGPU，FPGA和ASIC开发高度并行和特定的DCNN硬件方面进行了大量的研究工作。随机计算（SC）通过计算比特流中的数目来使用比特流表示[-1,1]内的数字，因此具有高可扩展性和超低硬件占用空间的DCNN的高潜力。由于可以使用SC中的AND门和多路复用器来计算乘法和加法，与传统的二进制算术实现相比，可以实现功率/能量和硬件占用面积的显着减少。功耗（能量）和硬件资源的巨大节省为增强硬件DCNN的可扩展性和鲁棒性带来了巨大的设计空间。本文提出了基于SC的DCNN（SC-DCNN）的第一个综合设计和优化框架。我们首先介绍执行基本操作的功能块的最佳设计，即内积，积分和激活函数。然后，我们提出了四种基本功能块组合的优化设计，称为特征提取块，负责从输入特征图中提取特征。此外，调查重量储存方法，以减少存放重量的面积和功率/能量消耗。最后，对整个SC-DCNN实施进行优化，精选特征提取模块，以最大限度地减少面积和功率/能量消耗，同时保持较高的网络精度水平。

##### URL
[https://arxiv.org/abs/1611.05939](https://arxiv.org/abs/1611.05939)

##### PDF
[https://arxiv.org/pdf/1611.05939](https://arxiv.org/pdf/1611.05939)

