---
layout: post
title: "A Gamut-Mapping Framework for Color-Accurate Reproduction of HDR Images"
date: 2017-11-24 11:06:07
categories: arXiv_CV
tags: arXiv_CV
author: E. Sikudova, T. Pouli, A. Artusi, A. O. Akyuz, F. Banterle, Z. M. Mazlumoglu, E. Reinhard
mathjax: true
---

* content
{:toc}

##### Abstract
Few tone mapping operators (TMOs) take color management into consideration, limiting compression to luminance values only. This may lead to changes in image chroma and hues which are typically managed with a post-processing step. However, current post-processing techniques for tone reproduction do not explicitly consider the target display gamut. Gamut mapping on the other hand, deals with mapping images from one color gamut to another, usually smaller, gamut but has traditionally focused on smaller scale, chromatic changes. In this context, we present a novel gamut and tone management framework for color-accurate reproduction of high dynamic range (HDR) images, which is conceptually and computationally simple, parameter-free, and compatible with existing TMOs. In the CIE LCh color space, we compress chroma to fit the gamut of the output color space. This prevents hue and luminance shifts while taking gamut boundaries into consideration. We also propose a compatible lightness compression scheme that minimizes the number of color space conversions. Our results show that our gamut management method effectively compresses the chroma of tone mapped images, respecting the target gamut and without reducing image quality.

##### Abstract (translated by Google)
很少有色调映射操作符（TMO）考虑色彩管理，仅将压缩限制为亮度值。这可能导致图像色度和色调的变化，这些变化通常是通过后处理步骤来管理的。然而，用于色调再现的当前后处理技术没有明确考虑目标显示器色域。另一方面，色域映射涉及将图像从一个色域映射到另一个色域，通常是较小的色域，但传统上集中于较小的色度变化。在这个背景下，我们提出了一个新的色域和色调管理框架，用于高精度重现高动态范围（HDR）图像，这是概念和计算简单，无参数，并与现有的TMO兼容。在CIE LCh色彩空间中，我们压缩色度以适应输出色彩空间的色域。这可以防止在考虑色域边界的同时调整色调和亮度。我们还提出了一种兼容的亮度压缩方案，可以最大限度地减少色彩空间转换次数。我们的结果表明，我们的色域管理方法有效地压缩色调映射图像的色度，尊重目标色域，而不会降低图像质量。

##### URL
[https://arxiv.org/abs/1711.08925](https://arxiv.org/abs/1711.08925)

##### PDF
[https://arxiv.org/pdf/1711.08925](https://arxiv.org/pdf/1711.08925)

