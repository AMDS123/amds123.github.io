---
layout: post
title: "Unsupervised Adversarial Learning of 3D Human Pose from 2D Joint Locations"
date: 2018-03-22 06:41:23
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Pose_Estimation Detection
author: Yasunori Kudo, Keisuke Ogaki, Yusuke Matsui, Yuri Odagiri
mathjax: true
---

* content
{:toc}

##### Abstract
The task of three-dimensional (3D) human pose estimation from a single image can be divided into two parts: (1) Two-dimensional (2D) human joint detection from the image and (2) estimating a 3D pose from the 2D joints. Herein, we focus on the second part, i.e., a 3D pose estimation from 2D joint locations. The problem with existing methods is that they require either (1) a 3D pose dataset or (2) 2D joint locations in consecutive frames taken from a video sequence. We aim to solve these problems. For the first time, we propose a method that learns a 3D human pose without any 3D datasets. Our method can predict a 3D pose from 2D joint locations in a single image. Our system is based on the generative adversarial networks, and the networks are trained in an unsupervised manner. Our primary idea is that, if the network can predict a 3D human pose correctly, the 3D pose that is projected onto a 2D plane should not collapse even if it is rotated perpendicularly. We evaluated the performance of our method using Human3.6M and the MPII dataset and showed that our network can predict a 3D pose well even if the 3D dataset is not available during training.

##### Abstract (translated by Google)
从单个图像中进行三维（3D）人体姿态估计的任务可以被分成两部分：（1）从图像中的二维（2D）人体关节检测和（2）根据二维关节估计三维姿态。这里，我们关注第二部分，即，来自2D关节位置的3D姿态估计。现有方法存在的问题是它们需要（1）从视频序列中获取的连续帧中的3D姿态数据集或（2）2D关节位置。我们旨在解决这些问题。我们第一次提出一种在没有任何3D数据集的情况下学习3D人体姿势的方法。我们的方法可以预测单个图像中2D关节位置的3D姿态。我们的系统基于生成的敌对网络，网络以无监督的方式进行训练。我们的主要想法是，如果网络可以正确预测3D人体姿态，则投射到2D平面上的3D姿态即使垂直旋转也不应该塌陷。我们使用Human3.6M和MPII数据集评估了我们方法的性能，结果表明我们的网络可以很好地预测3D姿态，即使3D数据集在训练期间不可用。

##### URL
[https://arxiv.org/abs/1803.08244](https://arxiv.org/abs/1803.08244)

##### PDF
[https://arxiv.org/pdf/1803.08244](https://arxiv.org/pdf/1803.08244)

