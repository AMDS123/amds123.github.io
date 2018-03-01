---
layout: post
title: "Multimodal Sensor-Based Semantic 3D Mapping for a Large-Scale Environment"
date: 2018-02-28 06:02:55
categories: arXiv_RO
tags: arXiv_RO Segmentation CNN Semantic_Segmentation
author: Jongmin Jeong, Tae Sung Yoon, Jin Bae Park
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic 3D mapping is one of the most important fields in robotics, and has been used in many applications, such as robot navigation, surveillance, and virtual reality. In general, semantic 3D mapping is mainly composed of 3D reconstruction and semantic segmentation. As these technologies evolve, there has been great progress in semantic 3D mapping in recent years. Furthermore, the number of robotic applications requiring semantic information in 3D mapping to perform high-level tasks has increased, and many studies on semantic 3D mapping have been published. Existing methods use a camera for both 3D reconstruction and semantic segmentation. However, this is not suitable for large-scale environments and has the disadvantage of high computational complexity. To address this problem, we propose a multimodal sensor-based semantic 3D mapping system using a 3D Lidar combined with a camera. In this study, we build a 3D map by estimating odometry based on a global positioning system (GPS) and an inertial measurement unit (IMU), and use the latest 2D convolutional neural network (CNN) for semantic segmentation. To build a semantic 3D map, we integrate the 3D map with semantic information by using coordinate transformation and Bayes' update scheme. In order to improve the semantic 3D map, we propose a 3D refinement process to correct wrongly segmented voxels and remove traces of moving vehicles in the 3D map. Through experiments on challenging sequences, we demonstrate that our method outperforms state-of-the-art methods in terms of accuracy and intersection over union (IoU). Thus, our method can be used for various applications that require semantic information in 3D map.

##### Abstract (translated by Google)
语义三维映射是机器人领域中最重要的领域之一，已经在机器人导航，监控，虚拟现实等多种应用中得到应用。一般来说，语义三维映射主要由三维重建和语义分割组成。随着这些技术的发展，近年来语义3D映射取得了很大进展。此外，需要3D映射中的语义信息来执行高级任务的机器人应用的数量已经增加，并且已经发表了关于语义3D映射的许多研究。现有方法使用相机进行三维重建和语义分割。然而，这不适合于大规模环境，并且具有计算复杂度高的缺点。为了解决这个问题，我们提出了一种基于多模式传感器的语义三维成像系统，使用三维激光雷达与相机相结合。在本研究中，我们通过基于全球定位系统（GPS）和惯性测量单元（IMU）估计测距法来构建3D地图，并使用最新的二维卷积神经网络（CNN）进行语义分割。为了构建语义3D地图，我们使用坐标变换和贝叶斯更新方案将3D地图与语义信息相结合。为了改进语义3D地图，我们提出了一种3D细化过程来纠正错误分割的体素并移除3D地图中移动车辆的痕迹。通过对具有挑战性的序列进行实验，我们证明了我们的方法在精度和联合交集（IoU）方面优于最先进的方法。因此，我们的方法可以用于需要3D地图中的语义信息的各种应用。

##### URL
[http://arxiv.org/abs/1802.10271](http://arxiv.org/abs/1802.10271)

##### PDF
[http://arxiv.org/pdf/1802.10271](http://arxiv.org/pdf/1802.10271)

