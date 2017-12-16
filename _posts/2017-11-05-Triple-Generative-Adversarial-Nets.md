---
layout: post
title: "Triple Generative Adversarial Nets"
date: 2017-11-05 17:25:11
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Classification
author: Chongxuan Li, Kun Xu, Jun Zhu, Bo Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Generative Adversarial Nets (GANs) have shown promise in image generation and semi-supervised learning (SSL). However, existing GANs in SSL have two problems: (1) the generator and the discriminator (i.e. the classifier) may not be optimal at the same time; and (2) the generator cannot control the semantics of the generated samples. The problems essentially arise from the two-player formulation, where a single discriminator shares incompatible roles of identifying fake samples and predicting labels and it only estimates the data without considering the labels. To address the problems, we present triple generative adversarial net (Triple-GAN), which consists of three players---a generator, a discriminator and a classifier. The generator and the classifier characterize the conditional distributions between images and labels, and the discriminator solely focuses on identifying fake image-label pairs. We design compatible utilities to ensure that the distributions characterized by the classifier and the generator both converge to the data distribution. Our results on various datasets demonstrate that Triple-GAN as a unified model can simultaneously (1) achieve the state-of-the-art classification results among deep generative models, and (2) disentangle the classes and styles of the input and transfer smoothly in the data space via interpolation in the latent space class-conditionally.

##### Abstract (translated by Google)
生成敌对网络（GAN）已经在图像生成和半监督学习（SSL）中显示出前景。然而，现有的SSL中的GAN有两个问题：（1）发生器和鉴别器（即分类器）可能不是同时最佳的; （2）生成器不能控制生成的样本的语义。这个问题基本上来自于双人公式，其中单个鉴别器共享识别假样本和预测标签的不兼容的作用，并且它仅估计数据而不考虑标签。为了解决这个问题，我们提出三重生成对抗网（Triple-GAN），它由三个参与者组成 - 一个生成器，一个鉴别器和一个分类器。生成器和分类器表征图像和标签之间的条件分布，鉴别器仅着重于识别伪造的图像 - 标签对。我们设计兼容的应用程序，以确保分类器和发生器所表征的分布都收敛于数据分布。我们在各种数据集上的结果表明，Triple-GAN作为一个统一的模型可以同时（1）实现深度生成模型中最先进的分类结果，（2）分解输入的类和样式，在数据空间中通过潜在空间类的插值条件。

##### URL
[https://arxiv.org/abs/1703.02291](https://arxiv.org/abs/1703.02291)

##### PDF
[https://arxiv.org/pdf/1703.02291](https://arxiv.org/pdf/1703.02291)

