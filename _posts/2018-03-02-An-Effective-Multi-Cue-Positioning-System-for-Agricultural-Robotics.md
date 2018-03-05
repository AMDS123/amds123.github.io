---
layout: post
title: "An Effective Multi-Cue Positioning System for Agricultural Robotics"
date: 2018-03-02 17:18:13
categories: arXiv_RO
tags: arXiv_RO Pose_Estimation Optimization
author: Marco Imperoli, Ciro Potena, Daniele Nardi, Giorgio Grisetti, Alberto Pretto
mathjax: true
---

* content
{:toc}

##### Abstract
The self-localization capability is a crucial component for Unmanned Ground Vehicles (UGV) in farming applications. Approaches based solely on visual information or on low-cost GPS are easily prone to fail in such scenarios. In this paper, we present a robust and accurate 3D global pose estimation framework, designed to take full advantage of heterogeneous sensory data. By modeling the pose estimation problem as a pose graph optimization, our approach simultaneously mitigates the cumulative drift introduced by motion estimation systems (wheel odometry, visual odometry, ...), and the noise introduced by the raw GPS readings. Along with a suitable motion model, our system also integrates two additional types of constraints: (i) a Digital Elevation Model (DEM) and (ii) a Markov Random Field (MRF) assumption. We demonstrate how using these additional cues substantially reduces the error along the altitude axis, and this benefit spreads to the other components of the state. We report exhaustive experiments combining several sensor setups, showing improvements from 37% to 76% of the localization accuracy with respect to using only the GPS. We also show that our approach provides accurate results even if the GPS temporarily change positioning mode. We released our C++ open-source implementation and two challenging datasets with their relative ground truth.

##### Abstract (translated by Google)
自我定位能力是农业应用中无人地面车辆（UGV）的重要组成部分。仅基于视觉信息或低成本GPS的方法很容易在这种情况下发生故障。在本文中，我们提出了一个强大而准确的3D全局姿态估计框架，旨在充分利用异构感官数据。通过将姿态估计问题建模为姿态图优化，我们的方法同时减轻了由运动估计系统（轮距测量，视觉测距，...）引入的累积漂移以及原始GPS读数引入的噪声。除了合适的运动模型外，我们的系统还集成了两种其他类型的约束：（i）数字高程模型（DEM）和（ii）马尔可夫随机场（MRF）假设。我们演示了如何使用这些附加线索大幅度降低沿高度轴线的误差，并将此优势扩展到该州的其他组成部分。我们报告了结合多种传感器设置的详尽实验，相对于仅使用GPS，其定位精度从37％提高到76％。我们还表明，即使GPS暂时改变定位模式，我们的方法也能提供准确的结果。我们发布了我们的C ++开源实现和两个具有挑战性的数据集，并提供了相关的基本事实。

##### URL
[http://arxiv.org/abs/1803.00954](http://arxiv.org/abs/1803.00954)

##### PDF
[http://arxiv.org/pdf/1803.00954](http://arxiv.org/pdf/1803.00954)

