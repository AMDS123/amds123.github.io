---
layout: post
title: "A Multi-Scale Cascade Fully Convolutional Network Face Detector"
date: 2016-09-12 19:13:46
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face CNN Detection Face_Detection
author: Zhenheng Yang, Ram Nevatia
mathjax: true
---

* content
{:toc}

##### Abstract
Face detection is challenging as faces in images could be present at arbitrary locations and in different scales. We propose a three-stage cascade structure based on fully convolutional neural networks (FCNs). It first proposes the approximate locations where the faces may be, then aims to find the accurate location by zooming on to the faces. Each level of the FCN cascade is a multi-scale fully-convolutional network, which generates scores at different locations and in different scales. A score map is generated after each FCN stage. Probable regions of face are selected and fed to the next stage. The number of proposals is decreased after each level, and the areas of regions are decreased to more precisely fit the face. Compared to passing proposals directly between stages, passing probable regions can decrease the number of proposals and reduce the cases where first stage doesn't propose good bounding boxes. We show that by using FCN and score map, the FCN cascade face detector can achieve strong performance on public datasets.

##### Abstract (translated by Google)
人脸检测是具有挑战性的，因为图像中的人脸可以呈现在任意位置和不同尺度上。我们提出了一个基于完全卷积神经网络（FCNs）的三级级联结构。它首先提出人脸的大概位置，然后通过放大脸部来寻找准确的位置。 FCN级联的每个级别都是一个多尺度的全卷积网络，它可以在不同的地点和不同的尺度上生成分数。在每个FCN阶段之后生成分数图。选择脸部的可能区域并将其馈送到下一个阶段。提案数量在每个级别之后都会下降，而地区的面积则会减少到更精确的面部。与阶段之间直接通过提案相比，通过可能的地区可以减少提案的数量，减少第一阶段不提出好的边界框的情况。我们表明，通过使用FCN和分数图，FCN级联人脸检测器可以在公共数据集上实现强大的性能。

##### URL
[https://arxiv.org/abs/1609.03536](https://arxiv.org/abs/1609.03536)

##### PDF
[https://arxiv.org/pdf/1609.03536](https://arxiv.org/pdf/1609.03536)

