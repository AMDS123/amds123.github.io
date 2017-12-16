---
layout: post
title: "LiDAR-Camera Calibration using 3D-3D Point correspondences"
date: 2017-05-27 07:57:50
categories: arXiv_CV
tags: arXiv_CV Inference
author: Ankit Dhall, Kunal Chelani, Vishnu Radhakrishnan, K.M. Krishna
mathjax: true
---

* content
{:toc}

##### Abstract
With the advent of autonomous vehicles, LiDAR and cameras have become an indispensable combination of sensors. They both provide rich and complementary data which can be used by various algorithms and machine learning to sense and make vital inferences about the surroundings. We propose a novel pipeline and experimental setup to find accurate rigid-body transformation for extrinsically calibrating a LiDAR and a camera. The pipeling uses 3D-3D point correspondences in LiDAR and camera frame and gives a closed form solution. We further show the accuracy of the estimate by fusing point clouds from two stereo cameras which align perfectly with the rotation and translation estimated by our method, confirming the accuracy of our method's estimates both mathematically and visually. Taking our idea of extrinsic LiDAR-camera calibration forward, we demonstrate how two cameras with no overlapping field-of-view can also be calibrated extrinsically using 3D point correspondences. The code has been made available as open-source software in the form of a ROS package, more information about which can be sought here: this https URL .

##### Abstract (translated by Google)
随着自主车辆的出现，LiDAR和相机已经成为传感器不可或缺的组合。它们都提供了丰富和互补的数据，可以被各种算法和机器学习用来感知和对周围环境做出重要的推论。我们提出了一种新颖的流水线和实验装置，以便为外部校准LiDAR和相机找到精确的刚体变换。管道在LiDAR和相机框架中使用3D-3D点对应关系，并给出一个封闭形式的解决方案。我们通过融合来自两个立体相机的点云来进一步显示估计的准确性，这些相机与我们的方法所估计的旋转和平移完全一致，从数学和视觉上确认了我们方法估计的准确性。将我们关于外部LiDAR相机校准的思想向前推进，我们演示了如何使用三维点对应关系实现两个没有重叠视场的相机的外部校准。该代码已经以ROS软件包的形式作为开源软件提供，有关可在此处查找的更多信息：此https URL。

##### URL
[https://arxiv.org/abs/1705.09785](https://arxiv.org/abs/1705.09785)

##### PDF
[https://arxiv.org/pdf/1705.09785](https://arxiv.org/pdf/1705.09785)

