---
layout: post
title: "Deep Generative Image Models using a Laplacian Pyramid of Adversarial Networks"
date: 2015-06-18 17:03:54
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN CNN Quantitative
author: Emily Denton, Soumith Chintala, Arthur Szlam, Rob Fergus
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we introduce a generative parametric model capable of producing high quality samples of natural images. Our approach uses a cascade of convolutional networks within a Laplacian pyramid framework to generate images in a coarse-to-fine fashion. At each level of the pyramid, a separate generative convnet model is trained using the Generative Adversarial Nets (GAN) approach (Goodfellow et al.). Samples drawn from our model are of significantly higher quality than alternate approaches. In a quantitative assessment by human evaluators, our CIFAR10 samples were mistaken for real images around 40% of the time, compared to 10% for samples drawn from a GAN baseline model. We also show samples from models trained on the higher resolution images of the LSUN scene dataset.

##### Abstract (translated by Google)
在本文中，我们介绍一个生成参数模型能够生产高质量的自然图像样本。我们的方法使用拉普拉斯金字塔框架内的级联卷积网络以粗到细的方式生成图像。在金字塔的每个级别，使用生成敌对​​网络（GAN）方法（Goodfellow等人）来训练单独的生成性的convnet模型。从我们的模型中抽取的样本比替代方法具有更高的质量。在由人类评估者进行的定量评估中，我们的CIFAR10样本在40％的时间内被误认为真实的图像，而从GAN基线模型中抽取的样本为10％。我们还展示了在LSUN场景数据集的高分辨率图像上训练的模型样本。

##### URL
[https://arxiv.org/abs/1506.05751](https://arxiv.org/abs/1506.05751)

##### PDF
[https://arxiv.org/pdf/1506.05751](https://arxiv.org/pdf/1506.05751)

