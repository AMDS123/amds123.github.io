---
layout: post
title: "Learning a Single Tucker Decomposition Network for Lossy Image Compression with Multiple Bits-Per-Pixel Rates"
date: 2018-07-10 03:40:36
categories: arXiv_CV
tags: arXiv_CV Image_Caption CNN
author: Jianrui Cai, Zisheng Cao, Lei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Lossy image compression (LIC), which aims to utilize inexact approximations to represent an image more compactly, is a classical problem in image processing. Recently, deep convolutional neural networks (CNNs) have achieved interesting results in LIC by learning an encoder-quantizer-decoder network from a large amount of data. However, existing CNN-based LIC methods usually can only train a network for a specific bits-per-pixel (bpp). Such a "one network per bpp" problem limits the generality and flexibility of CNNs to practical LIC applications. In this paper, we propose to learn a single CNN which can perform LIC at multiple bpp rates. A simple yet effective Tucker Decomposition Network (TDNet) is developed, where there is a novel tucker decomposition layer (TDL) to decompose a latent image representation into a set of projection matrices and a core tensor. By changing the rank of the core tensor and its quantization, we can easily adjust the bpp rate of latent image representation within a single CNN. Furthermore, an iterative non-uniform quantization scheme is presented to optimize the quantizer, and a coarse-to-fine training strategy is introduced to reconstruct the decompressed images. Extensive experiments demonstrate the state-of-the-art compression performance of TDNet in terms of both PSNR and MS-SSIM indices.

##### Abstract (translated by Google)
有损图像压缩（LIC）旨在利用不精确的近似来更紧凑地表示图像，这是图像处理中的经典问题。最近，深度卷积神经网络（CNN）通过从大量数据中学习编码器 - 量化器 - 解码器网络在LIC中获得了有趣的结果。然而，现有的基于CNN的LIC方法通常只能针对特定的每像素比特（bpp）训练网络。这种“每个bpp一个网络”问题限制了CNN对实际LIC应用的普遍性和灵活性。在本文中，我们建议学习一个能够以多个bpp速率执行LIC的CNN。开发了一种简单而有效的Tucker分解网络（TDNet），其中存在一种新颖的tucker分解层（TDL），用于将潜像表示分解为一组投影矩阵和核心张量。通过改变核心张量的等级及其量化，我们可以容易地调整单个CNN内的潜像表示的bpp率。此外，呈现迭代非均匀量化方案以优化量化器，并且引入粗略到精细训练策略以重建解压缩图像。大量实验证明了TDNet在PSNR和MS-SSIM指数方面的最先进压缩性能。

##### URL
[http://arxiv.org/abs/1807.03470](http://arxiv.org/abs/1807.03470)

##### PDF
[http://arxiv.org/pdf/1807.03470](http://arxiv.org/pdf/1807.03470)

