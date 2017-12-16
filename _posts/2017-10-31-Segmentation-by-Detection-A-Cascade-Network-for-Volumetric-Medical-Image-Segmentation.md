---
layout: post
title: "Segmentation-by-Detection: A Cascade Network for Volumetric Medical Image Segmentation"
date: 2017-10-31 23:04:28
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention CNN Detection
author: Min Tang, Zichen Zhang, Dana Cobzas, Martin Jagersand, Jacob L. Jaremko
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an attention mechanism for 3D medical image segmentation. The method, named segmentation-by-detection, is a cascade of a detection module followed by a segmentation module. The detection module enables a region of interest to come to attention and produces a set of object region candidates which are further used as an attention model. Rather than dealing with the entire volume, the segmentation module distills the information from the potential region. This scheme is an efficient solution for volumetric data as it reduces the influence of the surrounding noise which is especially important for medical data with low signal-to-noise ratio. Experimental results on 3D ultrasound data of the femoral head shows superiority of the proposed method when compared with a standard fully convolutional network like the U-Net.

##### Abstract (translated by Google)
我们提出了一个三维医学图像分割的注意机制。这个名为分段检测的方法是一个检测模块的级联，后面跟着一个分段模块。检测模块使得感兴趣的区域能够引起注意，并产生一组进一步用作关注模型的对象区域候选。分割模块不是处理整个体积，而是从潜在的区域中提取信息。该方案是体积数据的有效解决方案，因为它减少了周围噪声的影响，这对于低信噪比的医疗数据尤其重要。与U-Net等标准完全卷积网络相比，股骨头三维超声数据的实验结果显示了该方法的优越性。

##### URL
[https://arxiv.org/abs/1711.00139](https://arxiv.org/abs/1711.00139)

##### PDF
[https://arxiv.org/pdf/1711.00139](https://arxiv.org/pdf/1711.00139)

