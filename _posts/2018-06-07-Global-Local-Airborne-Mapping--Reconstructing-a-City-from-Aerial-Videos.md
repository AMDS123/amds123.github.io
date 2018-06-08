---
layout: post
title: "Global-Local Airborne Mapping : Reconstructing a City from Aerial Videos"
date: 2018-06-07 05:39:15
categories: arXiv_CV
tags: arXiv_CV Knowledge Optimization SLAM
author: Hasnain Vohra, Maxim Bazik, Matthew Antone, Joseph Mundy, William Stephenson
mathjax: true
---

* content
{:toc}

##### Abstract
Monocular visual SLAM has become an attractive practical approach for robot localization and 3D environment mapping, since cameras are small, lightweight, inexpensive, and produce high-rate, high-resolution data streams. Although numerous robust tools have been developed, most existing systems are designed to operate in terrestrial environments and at relatively small scale (a few thousand frames) due to constraints on computation and storage. 
 In this paper, we present a feature-based visual SLAM system for aerial video whose simple design permits near real-time operation, and whose scalability permits large-area mapping using tens of thousands of frames, all on a single conventional computer. Our approach consists of two parallel threads: the first incrementally creates small locally consistent submaps and estimates camera poses at video rate; the second aligns these submaps with one another to produce a single globally consistent map via factor graph optimization over both poses and landmarks. Scale drift is minimized through the use of 7-degree-of-freedom similarity transformations during submap alignment. 
 We quantify our system's performance on both simulated and real data sets, and demonstrate city-scale map reconstruction accurate to within 2 meters using nearly 90,000 aerial video frames - to our knowledge, the largest and fastest such reconstruction to date.

##### Abstract (translated by Google)
单眼视觉SLAM已成为机器人定位和3D环境映射的一种有吸引力的实用方法，因为相机体积小，重量轻，价格低廉，可生成高速率，高分辨率的数据流。尽管已经开发了许多强大的工具，但由于计算和存储的限制，大多数现有系统设计为在地面环境中运行，并且规模相对较小（几千帧）。
 在本文中，我们提出了一种基于特征的视觉SLAM系统，用于航空视频，其简单设计允许近实时操作，并且其可扩展性允许使用成千上万帧的大面积映射，全部在单个常规计算机上。我们的方法由两个并行线程组成：第一个增量地创建小的本地一致的子图，并以视频速率估计相机姿态;第二个将这些子地图彼此对齐，以通过因素图优化在姿势和地标上产生单个全局一致的地图。通过在子图对齐期间使用7自由度相似度转换来最小化尺度漂移。
 我们量化了我们的系统在模拟和真实数据集上的性能，并且使用近90,000个航空视频帧展示了城市规模的地图重建精确到2米以内 - 据我们所知，这是迄今为止规模最大，速度最快的重建。

##### URL
[http://arxiv.org/abs/1706.01580](http://arxiv.org/abs/1706.01580)

##### PDF
[http://arxiv.org/pdf/1706.01580](http://arxiv.org/pdf/1706.01580)

