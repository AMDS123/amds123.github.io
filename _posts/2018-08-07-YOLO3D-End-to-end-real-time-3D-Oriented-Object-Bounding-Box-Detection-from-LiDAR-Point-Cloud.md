---
layout: post
title: "YOLO3D: End-to-end real-time 3D Oriented Object Bounding Box Detection from LiDAR Point Cloud"
date: 2018-08-07 13:19:24
categories: arXiv_CV
tags: arXiv_CV Object_Detection Classification Detection
author: Waleed Ali, Sherif Abdelkarim, Mohamed Zahran, Mahmoud Zidan, Ahmad El Sallab
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection and classification in 3D is a key task in Automated Driving (AD). LiDAR sensors are employed to provide the 3D point cloud reconstruction of the surrounding environment, while the task of 3D object bounding box detection in real time remains a strong algorithmic challenge. In this paper, we build on the success of the one-shot regression meta-architecture in the 2D perspective image space and extend it to generate oriented 3D object bounding boxes from LiDAR point cloud. Our main contribution is in extending the loss function of YOLO v2 to include the yaw angle, the 3D box center in Cartesian coordinates and the height of the box as a direct regression problem. This formulation enables real-time performance, which is essential for automated driving. Our results are showing promising figures on KITTI benchmark, achieving real-time performance (40 fps) on Titan X GPU.

##### Abstract (translated by Google)
3D中的对象检测和分类是自动驾驶（AD）中的关键任务。 LiDAR传感器用于提供周围环境的3D点云重建，而3D物体边界框实时检测任务仍然是一个强大的算法挑战。在本文中，我们建立了二维透视图像空间中一次性回归元架构的成功，并将其扩展为从LiDAR点云生成定向三维对象边界框。我们的主要贡献在于扩展YOLO v2的损失函数，包括偏航角，笛卡尔坐标系中的3D框中心和框的高度作为直接回归问题。该配方可实现实时性能，这对于自动驾驶至关重要。我们的结果显示了KITTI基准测试的有希望的数据，在Titan X GPU上实现了实时性能（40 fps）。

##### URL
[http://arxiv.org/abs/1808.02350](http://arxiv.org/abs/1808.02350)

##### PDF
[http://arxiv.org/pdf/1808.02350](http://arxiv.org/pdf/1808.02350)

