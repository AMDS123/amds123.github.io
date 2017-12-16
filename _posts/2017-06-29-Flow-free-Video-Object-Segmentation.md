---
layout: post
title: "Flow-free Video Object Segmentation"
date: 2017-06-29 02:15:15
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Aditya Vora, Shanmuganathan Raman
mathjax: true
---

* content
{:toc}

##### Abstract
Segmenting foreground object from a video is a challenging task because of the large deformations of the objects, occlusions, and background clutter. In this paper, we propose a frame-by-frame but computationally efficient approach for video object segmentation by clustering visually similar generic object segments throughout the video. Our algorithm segments various object instances appearing in the video and then perform clustering in order to group visually similar segments into one cluster. Since the object that needs to be segmented appears in most part of the video, we can retrieve the foreground segments from the cluster having maximum number of segments, thus filtering out noisy segments that do not represent any object. We then apply a track and fill approach in order to localize the objects in the frames where the object segmentation framework fails to segment any object. Our algorithm performs comparably to the recent automatic methods for video object segmentation when benchmarked on DAVIS dataset while being computationally much faster.

##### Abstract (translated by Google)
从视频中分割前景对象是一个具有挑战性的任务，因为对象的大变形，遮挡和背景混乱。在本文中，我们提出了一种逐帧，但计算有效的视频对象分割方法，通过在视频中对视觉上相似的通用对象分段进行聚类。我们的算法对出现在视频中的各种对象实例进行分段，然后执行聚类，以将视觉上相似的分段分组到一个聚类中。由于需要分割的对象出现在视频的大部分中，因此我们可以从具有最大分割数的聚类中检索前景分段，从而过滤出不代表任何对象的噪声分段。然后，我们应用跟踪和填充的方法，以便在对象分割框架无法分割任何对象的框架中定位对象。当在DAVIS数据集上进行基准测试时，我们的算法执行与最近的用于视频对象分割的自动方法相当的性能，同时计算速度更快。

##### URL
[https://arxiv.org/abs/1706.09544](https://arxiv.org/abs/1706.09544)

##### PDF
[https://arxiv.org/pdf/1706.09544](https://arxiv.org/pdf/1706.09544)

