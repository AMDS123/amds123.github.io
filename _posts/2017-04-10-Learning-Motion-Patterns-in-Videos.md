---
layout: post
title: "Learning Motion Patterns in Videos"
date: 2017-04-10 11:33:59
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Pavel Tokmakov, Karteek Alahari, Cordelia Schmid
mathjax: true
---

* content
{:toc}

##### Abstract
The problem of determining whether an object is in motion, irrespective of camera motion, is far from being solved. We address this challenging task by learning motion patterns in videos. The core of our approach is a fully convolutional network, which is learned entirely from synthetic video sequences, and their ground-truth optical flow and motion segmentation. This encoder-decoder style architecture first learns a coarse representation of the optical flow field features, and then refines it iteratively to produce motion labels at the original high-resolution. We further improve this labeling with an objectness map and a conditional random field, to account for errors in optical flow, and also to focus on moving "things" rather than "stuff". The output label of each pixel denotes whether it has undergone independent motion, i.e., irrespective of camera motion. We demonstrate the benefits of this learning framework on the moving object segmentation task, where the goal is to segment all objects in motion. Our approach outperforms the top method on the recently released DAVIS benchmark dataset, comprising real-world sequences, by 5.6%. We also evaluate on the Berkeley motion segmentation database, achieving state-of-the-art results.

##### Abstract (translated by Google)
无论摄像机运动如何，确定物体是否在运动的问题都远远没有解决。我们通过学习视频中的运动模式来解决这个具有挑战性的任务我们的方法的核心是一个完全卷积网络，它是完全从合成视频序列，他们的地面实况光流和运动分割学习。这种编码器 - 解码器式架构首先获得光学流场特征的粗略表示，然后迭代地对其进行细化以产生原始高分辨率的运动标签。我们进一步改进这个标签，用一个对象图和一个条件随机场来解决光流的错误，并且把注意力放在移动“事物”而不是“东西”上。每个像素的输出标签表示它是否已经经历独立运动，即，不管摄像机运动如何。我们展示了这个学习框架对移动对象分割任务的好处，其目标是分割所有运动对象。我们的方法胜过了最近发布的DAVIS基准数据集的顶级方法，其中包括现实世界序列的5.6％。我们还对伯克利运动分割数据库进行了评估，取得了最先进的成果。

##### URL
[https://arxiv.org/abs/1612.07217](https://arxiv.org/abs/1612.07217)

##### PDF
[https://arxiv.org/pdf/1612.07217](https://arxiv.org/pdf/1612.07217)

