---
layout: post
title: "Discriminative Region Proposal Adversarial Networks for High-Quality Image-to-Image Translation"
date: 2018-08-06 15:26:44
categories: arXiv_CV
tags: arXiv_CV Adversarial Attention GAN Quantitative
author: Chao Wang, Haiyong Zheng, Zhibin Yu, Ziqiang Zheng, Zhaorui Gu, Bing Zheng
mathjax: true
---

* content
{:toc}

##### Abstract
Image-to-image translation has been made much progress with embracing Generative Adversarial Networks (GANs). However, it's still very challenging for translation tasks that require high quality, especially at high-resolution and photorealism. In this paper, we present Discriminative Region Proposal Adversarial Networks (DRPAN) for high-quality image-to-image translation. We decompose the procedure of image-to-image translation task into three iterated steps, first is to generate an image with global structure but some local artifacts (via GAN), second is using our DRPnet to propose the most fake region from the generated image, and third is to implement "image inpainting" on the most fake region for more realistic result through a reviser, so that the system (DRPAN) can be gradually optimized to synthesize images with more attention on the most artifact local part. Experiments on a variety of image-to-image translation tasks and datasets validate that our method outperforms state-of-the-arts for producing high-quality translation results in terms of both human perceptual studies and automatic quantitative measures.

##### Abstract (translated by Google)
采用生成性对抗网络（GAN），图像到图像的翻译取得了很大进展。然而，对于需要高质量的翻译任务来说仍然非常具有挑战性，特别是在高分辨率和照片级真实感的情况下。在本文中，我们提出了判别区域提议对抗网络（DRPAN），用于高质量的图像到图像转换。我们将图像到图像转换任务的过程分解为三个迭代步骤，首先是生成具有全局结构的图像但是一些局部伪像（通过GAN），其次是使用我们的DRPnet从生成的图像中提出最假的区域第三是通过修改器在最假区域上实现“图像修复”以获得更真实的结果，从而可以逐步优化系统（DRPAN）以更多地关注最神器局部部分来合成图像。对各种图像到图像翻译任务和数据集的实验验证了我们的方法在人类感知研究和自动定量测量方面都优于现有技术，可以产生高质量的翻译结果。

##### URL
[http://arxiv.org/abs/1711.09554](http://arxiv.org/abs/1711.09554)

##### PDF
[http://arxiv.org/pdf/1711.09554](http://arxiv.org/pdf/1711.09554)

