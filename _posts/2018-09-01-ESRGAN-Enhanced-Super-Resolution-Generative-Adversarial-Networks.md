---
layout: post
title: "ESRGAN: Enhanced Super-Resolution Generative Adversarial Networks"
date: 2018-09-01 16:21:03
categories: arXiv_CV
tags: arXiv_CV Adversarial Super_Resolution GAN
author: Xintao Wang, Ke Yu, Shixiang Wu, Jinjin Gu, Yihao Liu, Chao Dong, Chen Change Loy, Yu Qiao, Xiaoou Tang
mathjax: true
---

* content
{:toc}

##### Abstract
The Super-Resolution Generative Adversarial Network (SRGAN) is a seminal work that is capable of generating realistic textures during single image super-resolution. However, the hallucinated details are often accompanied with unpleasant artifacts. To further enhance the visual quality, we thoroughly study three key components of SRGAN - network architecture, adversarial loss and perceptual loss, and improve each of them to derive an Enhanced SRGAN (ESRGAN). In particular, we introduce the Residual-in-Residual Dense Block (RRDB) without batch normalization as the basic network building unit. Moreover, we borrow the idea from relativistic GAN to let the discriminator predict relative realness instead of the absolute value. Finally, we improve the perceptual loss by using the features before activation, which could provide stronger supervision for brightness consistency and texture recovery. Benefiting from these improvements, the proposed ESRGAN achieves consistently better visual quality with more realistic and natural textures than SRGAN and won the first place in the PIRM2018-SR Challenge. The code is available at https://github.com/xinntao/ESRGAN .

##### Abstract (translated by Google)
超分辨率生成对抗网络（SRGAN）是一项开创性的工作，能够在单一图像超分辨率期间生成逼真的纹理。然而，幻觉细节通常伴随着令人不快的伪影。为了进一步提高视觉质量，我们彻底研究了SRGAN的三个关键组成部分 - 网络架构，对抗性损失和感知损失，并改进每一部分以推导出增强型SRGAN（ESRGAN）。特别是，我们在没有批量标准化的情况下引入剩余残差密集块（RRDB）作为基本网络构建单元。此外，我们借用相对论GAN的思想来让鉴别器预测相对真实性而不是绝对值。最后，我们通过使用激活前的特征来改善感知损失，这可以提供更强的亮度一致性和纹理恢复的监督。得益于这些改进，所提出的ESRGAN实现了始终如一的更好的视觉质量，具有比SRGAN更逼真和自然的纹理，并在PIRM2018-SR挑战赛中获得第一名。该代码可在https://github.com/xinntao/ESRGAN获得。

##### URL
[http://arxiv.org/abs/1809.00219](http://arxiv.org/abs/1809.00219)

##### PDF
[http://arxiv.org/pdf/1809.00219](http://arxiv.org/pdf/1809.00219)

