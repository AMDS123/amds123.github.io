---
layout: post
title: "Beyond Textures: Learning from Multi-domain Artistic Images for Arbitrary Style Transfer"
date: 2018-05-25 05:54:39
categories: arXiv_CV
tags: arXiv_CV Adversarial Style_Transfer Quantitative
author: Zheng Xu, Michael Wilber, Chen Fang, Aaron Hertzmann, Hailin Jin
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a fast feed-forward network for arbitrary style transfer, which can generate stylized image for previously unseen content and style image pairs. Besides the traditional content and style representation based on deep features and statistics for textures, we use adversarial networks to regularize the generation of stylized images. Our adversarial network learns the intrinsic property of image styles from large-scale multi-domain artistic images. The adversarial training is challenging because both the input and output of our generator are diverse multi-domain images. We use a conditional generator that stylized content by shifting the statistics of deep features, and a conditional discriminator based on the coarse category of styles. Moreover, we propose a mask module to spatially decide the stylization level and stabilize adversarial training by avoiding mode collapse. As a side effect, our trained discriminator can be applied to rank and select representative stylized images. We qualitatively and quantitatively evaluate the proposed method, and compare with recent style transfer methods.

##### Abstract (translated by Google)
我们为任意样式传输提供了一个快速前馈网络，可以为以前看不见的内容和样式图像对生成风格化的图像。除了基于深度特征和纹理统计的传统内容和风格表示外，我们还使用对抗网络来调整程式化图像的生成。我们的对抗网络从大型多领域艺术图像中学习图像风格的内在属性。对抗训练是具有挑战性的，因为我们的发生器的输入和输出都是不同的多域图像。我们使用条件生成器，通过移动深度特征的统计信息和基于粗略风格类别的条件判别器来对内容进行风格化。此外，我们提出了一个面具模块来空间决定程式化水平，并通过避免模式崩溃来稳定对抗训练。作为副作用，我们的训练过的鉴别器可以用于排序和选择具有代表性的程式化图像。我们对所提出的方法进行了定性和定量评估，并与近期的风格转换方法进行了比较。

##### URL
[http://arxiv.org/abs/1805.09987](http://arxiv.org/abs/1805.09987)

##### PDF
[http://arxiv.org/pdf/1805.09987](http://arxiv.org/pdf/1805.09987)

