---
layout: post
title: "Precomputed Real-Time Texture Synthesis with Markovian Generative Adversarial Networks"
date: 2016-04-15 07:32:18
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Style_Transfer CNN Optimization
author: Chuan Li, Michael Wand
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes Markovian Generative Adversarial Networks (MGANs), a method for training generative neural networks for efficient texture synthesis. While deep neural network approaches have recently demonstrated remarkable results in terms of synthesis quality, they still come at considerable computational costs (minutes of run-time for low-res images). Our paper addresses this efficiency issue. Instead of a numerical deconvolution in previous work, we precompute a feed-forward, strided convolutional network that captures the feature statistics of Markovian patches and is able to directly generate outputs of arbitrary dimensions. Such network can directly decode brown noise to realistic texture, or photos to artistic paintings. With adversarial training, we obtain quality comparable to recent neural texture synthesis methods. As no optimization is required any longer at generation time, our run-time performance (0.25M pixel images at 25Hz) surpasses previous neural texture synthesizers by a significant margin (at least 500 times faster). We apply this idea to texture synthesis, style transfer, and video stylization.

##### Abstract (translated by Google)
本文提出了马尔可夫生成对抗网络（MGANs），一种用于高效纹理合成的生成神经网络的训练方法。尽管深度神经网络方法最近在合成质量方面表现出显着的结果，但是它们仍然具有相当大的计算成本（低分辨率图像的运行时间的分钟数）。我们的论文解决这个效率问题。在前面的工作中，我们没有采用数值解卷积的方法，而是预先计算了一个前馈的跨步卷积网络，该卷积网络捕获马尔可夫块的特征统计量，并能够直接生成任意维度的输出。这种网络可以直接将棕色的噪点解码为逼真的纹理，或者将照片直接解码为艺术画通过对抗训练，我们获得与近期神经纹理合成方法相媲美的质量。由于不再需要进行优化，因此我们的运行时间性能（25MHz下的0.25M像素图像）比以前的神经纹理合成器有明显的优势（至少快了500倍）。我们将这个想法应用于纹理合成，风格转换和视频风格化。

##### URL
[https://arxiv.org/abs/1604.04382](https://arxiv.org/abs/1604.04382)

##### PDF
[https://arxiv.org/pdf/1604.04382](https://arxiv.org/pdf/1604.04382)

