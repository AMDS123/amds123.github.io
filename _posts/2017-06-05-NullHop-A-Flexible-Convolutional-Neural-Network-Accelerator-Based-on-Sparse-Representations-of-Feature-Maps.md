---
layout: post
title: "NullHop: A Flexible Convolutional Neural Network Accelerator Based on Sparse Representations of Feature Maps"
date: 2017-06-05 16:20:24
categories: arXiv_CV
tags: arXiv_CV Sparse CNN
author: Alessandro Aimar, Hesham Mostafa, Enrico Calabrese, Antonio Rios-Navarro, Ricardo Tapiador-Morales, Iulia-Alexandra Lungu, Moritz B. Milde, Federico Corradi, Alejandro Linares-Barranco, Shih-Chii Liu, Tobi Delbruck
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNNs) have become the dominant neural network architecture for solving many state-of-the-art (SOA) visual processing tasks. Even though Graphical Processing Units (GPUs) are most often used in training and deploying CNNs, their power consumption becomes a problem for real time mobile applications. We propose a flexible and efficient CNN accelerator architecture which can support the implementation of SOA CNNs in low-power and low-latency application scenarios. This architecture exploits the sparsity of neuron activations in CNNs to accelerate the computation and reduce memory requirements. The flexible architecture allows high utilization of available computing resources across a wide range of convolutional network kernel sizes; and numbers of input and output feature maps. We implemented the proposed architecture on an FPGA platform and present results showing how our implementation reduces external memory transfers and compute time in five different CNNs ranging from small ones up to the widely known large VGG16 and VGG19 CNNs. We show how in RTL simulations in a 28nm process with a clock frequency of 500MHz, the NullHop core is able to reach over 450 GOp/s and efficiency of 368%, maintaining over 98% utilization of the MAC units and achieving a power efficiency of over 3TOp/s/W in a core area of 5.8mm2

##### Abstract (translated by Google)
卷积神经网络（CNN）已经成为解决许多现代（SOA）视觉处理任务的主要神经网络架构。尽管图形处理单元（GPU）最常用于培训和部署CNN，但其功耗却成为实时移动应用程序的一个难题。我们提出了一种灵活，高效的CNN加速器体系结构，可以支持在低功耗和低延迟应用场景下实现SOA CNN。该架构利用CNN中神经元激活的稀疏性来加速计算并减少内存需求。灵活的架构允许在广泛的卷积网络内核大小上高度利用可用的计算资源;以及输入和输出特征图的数量。我们在FPGA平台上实现了所提出的体系结构，并展示了我们的实现如何在五个不同的CNN（从小到大的VGG16和VGG19 CNN）范围内减少外部存储器传输和计算时间。我们展示了如何在时钟频率为500MHz的28nm工艺的RTL仿真中，NullHop核心能够达到超过450 GOp / s，效率为368％，保持了MAC单元的98％以上的利用率，并且实现了功率效率超过3TOp / s / W的核心区域5.8平方毫米

##### URL
[https://arxiv.org/abs/1706.01406](https://arxiv.org/abs/1706.01406)

##### PDF
[https://arxiv.org/pdf/1706.01406](https://arxiv.org/pdf/1706.01406)

