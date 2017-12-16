---
layout: post
title: "PoseTrack: Joint Multi-Person Pose Estimation and Tracking"
date: 2017-04-07 14:16:38
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Tracking Quantitative Detection
author: Umar Iqbal, Anton Milan, Juergen Gall
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we introduce the challenging problem of joint multi-person pose estimation and tracking of an unknown number of persons in unconstrained videos. Existing methods for multi-person pose estimation in images cannot be applied directly to this problem, since it also requires to solve the problem of person association over time in addition to the pose estimation for each person. We therefore propose a novel method that jointly models multi-person pose estimation and tracking in a single formulation. To this end, we represent body joint detections in a video by a spatio-temporal graph and solve an integer linear program to partition the graph into sub-graphs that correspond to plausible body pose trajectories for each person. The proposed approach implicitly handles occlusion and truncation of persons. Since the problem has not been addressed quantitatively in the literature, we introduce a challenging "Multi-Person PoseTrack" dataset, and also propose a completely unconstrained evaluation protocol that does not make any assumptions about the scale, size, location or the number of persons. Finally, we evaluate the proposed approach and several baseline methods on our new dataset.

##### Abstract (translated by Google)
在这项工作中，我们介绍一个具有挑战性的联合多人姿态估计和无约束视频的未知数量的跟踪的问题。现有的用于图像中多人姿态估计的方法不能直接应用于这个问题，因为除了每个人的姿态估计之外，还需要解决随时间变化的人际关联问题。因此，我们提出了一种联合建模多人姿态估计和跟踪的新方法。为此，我们通过时空图来表示视频中的身体关节检测，并且求解整数线性程序以将图划分成对应于对于每个人而言似乎合理的身体姿态轨迹的子图。所提出的方法隐含地处理人的遮挡和截断。由于这个问题在文献中并没有定量地解决，我们引入了一个具有挑战性的“多人姿势跟踪”数据集，并提出了一个完全不受限制的评估协议，它不对任何人的规模，大小，位置或人数。最后，我们评估提出的方法和我们的新数据集的几个基准方法。

##### URL
[https://arxiv.org/abs/1611.07727](https://arxiv.org/abs/1611.07727)

##### PDF
[https://arxiv.org/pdf/1611.07727](https://arxiv.org/pdf/1611.07727)

