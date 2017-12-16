---
layout: post
title: "A Non-Local Means Approach for Gaussian Noise Removal from Images using a Modified Weighting Kernel"
date: 2016-12-03 19:00:18
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention
author: Mojtaba Kazemi, Ehsan Mohammadi.P, Parichehr shahidi sadeghi, Mohamad B. Menhaj
mathjax: true
---

* content
{:toc}

##### Abstract
Gaussian noise removal is an interesting area in digital image processing not only to improve the visual quality, but for its impact on other post-processing algorithms like image registration or segmentation. Many presented state-of-the-art denoising methods are based on the self-similarity or patch-based image processing. Specifically, Non-Local Means (NLM) as a patch-based filter has gained increasing attention in recent years. Essentially, this filter tends to obtain the noise-less signal value by computing the Gaussian-weighted Euclidean distance between the patch under-processing and other patches inside the image. However, the NLM filter is sensitive to the outliers (pixels that their intensity values are far away from other pixels) inside the patch, meaning that the pixels with the symmetric locations in the patch are assigned the same weight. This can lead to sub-optimal denoising performance when the destructive nature of noise generates some outliers inside patches. In this paper, we propose a new weighting approach to modify the Gaussian kernel of the NLM filter. Our approach employs the geometric distance between image intensities to come up with new weights for each pixel of a patch, lowering the impact of outliers on the denoising performance. Experiments on a set of standard images and different noise levels show that our proposed method outperforms the other compared denoising filters.

##### Abstract (translated by Google)
高斯噪声去除是数字图像处理中一个有趣的领域，不仅要提高视觉质量，还要考虑到其对图像配准或分割等后处理算法的影响。许多提出的最先进的去噪方法是基于自相似性或基于补丁的图像处理。具体而言，近年来，非局部均值（NLM）作为基于贴片的滤波器已经引起越来越多的关注。本质上，这个滤波器通过计算图像内的补丁处理和其他补丁之间的高斯加权欧几里德距离来获得无噪声信号值。然而，NLM滤波器对贴片内的异常值（其强度值远离其他像素的像素）敏感，这意味着贴片中具有对称位置的像素被赋予相同的权重。当噪声的破坏性在补丁内部产生一些异常值时，这可能导致次优降噪性能。在本文中，我们提出了一种新的加权方法来修改NLM滤波器的高斯核。我们的方法采用图像强度之间的几何距离来为贴片的每个像素提供新的权重，降低了异常值对去噪性能的影响。在一组标准图像和不同噪声水平上的实验表明，我们提出的方法优于其他比较的去噪滤波器。

##### URL
[https://arxiv.org/abs/1612.01006](https://arxiv.org/abs/1612.01006)

##### PDF
[https://arxiv.org/pdf/1612.01006](https://arxiv.org/pdf/1612.01006)

