---
layout: post
title: "A LiDAR Point Cloud Generator: from a Virtual World to Autonomous Driving"
date: 2018-03-31 01:32:11
categories: arXiv_CV
tags: arXiv_CV Segmentation Deep_Learning
author: Xiangyu Yue, Bichen Wu, Sanjit A. Seshia, Kurt Keutzer, Alberto L. Sangiovanni-Vincentelli
mathjax: true
---

* content
{:toc}

##### Abstract
3D LiDAR scanners are playing an increasingly important role in autonomous driving as they can generate depth information of the environment. However, creating large 3D LiDAR point cloud datasets with point-level labels requires a significant amount of manual annotation. This jeopardizes the efficient development of supervised deep learning algorithms which are often data-hungry. We present a framework to rapidly create point clouds with accurate point-level labels from a computer game. The framework supports data collection from both auto-driving scenes and user-configured scenes. Point clouds from auto-driving scenes can be used as training data for deep learning algorithms, while point clouds from user-configured scenes can be used to systematically test the vulnerability of a neural network, and use the falsifying examples to make the neural network more robust through retraining. In addition, the scene images can be captured simultaneously in order for sensor fusion tasks, with a method proposed to do automatic calibration between the point clouds and captured scene images. We show a significant improvement in accuracy (+9%) in point cloud segmentation by augmenting the training dataset with the generated synthesized data. Our experiments also show by testing and retraining the network using point clouds from user-configured scenes, the weakness/blind spots of the neural network can be fixed.

##### Abstract (translated by Google)
3D LiDAR扫描仪在自动驾驶中扮演着越来越重要的角色，因为他们可以生成环境的深度信息。但是，创建具有点级标签的大型3D LiDAR点云数据集需要大量的手动注释。这危害了有监督的深度学习算法的高效发展，这些算法通常是数据饥饿的。我们提出了一个框架，可以通过计算机游戏快速创建具有精确点级标签的点云。该框架支持从自动驾驶场景和用户配置场景收集数据。自动驾驶场景中的点云可用作深度学习算法的训练数据，而来自用户配置场景的点云可用于系统地测试神经网络的脆弱性，并使用伪造示例使神经网络更加完善通过再培训强劲。另外，为了进行传感器融合任务，可以同时捕获场景图像，其中提出了一种用于在点云与捕获的场景图像之间进行自动校准的方法。我们通过用生成的合成数据增加训练数据集显示了点云分割准确度（+ 9％）的显着提高。我们的实验还通过使用用户配置场景中的点云对网络进行测试和再训练，可以确定神经网络的弱点/盲点。

##### URL
[http://arxiv.org/abs/1804.00103](http://arxiv.org/abs/1804.00103)

##### PDF
[http://arxiv.org/pdf/1804.00103](http://arxiv.org/pdf/1804.00103)

