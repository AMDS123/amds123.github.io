---
layout: post
title: "Deep Tensor Convolution on Multicores"
date: 2017-06-11 15:29:16
categories: arXiv_CV
tags: arXiv_CV Sparse CNN
author: David Budden, Alexander Matveev, Shibani Santurkar, Shraman Ray Chaudhuri, Nir Shavit
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural networks (ConvNets) of 3-dimensional kernels allow joint modeling of spatiotemporal features. These networks have improved performance of video and volumetric image analysis, but have been limited in size due to the low memory ceiling of GPU hardware. Existing CPU implementations overcome this constraint but are impractically slow. Here we extend and optimize the faster Winograd-class of convolutional algorithms to the $N$-dimensional case and specifically for CPU hardware. First, we remove the need to manually hand-craft algorithms by exploiting the relaxed constraints and cheap sparse access of CPU memory. Second, we maximize CPU utilization and multicore scalability by transforming data matrices to be cache-aware, integer multiples of AVX vector widths. Treating 2-dimensional ConvNets as a special (and the least beneficial) case of our approach, we demonstrate a 5 to 25-fold improvement in throughput compared to previous state-of-the-art.

##### Abstract (translated by Google)
三维核的深度卷积神经网络（ConvNets）允许对时空特征进行联合建模。这些网络具有改进的视频和体积图像分析性能，但是由于GPU硬件的内存最低限度，其尺寸受到限制。现有的CPU实现克服了这个限制，但是实际上很慢。在这里，我们将更快速的Winograd类的卷积算法扩展和优化到$ N $维的情况，特别是CPU硬件。首先，我们通过利用宽松的约束和廉价的CPU内存稀疏访问来消除手动手工制作算法的需求。其次，通过将数据矩阵转换为缓存感知，AVX向量宽度的整数倍，我们可以最大化CPU利用率和多核可扩展性。将二维ConvNets作为我们方法的一个特殊的（也是最不利的）案例，与先前的最新技术相比，我们展示了5到25倍的吞吐量改进。

##### URL
[https://arxiv.org/abs/1611.06565](https://arxiv.org/abs/1611.06565)

##### PDF
[https://arxiv.org/pdf/1611.06565](https://arxiv.org/pdf/1611.06565)

