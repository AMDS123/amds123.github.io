---
layout: post
title: "Supervised Adversarial Networks for Image Saliency Detection"
date: 2017-04-26 01:37:03
categories: arXiv_CV
tags: arXiv_CV Salient Adversarial GAN CNN Detection
author: Hengyue Pan, Hui Jiang
mathjax: true
---

* content
{:toc}

##### Abstract
In the past few years, Generative Adversarial Network (GAN) became a prevalent research topic. By defining two convolutional neural networks (G-Network and D-Network) and introducing an adversarial procedure between them during the training process, GAN has ability to generate good quality images that look like natural images from a random vector. Besides image generation, GAN may have potential to deal with wide range of real world problems. In this paper, we follow the basic idea of GAN and propose a novel model for image saliency detection, which is called Supervised Adversarial Networks (SAN). Specifically, SAN also trains two models simultaneously: the G-Network takes natural images as inputs and generates corresponding saliency maps (synthetic saliency maps), and the D-Network is trained to determine whether one sample is a synthetic saliency map or ground-truth saliency map. However, different from GAN, the proposed method uses fully supervised learning to learn both G-Network and D-Network by applying class labels of the training set. Moreover, a novel kind of layer call conv-comparison layer is introduced into the D-Network to further improve the saliency performance by forcing the high-level feature of synthetic saliency maps and ground-truthes as similar as possible. Experimental results on Pascal VOC 2012 database show that the SAN model can generate high quality saliency maps for many complicate natural images.

##### Abstract (translated by Google)
在过去的几年中，生成对抗网络（GAN）成为一个流行的研究课题。通过定义两个卷积神经网络（G网络和D网络），并在训练过程中引入一个对抗程序，GAN有能力从随机向量生成看起来像自然图像的高质量图像。除了图像生成之外，GAN可能有处理广泛的现实世界问题的潜力。在本文中，我们遵循GAN的基本思想，提出了一种新的图像显着性检测模型，称为监督对抗网络（SAN）。具体而言，SAN还同时训练两个模型：G网络将自然图像作为输入并生成相应的显着图（合成显着图），并且D网络被训练以确定一个样本是合成显着图还是地面实况显着图。但与GAN不同的是，该方法采用全监督学习，通过训练集的类标签来学习G网和D网。此外，在D网中引入了一种新型的层次呼叫比较层，通过强调综合显着图和地面站的高层特征尽可能相似，进一步提高了显着性。 Pascal VOC 2012数据库的实验结果表明，SAN模型可以为许多复杂的自然图像生成高质量的显着图。

##### URL
[https://arxiv.org/abs/1704.07242](https://arxiv.org/abs/1704.07242)

##### PDF
[https://arxiv.org/pdf/1704.07242](https://arxiv.org/pdf/1704.07242)

