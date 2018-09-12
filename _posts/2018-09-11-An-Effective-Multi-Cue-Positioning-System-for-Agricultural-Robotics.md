---
layout: post
title: "An Effective Multi-Cue Positioning System for Agricultural Robotics"
date: 2018-09-11 12:09:35
categories: arXiv_RO
tags: arXiv_RO Pose_Estimation Optimization
author: Marco Imperoli, Ciro Potena, Daniele Nardi, Giorgio Grisetti, Alberto Pretto
mathjax: true
---

* content
{:toc}

##### Abstract
The self-localization capability is a crucial component for Unmanned Ground Vehicles (UGV) in farming applications. Approaches based solely on visual cues or on low-cost GPS are easily prone to fail in such scenarios. In this paper, we present a robust and accurate 3D global pose estimation framework, designed to take full advantage of heterogeneous sensory data. By modeling the pose estimation problem as a pose graph optimization, our approach simultaneously mitigates the cumulative drift introduced by motion estimation systems (wheel odometry, visual odometry, ...), and the noise introduced by raw GPS readings. Along with a suitable motion model, our system also integrates two additional types of constraints: (i) a Digital Elevation Model and (ii) a Markov Random Field assumption. We demonstrate how using these additional cues substantially reduces the error along the altitude axis and, moreover, how this benefit spreads to the other components of the state. We report exhaustive experiments combining several sensor setups, showing accuracy improvements ranging from 37% to 76% with respect to the exclusive use of a GPS sensor. We show that our approach provides accurate results even if the GPS unexpectedly changes positioning mode. The code of our system along with the acquired datasets are released with this paper.

##### Abstract (translated by Google)
自定位能力是无人地面车辆（UGV）在农业应用中的关键组成部分。在这种情况下，仅基于视觉提示或低成本GPS的方法很容易失败。在本文中，我们提出了一个强大而准确的3D全局姿态估计框架，旨在充分利用异构传感数据。通过将姿势估计问题建模为姿势图优化，我们的方法同时减轻了运动估计系统（车轮测距法，视觉测距法......）引入的累积漂移以及原始GPS读数引入的噪声。除了合适的运动模型，我们的系统还集成了两种附加类型的约束：（i）数字高程模型和（ii）马尔可夫随机场假设。我们演示了如何使用这些额外的线索大大减少了沿高度轴的误差，此外，这种利益如何扩散到该州的其他组成部分。我们报告了结合多种传感器设置的详尽实验，相对于GPS传感器的独家使用，精度提高了37％至76％。我们表明，即使GPS意外地改变定位模式，我们的方法也能提供准确的结果。本文将发布我们系统的代码以及获取的数据集。

##### URL
[http://arxiv.org/abs/1803.00954](http://arxiv.org/abs/1803.00954)

##### PDF
[http://arxiv.org/pdf/1803.00954](http://arxiv.org/pdf/1803.00954)

