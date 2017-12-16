---
layout: post
title: "Real-Time Single Image and Video Super-Resolution Using an Efficient Sub-Pixel Convolutional Neural Network"
date: 2016-09-23 17:16:37
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN
author: Wenzhe Shi, Jose Caballero, Ferenc Huszár, Johannes Totz, Andrew P. Aitken, Rob Bishop, Daniel Rueckert, Zehan Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, several models based on deep neural networks have achieved great success in terms of both reconstruction accuracy and computational performance for single image super-resolution. In these methods, the low resolution (LR) input image is upscaled to the high resolution (HR) space using a single filter, commonly bicubic interpolation, before reconstruction. This means that the super-resolution (SR) operation is performed in HR space. We demonstrate that this is sub-optimal and adds computational complexity. In this paper, we present the first convolutional neural network (CNN) capable of real-time SR of 1080p videos on a single K2 GPU. To achieve this, we propose a novel CNN architecture where the feature maps are extracted in the LR space. In addition, we introduce an efficient sub-pixel convolution layer which learns an array of upscaling filters to upscale the final LR feature maps into the HR output. By doing so, we effectively replace the handcrafted bicubic filter in the SR pipeline with more complex upscaling filters specifically trained for each feature map, whilst also reducing the computational complexity of the overall SR operation. We evaluate the proposed approach using images and videos from publicly available datasets and show that it performs significantly better (+0.15dB on Images and +0.39dB on Videos) and is an order of magnitude faster than previous CNN-based methods.

##### Abstract (translated by Google)
最近，基于深度神经网络的几种模型在单幅图像超分辨率的重建精度和计算性能方面取得了巨大的成功。在这些方法中，低分辨率（LR）输入图像在重建之前使用单个滤波器（通常是双三次插值）被放大到高分辨率（HR）空间。这意味着超分辨率（SR）操作在HR空间中执行。我们证明这是次优的，增加了计算复杂度。在本文中，我们提出了第一个能够在单个K2 GPU上实现1080p视频实时SR的卷积神经网络（CNN）。为了实现这一点，我们提出了一种新颖的CNN架构，在LR空间中提取特征地图。另外，我们引入了一个有效的子像素卷积层，它学习了一系列放大滤波器，将最终的LR特征图提升到HR输出。通过这样做，我们有效地将SR管道中的手工双三次滤波器替换为针对每个特征映射特别训练的更复杂的放大滤波器，同时还减少了整个SR操作的计算复杂度。我们使用公开可用的数据集中的图像和视频来评估所提出的方法，并表明它的性能明显更好（图像+ 0.15dB，视频+ 0.39dB），比以前的基于CNN的方法快了一个数量级。

##### URL
[https://arxiv.org/abs/1609.05158](https://arxiv.org/abs/1609.05158)

##### PDF
[https://arxiv.org/pdf/1609.05158](https://arxiv.org/pdf/1609.05158)

