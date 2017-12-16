---
layout: post
title: "GPGPU Acceleration of the KAZE Image Feature Extraction Algorithm"
date: 2017-06-21 06:14:42
categories: arXiv_CV
tags: arXiv_CV Detection
author: Ramkumar B, R. S. Hegde, Rob Laber, Hristo Bojinov
mathjax: true
---

* content
{:toc}

##### Abstract
The recently proposed open-source KAZE image feature detection and description algorithm offers unprecedented performance in comparison to conventional ones like SIFT and SURF as it relies on nonlinear scale spaces instead of Gaussian linear scale spaces. The improved performance, however, comes with a significant computational cost limiting its use for many applications. We report a GPGPU implementation of the KAZE algorithm without resorting to binary descriptors for gaining speedup. For a 1920 by 1200 sized image our Compute Unified Device Architecture (CUDA) C based GPU version took around 300 milliseconds on a NVIDIA GeForce GTX Titan X (Maxwell Architecture-GM200) card in comparison to nearly 2400 milliseconds for a multithreaded CPU version (16 threaded Intel(R) Xeon(R) CPU E5-2650 processsor). The CUDA based parallel implementation is described in detail with fine-grained comparison between the GPU and CPU implementations. By achieving nearly 8 fold speedup without performance degradation our work expands the applicability of the KAZE algorithm. Additionally, the strategies described here can prove useful for the GPU implementation of other nonlinear scale space based methods.

##### Abstract (translated by Google)
最近提出的开源KAZE图像特征检测和描述算法与SIFT和SURF等传统算法相比，提供了前所未有的性能，因为它依赖于非线性尺度空间而不是高斯线性尺度空间。然而，改进的性能伴随着显着的计算成本，限制了其在许多应用中的使用。我们报告了KAZE算法的GPGPU实现，而不求助于提高加速的二进制描述符。对于1920×1200大小的图像，我们的计算统一设备架构（CUDA）C GPU版本在NVIDIA GeForce GTX Titan X（Maxwell Architecture-GM200）卡上花费了大约300毫秒，相比之下，多线程CPU版本的版本接近2400毫秒英特尔（R）至强（R）CPU E5-2650处理器）。 GPU和CPU实现之间的细粒度比较详细描述了基于CUDA的并行实现。通过实现接近8倍的加速而不降低性能，我们的工作扩展了KAZE算法的适用性。此外，这里描述的策略可以证明对其他非线性尺度空间方法的GPU实现有用。

##### URL
[https://arxiv.org/abs/1706.06750](https://arxiv.org/abs/1706.06750)

##### PDF
[https://arxiv.org/pdf/1706.06750](https://arxiv.org/pdf/1706.06750)

