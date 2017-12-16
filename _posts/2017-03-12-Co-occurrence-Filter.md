---
layout: post
title: "Co-occurrence Filter"
date: 2017-03-12 12:41:16
categories: arXiv_CV
tags: arXiv_CV
author: Roy J Jevnisek, Shai Avidan
mathjax: true
---

* content
{:toc}

##### Abstract
Co-occurrence Filter (CoF) is a boundary preserving filter. It is based on the Bilateral Filter (BF) but instead of using a Gaussian on the range values to preserve edges it relies on a co-occurrence matrix. Pixel values that co-occur frequently in the image (i.e., inside textured regions) will have a high weight in the co-occurrence matrix. This, in turn, means that such pixel pairs will be averaged and hence smoothed, regardless of their intensity differences. On the other hand, pixel values that rarely co-occur (i.e., across texture boundaries) will have a low weight in the co-occurrence matrix. As a result, they will not be averaged and the boundary between them will be preserved. The CoF therefore extends the BF to deal with boundaries, not just edges. It learns co-occurrences directly from the image. We can achieve various filtering results by directing it to learn the co-occurrence matrix from a part of the image, or a different image. We give the definition of the filter, discuss how to use it with color images and show several use cases.

##### Abstract (translated by Google)
共现滤波器（CoF）是一个边界保持滤波器。它基于双边滤波器（BF），而不是使用范围值上的高斯来保留边缘，而是依赖于共生矩阵。在图像中频繁共存的像素值（即纹理化区域内）将在共现矩阵中具有高权重。这又意味着这样的像素对将被平均并因此平滑，而不管它们的强度差异如何。另一方面，很少共同出现的像素值（即跨纹理边界）将在共现矩阵中具有低权重。因此，它们不会被平均，它们之间的边界将被保留下来。因此，CoF扩展了BF来处理边界，而不仅仅是边界。它直接从图像中学习共现。我们可以通过指导它从图像的一部分或不同的图像中学习共现矩阵来获得各种滤波结果。我们给出过滤器的定义，讨论如何在彩色图像中使用它并显示几个用例。

##### URL
[https://arxiv.org/abs/1703.04111](https://arxiv.org/abs/1703.04111)

##### PDF
[https://arxiv.org/pdf/1703.04111](https://arxiv.org/pdf/1703.04111)

