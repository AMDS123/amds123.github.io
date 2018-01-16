---
layout: post
title: "Controlling a Robotic Stereo Camera Under Image Quantization Noise"
date: 2018-01-14 03:31:19
categories: arXiv_RO
tags: arXiv_RO
author: Charles Freundlich, Yan Zhang, Alex Zihao Zhu, Philippos Mordohai, Michael M. Zavlanos
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we address the problem of controlling a mobile stereo camera under image quantization noise. Assuming that a pair of images of a set of targets is available, the camera moves through a sequence of Next-Best-Views (NBVs), i.e., a sequence of views that minimize the trace of the targets' cumulative state covariance, constructed using a realistic model of the stereo rig that captures image quantization noise and a Kalman Filter (KF) that fuses the observation history with new information. The proposed algorithm decomposes control into two stages: first the NBV is computed in the camera relative coordinates, and then the camera moves to realize this view in the fixed global coordinate frame. This decomposition allows the camera to drive to a new pose that effectively realizes the NBV in camera coordinates while satisfying Field-of-View constraints in global coordinates, a task that is particularly challenging using complex sensing models. We provide simulations and real experiments that illustrate the ability of the proposed mobile camera system to accurately localize sets of targets. We also propose a novel data-driven technique to characterize unmodeled uncertainty, such as calibration errors, at the pixel level and show that this method ensures stability of the KF.

##### Abstract (translated by Google)
在本文中，我们解决了在图像量化噪声下控制移动立体相机的问题。假设有一组目标的图像可用，摄像机通过一系列Next-Best-Views（NBV），即一系列使目标的累积状态协方差跟踪最小的视图序列，捕捉图像量化噪声的立体声装置的逼真模型和用新信息融合观察历史的卡尔曼滤波器（KF）。该算法将控制分解为两个阶段：首先在摄像机相对坐标中计算NBV，然后摄像机在固定的全局坐标系中移动实现该视图。这种分解使相机能够驾驶到一个新的姿态，有效地实现相机坐标中的NBV，同时满足全局坐标中的视场约束，这是使用复杂的感测模型特别具有挑战性的任务。我们提供模拟和真实实验，说明所提出的移动照相机系统能够准确地定位各组目标。我们还提出了一种新的数据驱动技术来表征未建模的不确定性，如像素级的校准误差，并表明这种方法确保了KF的稳定性。

##### URL
[http://arxiv.org/abs/1706.01966](http://arxiv.org/abs/1706.01966)

##### PDF
[http://arxiv.org/pdf/1706.01966](http://arxiv.org/pdf/1706.01966)

