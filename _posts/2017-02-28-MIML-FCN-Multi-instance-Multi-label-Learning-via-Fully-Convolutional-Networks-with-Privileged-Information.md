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
多实例多标签（MIML）学习在计算机视觉中有许多有趣的应用，包括多目标识别和自动图像标记。在这些应用中，在训练词语期间通常可以获得附加信息，例如边界框，图像标题和描述，这被称为特权信息（PI）。然而，由于使用PI只考虑实例级PI（特权的实例）学习现有的作品，他们未能利用包级PI（特权袋）在MIML学习提供。因此，在本文中，我们提出了两个流完全卷积网络，命名为MIML-FCN +，通过新颖的PI亏损统一解决MIML与特权包学习的问题。相比于PI之前的作品，建议MIML-FCN +利用现成的特权袋，而不是难以得到特权的情况下，使系统更加普遍和实用于真实世界的应用。由于建议PI损失是凸面和SGD兼容和框架本身是完全卷积网络，MIML-FCN +可容易地与最先进的深学习网络状态一体化。此外，卷积层的灵活性使我们能够利用实例之间的结构化相关性来促进更有效的训练和测试。在三个基准数据集上的实验结果证明了所提出的MIML-FCN +的有效性，其在多物体识别的应用中优于现有技术的方法。

##### URL
[https://arxiv.org/abs/1702.08681](https://arxiv.org/abs/1702.08681)

##### PDF
[https://arxiv.org/pdf/1702.08681](https://arxiv.org/pdf/1702.08681)

