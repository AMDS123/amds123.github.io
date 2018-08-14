---
layout: post
title: "Denoising of 3-D Magnetic Resonance Images Using a Residual Encoder-Decoder Wasserstein Generative Adversarial Network"
date: 2018-08-12 13:30:27
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Deep_Learning
author: Maosong Ran, Jinrong Hu, Yang Chen, Hu Chen, Huaiqiang Sun, Jiliu Zhou, Yi Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Structure-preserved denoising of 3-D magnetic resonance images (MRI) is a critical step in the medical image analysis. Over the past years, many algorithms have been proposed with impressive performances. Inspired by the idea of deep learning, in this paper, we introduce a MRI denoising method based on the residual encoder-decoder Wasserstein generative adversarial network (RED-WGAN). Specifically, to explore the structure similarity among neighboring slices, 3-D configuration are utilized as the basic processing unit. Residual autoencoder, combined with deconvolution operations are introduced into the generator network. Furthermore, to alleviate the shortcoming of traditional mean-squared error (MSE) loss function for over-smoothing, the perceptual similarity, which is implemented by calculating the distances in the feature space extracted by a pre-trained VGG-19 network, is incorporated with MSE and adversarial losses to form the new loss function. Extensive experiments are studied to access the performance of the proposed method. The experimental results show that the proposed RED-WGAN achieves superior performance relative to several state-of-art methods in both simulated and clinical data. Especially, our method demonstrates powerful ability in both noise suppression and structure preservation.

##### Abstract (translated by Google)
结构保持的三维磁共振图像（MRI）去噪是医学图像分析中的关键步骤。在过去几年中，已经提出了许多具有令人印象深刻性能的算法。受深度学习理念的启发，在本文中，我们介绍了一种基于残差编码器 - 解码器Wasserstein生成对抗网络（RED-WGAN）的MRI去噪方法。具体地，为了探索相邻切片之间的结构相似性，使用3-D配置作为基本处理单元。将残余自动编码器与解卷积操作结合引入发生器网络。此外，为了减轻过度平滑的传统均方误差（MSE）损失函数的缺点，通过计算由预训练的VGG-19网络提取的特征空间中的距离来实现的感知相似性被合并。与MSE和对抗性损失形成新的损失函数。进行了广泛的实验以获得所提出方法的性能。实验结果表明，相对于模拟和临床数据中的几种最新方法，所提出的RED-WGAN实现了优越的性能。特别是，我们的方法在噪声抑制和结构保存方面表现出强大的能力。

##### URL
[http://arxiv.org/abs/1808.03941](http://arxiv.org/abs/1808.03941)

##### PDF
[http://arxiv.org/pdf/1808.03941](http://arxiv.org/pdf/1808.03941)

