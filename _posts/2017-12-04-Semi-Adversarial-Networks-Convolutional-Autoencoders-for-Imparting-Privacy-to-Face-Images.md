---
layout: post
title: "Semi-Adversarial Networks: Convolutional Autoencoders for Imparting Privacy to Face Images"
date: 2017-12-04 16:19:05
categories: arXiv_CV
tags: arXiv_CV Adversarial CNN Recognition
author: Vahid Mirjalili, Sebastian Raschka, Anoop Namboodiri, Arun Ross
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we design and evaluate a convolutional autoencoder that perturbs an input face image to impart privacy to a subject. Specifically, the proposed autoencoder transforms an input face image such that the transformed image can be successfully used for face recognition but not for gender classification. In order to train this autoencoder, we propose a novel training scheme, referred to as semi-adversarial training in this work. The training is facilitated by attaching a semi-adversarial module consisting of a pseudo gender classifier and a pseudo face matcher to the autoencoder. The objective function utilized for training this network has three terms: one to ensure that the perturbed image is a realistic face image; another to ensure that the gender attributes of the face are confounded; and a third to ensure that biometric recognition performance due to the perturbed image is not impacted. Extensive experiments confirm the efficacy of the proposed architecture in extending gender privacy to face images.

##### Abstract (translated by Google)
在本文中，我们设计和评估卷积自动编码器扰乱输入人脸图像，以保护主体的隐私。具体而言，所提出的自编码器对输入人脸图像进行变换，使得变换后的图像可以成功用于人脸识别，但不能用于性别分类。为了训练这个自编码器，我们提出了一个新的训练方案，在本文中被称为半对抗训练。通过将由伪性别分类器和伪面部匹配器组成的半对抗模块附加到自动编码器来促进训练。用于训练这个网络的目标函数有三个术语：一个是确保被扰动的图像是真实的人脸图像;另一个是确保面部的性别属性混淆;第三，确保由于扰动图像引起的生物识别性能不受影响。广泛的实验证实了所提出的架构在将性别隐私扩展到人脸图像方面的功效。

##### URL
[http://arxiv.org/abs/1712.00321](http://arxiv.org/abs/1712.00321)

##### PDF
[http://arxiv.org/pdf/1712.00321](http://arxiv.org/pdf/1712.00321)

