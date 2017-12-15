---
layout: post
title: "Parallel Wavelet Schemes for Images"
date: 2016-10-12 14:38:22
categories: arXiv_CV
tags: arXiv_CV
author: David Barina, Michal Kula, Pavel Zemcik
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we introduce several new schemes for calculation of discrete wavelet transforms of images. These schemes reduce the number of steps and, as a consequence, allow to reduce the number of synchronizations on parallel architectures. As an additional useful property, the proposed schemes can reduce also the number of arithmetic operations. The schemes are primarily demonstrated on CDF 5/3 and CDF 9/7 wavelets employed in JPEG 2000 image compression standard. However, the presented method is general, and it can be applied on any wavelet transform. As a result, our scheme requires only two memory barriers for 2-D CDF 5/3 transform compared to four barriers in the original separable form or three barriers in the non-separable scheme recently published. Our reasoning is supported by exhaustive experiments on high-end graphics cards.

##### Abstract (translated by Google)
在本文中，我们介绍了几种计算图像离散小波变换的新方法。这些方案减少了步骤的数量，因此可以减少并行架构上的同步数量。作为附加的有用性质，所提出的方案也可以减少算术运算的数量。这些方案主要在JPEG 2000图像压缩标准中采用的CDF 5/3和CDF 9/7小波上进行演示。然而，所提出的方法是通用的，并且可以应用于任何小波变换。因此，我们的方案只需要两个内存屏障来进行二维CDF 5/3转换，而最初发布的不可分离方案中的四个屏障或三个不可分离方案中的三个屏障相比，我们的方案只需要两个内存屏障。我们的推理得到了高端显卡的详尽实验的支持。

##### URL
[https://arxiv.org/abs/1605.00561](https://arxiv.org/abs/1605.00561)

##### PDF
[https://arxiv.org/pdf/1605.00561](https://arxiv.org/pdf/1605.00561)

