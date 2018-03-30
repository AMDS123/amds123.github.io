---
layout: post
title: "Face Recognition with Hybrid Efficient Convolution Algorithms on FPGAs"
date: 2018-03-23 22:42:57
categories: arXiv_CV
tags: arXiv_CV Face CNN Optimization Recognition Face_Recognition
author: Chuanhao Zhuge, Xinheng Liu, Xiaofan Zhang, Sudeep Gummadi, Jinjun Xiong, Deming Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Convolutional Neural Networks have become a Swiss knife in solving critical artificial intelligence tasks. However, deploying deep CNN models for latency-critical tasks remains to be challenging because of the complex nature of CNNs. Recently, FPGA has become a favorable device to accelerate deep CNNs thanks to its high parallel processing capability and energy efficiency. In this work, we explore different fast convolution algorithms including Winograd and Fast Fourier Transform (FFT), and find an optimal strategy to apply them together on different types of convolutions. We also propose an optimization scheme to exploit parallelism on novel CNN architectures such as Inception modules in GoogLeNet. We implement a configurable IP-based face recognition acceleration system based on FaceNet using High-Level Synthesis. Our implementation on a Xilinx Ultrascale device achieves 3.75x latency speedup compared to a high-end NVIDIA GPU and surpasses previous FPGA results significantly.

##### Abstract (translated by Google)
深度卷积神经网络已成为解决关键人工智能任务的瑞士刀。但是，由于CNN的复杂性质，为延迟关键任务部署深度CNN模型仍然具有挑战性。近来，由于其高并行处理能力和高能效，FPGA已成为加速深度CNN的有利设备。在这项工作中，我们探索了不同的快速卷积算法，包括Winograd和快速傅里叶变换（FFT），并找到一个将它们一起应用于不同类型卷积的最佳策略。我们还提出了一个优化方案来利用新型CNN体系结构的并行性，例如GoogLeNet中的Inception模块。我们使用高层次综合实现了基于FaceNet的可配置的基于IP的人脸识别加速系统。与高端NVIDIA GPU相比，我们在Xilinx Ultrascale器件上的实现实现了3.75倍的延迟加速，并且明显优于以前的FPGA结果。

##### URL
[https://arxiv.org/abs/1803.09004](https://arxiv.org/abs/1803.09004)

##### PDF
[https://arxiv.org/pdf/1803.09004](https://arxiv.org/pdf/1803.09004)

