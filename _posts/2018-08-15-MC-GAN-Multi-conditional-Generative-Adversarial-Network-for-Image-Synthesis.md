---
layout: post
title: "MC-GAN: Multi-conditional Generative Adversarial Network for Image Synthesis"
date: 2018-08-15 08:35:43
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Hyojin Park, YoungJoon Yoo, Nojun Kwak
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we introduce a new method for generating an object image from text attributes on a desired location, when the base image is given. One step further to the existing studies on text-to-image generation mainly focusing on the object's appearance, the proposed method aims to generate an object image preserving the given background information, which is the first attempt in this field. To tackle the problem, we propose a multi-conditional GAN (MC-GAN) which controls both the object and background information jointly. As a core component of MC-GAN, we propose a synthesis block which disentangles the object and background information in the training stage. This block enables MC-GAN to generate a realistic object image with the desired background by controlling the amount of the background information from the given base image using the foreground information from the text attributes. From the experiments with Caltech-200 bird and Oxford-102 flower datasets, we show that our model is able to generate photo-realistic images with a resolution of 128 x 128. The source code of MC-GAN is released.

##### Abstract (translated by Google)
在本文中，我们介绍了一种新方法，用于在给定基本图像时从所需位置的文本属性生成对象图像。进一步研究文本到图像生成的现有研究主要集中在对象的外观上，所提出的方法旨在生成保留给定背景信息的对象图像，这是该领域的第一次尝试。为了解决这个问题，我们提出了一种多条件GAN（MC-GAN），它可以共同控制对象和背景信息。作为MC-GAN的核心组件，我们提出了一个合成块，它在训练阶段解开对象和背景信息。通过使用来自文本属性的前景信息控制来自给定基本图像的背景信息量，该块使MC-GAN能够生成具有所需背景的真实对象图像。通过Caltech-200 bird和Oxford-102花卉数据集的实验，我们证明了我们的模型能够生成分辨率为128 x 128的照片般逼真的图像.MCD-GAN的源代码已经发布。

##### URL
[http://arxiv.org/abs/1805.01123](http://arxiv.org/abs/1805.01123)

##### PDF
[http://arxiv.org/pdf/1805.01123](http://arxiv.org/pdf/1805.01123)

