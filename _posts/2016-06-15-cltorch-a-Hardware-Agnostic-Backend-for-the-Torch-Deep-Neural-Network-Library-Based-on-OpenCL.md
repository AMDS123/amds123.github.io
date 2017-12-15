---
layout: post
title: "cltorch: a Hardware-Agnostic Backend for the Torch Deep Neural Network Library, Based on OpenCL"
date: 2016-06-15 17:59:31
categories: arXiv_CV
tags: arXiv_CV CNN
author: Hugh Perkins (ASAPP)
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents cltorch, a hardware-agnostic backend for the Torch neural network framework. cltorch enables training of deep neural networks on GPUs from diverse hardware vendors, including AMD, NVIDIA, and Intel. cltorch contains sufficient implementation to run models such as AlexNet, VGG, Overfeat, and GoogleNet. It is written using the OpenCL language, a portable compute language, governed by the Khronos Group. cltorch is the top-ranked hardware-agnostic machine learning framework on Chintala's convnet-benchmarks page. This paper presents the technical challenges encountered whilst creating the cltorch backend for Torch, and looks in detail at the challenges related to obtaining a fast hardware-agnostic implementation. The convolutional layers are identified as the key area of focus for accelerating hardware-agnostic frameworks. Possible approaches to accelerating the convolutional implementation are identified including: implementation of the convolutions using the implicitgemm or winograd algorithm, using a GEMM implementation adapted to the geometries associated with the convolutional algorithm, or using a pluggable hardware-specific convolutional implementation.

##### Abstract (translated by Google)
本文提供了针对火炬神经网络框架的硬件无关后端cltorch。 cltorch能够在包括AMD，NVIDIA和Intel在内的不同硬件厂商的GPU上对深层神经网络进行培训。 cltorch包含足够的实现来运行AlexNet，VGG，Overfeat和GoogleNet等模型。它是使用由Khronos集团管理的OpenCL语言（一种便携式计算语言）编写的。 cltorch是Chintala的convnet-benchmarkmarks页面上与硬件无关的机器学习框架。本文介绍了为Torch创建后端时遇到的技术挑战，并详细讨论了与获取快速硬件无关实现有关的挑战。卷积层被认为是加速硬件不可知框架的关键领域。识别加速卷积实现的可能方法包括：使用implicitgemm或winograd算法实现卷积，使用适合于与卷积算法相关的几何结构的GEMM实现，或使用可插拔硬件特定的卷积实现。

##### URL
[https://arxiv.org/abs/1606.04884](https://arxiv.org/abs/1606.04884)

##### PDF
[https://arxiv.org/pdf/1606.04884](https://arxiv.org/pdf/1606.04884)

