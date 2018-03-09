---
layout: post
title: "Streaming Architecture for Large-Scale Quantized Neural Networks on an FPGA-Based Dataflow Platform"
date: 2018-03-08 11:44:36
categories: arXiv_CV
tags: arXiv_CV Classification
author: Chaim Baskin, Natan Liss, Evgenii Zheltonozhskii, Alex M. Bronshtein, Avi Mendelson
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks (DNNs) are used by different applications that are executed on a range of computer architectures, from IoT devices to supercomputers. The footprint of these networks is huge as well as their computational and communication needs. In order to ease the pressure on resources, research indicates that in many cases a low precision representation (1-2 bit per parameter) of weights and other parameters can achieve similar accuracy while requiring less resources. Using quantized values enables the use of FPGAs to run NNs, since FPGAs are well fitted to these primitives; e.g., FPGAs provide efficient support for bitwise operations and can work with arbitrary-precision representation of numbers. 
 This paper presents a new streaming architecture for running QNNs on FPGAs. The proposed architecture scales out better than alternatives, allowing us to take advantage of systems with multiple FPGAs. We also included support for skip connections, that are used in state-of-the art NNs, and shown that our architecture allows to add those connections almost for free. All this allowed us to implement an 18-layer ResNet for 224x224 images classification, achieving 57.5% top-1 accuracy. 
 In addition, we implemented a full-sized quantized AlexNet. In contrast to previous works, we use 2-bit activations instead of 1-bit ones, which improves AlexNet's top-1 accuracy from 41.8% to 51.03% for the ImageNet classification. Both AlexNet and ResNet can handle 1000-class real-time classification on an FPGA. 
 Our implementation of ResNet-18 consumes 5x less power and is 4x slower for ImageNet, when compared to the same NN on the latest Nvidia GPUs. Smaller NNs, that fit a single FPGA, are running faster then on GPUs on small (32x32) inputs, while consuming up to 20x less energy and power.

##### Abstract (translated by Google)
深度神经网络（DNN）被不同的应用程序所使用，这些应用程序在各种计算机体系结构上执行，从物联网设备到超级计算机。这些网络的占地面积巨大，以及它们的计算和通信需求。为了缓解资源压力，研究表明，在许多情况下，权重和其他参数的低精度表示（每个参数1-2位）可以达到相似的精度，同时需要更少的资源。使用量化值可以使用FPGA来运行神经网络，因为FPGA非常适合这些基元;例如，FPGA为按位操作提供有效的支持，并且可以使用数字的任意精度表示。
 本文介绍了一种用于在FPGA上运行QNN的新型流式架构。所提出的体系结构比其他体系更好地扩展，使我们能够利用具有多个FPGA的系统。我们还包括对跳过连接的支持，这些连接用于最先进的NN中，并且显示我们的架构允许几乎免费添加这些连接。所有这些使我们能够为224x224图像分类实施18层ResNet，实现57.5％的前1精度。
 另外，我们实施了一个全尺寸的量化AlexNet。与之前的作品相比，我们使用2位激活而不是1位激活，这将ImageNet分类中AlexNet的前1位精度从41.8％提高到51.03％。 AlexNet和ResNet都可以在FPGA上处理1000级实时分类。
 与最新Nvidia GPU上的相同NN相比，我们对ResNet-18的实施消耗的功率要少5倍，而ImageNet的速度则要慢4倍。在小型（32x32）输入上，较小的NN适合单个FPGA，运行速度更快，而GPU的运行速度更快，而能耗和功耗则降低20倍。

##### URL
[http://arxiv.org/abs/1708.00052](http://arxiv.org/abs/1708.00052)

##### PDF
[http://arxiv.org/pdf/1708.00052](http://arxiv.org/pdf/1708.00052)

