---
layout: post
title: "MC-GAN: Multi-conditional Generative Adversarial Network for Image Synthesis"
date: 2018-05-03 05:47:22
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Hyojin Park, Youngjoon Yoo, Nojun Kwak
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we introduce a new method for generating an object image from text attributes on a desired location, when the base image is given. One step further to the existing studies on text-to-image generation mainly focusing on the object appearance, the proposed method aims to generate the object images as well as to preserve the given background information, which is the first attempt in this field. To tackle the problem, we propose a multi-conditional GAN (MC-GAN) which controls both the object and background information jointly. As a core component of MC-GAN, we proposes a synthesis block which disentangles the object and background information in the training stage. This block enables MC-GAN to generate a realistic object image with the desired background by controlling the amount of the background information from the given base image through the foreground information from the text attributes. From the experiments with Caltech-200 bird and Oxford-102 flower datasets, we show that our model is able to generate photo-realistic images with a resolution of 128 x 128. The source code of MC-GAN is available soon.

##### Abstract (translated by Google)
在本文中，我们介绍了一种新的方法，用于在给定基本图像时从所需位置的文本属性生成对象图像。现有关于文本到图像生成的研究主要集中在对象外观方面，现在的研究进一步发展，所提出的方法旨在生成对象图像以及保存给定的背景信息，这是该领域的第一次尝试。为了解决这个问题，我们提出了一个多条件GAN（MC-GAN），它可以共同控制对象和背景信息。作为MC-GAN的核心组件，我们提出了一个综合模块，它在训练阶段解开对象和背景信息。通过控制来自给定基本图像的背景信息量和来自文本属性的前景信息，该块使MC-GAN能够生成具有所需背景的真实对象图像。从Caltech-200鸟类和Oxford-102花朵数据集的实验中，我们发现我们的模型能够生成分辨率为128 x 128的照片般逼真的图像。MC-GAN的源代码即将推出。

##### URL
[http://arxiv.org/abs/1805.01123](http://arxiv.org/abs/1805.01123)

##### PDF
[http://arxiv.org/pdf/1805.01123](http://arxiv.org/pdf/1805.01123)

