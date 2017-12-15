---
layout: post
title: "A robust and efficient video representation for action recognition"
date: 2015-04-21 17:44:07
categories: arXiv_CV
tags: arXiv_CV Object_Detection Action_Recognition Classification Detection Recognition
author: Heng Wang, Dan Oneata, Jakob Verbeek, Cordelia Schmid
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces a state-of-the-art video representation and applies it to efficient action recognition and detection. We first propose to improve the popular dense trajectory features by explicit camera motion estimation. More specifically, we extract feature point matches between frames using SURF descriptors and dense optical flow. The matches are used to estimate a homography with RANSAC. To improve the robustness of homography estimation, a human detector is employed to remove outlier matches from the human body as human motion is not constrained by the camera. Trajectories consistent with the homography are considered as due to camera motion, and thus removed. We also use the homography to cancel out camera motion from the optical flow. This results in significant improvement on motion-based HOF and MBH descriptors. We further explore the recent Fisher vector as an alternative feature encoding approach to the standard bag-of-words histogram, and consider different ways to include spatial layout information in these encodings. We present a large and varied set of evaluations, considering (i) classification of short basic actions on six datasets, (ii) localization of such actions in feature-length movies, and (iii) large-scale recognition of complex events. We find that our improved trajectory features significantly outperform previous dense trajectories, and that Fisher vectors are superior to bag-of-words encodings for video recognition tasks. In all three tasks, we show substantial improvements over the state-of-the-art results.

##### Abstract (translated by Google)
本文介绍了最先进的视频表示，并将其应用于高效的动作识别和检测。我们首先提出通过明确的相机运动估计来改进流行的密集轨迹特征。更具体地说，我们使用SURF描述符和密集光流来提取帧之间的特征点匹配。这些匹配用于估计与RANSAC的单应性。为了提高单应性估计的鲁棒性，由于人体运动不受相机约束，因此人类检测器被用于从人体中去除异常值匹配。与单应性一致的轨迹被视为由于相机运动而被移除。我们还使用单应性来消除光流中的相机运动。这导致了基于运动的HOF和MBH描述符的显着改进。我们进一步探讨了最近的Fisher矢量作为标准袋子直方图的替代特征编码方法，并考虑了在这些编码中包含空间布局信息的不同方式。我们提出了大量不同的评估集，考虑到（i）对六个数据集的短基本动作的分类，（ii）这些动作在特征长度电影中的本地化，以及（iii）对复杂事件的大规模识别。我们发现，我们的改进的轨迹特征明显胜过以前的密集轨迹，并且Fisher矢量优于用于视频识别任务的词袋编码。在所有这三项工作中，我们都展示了最先进的结果。

##### URL
[https://arxiv.org/abs/1504.05524](https://arxiv.org/abs/1504.05524)

##### PDF
[https://arxiv.org/pdf/1504.05524](https://arxiv.org/pdf/1504.05524)

