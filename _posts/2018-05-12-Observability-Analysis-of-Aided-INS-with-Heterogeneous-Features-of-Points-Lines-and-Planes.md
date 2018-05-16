---
layout: post
title: "Observability Analysis of Aided INS with Heterogeneous Features of Points, Lines and Planes"
date: 2018-05-12 00:49:37
categories: arXiv_RO
tags: arXiv_RO SLAM
author: Yulin Yang, Guoquan Huang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we perform a thorough observability analysis for linearized inertial navigation systems (INS) aided by exteroceptive range and/or bearing sensors (such as cameras, LiDAR and sonars) with different geometric features (points, lines and planes). While the observability of vision-aided INS (VINS) with point features has been extensively studied in the literature, we analytically show that the general aided INS with point features preserves the same observability property: that is, 4 unobservable directions, corresponding to the global yaw and the global position of the sensor platform. We further prove that there are at least 5 (and 7) unobservable directions for the linearized aided INS with a single line (and plane) feature; and, for the first time, analytically derive the unobservable subspace for the case of multiple lines/planes. Building upon this, we examine the system observability of the linearized aided INS with different combinations of points, lines and planes, and show that, in general, the system preserves at least 4 unobservable directions, while if global measurements are available, as expected, some unobservable directions diminish. In particular, when using plane features, we propose to use a minimal, closest point (CP) representation; and we also study in-depth the effects of 5 degenerate motions identified on observability. To numerically validate our analysis, we develop and evaluate both EKF-based visual-inertial SLAM and visual-inertial odometry (VIO) using heterogeneous geometric features in Monte Carlo simulations.

##### Abstract (translated by Google)
在本文中，我们对具有不同几何特征（点，线和平面）的外接范围和/或轴承传感器（如相机，激光雷达和声纳）辅助的线性化惯性导航系统（INS）进行了全面的可观测性分析。尽管在文献中已经广泛研究了具有点特征的视觉辅助INS（VINS）的可观测性，但我们通过分析显示具有点特征的通用辅助INS保留了相同的可观测性：也就是说，4个不可观测方向，对应于全局偏航和传感器平台的全球地位。我们进一步证明，具有单线（和平面）特征的线性化辅助INS至少有5（和7）个不可观测的方向;并且首次在多线/平面的情况下分析推导出不可观察的子空间。在此基础上，我们研究了不同点，线和平面组合的线性辅助惯性导航系统的系统可观测性，并且表明，一般来说，系统至少保留4个不可观测的方向，而如果全局测量可用，一些不可观察的方向减少。特别是，当使用平面特征时，我们建议使用最小的最近点（CP）表示;并且我们还深入研究了5个可观测性退化运动的影响。为了在数值上验证我们的分析，我们在Monte Carlo模拟中使用异构几何特征开发和评估基于EKF的视觉惯性SLAM和视觉惯性测距（VIO）。

##### URL
[http://arxiv.org/abs/1805.05876](http://arxiv.org/abs/1805.05876)

##### PDF
[http://arxiv.org/pdf/1805.05876](http://arxiv.org/pdf/1805.05876)

