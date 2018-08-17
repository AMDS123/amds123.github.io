---
layout: post
title: "V2V-PoseNet: Voxel-to-Voxel Prediction Network for Accurate 3D Hand and Human Pose Estimation from a Single Depth Map"
date: 2018-08-16 14:55:40
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN Deep_Learning Prediction
author: Gyeongsik Moon, Ju Yong Chang, Kyoung Mu Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Most of the existing deep learning-based methods for 3D hand and human pose estimation from a single depth map are based on a common framework that takes a 2D depth map and directly regresses the 3D coordinates of keypoints, such as hand or human body joints, via 2D convolutional neural networks (CNNs). The first weakness of this approach is the presence of perspective distortion in the 2D depth map. While the depth map is intrinsically 3D data, many previous methods treat depth maps as 2D images that can distort the shape of the actual object through projection from 3D to 2D space. This compels the network to perform perspective distortion-invariant estimation. The second weakness of the conventional approach is that directly regressing 3D coordinates from a 2D image is a highly non-linear mapping, which causes difficulty in the learning procedure. To overcome these weaknesses, we firstly cast the 3D hand and human pose estimation problem from a single depth map into a voxel-to-voxel prediction that uses a 3D voxelized grid and estimates the per-voxel likelihood for each keypoint. We design our model as a 3D CNN that provides accurate estimates while running in real-time. Our system outperforms previous methods in almost all publicly available 3D hand and human pose estimation datasets and placed first in the HANDS 2017 frame-based 3D hand pose estimation challenge. The code is available in https://github.com/mks0601/V2V-PoseNet_RELEASE.

##### Abstract (translated by Google)
从单个深度图中用于3D手和人体姿势估计的大多数现有的基于深度学习的方法基于采用2D深度图并且直接回归关键点的3D坐标的共同框架，例如手或人体关节，通过2D卷积神经网络（CNN）。这种方法的第一个缺点是2D深度图中存在透视畸变。虽然深度图本质上是3D数据，但是许多先前的方法将深度图视为2D图像，其可以通过从3D到2D空间的投影来扭曲实际对象的形状。这迫使网络执行透视失真不变量估计。传统方法的第二个缺点是直接从2D图像回归3D坐标是高度非线性映射，这导致学习过程的困难。为了克服这些缺点，我们首先将3D手和人体姿势估计问题从单个深度图投射到体素到体素预测中，该预测使用3D体素化网格并估计每个关键点的每体素可能性。我们将模型设计为3D CNN，可在实时运行时提供准确的估算。我们的系统在几乎所有公开的3D手和人体姿势估计数据集中都优于以前的方法，并且首先放在HANDS 2017基于框架的3D手部姿势估计挑战中。该代码可在https://github.com/mks0601/V2V-PoseNet_RELEASE中找到。

##### URL
[http://arxiv.org/abs/1711.07399](http://arxiv.org/abs/1711.07399)

##### PDF
[http://arxiv.org/pdf/1711.07399](http://arxiv.org/pdf/1711.07399)

