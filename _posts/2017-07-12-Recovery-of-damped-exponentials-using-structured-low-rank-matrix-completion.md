---
layout: post
title: "Recovery of damped exponentials using structured low rank matrix completion"
date: 2017-07-12 14:46:30
categories: arXiv_CV
tags: arXiv_CV Regularization CNN Relation
author: Arvind Balachandrasekaran, Vincent Magnotta, Mathews Jacob
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a structured low rank matrix completion algorithm to recover a series of images from their under-sampled measurements, where the signal along the parameter dimension at every pixel is described by a linear combination of exponentials. We exploit the exponential behavior of the signal at every pixel, along with the spatial smoothness of the exponential parameters to derive an annihilation relation in the Fourier domain. This relation translates to a low-rank property on a structured matrix constructed from the Fourier samples. We enforce the low rank property of the structured matrix as a regularization prior to recover the images. Since the direct use of current low rank matrix recovery schemes to this problem is associated with high computational complexity and memory demand, we adopt an iterative re-weighted least squares (IRLS) algorithm, which facilitates the exploitation of the convolutional structure of the matrix. Novel approximations involving two dimensional Fast Fourier Transforms (FFT) are introduced to drastically reduce the memory demand and computational complexity, which facilitates the extension of structured low rank methods to large scale three dimensional problems. We demonstrate our algorithm in the MR parameter mapping setting and show improvement over the state-of-the-art methods.

##### Abstract (translated by Google)
我们引入了一种结构化的低秩矩阵完成算法来从其欠采样测量中恢复一系列图像，其中沿着每个像素处的参数维度的信号由指数的线性组合来描述。我们利用信号在每个像素处的指数行为以及指数参数的空间平滑性来导出傅立叶域中的湮灭关系。这个关系转化为由傅里叶样本构造的结构化矩阵上的低秩属性。在恢复图像之前，我们强化结构化矩阵的低秩属性作为正则化。由于直接使用当前的低秩矩阵恢复方案来解决这个问题与高计算复杂度和内存需求相关，所以我们采用迭代加权最小二乘（IRLS）算法，这有利于矩阵的卷积结构的开发。引入了涉及二维快速傅里叶变换（FFT）的新颖近似，以大大减少内存需求和计算复杂度，这便于将结构化低秩方法扩展到大规模三维问题。我们在MR参数映射设置中演示了我们的算法，并显示了最先进方法的改进。

##### URL
[https://arxiv.org/abs/1704.04511](https://arxiv.org/abs/1704.04511)

##### PDF
[https://arxiv.org/pdf/1704.04511](https://arxiv.org/pdf/1704.04511)

