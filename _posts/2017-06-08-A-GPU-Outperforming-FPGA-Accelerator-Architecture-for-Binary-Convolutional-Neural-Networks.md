---
layout: post
title: "A GPU-Outperforming FPGA Accelerator Architecture for Binary Convolutional Neural Networks"
date: 2017-06-08 16:09:55
categories: arXiv_CV
tags: arXiv_CV Attention CNN
author: Yixing Li, Zichuan Liu, Kai Xu, Hao Yu, Fengbo Ren
mathjax: true
---

* content
{:toc}

##### Abstract
FPGA-based hardware accelerators for convolutional neural networks (CNNs) have obtained great attentions due to their higher energy efficiency than GPUs. However, it is challenging for FPGA-based solutions to achieve a higher throughput than GPU counterparts. In this paper, we demonstrate that FPGA acceleration can be a superior solution in terms of both throughput and energy efficiency when a CNN is trained with binary constraints on weights and activations. Specifically, we propose an optimized FPGA accelerator architecture tailored for bitwise convolution and normalization that features massive spatial parallelism with deep pipelines stages. A key advantage of the FPGA accelerator is that its performance is insensitive to data batch size, while the performance of GPU acceleration varies largely depending on the batch size of the data. Experiment results show that the proposed accelerator architecture for binary CNNs running on a Virtex-7 FPGA is 8.3x faster and 75x more energy-efficient than a Titan X GPU for processing online individual requests in small batch sizes. For processing static data in large batch sizes, the proposed solution is on a par with a Titan X GPU in terms of throughput while delivering 9.5x higher energy efficiency.

##### Abstract (translated by Google)
用于卷积神经网络（CNN）的基于FPGA的硬件加速器由于其比GPU更高的能量效率而备受关注。然而，基于FPGA的解决方案要实现比GPU更高的吞吐量是具有挑战性的。在本文中，我们演示了在加权和激活的二进制约束下对CNN进行训练时，FPGA加速可以成为吞吐量和能源效率方面的优越解决方案。具体来说，我们提出了一个优化的FPGA加速器体系结构，为按位卷积和规范化而量身定制，具有与深层流水线阶段的大规模空间并行性。 FPGA加速器的一个关键优势在于其性能对数据批量大小不敏感，而GPU加速的性能在很大程度上取决于数据的批量大小。实验结果表明，在Virtex-7 FPGA上运行的二进制CNN的加速器体系结构比用于处理小批量在线个人请求的Titan X GPU快8.3倍，能量效率高75倍。为了处理大批量的静态数据，所提出的解决方案在吞吐量方面与Titan X GPU相当，同时提供9.5倍的高能效。

##### URL
[https://arxiv.org/abs/1702.06392](https://arxiv.org/abs/1702.06392)

##### PDF
[https://arxiv.org/pdf/1702.06392](https://arxiv.org/pdf/1702.06392)

