---
layout: post
title: "High-resolution medical image synthesis using progressively grown generative adversarial networks"
date: 2018-05-08 16:25:13
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation GAN CNN Classification
author: Andrew Beers, James Brown, Ken Chang, J. Peter Campbell, Susan Ostmo, Michael F. Chiang, Jayashree Kalpathy-Cramer
mathjax: true
---

* content
{:toc}

##### Abstract
Generative adversarial networks (GANs) are a class of unsupervised machine learning algorithms that can produce realistic images from randomly-sampled vectors in a multi-dimensional space. Until recently, it was not possible to generate realistic high-resolution images using GANs, which has limited their applicability to medical images that contain biomarkers only detectable at native resolution. Progressive growing of GANs is an approach wherein an image generator is trained to initially synthesize low resolution synthetic images (8x8 pixels), which are then fed to a discriminator that distinguishes these synthetic images from real downsampled images. Additional convolutional layers are then iteratively introduced to produce images at twice the previous resolution until the desired resolution is reached. In this work, we demonstrate that this approach can produce realistic medical images in two different domains; fundus photographs exhibiting vascular pathology associated with retinopathy of prematurity (ROP), and multi-modal magnetic resonance images of glioma. We also show that fine-grained details associated with pathology, such as retinal vessels or tumor heterogeneity, can be preserved and enhanced by including segmentation maps as additional channels. We envisage several applications of the approach, including image augmentation and unsupervised classification of pathology.

##### Abstract (translated by Google)
生成对抗网络（GAN）是一类无监督机器学习算法，可以从多维空间中的随机采样矢量生成逼真的图像。直到最近，使用GAN生成逼真的高分辨率图像是不可能的，这限制了它们适用于仅包含天然分辨率下可检测的生物标记的医学图像。 GAN的逐步增长是一种方法，其中图像生成器被训练以初始合成低分辨率合成图像（8×8像素），然后将其馈送到区分这些合成图像与真实下采样图像的鉴别器。然后迭代地引入额外的卷积层以产生两倍于先前分辨率的图像，直到达到期望的分辨率。在这项工作中，我们证明这种方法可以在两个不同的领域产生逼真的医学图像;显示与早产儿视网膜病（ROP）相关的血管病理学的眼底照片，以及胶质瘤的多模态磁共振图像。我们还显示，通过将分割图作为附加通道，可以保留和增强与病理相关的细节细节，例如视网膜血管或肿瘤异质性。我们设想了该方法的几种应用，包括图像增强和病理学的无监督分类。

##### URL
[https://arxiv.org/abs/1805.03144](https://arxiv.org/abs/1805.03144)

##### PDF
[https://arxiv.org/pdf/1805.03144](https://arxiv.org/pdf/1805.03144)

