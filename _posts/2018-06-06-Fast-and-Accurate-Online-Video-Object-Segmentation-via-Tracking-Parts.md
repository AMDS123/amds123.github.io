---
layout: post
title: "Fast and Accurate Online Video Object Segmentation via Tracking Parts"
date: 2018-06-06 17:43:13
categories: arXiv_CV
tags: arXiv_CV Segmentation Tracking
author: Jingchun Cheng, Yi-Hsuan Tsai, Wei-Chih Hung, Shengjin Wang, Ming-Hsuan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Online video object segmentation is a challenging task as it entails to process the image sequence timely and accurately. To segment a target object through the video, numerous CNN-based methods have been developed by heavily finetuning on the object mask in the first frame, which is time-consuming for online applications. In this paper, we propose a fast and accurate video object segmentation algorithm that can immediately start the segmentation process once receiving the images. We first utilize a part-based tracking method to deal with challenging factors such as large deformation, occlusion, and cluttered background. Based on the tracked bounding boxes of parts, we construct a region-of-interest segmentation network to generate part masks. Finally, a similarity-based scoring function is adopted to refine these object parts by comparing them to the visual information in the first frame. Our method performs favorably against state-of-the-art algorithms in accuracy on the DAVIS benchmark dataset, while achieving much faster runtime performance.

##### Abstract (translated by Google)
在线视频对象分割是一项具有挑战性的任务，因为它需要及时和准确地处理图像序列。为了通过视频分割目标对象，已经开发了许多基于CNN的方法，通过在第一帧中严格调整对象掩模，这对于在线应用来说是耗时的。在本文中，我们提出了一种快速准确的视频对象分割算法，一旦接收图像就可以立即开始分割过程。我们首先利用基于部件的跟踪方法来处理具有挑战性的因素，如大变形，遮挡和混乱的背景。基于追踪的零件边界框，我们构建了一个感兴趣区域分割网络来生成零件蒙版。最后，通过将这些对象部分与第一帧中的视觉信息进行比较，采用基于相似性的评分函数来细化这些对象部分。我们的方法在DAVIS基准数据集的准确性上优于最先进的算法，同时实现更快的运行时性能。

##### URL
[http://arxiv.org/abs/1806.02323](http://arxiv.org/abs/1806.02323)

##### PDF
[http://arxiv.org/pdf/1806.02323](http://arxiv.org/pdf/1806.02323)

