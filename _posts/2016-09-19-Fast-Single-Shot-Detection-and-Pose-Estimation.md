---
layout: post
title: "Fast Single Shot Detection and Pose Estimation"
date: 2016-09-19 03:38:15
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Tracking CNN Object_Tracking Deep_Learning Detection SLAM
author: Patrick Poirson, Phil Ammirato, Cheng-Yang Fu, Wei Liu, Jana Kosecka, Alexander C. Berg
mathjax: true
---

* content
{:toc}

##### Abstract
For applications in navigation and robotics, estimating the 3D pose of objects is as important as detection. Many approaches to pose estimation rely on detecting or tracking parts or keypoints [11, 21]. In this paper we build on a recent state-of-the-art convolutional network for slidingwindow detection [10] to provide detection and rough pose estimation in a single shot, without intermediate stages of detecting parts or initial bounding boxes. While not the first system to treat pose estimation as a categorization problem, this is the first attempt to combine detection and pose estimation at the same level using a deep learning approach. The key to the architecture is a deep convolutional network where scores for the presence of an object category, the offset for its location, and the approximate pose are all estimated on a regular grid of locations in the image. The resulting system is as accurate as recent work on pose estimation (42.4% 8 View mAVP on Pascal 3D+ [21] ) and significantly faster (46 frames per second (FPS) on a TITAN X GPU). This approach to detection and rough pose estimation is fast and accurate enough to be widely applied as a pre-processing step for tasks including high-accuracy pose estimation, object tracking and localization, and vSLAM.

##### Abstract (translated by Google)
对于导航和机器人应用，估计物体的三维姿态与检测一样重要。许多姿态估计方法依赖于检测或跟踪部件或关键点[11,21]。在本文中，我们建立了一个最新的滑动窗口检测的最先进的卷积网络[10]，提供一次性检测和粗略的姿态估计，没有中间阶段的检测部分或初始边界框。虽然不是第一个将姿态估计视为分类问题的系统，但是这是第一次尝试使用深度学习方法将检测和姿态估计相结合。该体系结构的关键是深度卷积网络，其中存在对象类别的分数，其位置的偏移量以及近似姿态都是在图像中的规则网格上估计的。由此产生的系统与近期在姿态估计方面的工作一样精确（在Pascal 3D +上查看mAVP为42.4％），在TITAN X GPU上显着更快（每秒46帧（FPS））。这种检测和粗略姿态估计的方法足够快速和准确，可以广泛应用于包括高精度姿态估计，目标跟踪和定位以及vSLAM在内的任务的预处理步骤。

##### URL
[https://arxiv.org/abs/1609.05590](https://arxiv.org/abs/1609.05590)

##### PDF
[https://arxiv.org/pdf/1609.05590](https://arxiv.org/pdf/1609.05590)

