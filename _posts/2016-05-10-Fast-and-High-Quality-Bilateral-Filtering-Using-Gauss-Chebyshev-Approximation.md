---
layout: post
title: "Fast and High-Quality Bilateral Filtering Using Gauss-Chebyshev Approximation"
date: 2016-05-10 03:19:09
categories: arXiv_CV
tags: arXiv_CV
author: Sanjay Ghosh, Kunal N. Chaudhury
mathjax: true
---

* content
{:toc}

##### Abstract
The bilateral filter is an edge-preserving smoother that has diverse applications in image processing, computer vision, computer graphics, and computational photography. The filter uses a spatial kernel along with a range kernel to perform edge-preserving smoothing. In this paper, we consider the Gaussian bilateral filter where both the kernels are Gaussian. A direct implementation of the Gaussian bilateral filter requires $O(\sigma_s^2)$ operations per pixel, where $\sigma_s$ is the standard deviation of the spatial Gaussian. In fact, it is well-known that the direct implementation is slow in practice. We present an approximation of the Gaussian bilateral filter, whereby we can cut down the number of operations to $O(1)$ per pixel for any arbitrary $\sigma_s$, and yet achieve very high-quality filtering that is almost indistinguishable from the output of the original filter. We demonstrate that the proposed approximation is few orders faster in practice compared to the direct implementation. We also demonstrate that the approximation is competitive with existing fast algorithms in terms of speed and accuracy.

##### Abstract (translated by Google)
双边滤波器是一个边缘保持平滑器，在图像处理，计算机视觉，计算机图形学和计算摄影方面具有不同的应用。过滤器使用空间内核和范围内核来执行边缘保留平滑。在本文中，我们考虑两个核都是高斯的高斯双边滤波器。直接实现高斯双边滤波器需要每个像素$ O（\ sigma_s ^ 2）$操作，其中$ \ sigma_s $是空间高斯的标准偏差。其实众所周知，直接实施在实践中是缓慢的。我们给出了一个近似的高斯双边滤波器，从而我们可以将任意$ \ sigma_s $减少到$ O（1）$像素的运算次数，而且实现了非常高质量的滤波，几乎没有什么区别。原始过滤器的输出。我们证明，与直接实施相比，提出的近似在实践中几乎是较少的订单。我们还证明了近似在速度和准确性方面与现有的快速算法具有竞争性。

##### URL
[https://arxiv.org/abs/1605.02178](https://arxiv.org/abs/1605.02178)

##### PDF
[https://arxiv.org/pdf/1605.02178](https://arxiv.org/pdf/1605.02178)

