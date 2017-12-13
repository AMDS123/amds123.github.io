---
layout: post
title: "CNN-MERP: An FPGA-Based Memory-Efficient Reconfigurable Processor for Forward and Backward Propagation of Convolutional Neural Networks"
date: 2017-03-22 01:31:23
categories: arXiv_CV
tags: arXiv_CV CNN Optimization
author: Xushen Han, Dajiang Zhou, Shihao Wang, Shinji Kimura
mathjax: true
---

* content
{:toc}

##### Abstract
Large-scale deep convolutional neural networks (CNNs) are widely used in machine learning applications. While CNNs involve huge complexity, VLSI (ASIC and FPGA) chips that deliver high-density integration of computational resources are regarded as a promising platform for CNN's implementation. At massive parallelism of computational units, however, the external memory bandwidth, which is constrained by the pin count of the VLSI chip, becomes the system bottleneck. Moreover, VLSI solutions are usually regarded as a lack of the flexibility to be reconfigured for the various parameters of CNNs. This paper presents CNN-MERP to address these issues. CNN-MERP incorporates an efficient memory hierarchy that significantly reduces the bandwidth requirements from multiple optimizations including on/off-chip data allocation, data flow optimization and data reuse. The proposed 2-level reconfigurability is utilized to enable fast and efficient reconfiguration, which is based on the control logic and the multiboot feature of FPGA. As a result, an external memory bandwidth requirement of 1.94MB/GFlop is achieved, which is 55% lower than prior arts. Under limited DRAM bandwidth, a system throughput of 1244GFlop/s is achieved at the Vertex UltraScale platform, which is 5.48 times higher than the state-of-the-art FPGA implementations.

##### Abstract (translated by Google)
大规模深度卷积神经网络（CNN）被广泛应用于机器学习应用中。虽然CNN涉及的复杂性非常高，但是将高密度集成计算资源的VLSI（ASIC和FPGA）芯片视为CNN实施的有前途的平台。然而，在计算单元的大规模并行性中，受VLSI芯片管脚数限制的外部存储器带宽成为系统瓶颈。而且，VLSI解决方案通常被认为缺乏对CNN的各种参数进行重新配置的灵活性。本文介绍了CNN-MERP来解决这些问题。 CNN-MERP集成了高效的存储器层次结构，可显着降低多种优化（包括片上/片外数据分配，数据流优化和数据重用）带宽需求。所提出的2级可重构性被用来实现基于FPGA的控制逻辑和多重引导特性的快速且高效的重新配置。因此，实现了1.94MB / GFlop的外部存储器带宽要求，比现有技术低55％。在有限的DRAM带宽下，Vertex UltraScale平台的系统吞吐量达到1244GFlop / s，比现有的FPGA实现高5.48倍。

##### URL
[https://arxiv.org/abs/1703.07348](https://arxiv.org/abs/1703.07348)

##### PDF
[https://arxiv.org/pdf/1703.07348](https://arxiv.org/pdf/1703.07348)

