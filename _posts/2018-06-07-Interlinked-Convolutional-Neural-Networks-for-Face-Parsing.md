---
layout: post
title: "Interlinked Convolutional Neural Networks for Face Parsing"
date: 2018-06-07 01:10:08
categories: arXiv_CV
tags: arXiv_CV Face CNN
author: Yisu Zhou, Xiaolin Hu, Bo Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Face parsing is a basic task in face image analysis. It amounts to labeling each pixel with appropriate facial parts such as eyes and nose. In the paper, we present a interlinked convolutional neural network (iCNN) for solving this problem in an end-to-end fashion. It consists of multiple convolutional neural networks (CNNs) taking input in different scales. A special interlinking layer is designed to allow the CNNs to exchange information, enabling them to integrate local and contextual information efficiently. The hallmark of iCNN is the extensive use of downsampling and upsampling in the interlinking layers, while traditional CNNs usually uses downsampling only. A two-stage pipeline is proposed for face parsing and both stages use iCNN. The first stage localizes facial parts in the size-reduced image and the second stage labels the pixels in the identified facial parts in the original image. On a benchmark dataset we have obtained better results than the state-of-the-art methods.

##### Abstract (translated by Google)
人脸解析是人脸图像分析的基本任务。它相当于用适当的面部部分例如眼睛和鼻子来标记每个像素。在这篇论文中，我们提出了一种互连的卷积神经网络（iCNN），以端到端的方式解决这个问题。它由多个卷积神经网络（CNN）以不同比例输入。一个特殊的链接层旨在允许CNN交换信息，使他们能够有效地整合本地和上下文信息。 iCNN的标志是在互连层中广泛使用下采样和上采样，而传统的CNN通常只使用下采样。提出了一种两阶段流水线用于面部解析，并且两个阶段都使用iCNN。第一阶段在缩小尺寸的图像中定位面部部分，第二阶段在原始图像中标识所标识的面部部分中的像素。在基准数据集上，我们获得了比最先进的方法更好的结果。

##### URL
[http://arxiv.org/abs/1806.02479](http://arxiv.org/abs/1806.02479)

##### PDF
[http://arxiv.org/pdf/1806.02479](http://arxiv.org/pdf/1806.02479)

