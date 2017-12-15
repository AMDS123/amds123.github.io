---
layout: post
title: "Fast and Provably Accurate Bilateral Filtering"
date: 2016-03-26 14:05:34
categories: arXiv_CV
tags: arXiv_CV Relation
author: Kunal N. Chaudhury, Swapnil D. Dabhade
mathjax: true
---

* content
{:toc}

##### Abstract
The bilateral filter is a non-linear filter that uses a range filter along with a spatial filter to perform edge-preserving smoothing of images. A direct computation of the bilateral filter requires $O(S)$ operations per pixel, where $S$ is the size of the support of the spatial filter. In this paper, we present a fast and provably accurate algorithm for approximating the bilateral filter when the range kernel is Gaussian. In particular, for box and Gaussian spatial filters, the proposed algorithm can cut down the complexity to $O(1)$ per pixel for any arbitrary $S$. The algorithm has a simple implementation involving $N+1$ spatial filterings, where $N$ is the approximation order. We give a detailed analysis of the filtering accuracy that can be achieved by the proposed approximation in relation to the target bilateral filter. This allows us to to estimate the order $N$ required to obtain a given accuracy. We also present comprehensive numerical results to demonstrate that the proposed algorithm is competitive with state-of-the-art methods in terms of speed and accuracy.

##### Abstract (translated by Google)
双边滤波器是一种非线性滤波器，它使用范围滤波器和空间滤波器来执行图像的边缘保持平滑。直接计算双边滤波器需要每个像素$ O（S）$操作，其中$ S $是空间滤波器支持的大小。在本文中，我们提出了一个快速的，可证明的准确算法，当距离核高斯时，用于近似双边滤波器。特别地，对于盒和高斯空间滤波器，所提出的算法可以将任意$ S $的复杂度降低到每像素$ O（1）$。该算法有一个涉及$ N + 1 $空间过滤的简单实现，其中$ N $是近似顺序。我们详细分析了所提出的与目标双边滤波器有关的逼近可以达到的滤波精度。这使我们能够估计获得给定准确度所需的订单$ N $。我们还提出了全面的数值结果，以证明所提出的算法在速度和准确性方面与最先进的方法是竞争的。

##### URL
[https://arxiv.org/abs/1603.08109](https://arxiv.org/abs/1603.08109)

##### PDF
[https://arxiv.org/pdf/1603.08109](https://arxiv.org/pdf/1603.08109)

