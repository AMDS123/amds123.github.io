---
layout: post
title: "Towards Accurate and High-Speed Spiking Neuromorphic Systems with Data Quantization-Aware Deep Networks"
date: 2018-05-08 14:30:19
categories: arXiv_CV
tags: arXiv_CV
author: Fuqiang Liu, C. Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Neural Networks (DNNs) have gained immense success in cognitive applications and greatly pushed today's artificial intelligence forward. The biggest challenge in executing DNNs is their extremely data-extensive computations. The computing efficiency in speed and energy is constrained when traditional computing platforms are employed in such computational hungry executions. Spiking neuromorphic computing (SNC) has been widely investigated in deep networks implementation own to their high efficiency in computation and communication. However, weights and signals of DNNs are required to be quantized when deploying the DNNs on the SNC, which results in unacceptable accuracy loss. %However, the system accuracy is limited by quantizing data directly in deep networks deployment. Previous works mainly focus on weights discretize while inter-layer signals are mainly neglected. In this work, we propose to represent DNNs with fixed integer inter-layer signals and fixed-point weights while holding good accuracy. We implement the proposed DNNs on the memristor-based SNC system as a deployment example. With 4-bit data representation, our results show that the accuracy loss can be controlled within 0.02% (2.3%) on MNIST (CIFAR-10). Compared with the 8-bit dynamic fixed-point DNNs, our system can achieve more than 9.8x speedup, 89.1% energy saving, and 30% area saving.

##### Abstract (translated by Google)
深度神经网络（DNN）在认知应用领域取得了巨大成功，并大大推动了今天的人工智能的发展。执行DNN最大的挑战是数据非常广泛的计算。当传统的计算平台被用于计算饥饿的执行时，速度和能量的计算效率受到限制。 Spiking神经形态计算（SNC）在深度网络实现方面已被广泛研究，这是因为它们在计算和通信方面的高效率。然而，在SNC上部署DNN时需要对DNN的权重和信号进行量化，从而导致不可接受的精度损失。但是，系统精度受限于直接在深度网络部署中量化数据。以往的工作主要集中在权重离散化，而层间信号则主要被忽略。在这项工作中，我们提出用固定的整数层间信号和定点权重表示DNN，同时保持良好的精度。作为部署示例，我们在忆阻器的SNC系统上实施建议的DNN。对于4位数据表示，我们的结果显示MNIST（CIFAR-10）的精度损失可控制在0.02％（2.3％）以内。与8位动态定点DNN相比，我们的系统可以实现9.8倍以上的加速，89.1％的节能和30％的面积节省。

##### URL
[https://arxiv.org/abs/1805.03054](https://arxiv.org/abs/1805.03054)

##### PDF
[https://arxiv.org/pdf/1805.03054](https://arxiv.org/pdf/1805.03054)

