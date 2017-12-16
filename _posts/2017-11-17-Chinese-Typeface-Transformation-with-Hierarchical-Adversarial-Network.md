---
layout: post
title: "Chinese Typeface Transformation with Hierarchical Adversarial Network"
date: 2017-11-17 08:05:49
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Face Style_Transfer
author: Jie Chang, Yujun Gu, Ya Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we explore automated typeface generation through image style transfer which has shown great promise in natural image generation. Existing style transfer methods for natural images generally assume that the source and target images share similar high-frequency features. However, this assumption is no longer true in typeface transformation. Inspired by the recent advancement in Generative Adversarial Networks (GANs), we propose a Hierarchical Adversarial Network (HAN) for typeface transformation. The proposed HAN consists of two sub-networks: a transfer network and a hierarchical adversarial discriminator. The transfer network maps characters from one typeface to another. A unique characteristic of typefaces is that the same radicals may have quite different appearances in different characters even under the same typeface. Hence, a stage-decoder is employed by the transfer network to leverage multiple feature layers, aiming to capture both the global and local features. The hierarchical adversarial discriminator implicitly measures data discrepancy between the generated domain and the target domain. To leverage the complementary discriminating capability of different feature layers, a hierarchical structure is proposed for the discriminator. We have experimentally demonstrated that HAN is an effective framework for typeface transfer and characters restoration.

##### Abstract (translated by Google)
在本文中，我们探讨了通过图像风格转换自动生成字体，这在自然图像生成中显示出很大的希望。对于自然图像的现有样式转换方法通常假设源图像和目标图像共享相似的高频特征。但是，这种假设在字体转换中不再是正确的。受到最近在生成敌对网络（GANs）中的进步的启发，我们提出了一个用于字体转换的分层对抗网络（Hierarchical Adversarial Network，HAN）。所提出的HAN由两个子网络组成：传输网络和分层对抗鉴别器。传输网络将字符从一个字体映射到另一个字体。字体的独特之处在于，即使在相同的字体下，相同的字根在不同的字符中也可能具有相当不同的外观。因此，传输网络采用阶段解码器来利用多个特征层，旨在捕获全局特征和局部特征。分层对抗鉴别器隐含地测量生成的域和目标域之间的数据差异。为了利用不同特征层的互补区分能力，提出了一种鉴别器的层次结构。我们已经通过实验证明了HAN是字体转换和字符修复的有效框架。

##### URL
[https://arxiv.org/abs/1711.06448](https://arxiv.org/abs/1711.06448)

##### PDF
[https://arxiv.org/pdf/1711.06448](https://arxiv.org/pdf/1711.06448)

