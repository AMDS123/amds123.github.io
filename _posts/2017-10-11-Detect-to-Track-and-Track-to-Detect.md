---
layout: post
title: "Detect to Track and Track to Detect"
date: 2017-10-11 08:33:48
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Detection Relation
author: Christoph Feichtenhofer, Axel Pinz, Andrew Zisserman
mathjax: true
---

* content
{:toc}

##### Abstract
Recent approaches for high accuracy detection and tracking of object categories in video consist of complex multistage solutions that become more cumbersome each year. In this paper we propose a ConvNet architecture that jointly performs detection and tracking, solving the task in a simple and effective way. Our contributions are threefold: (i) we set up a ConvNet architecture for simultaneous detection and tracking, using a multi-task objective for frame-based object detection and across-frame track regression; (ii) we introduce correlation features that represent object co-occurrences across time to aid the ConvNet during tracking; and (iii) we link the frame level detections based on our across-frame tracklets to produce high accuracy detections at the video level. Our ConvNet architecture for spatiotemporal object detection is evaluated on the large-scale ImageNet VID dataset where it achieves state-of-the-art results. Our approach provides better single model performance than the winning method of the last ImageNet challenge while being conceptually much simpler. Finally, we show that by increasing the temporal stride we can dramatically increase the tracker speed.

##### Abstract (translated by Google)
近年来，对视频中的对象类别进行高精度检测和跟踪的方法由复杂的多级解决方案组成，每年解决方案越来越麻烦。在本文中，我们提出了一种联合执行检测和跟踪的ConvNet架构，以简单有效的方式解决任务。我们的贡献有三个：（1）我们建立了ConvNet架构，用于同时检测和跟踪，使用基于帧的对象检测和跨帧跟踪回归的多任务目标; （ii）我们引入了相关特征，这些特征代表了在跟踪过程中随时间变化的对象共现;和（iii）我们链接基于我们的跨帧tracklets的帧级别检测，以在视频级别产生高精度的检测。我们的ConvNet时空目标检测体系结构在大规模的ImageNet VID数据集上进行评估，从而获得最新的结果。我们的方法提供了比上一次ImageNet挑战的获胜方法更好的单一模型性能，同时在概念上更简单。最后，我们表明通过增加时间跨度，我们可以显着提高跟踪器的速度。

##### URL
[https://arxiv.org/abs/1710.03958](https://arxiv.org/abs/1710.03958)

##### PDF
[https://arxiv.org/pdf/1710.03958](https://arxiv.org/pdf/1710.03958)

