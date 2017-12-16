---
layout: post
title: "Photo-Realistic Single Image Super-Resolution Using a Generative Adversarial Network"
date: 2017-05-25 11:25:41
categories: arXiv_CV
tags: arXiv_CV Adversarial Super_Resolution Knowledge GAN CNN Optimization
author: Christian Ledig, Lucas Theis, Ferenc Huszar, Jose Caballero, Andrew Cunningham, Alejandro Acosta, Andrew Aitken, Alykhan Tejani, Johannes Totz, Zehan Wang, Wenzhe Shi
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the breakthroughs in accuracy and speed of single image super-resolution using faster and deeper convolutional neural networks, one central problem remains largely unsolved: how do we recover the finer texture details when we super-resolve at large upscaling factors? The behavior of optimization-based super-resolution methods is principally driven by the choice of the objective function. Recent work has largely focused on minimizing the mean squared reconstruction error. The resulting estimates have high peak signal-to-noise ratios, but they are often lacking high-frequency details and are perceptually unsatisfying in the sense that they fail to match the fidelity expected at the higher resolution. In this paper, we present SRGAN, a generative adversarial network (GAN) for image super-resolution (SR). To our knowledge, it is the first framework capable of inferring photo-realistic natural images for 4x upscaling factors. To achieve this, we propose a perceptual loss function which consists of an adversarial loss and a content loss. The adversarial loss pushes our solution to the natural image manifold using a discriminator network that is trained to differentiate between the super-resolved images and original photo-realistic images. In addition, we use a content loss motivated by perceptual similarity instead of similarity in pixel space. Our deep residual network is able to recover photo-realistic textures from heavily downsampled images on public benchmarks. An extensive mean-opinion-score (MOS) test shows hugely significant gains in perceptual quality using SRGAN. The MOS scores obtained with SRGAN are closer to those of the original high-resolution images than to those obtained with any state-of-the-art method.

##### Abstract (translated by Google)
尽管使用更快和更深的卷积神经网络在单幅图像超分辨率的准确性和速度方面取得了突破，但是一个中心问题仍然很大程度上没有解决：当我们在大规模放大因子上超解析时，如何恢复更精细的纹理细节？基于优化的超分辨率方法的行为主要由目标函数的选择驱动。最近的工作主要集中在最小化均方重建误差。由此产生的估计具有较高的峰值信噪比，但是它们通常缺乏高频细节，并且在不能与较高分辨率期望的保真度匹配的意义上感知不到。在本文中，我们提出SRGAN，图像超分辨率（SR）的生成敌对网络（GAN）。据我们所知，这是第一个能推出4倍放大因子的照片般逼真的自然图像的框架。为了达到这个目的，我们提出了一个由对抗性损失和内容损失构成的感知损失函数。对抗性损失将我们的解决方案推向使用辨识器网络的自然图像流形，该辨识器网络经过训练以区分超分辨图像和原始照片真实图像。此外，我们使用感知相似性驱动的内容损失，而不是像素空间中的相似性。我们的深度残留网络能够从公共基准上的严重下采样图像恢复照片般逼真的纹理。广泛的平均评分（MOS）测试显示使用SRGAN的感知质量的巨大显着增益。用SRGAN获得的MOS分数比用最先进的方法获得的分数更接近于原来的高分辨率图像。

##### URL
[https://arxiv.org/abs/1609.04802](https://arxiv.org/abs/1609.04802)

##### PDF
[https://arxiv.org/pdf/1609.04802](https://arxiv.org/pdf/1609.04802)

