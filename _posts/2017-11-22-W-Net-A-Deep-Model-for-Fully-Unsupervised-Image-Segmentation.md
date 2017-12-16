---
layout: post
title: "W-Net: A Deep Model for Fully Unsupervised Image Segmentation"
date: 2017-11-22 21:06:13
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention CNN Semantic_Segmentation Prediction
author: Xide Xia, Brian Kulis
mathjax: true
---

* content
{:toc}

##### Abstract
While significant attention has been recently focused on designing supervised deep semantic segmentation algorithms for vision tasks, there are many domains in which sufficient supervised pixel-level labels are difficult to obtain. In this paper, we revisit the problem of purely unsupervised image segmentation and propose a novel deep architecture for this problem. We borrow recent ideas from supervised semantic segmentation methods, in particular by concatenating two fully convolutional networks together into an autoencoder--one for encoding and one for decoding. The encoding layer produces a k-way pixelwise prediction, and both the reconstruction error of the autoencoder as well as the normalized cut produced by the encoder are jointly minimized during training. When combined with suitable postprocessing involving conditional random field smoothing and hierarchical segmentation, our resulting algorithm achieves impressive results on the benchmark Berkeley Segmentation Data Set, outperforming a number of competing methods.

##### Abstract (translated by Google)
近年来，人们对视觉任务的有监督深度语义分割算法的研究越来越引起人们的关注，但其中有许多领域难以获得足够的监督像素级标签。在本文中，我们重新审视纯粹无监督的图像分割问题，并提出了一个新的深层次的体系结构。我们从监督的语义分割方法中借鉴了最近的想法，特别是通过将两个完全卷积网络连接在一起成为自编码器 - 一个用于编码和一个用于解码。编码层产生k路像素预测，并且训练期间自编码器的重构误差以及由编码器产生的归一化切割都被联合最小化。当结合适当的后处理涉及条件随机场平滑和分层分割，我们的结果算法在基准伯克利分割数据集上实现了令人印象深刻的结果，胜过了一些竞争方法。

##### URL
[https://arxiv.org/abs/1711.08506](https://arxiv.org/abs/1711.08506)

##### PDF
[https://arxiv.org/pdf/1711.08506](https://arxiv.org/pdf/1711.08506)

