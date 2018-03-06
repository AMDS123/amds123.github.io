---
layout: post
title: "Relocalization, Global Optimization and Map Merging for Monocular Visual-Inertial SLAM"
date: 2018-03-05 08:13:42
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Optimization SLAM
author: Tong Qin, Perliang Li, Shaojie Shen
mathjax: true
---

* content
{:toc}

##### Abstract
The monocular visual-inertial system (VINS), which consists one camera and one low-cost inertial measurement unit (IMU), is a popular approach to achieve accurate 6-DOF state estimation. However, such locally accurate visual-inertial odometry is prone to drift and cannot provide absolute pose estimation. Leveraging history information to relocalize and correct drift has become a hot topic. In this paper, we propose a monocular visual-inertial SLAM system, which can relocalize camera and get the absolute pose in a previous-built map. Then 4-DOF pose graph optimization is performed to correct drifts and achieve global consistent. The 4-DOF contains x, y, z, and yaw angle, which is the actual drifted direction in the visual-inertial system. Furthermore, the proposed system can reuse a map by saving and loading it in an efficient way. Current map and previous map can be merged together by the global pose graph optimization. We validate the accuracy of our system on public datasets and compare against other state-of-the-art algorithms. We also evaluate the map merging ability of our system in the large-scale outdoor environment. The source code of map reuse is integrated into our public code, VINS-Mono.

##### Abstract (translated by Google)
由一个摄像头和一个低成本惯性测量单元（IMU）组成的单目视觉 - 惯性系统（VINS）是实现精确6-DOF状态估计的流行方法。但是，这种局部准确的视觉惯性测距法容易出现漂移，无法提供绝对的姿态估计。利用历史信息重新定位和纠正漂移已成为一个热门话题。在本文中，我们提出了一个单目视觉惯性SLAM系统，它可以重新定位摄像机并获得先前建立的地图中的绝对姿态。然后执行四自由度姿态图优化以校正漂移并实现全局一致。 4自由度包含x，y，z和偏航角，这是视觉惯性系统中的实际漂移方向。此外，所提出的系统可以通过以有效的方式保存和加载地图来重新使用地图。当前地图和先前的地图可以通过全局姿态图优化合并在一起。我们验证了我们系统在公共数据集上的准确性，并与其他最先进的算法进行了比较。我们还评估了我们的系统在大型户外环境中的地图合并能力。地图重用的源代码被集成到我们的公共代码VINS-Mono中。

##### URL
[http://arxiv.org/abs/1803.01549](http://arxiv.org/abs/1803.01549)

##### PDF
[http://arxiv.org/pdf/1803.01549](http://arxiv.org/pdf/1803.01549)

