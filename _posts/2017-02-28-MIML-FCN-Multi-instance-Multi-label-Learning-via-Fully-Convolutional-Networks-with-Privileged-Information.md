---
layout: post
title: "MIML-FCN+: Multi-instance Multi-label Learning via Fully Convolutional Networks with Privileged Information"
date: 2017-02-28 07:54:22
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption CNN Deep_Learning Relation Recognition
author: Hao Yang, Joey Tianyi Zhou, Jianfei Cai, Yew Soon Ong
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-instance multi-label (MIML) learning has many interesting applications in computer visions, including multi-object recognition and automatic image tagging. In these applications, additional information such as bounding-boxes, image captions and descriptions is often available during training phrase, which is referred as privileged information (PI). However, as existing works on learning using PI only consider instance-level PI (privileged instances), they fail to make use of bag-level PI (privileged bags) available in MIML learning. Therefore, in this paper, we propose a two-stream fully convolutional network, named MIML-FCN+, unified by a novel PI loss to solve the problem of MIML learning with privileged bags. Compared to the previous works on PI, the proposed MIML-FCN+ utilizes the readily available privileged bags, instead of hard-to-obtain privileged instances, making the system more general and practical in real world applications. As the proposed PI loss is convex and SGD compatible and the framework itself is a fully convolutional network, MIML-FCN+ can be easily integrated with state of-the-art deep learning networks. Moreover, the flexibility of convolutional layers allows us to exploit structured correlations among instances to facilitate more effective training and testing. Experimental results on three benchmark datasets demonstrate the effectiveness of the proposed MIML-FCN+, outperforming state-of-the-art methods in the application of multi-object recognition.

##### Abstract (translated by Google)
多实例多标签（MIML）学习在计算机视觉中具有许多有趣的应用，包括多对象识别和自动图像标记。在这些应用程序中，在训练短语期间通常可以获得诸如边界框，图像标题和描述之类的附加信息，其被称为特权信息（PI）。但是，由于使用PI进行学习的现有工作仅考虑实例级PI（特权实例），因此无法使用MIML学习中可用的行级PI（特权包）。因此，在本文中，我们提出了一个双流完全卷积网络，名为MIML-FCN +，由一个新的PI丢失统一，以解决MIML学习特权包的问题。与之前关于PI的工作相比，所提出的MIML-FCN +利用了现有的特权包，而不是难以获得的特权实例，使得该系统在现实世界的应用中更加通用和实用。由于提出的PI损失是凸的和SGD兼容的，并且框架本身是一个完全卷积网络，MIML-FCN +可以很容易地与最先进的深度学习网络集成。此外，卷积层的灵活性允许我们利用实例之间的结构化相关性来促进更有效的训练和测试。三个基准数据集的实验结果证明了所提出的MIML-FCN +的有效性，在多目标识别的应用中表现优于最先进的方法。

##### URL
[https://arxiv.org/abs/1702.08681](https://arxiv.org/abs/1702.08681)

##### PDF
[https://arxiv.org/pdf/1702.08681](https://arxiv.org/pdf/1702.08681)

