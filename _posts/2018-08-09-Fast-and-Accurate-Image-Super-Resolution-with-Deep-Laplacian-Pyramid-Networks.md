---
layout: post
title: "Fast and Accurate Image Super-Resolution with Deep Laplacian Pyramid Networks"
date: 2018-08-09 19:31:38
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN Quantitative
author: Wei-Sheng Lai, Jia-Bin Huang, Narendra Ahuja, Ming-Hsuan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks have recently demonstrated high-quality reconstruction for single image super-resolution. However, existing methods often require a large number of network parameters and entail heavy computational loads at runtime for generating high-accuracy super-resolution results. In this paper, we propose the deep Laplacian Pyramid Super-Resolution Network for fast and accurate image super-resolution. The proposed network progressively reconstructs the sub-band residuals of high-resolution images at multiple pyramid levels. In contrast to existing methods that involve the bicubic interpolation for pre-processing (which results in large feature maps), the proposed method directly extracts features from the low-resolution input space and thereby entails low computational loads. We train the proposed network with deep supervision using the robust Charbonnier loss functions and achieve high-quality image reconstruction. Furthermore, we utilize the recursive layers to share parameters across as well as within pyramid levels, and thus drastically reduce the number of parameters. Extensive quantitative and qualitative evaluations on benchmark datasets show that the proposed algorithm performs favorably against the state-of-the-art methods in terms of run-time and image quality.

##### Abstract (translated by Google)
卷积神经网络最近证明了单图像超分辨率的高质量重建。然而，现有方法通常需要大量网络参数并且在运行时需要大量计算负荷以产生高精度超分辨率结果。在本文中，我们提出了深拉普拉斯金字塔超分辨率网络，以实现快速准确的图像超分辨率。所提出的网络逐步重建多个金字塔等级的高分辨率图像的子带残差。与涉及用于预处理的双三次插值（其导致大特征图）的现有方法相比，所提出的方法直接从低分辨率输入空间提取特征，从而需要低计算负荷。我们使用强大的Charbonnier损失函数深入监控所提出的网络，并实现高质量的图像重建。此外，我们利用递归层在金字塔等级内共享参数，从而大大减少参数的数量。对基准数据集进行广泛的定量和定性评估表明，所提出的算法在运行时和图像质量方面对最先进的方法表现出色。

##### URL
[http://arxiv.org/abs/1710.01992](http://arxiv.org/abs/1710.01992)

##### PDF
[http://arxiv.org/pdf/1710.01992](http://arxiv.org/pdf/1710.01992)

