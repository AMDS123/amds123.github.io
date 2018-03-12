---
layout: post
title: "Cross-View Image Synthesis using Conditional GANs"
date: 2018-03-09 06:53:36
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation GAN Semantic_Segmentation Quantitative
author: Krishna Regmi, Ali Borji
mathjax: true
---

* content
{:toc}

##### Abstract
Learning to generate natural scenes has always been a challenging task in computer vision. It is even more painstaking when the generation is conditioned on images with drastically different views. This is mainly because understanding, corresponding, and transforming appearance and semantic information across views is not trivial. In this paper, we attempt to solve the novel problem of cross-view image synthesis, aerial to street view and vice versa, using conditional generative adversarial networks (cGAN). Two new architectures called Crossview Fork (XFork) and Crossview Sequential (X-Seq) are proposed to generate scenes with resolutions of 64x64 and 256x256 pixels. X-Fork architecture has a single discriminator and a single generator. The generator hallucinates both the image and its semantic segmentation in the target view. X-Seq architecture utilizes two cGANs. The first one generates the target image which is subsequently fed to the second cGAN for generating its corresponding semantic segmentation map. The feedback from the second cGAN helps the first cGAN generate sharper images. Both of our proposed architectures learn to generate natural images as well as their semantic segmentation maps. Extensive qualitative and quantitative evaluations support the effectiveness of our frameworks, compared to two state of the art methods, for natural scene generation across drastically different views.

##### Abstract (translated by Google)
学习生成自然场景在计算机视觉领域一直是一项具有挑战性的任务。当一代人受到截然不同意见的影响时，更加痛苦。这主要是因为在视图之间理解，对应和转换外观和语义信息并非微不足道。在本文中，我们尝试使用条件生成对抗网络（cGAN）来解决交叉视图图像合成的新问题，从空中到街景，反之亦然。提出了两种称为Crossview Fork（XFork）和Crossview Sequential（X-Seq）的新体系结构，用于生成分辨率为64x64和256x256像素的场景。 X叉架构有一个鉴别器和一个单一的发生器。生成器在目标视图中幻觉图像及其语义分割。 X-Seq架构使用两个cGAN。第一个生成随后被馈送到第二cGAN的目标图像，以生成其对应的语义分割图。来自第二个cGAN的反馈有助于第一个cGAN生成更清晰的图像。我们提出的两种架构都可以学习生成自然图像以及语义分割图。与两种最先进的方法相比，广泛的定性和定量评估支持我们的框架的有效性，以便在截然不同的视图中生成自然场景。

##### URL
[http://arxiv.org/abs/1803.03396](http://arxiv.org/abs/1803.03396)

##### PDF
[http://arxiv.org/pdf/1803.03396](http://arxiv.org/pdf/1803.03396)

