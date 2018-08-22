---
layout: post
title: "Estimating Metric Poses of Dynamic Objects Using Monocular Visual-Inertial Fusion"
date: 2018-08-21 04:04:20
categories: arXiv_CV
tags: arXiv_CV Knowledge Pose_Estimation Tracking Object_Tracking Relation
author: Kejie Qiu, Tong Qin, Hongwen Xie, Shaojie Shen
mathjax: true
---

* content
{:toc}

##### Abstract
A monocular 3D object tracking system generally has only up-to-scale pose estimation results without any prior knowledge of the tracked object. In this paper, we propose a novel idea to recover the metric scale of an arbitrary dynamic object by optimizing the trajectory of the objects in the world frame, without motion assumptions. By introducing an additional constraint in the time domain, our monocular visual-inertial tracking system can obtain continuous six degree of freedom (6-DoF) pose estimation without scale ambiguity. Our method requires neither fixed multi-camera nor depth sensor settings for scale observability, instead, the IMU inside the monocular sensing suite provides scale information for both camera itself and the tracked object. We build the proposed system on top of our monocular visual-inertial system (VINS) to obtain accurate state estimation of the monocular camera in the world frame. The whole system consists of a 2D object tracker, an object region-based visual bundle adjustment (BA), VINS and a correlation analysis-based metric scale estimator. Experimental comparisons with ground truth demonstrate the tracking accuracy of our 3D tracking performance while a mobile augmented reality (AR) demo shows the feasibility of potential applications.

##### Abstract (translated by Google)
单眼3D对象跟踪系统通常仅具有按比例的姿势估计结果，而没有跟踪对象的任何先验知识。在本文中，我们提出了一种新颖的想法，即通过优化世界框架中物体的轨迹来恢复任意动态物体的度量尺度，而不需要运动假设。通过在时域中引入附加约束，我们的单目视觉惯性跟踪系统可以获得连续的六自由度（6-DoF）姿态估计而没有尺度模糊。我们的方法既不需要固定的多相机也不需要深度传感器设置来实现尺度可观察性，相反，单眼感应套件内的IMU为相机本身和被跟踪物体提供尺度信息。我们在单眼视觉惯性系统（VINS）之上构建了所​​提出的系统，以获得世界框架中单目摄像机的准确状态估计。整个系统由2D对象跟踪器，基于对象区域的视觉束调整（BA），VINS和基于相关分析的度量尺度估计器组成。与地面事实的实验比较表明我们的3D跟踪性能的跟踪准确性，而移动增强现实（AR）演示显示了潜在应用的可行性。

##### URL
[http://arxiv.org/abs/1808.06753](http://arxiv.org/abs/1808.06753)

##### PDF
[http://arxiv.org/pdf/1808.06753](http://arxiv.org/pdf/1808.06753)

