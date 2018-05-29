---
layout: post
title: "Face hallucination using cascaded super-resolution and identity priors"
date: 2018-05-28 14:25:31
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Face CNN Recognition Face_Recognition
author: Klemen Grm, Simon Dobri&#x161;ek, Walter J. Scheirer, Vitomir &#x160;truc
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we address the problem of hallucinating high-resolution facial images from unaligned low-resolution inputs at high magnification factors. We approach the problem with convolutional neural networks (CNNs) and propose a novel (deep) face hallucination model that incorporates identity priors into the learning procedure. The model consists of two main parts: i) a cascaded super-resolution network that upscales the low-resolution images, and ii) an ensemble of face recognition models that act as identity priors for the super-resolution network during training. Different from competing super-resolution approaches that typically rely on a single model for upscaling (even with large magnification factors), our network uses a cascade of multiple SR models that progressively upscale the low-resolution images using steps of $2\times$. This characteristic allows us to apply supervision signals (target appearances) at different resolutions and incorporate identity constraints at multiple-scales. Our model is able to upscale (very) low-resolution images captured in unconstrained conditions and produce visually convincing results. We rigorously evaluate the proposed model on a large datasets of facial images and report superior performance compared to the state-of-the-art.

##### Abstract (translated by Google)
在本文中，我们解决了在高放大倍数下从未对齐的低分辨率输入幻觉高分辨率人脸图像的问题。我们用卷积神经网络（CNN）来解决这个问题，并提出了一种新颖的（深层）面部幻觉模型，将身份先验融入到学习过程中。该模型由两个主要部分组成：i）级联超分辨率网络，可以放大低分辨率图像; ii）人脸识别模型的集合，在训练过程中充当超分辨率网络的身份先验。与竞争的超分辨率方法不同，即通常依靠单一模型进行放大（即使放大倍数较大），我们的网络使用多个SR模型级联，逐步使用$ 2 \ times $步骤升级低分辨率图像。这个特性使我们能够以不同的分辨率应用监控信号（目标外观），并在多个尺度上纳入身份约束。我们的模型能够在非限制条件下高分辨率（非常）低分辨率的图像，并产生视觉上令人信服的结果。我们在面部图像的大型数据集上严格评估所提出的模型，并报告与最先进的技术相比的优越性能。

##### URL
[http://arxiv.org/abs/1805.10938](http://arxiv.org/abs/1805.10938)

##### PDF
[http://arxiv.org/pdf/1805.10938](http://arxiv.org/pdf/1805.10938)

