---
layout: post
title: "MEGAN: Mixture of Experts of Generative Adversarial Networks for Multimodal Image Generation"
date: 2018-05-07 12:49:04
categories: arXiv_CV
tags: arXiv_CV Salient Adversarial GAN Image_Generation
author: David Keetae Park, Seungjoo Yoo, Hyojin Bahng, Jaegul Choo, Noseong Park
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, generative adversarial networks (GANs) have shown promising performance in generating realistic images. However, they often struggle in learning complex underlying modalities in a given dataset, resulting in poor-quality generated images. To mitigate this problem, we present a novel approach called mixture of experts GAN (MEGAN), an ensemble approach of multiple generator networks. Each generator network in MEGAN specializes in generating images with a particular subset of modalities, e.g., an image class. Instead of incorporating a separate step of handcrafted clustering of multiple modalities, our proposed model is trained through an end-to-end learning of multiple generators via gating networks, which is responsible for choosing the appropriate generator network for a given condition. We adopt the categorical reparameterization trick for a categorical decision to be made in selecting a generator while maintaining the flow of the gradients. We demonstrate that individual generators learn different and salient subparts of the data and achieve a multiscale structural similarity (MS-SSIM) score of 0.2470 for CelebA and a competitive unsupervised inception score of 8.33 in CIFAR-10.

##### Abstract (translated by Google)
最近，生成敌对网络（GAN）在生成逼真的图像方面表现出有前途的性能。但是，他们经常在学习给定数据集中复杂的基础模态方面遇到困难，导致生成质量差的图像。为了缓解这个问题，我们提出了一种称为混合专家GAN（MEGAN）的新方法，这是一种多发电机网络的集成方法。 MEGAN中的每个生成器网络专门用于生成具有特定模态子集（例如图像类别）的图像。我们提出的模型是通过端对端学习多个发电机，通过选通网络进行训练，而不是单独采用多模式的手工分群的方式，这种网络负责为给定条件选择合适的发电机网络。我们采用分类重新参数化技巧做出选择发电机的分类决策，同时保持梯度的流动。我们证明个体生成者学习不同的和显着的数据子部分，并实现CelebA的多尺度结构相似性（MS-SSIM）得分为0.2470，在CIFAR-10中得到8.33的竞争无监督初始得分。

##### URL
[http://arxiv.org/abs/1805.02481](http://arxiv.org/abs/1805.02481)

##### PDF
[http://arxiv.org/pdf/1805.02481](http://arxiv.org/pdf/1805.02481)

