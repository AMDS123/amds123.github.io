---
layout: post
title: "Learning monocular visual odometry with dense 3D mapping from dense 3D flow"
date: 2018-03-06 16:26:06
categories: arXiv_CV
tags: arXiv_CV Deep_Learning SLAM Relation
author: Cheng Zhao, Li Sun, Pulak Purkait, Tom Duckett, Rustam Stolkin
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces a fully deep learning approach to monocular SLAM, which can perform simultaneous localization using a neural network for learning visual odometry (L-VO) and dense 3D mapping. Dense 2D flow and a depth image are generated from monocular images by sub-networks, which are then used by a 3D flow associated layer in the L-VO network to generate dense 3D flow. Given this 3D flow, the dual-stream L-VO network can then predict the 6DOF relative pose and furthermore reconstruct the vehicle trajectory. In order to learn the correlation between motion directions, the Bivariate Gaussian modelling is employed in the loss function. The L-VO network achieves an overall performance of 2.68% for average translational error and 0.0143 deg/m for average rotational error on the KITTI odometry benchmark. Moreover, the learned depth is fully leveraged to generate a dense 3D map. As a result, an entire visual SLAM system, that is, learning monocular odometry combined with dense 3D mapping, is achieved.

##### Abstract (translated by Google)
本文介绍了单眼SLAM的全深度学习方法，该方法可以使用神经网络来学习视觉测距（L-VO）和密集的3D测绘进行同时定位。通过子网络从单眼图像生成密集的2D流和深度图像，然后由L-VO网络中的3D流相关层使用该层以生成密集的3D流。鉴于此3D流程，双流L-VO网络可以预测6DOF相对姿态并进一步重建车辆轨迹。为了学习运动方向之间的相关性，在损失函数中采用双变量高斯建模。 L-VO网络在平均平移误差方面的平均旋转误差为2.68％，KITTI odometry基准平均旋转误差为0.0143度/平方米。而且，学习深度可以充分利用来生成密集的3D地图。结果，实现了整个视觉SLAM系统，即学习单眼测距与密集3D测绘相结合。

##### URL
[http://arxiv.org/abs/1803.02286](http://arxiv.org/abs/1803.02286)

##### PDF
[http://arxiv.org/pdf/1803.02286](http://arxiv.org/pdf/1803.02286)

