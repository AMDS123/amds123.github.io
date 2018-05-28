---
layout: post
title: "f-CNN$^{text{x}}$: A Toolflow for Mapping Multiple Convolutional Neural Networks on FPGAs"
date: 2018-05-25 14:25:18
categories: arXiv_AI
tags: arXiv_AI Drone CNN
author: Stylianos I. Venieris, Christos-Savvas Bouganis
mathjax: true
---

* content
{:toc}

##### Abstract
The predictive power of Convolutional Neural Networks (CNNs) has been an integral factor for emerging latency-sensitive applications, such as autonomous drones and vehicles. Such systems employ multiple CNNs, each one trained for a particular task. The efficient mapping of multiple CNNs on a single FPGA device is a challenging task as the allocation of compute resources and external memory bandwidth needs to be optimised at design time. This paper proposes f-CNN$^{\text{x}}$, an automated toolflow for the optimised mapping of multiple CNNs on FPGAs, comprising a novel multi-CNN hardware architecture together with an automated design space exploration method that considers the user-specified performance requirements for each model to allocate compute resources and generate a synthesisable accelerator. Moreover, f-CNN$^{\text{x}}$ employs a novel scheduling algorithm that alleviates the limitations of the memory bandwidth contention between CNNs and sustains the high utilisation of the architecture. Experimental evaluation shows that f-CNN$^{\text{x}}$'s designs outperform contention-unaware FPGA mappings by up to 50% and deliver up to 6.8x higher performance-per-Watt over highly optimised GPU designs for multi-CNN systems.

##### Abstract (translated by Google)
卷积神经网络（CNN）的预测能力已经成为新兴的延迟敏感型应用（如自主无人机和车辆）的一个必不可少的因素。这种系统使用多个CNN，每个CNN都受过特定任务的训练。在单个FPGA器件上有效地映射多个CNN是一项具有挑战性的任务，因为计算资源和外部存储器带宽的分配需要在设计时进行优化。本文提出了f-CNN $ ^ {\ text {x}} $，这是一种自动工具流程，用于优化FPGA上多个CNN的映射，包括一种新型多CNN硬件体系结构以及考虑用户的自动化设计空间探索方法 - 为每个模型分配计算资源并生成可合成加速器的指定性能要求。此外，f-CNN $ {\ text {x}} $采用了一种新颖的调度算法，可以缓解CNN之间存储器带宽争用的局限性，并保持架构的高利用率。实验评估表明，在高度优化的多GPU设计中，f-CNN $ {\ text {x}} $的设计性能优于竞争未知的FPGA映射高达50％，并且每瓦性能提高了6.8倍-CNN系统。

##### URL
[http://arxiv.org/abs/1805.10174](http://arxiv.org/abs/1805.10174)

##### PDF
[http://arxiv.org/pdf/1805.10174](http://arxiv.org/pdf/1805.10174)

