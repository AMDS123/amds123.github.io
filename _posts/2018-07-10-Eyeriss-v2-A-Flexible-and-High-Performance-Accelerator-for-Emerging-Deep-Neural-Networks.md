---
layout: post
title: "Eyeriss v2: A Flexible and High-Performance Accelerator for Emerging Deep Neural Networks"
date: 2018-07-10 16:12:07
categories: arXiv_CV
tags: arXiv_CV Quantitative
author: Yu-Hsin Chen, Joel Emer, Vivienne Sze
mathjax: true
---

* content
{:toc}

##### Abstract
The design of DNNs has increasingly focused on reducing the computational complexity in addition to improving accuracy. While emerging DNNs tend to have fewer weights and operations, they also reduce the amount of data reuse with more widely varying layer shapes and sizes. This leads to a diverse set of DNNs, ranging from large ones with high reuse (e.g., AlexNet) to compact ones with high bandwidth requirements (e.g., MobileNet). However, many existing DNN processors depend on certain DNN properties, e.g., a large number of channels, to achieve high performance and energy efficiency and do not have sufficient flexibility to efficiently process a diverse set of DNNs. In this work, we present Eyexam, a performance analysis framework that quantitatively identifies the sources of performance loss in DNN processors. It highlights two architectural bottlenecks in many existing designs. First, their dataflows are not flexible enough to adapt to the varying layer shapes and sizes of different DNNs. Second, their network-on-chip (NoC) can't adapt to support both high data reuse and high bandwidth scenarios. Based on this analysis, we present Eyeriss v2, a high-performance DNN accelerator that adapts to a wide range of DNNs. Eyeriss v2 has a new dataflow, called Row-Stationary Plus (RS+), that enables the spatial tiling of data from all dimensions to fully utilize the parallelism for high performance. To support RS+, it has a low-cost and scalable NoC design, called hierarchical mesh, that connects the high-bandwidth global buffer to the array of processing elements (PEs) in a two-level hierarchy. This enables high-bandwidth data delivery while still being able to harness any available data reuse. Compared with Eyeriss, Eyeriss v2 has a performance increase of 10.4x-17.9x for 256 PEs, 37.7x-71.5x for 1024 PEs, and 448.8x-1086.7x for 16384 PEs on DNNs with widely varying amounts of data reuse.

##### Abstract (translated by Google)
除了提高准确性之外，DNN的设计越来越注重降低计算复杂性。虽然新兴的DNN往往具有较少的权重和操作，但它们还可以通过更广泛变化的层形状和大小来减少数据重用的数量。这导致了各种各样的DNN，从具有高重用率的大型DNN（例如，AlexNet）到具有高带宽要求的紧凑型DNN（例如，MobileNet）。然而，许多现有的DNN处理器依赖于某些DNN特性，例如大量信道，以实现高性能和能量效率，并且没有足够的灵活性来有效地处理各种DNN。在这项工作中，我们介绍了Eyexam，这是一个性能分析框架，可定量识别DNN处理器中性能损失的来源。它突出了许多现有设计中的两个架构瓶颈。首先，他们的数据流不够灵活，无法适应不同DNN的不同层形状和大小。其次，他们的片上网络（NoC）无法适应高数据重用和高带宽场景。基于此分析，我们提供了Eyeriss v2，这是一种适用于各种DNN的高性能DNN加速器。 Eyeriss v2有一个名为Row-Stationary Plus（RS +）的新数据流，可以对所有维度的数据进行空间平铺，以充分利用并行性来实现高性能。为了支持RS +，它具有低成本和可扩展的NoC设计，称为分层网格，它将高带宽全局缓冲区连接到两级层次结构中的处理元素（PE）阵列。这样可以实现高带宽数据传输，同时仍然能够利用任何可用的数据重用。与Eyeriss相比，Eyeriss v2的256个PE的性能提升为10.4x-17.9x，1024个PE的性能提升为37.7x-71.5x，DNN的16384个PE的性能提升为448.8x-1086.7x，数据重用量大不相同。

##### URL
[http://arxiv.org/abs/1807.07928](http://arxiv.org/abs/1807.07928)

##### PDF
[http://arxiv.org/pdf/1807.07928](http://arxiv.org/pdf/1807.07928)

