---
layout: post
title: "Adversarial Training of Variational Auto-encoders for High Fidelity Image Generation"
date: 2018-04-27 02:19:35
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Salman H. Khan, Munawar Hayat, Nick Barnes
mathjax: true
---

* content
{:toc}

##### Abstract
Variational auto-encoders (VAEs) provide an attractive solution to image generation problem. However, they tend to produce blurred and over-smoothed images due to their dependence on pixel-wise reconstruction loss. This paper introduces a new approach to alleviate this problem in the VAE based generative models. Our model simultaneously learns to match the data, reconstruction loss and the latent distributions of real and fake images to improve the quality of generated samples. To compute the loss distributions, we introduce an auto-encoder based discriminator model which allows an adversarial learning procedure. The discriminator in our model also provides perceptual guidance to the VAE by matching the learned similarity metric of the real and fake samples in the latent space. To stabilize the overall training process, our model uses an error feedback approach to maintain the equilibrium between competing networks in the model. Our experiments show that the generated samples from our proposed model exhibit a diverse set of attributes and facial expressions and scale up to high-resolution images very well.

##### Abstract (translated by Google)
变分自动编码器（VAEs）为图像生成问题提供了一个有吸引力的解决方案。然而，由于它们依赖于像素重建损失，它们往往会产生模糊和过平滑的图像。本文介绍了一种新的方法来缓解基于VAE的生成模型中的这个问题。我们的模型同时学习匹配数据，重建损失和真实和假图像的潜在分布，以提高生成样本的质量。为了计算损失分布，我们引入基于自动编码器的鉴别器模型，其允许敌对学习过程。我们模型中的鉴别器还通过匹配潜在空间中真实和假样本的学习相似性度量来为VAE提供感知指导。为了稳定整个培训过程，我们的模型使用错误反馈方法来维持模型中竞争网络之间的平衡。我们的实验表明，从我们提出的模型生成的样本表现出多种属性和面部表情，并且可以很好地放大到高分辨率图像。

##### URL
[https://arxiv.org/abs/1804.10323](https://arxiv.org/abs/1804.10323)

##### PDF
[https://arxiv.org/pdf/1804.10323](https://arxiv.org/pdf/1804.10323)

