---
layout: post
title: "Guided Filter based Edge-preserving Image Non-blind Deconvolution"
date: 2016-09-07 05:16:35
categories: arXiv_CV
tags: arXiv_CV Regularization
author: Hang Yang, Ming Zhu, Zhongbo Zhang, Heyan Huang
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we propose a new approach for efficient edge-preserving image deconvolution. Our algorithm is based on a novel type of explicit image filter - guided filter. The guided filter can be used as an edge-preserving smoothing operator like the popular bilateral filter, but has better behaviors near edges. We propose an efficient iterative algorithm with the decouple of deblurring and denoising steps in the restoration process. In deblurring step, we proposed two cost function which could be computed with fast Fourier transform efficiently. The solution of the first one is used as the guidance image, and another solution will be filtered in next step. In the denoising step, the guided filter is used with the two obtained images for efficient edge-preserving filtering. Furthermore, we derive a simple and effective method to automatically adjust the regularization parameter at each iteration. We compare our deconvolution algorithm with many competitive deconvolution techniques in terms of ISNR and visual quality.

##### Abstract (translated by Google)
在这项工作中，我们提出了一种新的有效的边缘保留图像去卷积方法。我们的算法是基于一种新型的显式图像滤波器引导滤波器。引导滤波器可以像流行的双边滤波器一样用作边缘保留平滑算子，但在边缘附近具有更好的行为。我们提出了一种高效的迭代算法，在恢复过程中去除去噪和去噪的步骤。在去模糊步骤中，我们提出了两个可以用快速傅里叶变换高效计算的代价函数。第一个解决方案被用作引导图像，另一个解决方案将在下一步被过滤。在去噪步骤中，将导向滤波器与获得的两个图像一起用于有效的边缘保留滤波。此外，我们推导出一种简单而有效的方法来自动调整每次迭代的正则化参数。我们将我们的去卷积算法与ISNR和视觉质量方面的许多竞争性去卷积技术进行比较。

##### URL
[https://arxiv.org/abs/1609.01839](https://arxiv.org/abs/1609.01839)

##### PDF
[https://arxiv.org/pdf/1609.01839](https://arxiv.org/pdf/1609.01839)

