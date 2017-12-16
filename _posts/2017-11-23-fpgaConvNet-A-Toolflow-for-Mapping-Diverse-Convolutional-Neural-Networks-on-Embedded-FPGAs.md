---
layout: post
title: "fpgaConvNet: A Toolflow for Mapping Diverse Convolutional Neural Networks on Embedded FPGAs"
date: 2017-11-23 15:37:21
categories: arXiv_CV
tags: arXiv_CV CNN
author: Stylianos I. Venieris, Christos-Savvas Bouganis
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, Convolutional Neural Networks (ConvNets) have become an enabling technology for a wide range of novel embedded Artificial Intelligence systems. Across the range of applications, the performance needs vary significantly, from high-throughput video surveillance to the very low-latency requirements of autonomous cars. In this context, FPGAs can provide a potential platform that can be optimally configured based on the different performance needs. However, the complexity of ConvNet models keeps increasing making their mapping to an FPGA device a challenging task. This work presents fpgaConvNet, an end-to-end framework for mapping ConvNets on FPGAs. The proposed framework employs an automated design methodology based on the Synchronous Dataflow (SDF) paradigm and defines a set of SDF transformations in order to efficiently explore the architectural design space. By selectively optimising for throughput, latency or multiobjective criteria, the presented tool is able to efficiently explore the design space and generate hardware designs from high-level ConvNet specifications, explicitly optimised for the performance metric of interest. Overall, our framework yields designs that improve the performance by up to 6.65x over highly optimised embedded GPU designs for the same power constraints in embedded environments.

##### Abstract (translated by Google)
近年来，卷积神经网络（ConvNets）已经成为广泛的新型嵌入式人工智能系统的一个支持技术。在整个应用范围内，从高吞吐量视频监控到自动驾驶汽车的低延迟要求，性能需求都有很大不同。在这种情况下，FPGA可以提供一个潜在的平台，可以根据不同的性能需求进行优化配置。但是，ConvNet模型的复杂性不断增加，使得它们映射到FPGA器件成为一项具有挑战性的任务。这项工作提出了fpgaConvNet，这是一种在FPGA上映射ConvNets的端到端框架。所提出的框架采用基于同步数据流（SDF）范例的自动化设计方法，并定义一组SDF变换以有效地探索建筑设计空间。通过选择性地优化吞吐量，延迟或多目标准则，所提供的工具能够有效地探索设计空间，并根据高级ConvNet规范生成硬件设计，并针对感兴趣的性能度量进行明确优化。总的来说，我们的架构产生的设计与嵌入式环境中相同的功耗限制相比，高度优化的嵌入式GPU设计性能提高了6.65倍。

##### URL
[https://arxiv.org/abs/1711.08740](https://arxiv.org/abs/1711.08740)

##### PDF
[https://arxiv.org/pdf/1711.08740](https://arxiv.org/pdf/1711.08740)

