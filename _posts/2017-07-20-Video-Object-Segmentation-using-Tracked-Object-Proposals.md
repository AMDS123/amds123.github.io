---
layout: post
title: "Video Object Segmentation using Tracked Object Proposals"
date: 2017-07-20 14:31:12
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Tracking CNN Object_Tracking Prediction Detection
author: Gilad Sharir, Eddie Smolyansky, Itamar Friedman
mathjax: true
---

* content
{:toc}

##### Abstract
We present an approach to semi-supervised video object segmentation, in the context of the DAVIS 2017 challenge. Our approach combines category-based object detection, category-independent object appearance segmentation and temporal object tracking. We are motivated by the fact that the objects semantic category tends not to change throughout the video while its appearance and location can vary considerably. In order to capture the specific object appearance independent of its category, for each video we train a fully convolutional network using augmentations of the given annotated frame. We refine the appearance segmentation mask with the bounding boxes provided either by a semantic object detection network, when applicable, or by a previous frame prediction. By introducing a temporal continuity constraint on the detected boxes, we are able to improve the object segmentation mask of the appearance network and achieve competitive results on the DAVIS datasets.

##### Abstract (translated by Google)
在DAVIS 2017挑战的背景下，我们提出了一种半监督视频对象分割的方法。我们的方法结合了基于类别的对象检测，与类别无关的对象外观分割和时间对象跟踪。我们的动机是这样的事实：对象语义类别在整个视频中往往不会改变，而其外观和位置可以相差很大。为了捕获独立于其类别的特定对象外观，对于每个视频，我们使用给定的带注释的帧的增强来训练完全卷积网络。我们使用由语义对象检测网络（如果适用的话）或先前的帧预测提供的边界框来细化外观分割掩模。通过在检测到的盒子上引入时间连续性约束，我们能够改善外观网络的对象分割掩模，并在DAVIS数据集上获得竞争结果。

##### URL
[https://arxiv.org/abs/1707.06545](https://arxiv.org/abs/1707.06545)

##### PDF
[https://arxiv.org/pdf/1707.06545](https://arxiv.org/pdf/1707.06545)

