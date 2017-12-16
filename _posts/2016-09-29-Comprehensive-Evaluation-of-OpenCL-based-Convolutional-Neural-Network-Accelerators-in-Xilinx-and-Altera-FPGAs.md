---
layout: post
title: "Comprehensive Evaluation of OpenCL-based Convolutional Neural Network Accelerators in Xilinx and Altera FPGAs"
date: 2016-09-29 11:03:21
categories: arXiv_CV
tags: arXiv_CV CNN Classification Deep_Learning
author: R. Tapiador, A. Rios-Navarro, A. Linares-Barranco, Minkyu Kim, Deepak Kadetotad, Jae-sun Seo
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning has significantly advanced the state of the art in artificial intelligence, gaining wide popularity from both industry and academia. Special interest is around Convolutional Neural Networks (CNN), which take inspiration from the hierarchical structure of the visual cortex, to form deep layers of convolutional operations, along with fully connected classifiers. Hardware implementations of these deep CNN architectures are challenged with memory bottlenecks that require many convolution and fully-connected layers demanding large amount of communication for parallel computation. Multi-core CPU based solutions have demonstrated their inadequacy for this problem due to the memory wall and low parallelism. Many-core GPU architectures show superior performance but they consume high power and also have memory constraints due to inconsistencies between cache and main memory. FPGA design solutions are also actively being explored, which allow implementing the memory hierarchy using embedded BlockRAM. This boosts the parallel use of shared memory elements between multiple processing units, avoiding data replicability and inconsistencies. This makes FPGAs potentially powerful solutions for real-time classification of CNNs. Both Altera and Xilinx have adopted OpenCL co-design framework from GPU for FPGA designs as a pseudo-automatic development solution. In this paper, a comprehensive evaluation and comparison of Altera and Xilinx OpenCL frameworks for a 5-layer deep CNN is presented. Hardware resources, temporal performance and the OpenCL architecture for CNNs are discussed. Xilinx demonstrates faster synthesis, better FPGA resource utilization and more compact boards. Altera provides multi-platforms tools, mature design community and better execution times.

##### Abstract (translated by Google)
深度学习大大提高了人工智能的先进水平，获得了业界和学术界的广泛认可。卷积神经网络（CNN）特别感兴趣，它从视觉皮层的层次结构中获得灵感，形成深层次的卷积运算以及完全连接的分类器。这些深度CNN体系结构的硬件实现受到内存瓶颈的挑战，这些内存瓶颈需要许多卷积和完全连接的层，要求大量的并行计算通信。由于存储墙和低并行性，基于多核CPU的解决方案已经证明了这个问题的不足。多核GPU架构表现出优越的性能，但是由于高速缓存和主存储器之间的不一致性，它们消耗高功率并且还具有存储器限制。 FPGA设计解决方案也在积极探索之中，它们允许使用嵌入式BlockRAM来实现存储器层次结构。这增强了多个处理单元之间共享内存元素的并行使用，避免了数据的可复制性和不一致性。这使得FPGA成为实时分类CNN的强大解决方案。 Altera和Xilinx都采用了OpenGL的GPU协同设计框架作为FPGA设计的伪自动开发解决方案。本文对5层深CNN的Altera和Xilinx OpenCL框架进行了综合评估和比较。讨论了硬件资源，时态性能和CNN的OpenCL体系结构。赛灵思展示了更快的综合，更好的FPGA资源利用率和更紧凑的电路板。 Altera提供多平台工具，成熟的设计团队和更好的执行时间。

##### URL
[https://arxiv.org/abs/1609.09296](https://arxiv.org/abs/1609.09296)

##### PDF
[https://arxiv.org/pdf/1609.09296](https://arxiv.org/pdf/1609.09296)

