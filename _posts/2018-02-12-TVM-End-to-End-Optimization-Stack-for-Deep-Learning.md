---
layout: post
title: "TVM: End-to-End Optimization Stack for Deep Learning"
date: 2018-02-12 20:49:34
categories: arXiv_AI
tags: arXiv_AI Optimization Deep_Learning
author: Tianqi Chen, Thierry Moreau, Ziheng Jiang, Haichen Shen, Eddie Yan, Leyuan Wang, Yuwei Hu, Luis Ceze, Carlos Guestrin, Arvind Krishnamurthy
mathjax: true
---

* content
{:toc}

##### Abstract
Scalable frameworks, such as TensorFlow, MXNet, Caffe, and PyTorch drive the current popularity and utility of deep learning. However, these frameworks are optimized for a narrow range of server-class GPUs and deploying workloads to other platforms such as mobile phones, embedded devices, and specialized accelerators (e.g., FPGAs, ASICs) requires laborious manual effort. We propose TVM, an end-to-end optimization stack that exposes graph-level and operator-level optimizations to provide performance portability to deep learning workloads across diverse hardware back-ends. We discuss the optimization challenges specific to deep learning that TVM solves: high-level operator fusion, low-level memory reuse across threads, mapping to arbitrary hardware primitives, and memory latency hiding. Experimental results demonstrate that TVM delivers performance across hardware back-ends that are competitive with state-of-the-art libraries for low-power CPU and server-class GPUs. We also demonstrate TVM's ability to target new hardware accelerator back-ends by targeting an FPGA-based generic deep learning accelerator. The compiler infrastructure is open sourced.

##### Abstract (translated by Google)
可扩展框架，如TensorFlow，MXNet，Caffe和PyTorch推动了深度学习的当前流行和实用性。然而，这些框架针对范围较窄的服务器级GPU进行了优化，并将工作负载部署到其他平台（如移动电话，嵌入式设备和专用加速器（例如，FPGA，ASIC））需要费力的手动工作。我们提出了一个端到端的优化堆栈TVM，它揭示了图形层面和运营层面的优化，为不同硬件后端的深度学习工作负载提供了性能可移植性。我们讨论TVM解决特定于深度学习的优化挑战：高级操作符融合，跨线程的低级内存重用，映射到任意硬件原语以及内存延迟隐藏。实验结果表明，TVM在硬件后端提供了性能，可与低功耗CPU和服务器级GPU的最新库竞争。我们还通过针对基于FPGA的通用深度学习加速器展示了TVM针对新硬件加速器后端的能力。编译器基础结构是开源的。

##### URL
[http://arxiv.org/abs/1802.04799](http://arxiv.org/abs/1802.04799)

##### PDF
[http://arxiv.org/pdf/1802.04799](http://arxiv.org/pdf/1802.04799)

