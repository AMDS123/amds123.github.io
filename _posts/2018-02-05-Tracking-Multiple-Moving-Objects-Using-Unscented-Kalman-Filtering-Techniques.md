---
layout: post
title: "Tracking Multiple Moving Objects Using Unscented Kalman Filtering Techniques"
date: 2018-02-05 02:27:56
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Object_Tracking Detection
author: Xi Chen, Xiao Wang, Jianhua Xuan
mathjax: true
---

* content
{:toc}

##### Abstract
It is an important task to reliably detect and track multiple moving objects for video surveillance and monitoring. However, when occlusion occurs in nonlinear motion scenarios, many existing methods often fail to continuously track multiple moving objects of interest. In this paper we propose an effective approach for detection and tracking of multiple moving objects with occlusion. Moving targets are initially detected using a simple yet efficient block matching technique, providing rough location information for multiple object tracking. More accurate location information is then estimated for each moving object by a nonlinear tracking algorithm. Considering the ambiguity caused by the occlusion among multiple moving objects, we apply an unscented Kalman filtering (UKF) technique for reliable object detection and tracking. Different from conventional Kalman filtering (KF), which cannot achieve the optimal estimation in nonlinear tracking scenarios, UKF can be used to track both linear and nonlinear motions due to the unscented transform. Further, it estimates the velocity information for each object to assist to the object detection algorithm, effectively delineating multiple moving objects of occlusion. The experimental results demonstrate that the proposed method can correctly detect and track multiple moving objects with nonlinear motion patterns and occlusions.

##### Abstract (translated by Google)
可靠地检测和跟踪视频监视和监视的多个移动对象是一项重要任务。然而，当在非线性运动场景中发生遮挡时，许多现有的方法往往不能连续跟踪多个感兴趣的移动物体。在本文中，我们提出了一种有效的方法来检测和跟踪多个运动对象的遮挡。运动目标最初使用简单而有效的块匹配技术来检测，为多个目标跟踪提供粗略的位置信息。然后通过非线性跟踪算法为每个运动物体估计更准确的位置信息。考虑到多个运动物体之间的遮挡造成的模糊性，我们采用无迹卡尔曼滤波（UKF）技术进行可靠的物体检测和跟踪。与传统的卡尔曼滤波（KF）不同，它不能在非线性跟踪场景下实现最优估计，UKF可以用来跟踪由于无迹变换引起的线性运动和非线性运动。此外，它估计每个对象的速度信息以辅助对象检测算法，有效地描绘多个遮挡的移动对象。实验结果表明，该方法能够正确检测和跟踪具有非线性运动模式和遮挡的多个运动物体。

##### URL
[http://arxiv.org/abs/1802.01235](http://arxiv.org/abs/1802.01235)

##### PDF
[http://arxiv.org/pdf/1802.01235](http://arxiv.org/pdf/1802.01235)

