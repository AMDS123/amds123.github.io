---
layout: post
title: "Streaming Architecture for Large-Scale Quantized Neural Networks on an FPGA-Based Dataflow Platform"
date: 2017-07-31 19:53:48
categories: arXiv_CV
tags: arXiv_CV Classification
author: Chaim Baskin, Natan Liss, Avi Mendelson, Evgenii Zheltonozhskii
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks (DNNs) are used by different applications that are executed on a range of computer architectures, from IoT devices to supercomputers. The footprint of these networks is huge as well as their computational and communication needs. In order to ease the pressure on resources, research indicates that in many cases a low precision representation (1-2 bit per parameter) of weights and other parameters can achieve similar accuracy while requiring less resources. Using quantized values enables the use of FPGAs to run NNs, since FPGAs are well fitted to these primitives; e.g., FPGAs provide efficient support for bitwise operations and can work with arbitrary-precision representation of numbers. This paper presents a new streaming architecture for running QNNs on FPGAs. The proposed architecture scales out better than alternatives, allowing us to take advantage of systems with multiple FPGAs. We also included support for skip connections, that are used in state-of-the art NNs, and shown that our architecture allows to add those connections almost for free. All this allowed us to implement an 18-layer ResNet for $224\times224$ images classification, achieving $57.5\%$ top-1 accuracy. In addition, we implemented a full-sized quantized AlexNet. In contrast to previous works, we use 2-bit activations instead of 1-bit ones, which improves AlexNet's top-1 accuracy from $41.8\%$ to $51.03\%$ for the ImageNet classification. Both AlexNet and ResNet can handle 1000-class real-time classification on an FPGA. Our implementation of ResNet-18 consumes $5\times$ less power and is $4\times$ slower for ImageNet, when compared to the same NN on the latest Nvidia GPUs. Smaller NNs, that fit a single FPGA, are running faster then on GPUs on small ($32\times32$) inputs, while consuming up to $20\times$ less energy and power.

##### Abstract (translated by Google)
深度神经网络（DNN）被不同的应用程序所使用，这些应用程序在从物联网设备到超级计算机的各种计算机体系结构上执行。这些网络的占地面积巨大，以及他们的计算和通信需求。为了减轻对资源的压力，研究表明，在许多情况下，权重和其他参数的低精度表示（每个参数1-2位）可以达到相似的精度，同时需要较少的资源。使用量化值可以使用FPGA来运行神经网络，因为FPGA非常适合这些基元;例如，FPGA为按位运算提供有效的支持，并可以以任意精度的数字表示工作。本文提出了一种在FPGA上运行QNN的新型流式架构。所提出的架构可以比替代方案更好地扩展，使我们能够利用具有多个FPGA的系统。我们还包括对跳过连接的支持，这些连接用于最先进的神经网络，并且显示我们的架构允许几乎免费地添加这些连接。所有这一切使我们能够以224美元/次224美元的图像分类实现18层ResNet，实现了57.5美元/美元的前1精度。另外，我们实现了一个全尺寸的量子AlexNet。与之前的作品相比，我们使用2位激活而不是1位激活，从而将AlexNet的前1精度从41.8 \％$提高到$ 51.03 \％$。 AlexNet和ResNet都可以在FPGA上处理1000级的实时分类。与最新的Nvidia GPU上相同的NN相比，我们的ResNet-18的实现消耗的功耗低$ 5 /倍，ImageNet的消耗低$ 4 /倍。在小型（$ 32 \ times32 $）输入上，较小的NN适合单个FPGA运行速度更快，然后耗费高达20倍的能源和功耗。

##### URL
[https://arxiv.org/abs/1708.00052](https://arxiv.org/abs/1708.00052)

##### PDF
[https://arxiv.org/pdf/1708.00052](https://arxiv.org/pdf/1708.00052)

