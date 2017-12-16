---
layout: post
title: "Accelerating Discrete Wavelet Transforms on GPUs"
date: 2017-05-18 14:42:19
categories: arXiv_CV
tags: arXiv_CV Optimization
author: David Barina, Michal Kula, Michal Matysek, Pavel Zemcik
mathjax: true
---

* content
{:toc}

##### Abstract
The two-dimensional discrete wavelet transform has a huge number of applications in image-processing techniques. Until now, several papers compared the performance of such transform on graphics processing units (GPUs). However, all of them only dealt with lifting and convolution computation schemes. In this paper, we show that corresponding horizontal and vertical lifting parts of the lifting scheme can be merged into non-separable lifting units, which halves the number of steps. We also discuss an optimization strategy leading to a reduction in the number of arithmetic operations. The schemes were assessed using the OpenCL and pixel shaders. The proposed non-separable lifting scheme outperforms the existing schemes in many cases, irrespective of its higher complexity.

##### Abstract (translated by Google)
二维离散小波变换在图像处理技术中具有大量的应用。到目前为止，一些论文比较了图形处理单元（GPU）上这种转换的性能。但是，它们都只涉及到提升和卷积计算方案。在本文中，我们表明，提升方案的相应的水平和垂直提升部分可合并成不可分离的提升单元，其步数减半。我们还讨论了一个优化策略，可以减少算术运算的次数。这些方案使用OpenCL和像素着色器进行评估。所提出的非分离提升方案在许多情况下胜过现有方案，不管其复杂性如何。

##### URL
[https://arxiv.org/abs/1705.08266](https://arxiv.org/abs/1705.08266)

##### PDF
[https://arxiv.org/pdf/1705.08266](https://arxiv.org/pdf/1705.08266)

