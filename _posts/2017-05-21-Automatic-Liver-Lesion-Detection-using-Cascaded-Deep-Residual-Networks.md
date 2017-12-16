---
layout: post
title: "Automatic Liver Lesion Detection using Cascaded Deep Residual Networks"
date: 2017-05-21 02:58:40
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation CNN Deep_Learning Detection
author: Lei Bi, Jinman Kim, Ashnil Kumar, Dagan Feng
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic segmentation of liver lesions is a fundamental requirement towards the creation of computer aided diagnosis (CAD) and decision support systems (CDS). Traditional segmentation approaches depend heavily upon hand-crafted features and a priori knowledge of the user. As such, these methods are difficult to adopt within a clinical environment. Recently, deep learning methods based on fully convolutional networks (FCNs) have been successful in many segmentation problems primarily because they leverage a large labelled dataset to hierarchically learn the features that best correspond to the shallow visual appearance as well as the deep semantics of the areas to be segmented. However, FCNs based on a 16 layer VGGNet architecture have limited capacity to add additional layers. Therefore, it is challenging to learn more discriminative features among different classes for FCNs. In this study, we overcome these limitations using deep residual networks (ResNet) to segment liver lesions. ResNet contain skip connections between convolutional layers, which solved the problem of the training degradation of training accuracy in very deep networks and thereby enables the use of additional layers for learning more discriminative features. In addition, we achieve more precise boundary definitions through a novel cascaded ResNet architecture with multi-scale fusion to gradually learn and infer the boundaries of both the liver and the liver lesions. Our proposed method achieved 4th place in the ISBI 2017 Liver Tumor Segmentation Challenge by the submission deadline.

##### Abstract (translated by Google)
自动分割肝脏病变是创建计算机辅助诊断（CAD）和决策支持系统（CDS）的基本要求。传统的分割方法在很大程度上取决于手工特征和用户的先验知识。因此，这些方法在临床环境中很难采用。最近，基于完全卷积网络（FCNs）的深度学习方法在许多分割问题中取得了成功，主要是因为它们利用大型标记数据集来分层学习与浅视觉外观以及该区域的深层语义相对应的特征被分割。但是，基于16层VGGNet架构的FCN具有增加附加层的能力有限。因此，要学习FCNs在不同类别间更具区别性的特征是具有挑战性的。在这项研究中，我们克服了这些限制使用深度残留网络（ResNet）来分割肝脏病变。 ResNet包含卷积层之间的跳过连接，它解决了非常深的网络中训练精度的训练退化问题，从而使得能够使用附加层学习更多的判别特征。另外，我们通过一种新的多级融合的ResNet架构实现更精确的边界定义，逐渐学习和推断肝脏和肝脏病变的边界。我们提出的方法在截止日期之前在ISBI 2017肝肿瘤分割挑战赛中获得了第四名。

##### URL
[https://arxiv.org/abs/1704.02703](https://arxiv.org/abs/1704.02703)

##### PDF
[https://arxiv.org/pdf/1704.02703](https://arxiv.org/pdf/1704.02703)

