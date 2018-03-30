---
layout: post
title: "FPGA Implementations of 3D-SIMD Processor Architecture for Deep Neural Networks Using Relative Indexed Compressed Sparse Filter Encoding Format and Stacked Filters Stationary Flow"
date: 2018-03-28 11:56:20
categories: arXiv_CV
tags: arXiv_CV Sparse CNN
author: Yuechao Gao, Nianhong Liu, Sheng Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
It is a challenging task to deploy computationally and memory intensive State-of-the-art deep neural networks (DNNs) on embedded systems with limited hardware resources and power budgets. Recently developed techniques like Deep Compression make it possible to fit large DNNs, such as AlexNet and VGGNet, fully in on-chip SRAM. But sparse networks compressed using existing encoding formats, like CSR or CSC, complex the computation at runtime due to their irregular memory access characteristics. In [1], we introduce a computation dataflow, stacked filters stationary dataflow (SFS), and a corresponding data encoding format, relative indexed compressed sparse filter format (CSF), to make the best of data sparsity, and simplify data handling at execution time. In this paper we present FPGA implementations of these methods. We implement several compact streaming fully connected (FC) and Convolutional (CONV) neural network processors to show their efficiency. Comparing with the state-of-the-art results [2,3,4], our methods achieve at least 2x improvement for computation efficiency per PE on most layers. Especially, our methods achieve 8x improvement on AlexNet layer CONV4 with 384 filters, and 11x improvement on VGG16 layer CONV5-3 with 512 filters.

##### Abstract (translated by Google)
在硬件资源和功耗预算有限的嵌入式系统上部署计算和内存密集型最先进的深度神经网络（DNN）是一项具有挑战性的任务。最近开发的深度压缩技术使得将大型DNN（如AlexNet和VGGNet）完全集成到片上SRAM成为可能。但是，使用现有编码格式（如CSR或CSC）压缩的稀疏网络由于其不规则的内存访问特性而使运算在运行时变得复杂。在[1]中，我们引入了计算数据流，堆栈滤波器固定数据流（SFS）和相应的数据编码格式，相对索引压缩稀疏滤波格式（CSF），以实现最佳的数据稀疏性，并简化执行时的数据处理时间。在本文中，我们介绍这些方法的FPGA实现。我们实现了几个紧凑型流式全连接（FC）和卷积（CONV）神经网络处理器来展示它们的效率。与最先进的结果[2,3,4]相比，我们的方法在大多数层上对每个PE的计算效率至少提高了2倍。特别是，我们的方法在384个过滤器的AlexNet层CONV4上实现了8倍的改进，在512个过滤器的VGG16层CONV5-3上实现了11倍的改进。

##### URL
[https://arxiv.org/abs/1803.10548](https://arxiv.org/abs/1803.10548)

##### PDF
[https://arxiv.org/pdf/1803.10548](https://arxiv.org/pdf/1803.10548)

