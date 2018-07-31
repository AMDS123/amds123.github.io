---
layout: post
title: "A+D Net: Training a Shadow Detector with Adversarial Shadow Attenuation"
date: 2018-07-27 19:44:31
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection GAN Prediction Detection
author: Hieu Le, Tomas F. Yago Vicente, Vu Nguyen, Minh Hoai, Dimitris Samaras
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel GAN-based framework for detecting shadows in images, in which a shadow detection network (D-Net) is trained together with a shadow attenuation network (A-Net) that generates adversarial training examples. The A-Net modifies the original training images constrained by a simplified physical shadow model and is focused on fooling the D-Net's shadow predictions. Hence, it is effectively augmenting the training data for D-Net with hard-to-predict cases. The D-Net is trained to predict shadows in both original images and generated images from the A-Net. Our experimental results show that the additional training data from A-Net significantly improves the shadow detection accuracy of D-Net. Our method outperforms the state-of-the-art methods on the most challenging shadow detection benchmark (SBU) and also obtains state-of-the-art results on a cross-dataset task, testing on UCF. Furthermore, the proposed method achieves accurate real-time shadow detection at 45 frames per second.

##### Abstract (translated by Google)
我们提出了一种新的基于GAN的框架，用于检测图像中的阴影，其中阴影检测网络（D-Net）与阴影衰减网络（A-Net）一起训练，生成对抗性训练示例。 A-Net修改了由简化的物理阴影模型约束的原始训练图像，并专注于欺骗D-Net的阴影预测。因此，它有效地增加了具有难以预测的案例的D-Net的训练数据。训练D-Net以预测原始图像中的阴影和来自A-Net的生成图像。我们的实验结果表明，来自A-Net的额外训练数据显着提高了D-Net的阴影检测精度。我们的方法在最具挑战性的阴影检测基准（SBU）上优于最先进的方法，并且还在跨数据集任务上获得最先进的结果，在UCF上进行测试。此外，所提出的方法以每秒45帧的速度实现精确的实时阴影检测。

##### URL
[http://arxiv.org/abs/1712.01361](http://arxiv.org/abs/1712.01361)

##### PDF
[http://arxiv.org/pdf/1712.01361](http://arxiv.org/pdf/1712.01361)

