---
layout: post
title: "On Fast Bilateral Filtering using Fourier Kernels"
date: 2016-03-26 07:09:58
categories: arXiv_CV
tags: arXiv_CV
author: Sanjay Ghosh, Kunal N. Chaudhury
mathjax: true
---

* content
{:toc}

##### Abstract
It was demonstrated in earlier work that, by approximating its range kernel using shiftable functions, the non-linear bilateral filter can be computed using a series of fast convolutions. Previous approaches based on shiftable approximation have, however, been restricted to Gaussian range kernels. In this work, we propose a novel approximation that can be applied to any range kernel, provided it has a pointwise-convergent Fourier series. More specifically, we propose to approximate the Gaussian range kernel of the bilateral filter using a Fourier basis, where the coefficients of the basis are obtained by solving a series of least-squares problems. The coefficients can be efficiently computed using a recursive form of the QR decomposition. By controlling the cardinality of the Fourier basis, we can obtain a good tradeoff between the run-time and the filtering accuracy. In particular, we are able to guarantee sub-pixel accuracy for the overall filtering, which is not provided by most existing methods for fast bilateral filtering. We present simulation results to demonstrate the speed and accuracy of the proposed algorithm.

##### Abstract (translated by Google)
在前面的工作中已经证明，通过使用可移位函数来逼近其范围内核，可以使用一系列快速卷积来计算非线性双边滤波器。然而，基于可移位近似的以前的方法已被限制在高斯距离内核。在这项工作中，我们提出了一个新的近似，可以应用于任何距离内核，只要它有一个逐点收敛的傅里叶级数。更具体地说，我们建议使用傅里叶基来逼近双边滤波器的高斯距离核，其中通过求解一系列最小二乘问题来获得基的系数。可以使用QR分解的递归形式有效地计算系数。通过控制傅里叶基的基数，我们可以在运行时间和滤波精度之间取得良好的折衷。特别是，我们能够保证整个滤波的子像素精度，这是大多数现有的快速双边滤波方法所不能提供的。我们提出的仿真结果来证明算法的速度和准确性。

##### URL
[https://arxiv.org/abs/1603.08081](https://arxiv.org/abs/1603.08081)

##### PDF
[https://arxiv.org/pdf/1603.08081](https://arxiv.org/pdf/1603.08081)

