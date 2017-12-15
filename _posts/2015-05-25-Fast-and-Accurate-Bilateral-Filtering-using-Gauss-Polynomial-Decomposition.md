---
layout: post
title: "Fast and Accurate Bilateral Filtering using Gauss-Polynomial Decomposition"
date: 2015-05-25 09:50:02
categories: arXiv_CV
tags: arXiv_CV
author: Kunal N. Chaudhury
mathjax: true
---

* content
{:toc}

##### Abstract
The bilateral filter is a versatile non-linear filter that has found diverse applications in image processing, computer vision, computer graphics, and computational photography. A widely-used form of the filter is the Gaussian bilateral filter in which both the spatial and range kernels are Gaussian. A direct implementation of this filter requires $O(\sigma^2)$ operations per pixel, where $\sigma$ is the standard deviation of the spatial Gaussian. In this paper, we propose an accurate approximation algorithm that can cut down the computational complexity to $O(1)$ per pixel for any arbitrary $\sigma$ (constant-time implementation). This is based on the observation that the range kernel operates via the translations of a fixed Gaussian over the range space, and that these translated Gaussians can be accurately approximated using the so-called Gauss-polynomials. The overall algorithm emerging from this approximation involves a series of spatial Gaussian filtering, which can be implemented in constant-time using separability and recursion. We present some preliminary results to demonstrate that the proposed algorithm compares favorably with some of the existing fast algorithms in terms of speed and accuracy.

##### Abstract (translated by Google)
双边滤波器是一种多功能的非线性滤波器，在图像处理，计算机视觉，计算机图形学和计算机摄影等领域有广泛的应用。一种广泛使用的滤波器形式是高斯双边滤波器，其中空间和距离内核都是高斯的。直接实现这个过滤器需要每个像素$ O（\ sigma ^ 2）$操作，其中$ \ sigma $是空间高斯的标准偏差。在本文中，我们提出了一个精确的近似算法，可以将任意$ \ sigma $（恒定时间实现）的计算复杂度降低到$ O（1）$像素。这是基于观察范围核心通过在范围空间上的固定高斯的平移来操作，并且这些被翻译的高斯可以使用所谓的高斯多项式来精确地近似。从这个近似出现的整体算法涉及一系列空间高斯滤波，可以使用可分性和递归在恒定时间内实现。我们提出了一些初步的结果来证明所提出的算法在速度和准确性方面与现有的一些快速算法相比有优势。

##### URL
[https://arxiv.org/abs/1505.00077](https://arxiv.org/abs/1505.00077)

##### PDF
[https://arxiv.org/pdf/1505.00077](https://arxiv.org/pdf/1505.00077)

