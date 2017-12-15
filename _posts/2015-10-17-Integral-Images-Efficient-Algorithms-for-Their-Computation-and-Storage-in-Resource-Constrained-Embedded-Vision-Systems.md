---
layout: post
title: "Integral Images: Efficient Algorithms for Their Computation and Storage in Resource-Constrained Embedded Vision Systems"
date: 2015-10-17 15:41:26
categories: arXiv_CV
tags: arXiv_CV Image_Caption Detection
author: Shoaib Ehsan, Adrian F. Clark, Naveed ur Rehman, Klaus D. McDonald-Maier
mathjax: true
---

* content
{:toc}

##### Abstract
The integral image, an intermediate image representation, has found extensive use in multi-scale local feature detection algorithms, such as Speeded-Up Robust Features (SURF), allowing fast computation of rectangular features at constant speed, independent of filter size. For resource-constrained real-time embedded vision systems, computation and storage of integral image presents several design challenges due to strict timing and hardware limitations. Although calculation of the integral image only consists of simple addition operations, the total number of operations is large owing to the generally large size of image data. Recursive equations allow substantial decrease in the number of operations but require calculation in a serial fashion. This paper presents two new hardware algorithms that are based on the decomposition of these recursive equations, allowing calculation of up to four integral image values in a row-parallel way without significantly increasing the number of operations. An efficient design strategy is also proposed for a parallel integral image computation unit to reduce the size of the required internal memory (nearly 35% for common HD video). Addressing the storage problem of integral image in embedded vision systems, the paper presents two algorithms which allow substantial decrease (at least 44.44%) in the memory requirements. Finally, the paper provides a case study that highlights the utility of the proposed architectures in embedded vision systems.

##### Abstract (translated by Google)
积分图像是一种中间图像表示法，已经广泛用于多尺度局部特征检测算法，如加速鲁棒特征（SURF），允许以恒定速度快速计算矩形特征，而与滤波器大小无关。对于资源受限的实时嵌入式视觉系统，由于严格的时序和硬件限制，积分图像的计算和存储呈现出若干设计挑战。尽管积分图像的计算仅由简单的加法操作组成，但由于图像数据的大小通常较大，所以操作总数很大。递归方程允许大量减少操作次数，但需要以串行方式进行计算。本文提出了两种基于这些递归方程分解的新硬件算法，允许以行并行方式计算多达四个整数图像值，而不会显着增加操作次数。并行积分图像计算单元也提出了一种有效的设计策略，以减小所需内部存储器的尺寸（普通高清视频的接近35％）。针对嵌入式视觉系统中积分图像的存储问题，本文提出了两种算法，可以大大减少内存需求（至少44.44％）。最后，本文提供了一个案例研究，突出了所提出的体系结构在嵌入式视觉系统中的实用性。

##### URL
[https://arxiv.org/abs/1510.05138](https://arxiv.org/abs/1510.05138)

##### PDF
[https://arxiv.org/pdf/1510.05138](https://arxiv.org/pdf/1510.05138)

