---
layout: post
title: "TVM: An Automated End-to-End Optimizing Compiler for Deep Learning"
date: 2018-05-20 18:44:40
categories: arXiv_AI
tags: arXiv_AI Optimization Deep_Learning
author: Tianqi Chen, Thierry Moreau, Ziheng Jiang, Lianmin Zheng, Eddie Yan, Meghan Cowan, Haichen Shen, Leyuan Wang, Yuwei Hu, Luis Ceze, Carlos Guestrin, Arvind Krishnamurthy
mathjax: true
---

* content
{:toc}

##### Abstract
There is an increasing need to bring machine learning to a wide diversity of hardware devices. Current frameworks rely on vendor-specific operator libraries and optimize for a narrow range of server-class GPUs. Deploying workloads to new platforms such as mobile phones, embedded devices, and accelerators (e.g., FPGAs, ASICs) requires significant manual effort. We propose TVM, a compiler that exposes graph-level and operator-level optimizations to provide performance portability to deep learning workloads across diverse hardware back-ends. TVM solves optimization challenges specific to deep learning such as high-level operator fusion, mapping to arbitrary hardware primitives, and memory latency hiding. TVM also offers automated optimization of low-level programs to hardware characteristics by employing a novel learning-based cost modeling method for rapid exploration of code optimizations. Experimental results demonstrate that TVM delivers performance across hardware back-ends that are competitive with state-of-the-art hand-tuned libraries for low-power CPU, mobile GPU, and server-class GPUs. We also demonstrate TVM's ability to target new accelerator back-ends by targeting an FPGA-based generic deep learning accelerator. The system is open sourced and in production use inside several major companies.

##### Abstract (translated by Google)
将机器学习带入各种硬件设备的需求日益增加。目前的框架依赖于供应商特定的运营商库，并针对范围较窄的服务器级GPU进行优化。将工作负载部署到移动电话，嵌入式设备和加速器（例如，FPGA，ASIC）等新平台需要大量的人力。我们建议使用TVM，这是一种编译器，它公开了图形级别和运算符级别的优化，以提供跨不同硬件后端的深度学习工作负载的性能可移植性。 TVM解决了特定于深度学习的优化挑战，例如高级操作符融合，映射到任意硬件原语以及内存延迟隐藏。 TVM还通过采用一种新颖的基于学习的成本建模方法来快速探索代码优化，从而自动优化低级程序的硬件特性。实验结果表明，TVM在硬件后端提供了性能，可与低功耗CPU，移动GPU和服务器级GPU的先进手动库相媲美。我们还通过针对基于FPGA的通用深度学习加速器展示了TVM能够瞄准新的加速器后端。该系统开源并在几家大公司内部进行生产使用。

##### URL
[http://arxiv.org/abs/1802.04799](http://arxiv.org/abs/1802.04799)

##### PDF
[http://arxiv.org/pdf/1802.04799](http://arxiv.org/pdf/1802.04799)

