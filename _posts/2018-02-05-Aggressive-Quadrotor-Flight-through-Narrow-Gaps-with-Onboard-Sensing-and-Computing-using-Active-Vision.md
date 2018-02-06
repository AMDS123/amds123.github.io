---
layout: post
title: "Aggressive Quadrotor Flight through Narrow Gaps with Onboard Sensing and Computing using Active Vision"
date: 2018-02-05 12:40:46
categories: arXiv_RO
tags: arXiv_RO Knowledge Face Detection
author: Davide Falanga, Elias Mueggler, Matthias Faessler, Davide Scaramuzza
mathjax: true
---

* content
{:toc}

##### Abstract
We address one of the main challenges towards autonomous quadrotor flight in complex environments, which is flight through narrow gaps. While previous works relied on off-board localization systems or on accurate prior knowledge of the gap position and orientation, we rely solely on onboard sensing and computing and estimate the full state by fusing gap detection from a single onboard camera with an IMU. This problem is challenging for two reasons: (i) the quadrotor pose uncertainty with respect to the gap increases quadratically with the distance from the gap; (ii) the quadrotor has to actively control its orientation towards the gap to enable state estimation (i.e., active vision). We solve this problem by generating a trajectory that considers geometric, dynamic, and perception constraints: during the approach maneuver, the quadrotor always faces the gap to allow state estimation, while respecting the vehicle dynamics; during the traverse through the gap, the distance of the quadrotor to the edges of the gap is maximized. Furthermore, we replan the trajectory during its execution to cope with the varying uncertainty of the state estimate. We successfully evaluate and demonstrate the proposed approach in many real experiments. To the best of our knowledge, this is the first work that addresses and achieves autonomous, aggressive flight through narrow gaps using only onboard sensing and computing and without prior knowledge of the pose of the gap.

##### Abstract (translated by Google)
我们解决了在复杂环境下自主四旋翼飞行的主要挑战之一，这是通过狭窄的空白飞行。虽然之前的工作依赖于板外定位系统或者对于间隙位置和方向的准确的先验知识，但是我们仅依赖于板载感测和计算，并通过将单个板载相机的间隙检测与IMU融合来估计完整状态。由于两个原因，这个问题是有挑战性的：（i）四旋翼飞行器对间隙的不确定性随间隙距离的增加而呈二次曲线增长; （ii）四旋翼飞行器必须主动地控制其朝向间隙的方向以实现状态估计（即主动视觉）。我们通过生成一个考虑几何，动态和感知约束的轨迹来解决这个问题：在进近机动过程中，四旋翼飞行器总是面临间隙以允许状态估计，同时尊重车辆动力学;在穿过间隙的过程中，四旋翼飞行器到间隙边缘的距离被最大化。此外，我们在执行过程中重新规划了轨迹，以应对状态估计的不确定性。我们在许多真实的实验中成功地评估和证明了所提出的方法就我们所知，这是第一个通过仅使用板载传感和计算，在事先不了解差距姿态的情况下，通过狭窄差距解决和实现自主进取的飞行的工作。

##### URL
[http://arxiv.org/abs/1612.00291](http://arxiv.org/abs/1612.00291)

##### PDF
[http://arxiv.org/pdf/1612.00291](http://arxiv.org/pdf/1612.00291)

