---
layout: post
title: "A+D-Net: Shadow Detection with Adversarial Shadow Attenuation"
date: 2017-12-04 21:14:32
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Detection
author: Hieu Le, Tomas F. Yago Vicente, Vu Nguyen, Minh Hoai, Dimitris Samaras
mathjax: true
---

* content
{:toc}

##### Abstract
Single image shadow detection is a very challenging problem because of the limited amount of information available in one image, as well as the scarcity of annotated training data. In this work, we propose a novel adversarial training based framework that yields a high performance shadow detection network (D-Net). D-Net is trained together with an Attenuator network (A-Net) that generates adversarial training examples. A-Net performs shadow attenuation in original training images constrained by a simplified physical shadow model and focused on fooling D-Net's shadow predictions. Hence, it is effectively augmenting the training data for D-Net with hard to predict cases. Experimental results on the most challenging shadow detection benchmark show that our method outperforms the state-of-the-art with a 38% error reduction, measured in terms of balanced error rate (BER). Our proposed shadow detector also obtains state-of-the-art results on a cross-dataset task testing on UCF with a 14% error reduction. Furthermore, the proposed method can perform accurate close to real-time shadow detection at a rate of 13 frames per second.

##### Abstract (translated by Google)
单图像阴影检测是一个非常具有挑战性的问题，因为一幅图像中可用的信息量有限，以及注释训练数据的稀缺性。在这项工作中，我们提出了一个新的基于对抗训练的框架，产生一个高性能的阴影检测网络（D-Net）。 D-Net与衰减器网络（A-Net）一起训练，产生敌对训练的例子。 A-Net在由简化的物理阴影模型约束的原始训练图像中执行阴影衰减，并且集中于愚弄D-Net的阴影预测。因此，它有效地增加了D-Net的训练数据，难以预测病例。在最具挑战性的阴影检测基准测试的实验结果表明，我们的方法比平衡错误率（BER）衡量的38％的错误减少性能优于最先进的技术。我们提出的阴影检测器也获得了UCF上交叉数据集任务测试的最新结果，误差减少了14％。此外，所提出的方法可以以每秒13帧的速率执行准确接近实时的阴影检测。

##### URL
[http://arxiv.org/abs/1712.01361](http://arxiv.org/abs/1712.01361)

