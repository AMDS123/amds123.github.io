---
layout: post
title: "Discriminative Region Proposal Adversarial Networks for High-Quality Image-to-Image Translation"
date: 2017-12-01 13:12:55
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Quantitative
author: Chao Wang, Haiyong Zheng, Zhibin Yu, Ziqiang Zheng, Zhaorui Gu, Bing Zheng
mathjax: true
---

* content
{:toc}

##### Abstract
Image-to-image translation has been made much progress with embracing Generative Adversarial Networks (GANs). However, it's still very challenging for translation tasks that require high-quality, especially at high-resolution and photo-reality. In this paper, we present Discriminative Region Proposal Adversarial Networks (DRPANs) with three components: a generator, a discriminator and a reviser, for high-quality image-to-image translation. To reduce the artifacts and blur problems while translation, based on GAN, we explore a patch discriminator to find and extract the most artificial image patch by sliding the output score map with a window, and map the proposed image patch onto the synthesized fake image as our discriminative region. We then mask the corresponding real image using the discriminative region to obtain a fake-mask real image. For providing constructive revisions to generator, we propose a reviser for GANs to distinguish the real from the fake-mask real for producing realistic details and serve as auxiliaries to generate high-quality translation results. Experiments on a variety of image-to-image translation tasks and datasets validate that our method outperforms state-of-the-art translation methods for producing high-quality translation results in terms of both human perceptual studies and automatic quantitative measures.

##### Abstract (translated by Google)
采用生成敌对​​网络（GAN），图像到图像的翻译已经取得了很大的进展。然而，对于需要高质量的翻译任务，特别是在高分辨率和照片真实的情况下，这仍然是非常具有挑战性的。在本文中，我们提出了三个组件：一个发电机，一个鉴别器和一个修订器，用于高质量的图像到图像转换的鉴别区域建议敌对网络（DRPANs）。为了减少平移过程中的伪像和模糊问题，基于GAN，我们探索了一种斑块鉴别器，通过用窗口滑动输出得分图来寻找和提取最为人造的图像块，并将所提出的图像块映射到合成的伪造图像上我们的区别地区。然后，我们使用判别区域掩盖相应的真实图像，以获得假面具真实图像。为了给生成者提供建设性的修改，我们提出了一个修改GAN的方法，以便从真实的面具真实中区分真实的细节，并作为辅助手段来生成高质量的翻译结果。对各种图像到图像的翻译任务和数据集的实验验证了我们的方法在人类感知研究和自动定量测量方面胜过了用于产生高质量翻译结果的最先进的翻译方法。

##### URL
[https://arxiv.org/abs/1711.09554](https://arxiv.org/abs/1711.09554)

##### PDF
[https://arxiv.org/pdf/1711.09554](https://arxiv.org/pdf/1711.09554)

