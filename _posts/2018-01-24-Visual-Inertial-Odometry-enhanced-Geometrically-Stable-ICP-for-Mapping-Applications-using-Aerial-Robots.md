---
layout: post
title: "Visual-Inertial Odometry-enhanced Geometrically Stable ICP for Mapping Applications using Aerial Robots"
date: 2018-01-24 22:43:16
categories: arXiv_RO
tags: arXiv_RO
author: Tung Dang, Shehryar Khattak, Christos Papachristos, Kostas Alexis
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a visual-inertial odometry-enhanced geometrically stable Iterative Closest Point (ICP) algorithm for accurate mapping using aerial robots. The proposed method employs a visual-inertial odometry framework in order to provide robust priors to the ICP step and calculate the overlap among point clouds derived from an onboard time-of-flight depth sensor. Within the overlapping parts of the point clouds, the method samples points such that the distribution of normals among them is as large as possible. As different geometries and sensor trajectories will influence the performance of the alignment process, evaluation of the expected geometric stability of the ICP step is conducted. It is only when this test is successful that the matching, outlier rejection, and minimization of the error metric ICP steps are conducted and the new relative translation and rotational components are estimated, otherwise the system relies on the visual-inertial odometry transformation estimates. The proposed strategy was evaluated within handheld, automated and fully autonomous exploration and mapping missions using a small aerial robot and was shown to provide robust results of superior quality at an affordable increase of the computational load.

##### Abstract (translated by Google)
本文提出了一种视觉惯性测距增强几何稳定迭代最近点（ICP）算法，用于使用空中机器人进行精确测绘。所提出的方法采用视觉 - 惯性测距框架，以便为ICP步骤提供稳健的先验，并计算从机载飞行时间深度传感器导出的点云之间的重叠。在点云的重叠部分中，方法采样点使得法线之间的分布尽可能大。由于不同的几何形状和传感器轨迹将影响对准过程的性能，因此对ICP步骤的预期几何稳定性进行评估。只有在这个测试成功的情况下，才进行匹配，异常排斥和误差度量ICP步骤的最小化，并且估计新的相对平移和旋转分量，否则系统依赖于视觉 - 惯性测距变换估计。所提出的策略在手持式，自动化和完全自主化的勘探和绘图任务中使用小型空中机器人进行了评估，并被证明能够以可承受的计算负荷增加提供卓越质量的可靠结果。

##### URL
[http://arxiv.org/abs/1801.08228](http://arxiv.org/abs/1801.08228)

##### PDF
[http://arxiv.org/pdf/1801.08228](http://arxiv.org/pdf/1801.08228)

