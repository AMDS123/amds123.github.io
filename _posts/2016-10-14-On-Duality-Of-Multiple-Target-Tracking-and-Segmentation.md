---
layout: post
title: "On Duality Of Multiple Target Tracking and Segmentation"
date: 2016-10-14 17:18:46
categories: arXiv_CV
tags: arXiv_CV Segmentation Tracking Object_Tracking
author: Yicong Tian, Mubarak Shah
mathjax: true
---

* content
{:toc}

##### Abstract
Traditionally, object tracking and segmentation are treated as two separate problems and solved independently. However, in this paper, we argue that tracking and segmentation are actually closely related and solving one should help the other. On one hand, the object track, which is a set of bounding boxes with one bounding box in every frame, would provide strong high-level guidance for the target/background segmentation task. On the other hand, the object segmentation would separate object from other objects and background, which will be useful for determining track locations in every frame. We propose a novel framework which combines online multiple target tracking and segmentation in a video. In our approach, the tracking and segmentation problems are coupled by Lagrange dual decomposition, which leads to more accurate segmentation results and also \emph{helps resolve typical difficulties in multiple target tracking, such as occlusion handling, ID-switch and track drifting}. To track targets, an individual appearance model is learned for each target via structured learning and network flow is employed to generate tracks from densely sampled candidates. For segmentation, multi-label Conditional Random Field (CRF) is applied to a superpixel based spatio-temporal graph in a segment of video to assign background or target labels to every superpixel. The experiments on diverse sequences show that our method outperforms state-of-the-art approaches for multiple target tracking as well as segmentation.

##### Abstract (translated by Google)
传统上，对象跟踪和分割被视为两个独立的问题，并独立解决。然而，在本文中，我们认为跟踪和分割其实是密切相关的，解决方法应该帮助另一个。一方面，对象轨迹是每帧中一个边界框的一组边界框，为目标/背景分割任务提供强有力的高层次指导。另一方面，对象分割会将对象与其他对象和背景分开，这对确定每帧中的轨迹位置将是有用的。我们提出了一个新的框架，结合在线多目标跟踪和分割视频。在我们的方法中，跟踪和分割问题通过拉格朗日对偶分解相结合，从而导致更精确的分割结果，同时也有助于解决多目标跟踪中的典型困难，如遮挡处理，ID切换和跟踪漂移。为了跟踪目标，通过结构化学习为每个目标学习单独的外观模型，并且使用网络流来从密集采样的候选者生成轨迹。对于分割，将多标签条件随机场（CRF）应用于视频片段中的基于超像素的时空图，以将背景或目标标签分配给每个超像素。对不同序列的实验表明，我们的方法胜过了用于多目标跟踪以及分割的最先进的方法。

##### URL
[https://arxiv.org/abs/1610.04542](https://arxiv.org/abs/1610.04542)

##### PDF
[https://arxiv.org/pdf/1610.04542](https://arxiv.org/pdf/1610.04542)

