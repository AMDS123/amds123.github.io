---
layout: post
title: "Channel-Recurrent Autoencoding for Image Modeling"
date: 2018-03-11 09:00:51
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial GAN Face Inference
author: Wenling Shang, Kihyuk Sohn, Yuandong Tian
mathjax: true
---

* content
{:toc}

##### Abstract
Despite recent successes in synthesizing faces and bedrooms, existing generative models struggle to capture more complex image types, potentially due to the oversimplification of their latent space constructions. To tackle this issue, building on Variational Autoencoders (VAEs), we integrate recurrent connections across channels to both inference and generation steps, allowing the high-level features to be captured in global-to-local, coarse-to-fine manners. Combined with adversarial loss, our channel-recurrent VAE-GAN (crVAE-GAN) outperforms VAE-GAN in generating a diverse spectrum of high resolution images while maintaining the same level of computational efficacy. Our model produces interpretable and expressive latent representations to benefit downstream tasks such as image completion. Moreover, we propose two novel regularizations, namely the KL objective weighting scheme over time steps and mutual information maximization between transformed latent variables and the outputs, to enhance the training.

##### Abstract (translated by Google)
尽管最近在合成人脸和卧室方面取得了成功，但现有的生成模型很难捕捉更复杂的图像类型，这可能是由于其潜在空间结构过于简单化。为了解决这个问题，我们建立在变分自动编码器（VAEs）的基础上，将跨渠道的经常性连接集成到推理和生成步骤中，从而以全局到局部，从粗到精的方式捕获高级功能。结合对抗性损失，我们的频道复发VAE-GAN（crVAE-GAN）优于VAE-GAN，可在生成各种高分辨率图像的同时保持相同的计算效能水平。我们的模型产生可解释和表达的潜在表示，从而使图像完成等下游任务受益。此外，我们提出了两种新的正则化，即KL时间步长客观赋权方案和变换潜变量与产出之间互信息最大化，以加强培训。

##### URL
[http://arxiv.org/abs/1706.03729](http://arxiv.org/abs/1706.03729)

##### PDF
[http://arxiv.org/pdf/1706.03729](http://arxiv.org/pdf/1706.03729)

