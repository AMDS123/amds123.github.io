---
layout: post
title: "ProNet: Learning to Propose Object-specific Boxes for Cascaded Neural Networks"
date: 2016-04-13 02:56:43
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Chen Sun, Manohar Paluri, Ronan Collobert, Ram Nevatia, Lubomir Bourdev
mathjax: true
---

* content
{:toc}

##### Abstract
This paper aims to classify and locate objects accurately and efficiently, without using bounding box annotations. It is challenging as objects in the wild could appear at arbitrary locations and in different scales. In this paper, we propose a novel classification architecture ProNet based on convolutional neural networks. It uses computationally efficient neural networks to propose image regions that are likely to contain objects, and applies more powerful but slower networks on the proposed regions. The basic building block is a multi-scale fully-convolutional network which assigns object confidence scores to boxes at different locations and scales. We show that such networks can be trained effectively using image-level annotations, and can be connected into cascades or trees for efficient object classification. ProNet outperforms previous state-of-the-art significantly on PASCAL VOC 2012 and MS COCO datasets for object classification and point-based localization.

##### Abstract (translated by Google)
本文的目的是准确和有效地分类和定位对象，而不使用边界框注释。由于野外的物体可以出现在任意的地点和不同的尺度，因此具有挑战性。在本文中，我们提出了一种基于卷积神经网络的新型分类结构ProNet。它使用计算有效的神经网络来提出可能包含对象的图像区域，并且在所提出的区域上应用更强大但更慢的网络。基本构建模块是一个多尺度全卷积网络，它将对象置信度分数分配给不同位置和尺度的盒子。我们表明，这样的网络可以使用图像级别的注释进行有效的训练，并且可以连接成级联或树状结构进行高效的对象分类。 ProNet在PASCAL VOC 2012和MS COCO数据集上的表现优于以前的最新技术，用于对象分类和基于点的本地化。

##### URL
[https://arxiv.org/abs/1511.03776](https://arxiv.org/abs/1511.03776)

##### PDF
[https://arxiv.org/pdf/1511.03776](https://arxiv.org/pdf/1511.03776)

