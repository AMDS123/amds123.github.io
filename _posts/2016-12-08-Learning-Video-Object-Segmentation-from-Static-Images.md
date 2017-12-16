---
layout: post
title: "Learning Video Object Segmentation from Static Images"
date: 2016-12-08 13:59:18
categories: arXiv_CV
tags: arXiv_CV Segmentation Tracking Object_Tracking Deep_Learning
author: Anna Khoreva, Federico Perazzi, Rodrigo Benenson, Bernt Schiele, Alexander Sorkine-Hornung
mathjax: true
---

* content
{:toc}

##### Abstract
Inspired by recent advances of deep learning in instance segmentation and object tracking, we introduce video object segmentation problem as a concept of guided instance segmentation. Our model proceeds on a per-frame basis, guided by the output of the previous frame towards the object of interest in the next frame. We demonstrate that highly accurate object segmentation in videos can be enabled by using a convnet trained with static images only. The key ingredient of our approach is a combination of offline and online learning strategies, where the former serves to produce a refined mask from the previous frame estimate and the latter allows to capture the appearance of the specific object instance. Our method can handle different types of input annotations: bounding boxes and segments, as well as incorporate multiple annotated frames, making the system suitable for diverse applications. We obtain competitive results on three different datasets, independently from the type of input annotation.

##### Abstract (translated by Google)
受到实例分割和对象跟踪等深层次学习的深入研究的启发，引入视频对象分割问题作为引导实例分割的概念。我们的模型在每帧的基础上进行，以前一帧的输出为指向下一帧感兴趣的对象。我们证明，通过使用仅使用静态图像训练的闭包，可以启用视频中高度准确的对象分割。我们的方法的关键组成部分是离线和在线学习策略的组合，其中前者用于从前一帧估计产生精确的掩模，后者允许捕获特定对象实例的外观。我们的方法可以处理不同类型的输入注释：边界框和分段，并且包含多个带注释的框架，使系统适用于多种应用。我们获得三个不同的数据集的竞争结果，独立于输入注释的类型。

##### URL
[https://arxiv.org/abs/1612.02646](https://arxiv.org/abs/1612.02646)

##### PDF
[https://arxiv.org/pdf/1612.02646](https://arxiv.org/pdf/1612.02646)

