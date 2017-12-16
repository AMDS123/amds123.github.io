---
layout: post
title: "Deep Identity-aware Transfer of Facial Attributes"
date: 2016-10-18 12:56:47
categories: arXiv_CV
tags: arXiv_CV GAN Face CNN
author: Mu Li, Wangmeng Zuo, David Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a Deep convolutional network model for Identity-Aware Transfer (DIAT) of facial attributes. Given the source input image and the reference attribute, DIAT aims to generate a facial image (i.e., target image) that not only owns the reference attribute but also keep the same or similar identity to the input image. We develop a two-stage scheme to transfer the input image to each reference attribute label. A feed-forward transform network is first trained by combining perceptual identity-aware loss and GAN-based attribute loss, and a face enhancement network is then introduced to improve the visual quality. We further define perceptual identity loss on the convolutional feature maps of the attribute discriminator, resulting in a DIAT-A model. Our DIAT and DIAT-A models can provide a unified solution for several representative facial attribute transfer tasks such as expression transfer, accessory removal, age progression, and gender transfer. The experimental results validate their effectiveness. Even for some identity-related attribute (e.g., gender), our DIAT-A can obtain visually impressive results by changing the attribute while retaining most identity features of the source image.

##### Abstract (translated by Google)
本文提出了面部属性身份识别转移（DIAT）的深度卷积网络模型。给定源输入图像和参考属性，DIAT旨在生成不仅拥有参考属性而且与输入图像保持相同或相似的身份的面部图像（即目标图像）。我们开发了一个两阶段的方案来将输入图像转移到每个参考属性标签。前馈变换网络首先结合感知身份感知损失和基于GAN的属性损失进行训练，然后引入人脸增强网络来提高视觉质量。我们进一步定义属性鉴别器的卷积特征映射上的感知身份损失，导致DIAT-A模型。我们的DIAT和DIAT-A模型可以为几个有代表性的面部属性转移任务提供统一的解决方案，如表达转移，附件移除，年龄进展和性别转移。实验结果验证了它们的有效性。即使对于一些与身份有关的属性（例如性别），我们的DIAT-A也可以通过改变属性来获得视觉上令人印象深刻的结果，同时保留源图像的大部分身份特征。

##### URL
[https://arxiv.org/abs/1610.05586](https://arxiv.org/abs/1610.05586)

##### PDF
[https://arxiv.org/pdf/1610.05586](https://arxiv.org/pdf/1610.05586)

