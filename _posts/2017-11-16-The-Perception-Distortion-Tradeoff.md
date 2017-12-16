---
layout: post
title: "The Perception-Distortion Tradeoff"
date: 2017-11-16 13:22:30
categories: arXiv_CV
tags: arXiv_CV Adversarial Super_Resolution GAN
author: Yochai Blau, Tomer Michaeli
mathjax: true
---

* content
{:toc}

##### Abstract
Image restoration algorithms are typically evaluated by some distortion measure (e.g. PSNR, SSIM) or by human opinion scores that directly quantify perceived perceptual quality. In this paper, we prove mathematically that distortion and perceptual quality are at odds with each other. Specifically, we study the optimal probability for discriminating the outputs of an image restoration algorithm from real images. We show that as the mean distortion decreases, this probability must increase (indicating lower perceptual quality). Surprisingly, this result holds true for any distortion measure (including advanced criteria). However, as we show experimentally, for some measures it is less severe (e.g. distances between VGG features). We also show that generative-adversarial-nets (GANs) provide a principled way to approach the perception-distortion bound. This constitutes theoretical support to their observed success in low-level vision tasks. Based on our analysis, we propose a new methodology for evaluating image restoration methods, and use it to perform an extensive comparison between recent super-resolution algorithms.

##### Abstract (translated by Google)
通常通过一些失真度量（例如PSNR，SSIM）或通过直接量化感知质量的人类意见分数来评估图像恢复算法。在本文中，我们从数学上证明扭曲和感知质量是相互矛盾的。具体而言，我们研究了用于从真实图像中区分图像恢复算法的输出的最佳概率。我们表明，随着平均失真减少，这个概率必须增加（表明较低的感知质量）。令人惊讶的是，这个结果适用于任何失真度量（包括高级标准）。然而，正如我们在实验中显示的那样，对于一些措施来说，它不那么严重（例如，VGG特征之间的距离）。我们还表明，生成对抗网（GAN）提供了一个原则性的方法来处理感知扭曲的界限。这构成了他们在低级别视觉任务中观察到的成功的理论支持。基于我们的分析，我们提出了一种评估图像恢复方法的新方法，并用它来进行最近的超分辨率算法之间的广泛比较。

##### URL
[https://arxiv.org/abs/1711.06077](https://arxiv.org/abs/1711.06077)

##### PDF
[https://arxiv.org/pdf/1711.06077](https://arxiv.org/pdf/1711.06077)

