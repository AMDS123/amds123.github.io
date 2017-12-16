---
layout: post
title: "Fully Automatic and Real-Time Catheter Segmentation in X-Ray Fluoroscopy"
date: 2017-07-17 13:18:37
categories: arXiv_CV
tags: arXiv_CV Segmentation Tracking CNN Detection
author: Pierre Ambrosini, Daniel Ruijters, Wiro J. Niessen, Adriaan Moelker, Theo van Walsum
mathjax: true
---

* content
{:toc}

##### Abstract
Augmenting X-ray imaging with 3D roadmap to improve guidance is a common strategy. Such approaches benefit from automated analysis of the X-ray images, such as the automatic detection and tracking of instruments. In this paper, we propose a real-time method to segment the catheter and guidewire in 2D X-ray fluoroscopic sequences. The method is based on deep convolutional neural networks. The network takes as input the current image and the three previous ones, and segments the catheter and guidewire in the current image. Subsequently, a centerline model of the catheter is constructed from the segmented image. A small set of annotated data combined with data augmentation is used to train the network. We trained the method on images from 182 X-ray sequences from 23 different interventions. On a testing set with images of 55 X-ray sequences from 5 other interventions, a median centerline distance error of 0.2 mm and a median tip distance error of 0.9 mm was obtained. The segmentation of the instruments in 2D X-ray sequences is performed in a real-time fully-automatic manner.

##### Abstract (translated by Google)
用3D路线图增强X射线成像来改善指导是一种常见的策略。这些方法受益于X射线图像的自动分析，例如仪器的自动检测和跟踪。在本文中，我们提出了一个实时的方法来分割导管和导丝的二维X射线透视序列。该方法基于深度卷积神经网络。网络将当前图像和前三个图像作为输入，并在当前图像中分割导管和导丝。随后，从分割的图像构建导管的中心线模型。一小组带有数据增加的注释数据被用来训练网络。我们对来自23种不同干预的182个X射线序列的图像进行了训练。在来自5次其他干预的55个X射线序列的图像的测试集上，获得了中值中心线距离误差0.2mm和中值末端距离误差0.9mm。二维X射线序列中仪器的分割是以实时全自动的方式进行的。

##### URL
[https://arxiv.org/abs/1707.05137](https://arxiv.org/abs/1707.05137)

##### PDF
[https://arxiv.org/pdf/1707.05137](https://arxiv.org/pdf/1707.05137)

