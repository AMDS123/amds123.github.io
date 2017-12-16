---
layout: post
title: "Unsupervised Holistic Image Generation from Key Local Patches"
date: 2017-04-03 00:38:12
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Donghoon Lee, Sangdoo Yun, Sungjoon Choi, Hwiyeon Yoo, Ming-Hsuan Yang, Songhwai Oh
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a new problem of generating an image based on a small number of key local patches without any geometric prior. In this work, key local patches are defined as informative regions of the target object or scene. This is a challenging problem since it requires generating realistic images and predicting locations of parts at the same time. We construct adversarial networks to tackle this problem. A generator network generates a fake image as well as a mask based on the encoder-decoder framework. On the other hand, a discriminator network aims to detect fake images. The network is trained with three losses to consider spatial, appearance, and adversarial information. The spatial loss determines whether the locations of predicted parts are correct. Input patches are restored in the output image without much modification due to the appearance loss. The adversarial loss ensures output images are realistic. The proposed network is trained without supervisory signals since no labels of key parts are required. Experimental results on six datasets demonstrate that the proposed algorithm performs favorably on challenging objects and scenes.

##### Abstract (translated by Google)
我们引入了一个新的问题，基于少量的关键本地补丁生成图像没有任何几何先验。在这项工作中，关键的本地补丁被定义为目标对象或场景的信息区域。这是一个具有挑战性的问题，因为它需要生成逼真的图像并同时预测零件的位置。我们构建对抗性网络来解决这个问题。生成器网络根据编码器 - 解码器框架生成假图像和掩码。另一方面，鉴别器网络旨在检测假图像。该网络受到三次损失的培训，以考虑空间，外观和敌对信息。空间损失决定了预测部位的位置是否正确。由于出现丢失，输入图像在输出图像中被恢复而没有太多修改。敌对损失确保输出图像是现实的。所建议的网络在没有监控信号的情况下进行训练，因为不需要关键部件的标签。在六个数据集上的实验结果表明，所提出的算法在有挑战性的对象和场景中表现良好。

##### URL
[https://arxiv.org/abs/1703.10730](https://arxiv.org/abs/1703.10730)

##### PDF
[https://arxiv.org/pdf/1703.10730](https://arxiv.org/pdf/1703.10730)

