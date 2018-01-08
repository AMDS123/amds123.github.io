---
layout: post
title: "Learning Implicit Brain MRI Manifolds with Deep Learning"
date: 2018-01-05 17:24:37
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Deep_Learning Quantitative Relation
author: Camilo Bermudez, Andrew J. Plassard, Larry T. Davis, Allen T. Newton, Susan M Resnick, Bennett A. Landman
mathjax: true
---

* content
{:toc}

##### Abstract
An important task in image processing and neuroimaging is to extract quantitative information from the acquired images in order to make observations about the presence of disease or markers of development in populations. Having a lowdimensional manifold of an image allows for easier statistical comparisons between groups and the synthesis of group representatives. Previous studies have sought to identify the best mapping of brain MRI to a low-dimensional manifold, but have been limited by assumptions of explicit similarity measures. In this work, we use deep learning techniques to investigate implicit manifolds of normal brains and generate new, high-quality images. We explore implicit manifolds by addressing the problems of image synthesis and image denoising as important tools in manifold learning. First, we propose the unsupervised synthesis of T1-weighted brain MRI using a Generative Adversarial Network (GAN) by learning from 528 examples of 2D axial slices of brain MRI. Synthesized images were first shown to be unique by performing a crosscorrelation with the training set. Real and synthesized images were then assessed in a blinded manner by two imaging experts providing an image quality score of 1-5. The quality score of the synthetic image showed substantial overlap with that of the real images. Moreover, we use an autoencoder with skip connections for image denoising, showing that the proposed method results in higher PSNR than FSL SUSAN after denoising. This work shows the power of artificial networks to synthesize realistic imaging data, which can be used to improve image processing techniques and provide a quantitative framework to structural changes in the brain.

##### Abstract (translated by Google)
图像处理和神经影像学的一个重要任务是从获取的图像中提取定量信息，以便观察疾病的存在或人群发育的标记。有一个图像的低维流形允许更容易统计比较组和组代表的合成。以前的研究试图找出脑MRI的最佳映射到低维流形，但受限于显式相似性测量的假设。在这项工作中，我们使用深度学习技术来调查正常大脑的隐式流形并生成新的高质量图像。通过解决图像合成和图像去噪作为流形学习的重要工具，我们探索隐式流形。首先，我们通过从脑部MRI的二维轴向切片的528个示例中学习，使用生成对抗网络（GAN）提出了无监督的T1加权脑MRI的合成。首先通过与训练集执行互相关来合成图像是唯一的。然后由两名成像专家以盲视的方式评估真实和合成的图像，提供1-5的图像质量分数。合成图像的质量分数与真实图像的质量分数显着重叠。此外，我们使用一个带有跳转连接的自编码器进行图像去噪，表明所提出的方法在去噪之后比FSL SUSAN产生更高的PSNR。这项工作显示人造网络合成逼真的成像数据的力量，可以用来改善图像处理技术，并提供一个定量的框架结构变化的大脑。

##### URL
[http://arxiv.org/abs/1801.01847](http://arxiv.org/abs/1801.01847)

##### PDF
[http://arxiv.org/pdf/1801.01847](http://arxiv.org/pdf/1801.01847)

