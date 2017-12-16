---
layout: post
title: "Learning Diverse Image Colorization"
date: 2017-04-27 14:34:28
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Embedding
author: Aditya Deshpande, Jiajun Lu, Mao-Chuang Yeh, Min Jin Chong, David Forsyth
mathjax: true
---

* content
{:toc}

##### Abstract
Colorization is an ambiguous problem, with multiple viable colorizations for a single grey-level image. However, previous methods only produce the single most probable colorization. Our goal is to model the diversity intrinsic to the problem of colorization and produce multiple colorizations that display long-scale spatial co-ordination. We learn a low dimensional embedding of color fields using a variational autoencoder (VAE). We construct loss terms for the VAE decoder that avoid blurry outputs and take into account the uneven distribution of pixel colors. Finally, we build a conditional model for the multi-modal distribution between grey-level image and the color field embeddings. Samples from this conditional model result in diverse colorization. We demonstrate that our method obtains better diverse colorizations than a standard conditional variational autoencoder (CVAE) model, as well as a recently proposed conditional generative adversarial network (cGAN).

##### Abstract (translated by Google)
着色是一个模棱两可的问题，对于单个灰度级图像具有多个可行的着色。但是，以前的方法只能产生最可能的着色。我们的目标是模拟色彩问题所固有的多样性，并产生显示长期空间协调的多种色彩。我们使用变分自动编码器（VAE）学习颜色场的低维嵌入。我们构造VAE解码器的损失项，避免模糊输出，并考虑像素颜色的不均匀分布。最后，我们建立了灰度图像与色域嵌入之间多模态分布的条件模型。来自这个条件模型的样本会导致不同的着色。我们证明，我们的方法比标准的条件变分自动编码器（CVAE）模型以及最近提出的条件生成对抗网络（cGAN）获得更好的多样化着色。

##### URL
[https://arxiv.org/abs/1612.01958](https://arxiv.org/abs/1612.01958)

##### PDF
[https://arxiv.org/pdf/1612.01958](https://arxiv.org/pdf/1612.01958)

