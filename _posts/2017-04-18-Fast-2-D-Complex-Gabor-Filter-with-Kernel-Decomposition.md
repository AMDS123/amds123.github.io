---
layout: post
title: "Fast 2-D Complex Gabor Filter with Kernel Decomposition"
date: 2017-04-18 08:34:33
categories: arXiv_CV
tags: arXiv_CV
author: Suhyuk Um, Jaeyoon Kim, Dongbo Min (Senior Member, IEEE)
mathjax: true
---

* content
{:toc}

##### Abstract
2-D complex Gabor filtering has found numerous applications in the fields of computer vision and image processing. Especially, in some applications, it is often needed to compute 2-D complex Gabor filter bank consisting of the 2-D complex Gabor filtering outputs at multiple orientations and frequencies. Although several approaches for fast 2-D complex Gabor filtering have been proposed, they primarily focus on reducing the runtime of performing the 2-D complex Gabor filtering once at specific orientation and frequency. To obtain the 2-D complex Gabor filter bank output, existing methods are repeatedly applied with respect to multiple orientations and frequencies. In this paper, we propose a novel approach that efficiently computes the 2-D complex Gabor filter bank by reducing the computational redundancy that arises when performing the Gabor filtering at multiple orientations and frequencies. The proposed method first decomposes the Gabor basis kernels to allow a fast convolution with the Gaussian kernel in a separable manner. This enables reducing the runtime of the 2-D complex Gabor filter bank by reusing intermediate results of the 2-D complex Gabor filtering computed at a specific orientation. Furthermore, we extend this idea into 2-D localized sliding discrete Fourier transform (SDFT) using the Gaussian kernel in the DFT computation, which lends a spatial localization ability as in the 2-D complex Gabor filter. Experimental results demonstrate that our method runs faster than state-of-the-arts methods for fast 2-D complex Gabor filtering, while maintaining similar filtering quality.

##### Abstract (translated by Google)
二维复杂的Gabor滤波在计算机视觉和图像处理领域有着广泛的应用。特别是在某些应用中，往往需要计算由多个方向和频率的二维复Gabor滤波输出组成的二维复Gabor滤波器组。尽管已经提出了几种用于快速二维复Gabor滤波的方法，但是它们主要集中于减少在特定方向和频率下执行二维复Gabor滤波的运行时间。为了获得二维复Gabor滤波器组的输出，现有的方法被重复应用于多个方向和频率。在本文中，我们提出了一种新颖的方法，通过减少在多个方向和频率上执行Gabor滤波时产生的计算冗余，有效地计算二维复Gabor滤波器组。所提出的方法首先分解Gabor基核以允许以可分离的方式与高斯核进行快速卷积。这样可以通过重新使用在特定方向上计算的二维复杂Gabor滤波的中间结果来减少二维复杂Gabor滤波器组的运行时间。此外，我们将这个思想扩展到使用DFT计算中的高斯内核的二维局部滑动离散傅里叶变换（SDFT），这提供了如在二维复Gabor滤波器中的空间定位能力。实验结果表明，我们的方法运行速度比现有技术快速的二维复杂Gabor滤波方法，同时保持相似的过滤质量。

##### URL
[https://arxiv.org/abs/1704.05231](https://arxiv.org/abs/1704.05231)

##### PDF
[https://arxiv.org/pdf/1704.05231](https://arxiv.org/pdf/1704.05231)

