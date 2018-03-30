---
layout: post
title: "3D Reconstruction & Assessment Framework based on affordable 2D Lidar"
date: 2018-03-24 22:09:08
categories: arXiv_RO
tags: arXiv_RO SLAM
author: Xueyang Kang, Yinglong Fen
mathjax: true
---

* content
{:toc}

##### Abstract
Lidar is extensively used in the industry and mass market, due to its measurement accuracy and insensitivity to brightness compared to cameras. It is applied onto a broad range of applications, like geodetic engineering, self driving cars or virtual reality. But the 3D Lidar with multiple beams is very expensive, and the massive measurements data can not be fully processed timely. The purpose of this paper is to explore the possibility of using cheap 2D Lidar off-the-shelf, for 3D reconstruction with high accuracy. The 3D map quality is evaluated by our proposed metrics in this paper lastly. The 3D map is constructed in two ways, one way in which the scan is performed at known positions. The other way, in which the 2D Lidar for mapping and the localization part are placed on a trolley, then the trolley is pushed on the ground. The generated maps by these approaches are converted to octomaps before the evaluation. The similarity and difference between the two maps will be evaluated by these metrics in a normalized value ranging from 0 to 1. The established mapping system is composed of several modular components. A 3D bracket is designed for assembling the Lidar with a long range, the driver and the motor. A cover platform is designed for the imu and Lidar with a shorter range but high accuracy, which will be used to implement 2D SLAM. The software is stacked up in different packages on ROS.

##### Abstract (translated by Google)
激光雷达由于其测量精度和相对于相机的亮度不敏感而广泛用于工业和大众市场。它应用于广泛的应用领域，如大地测量工程，自动驾驶汽车或虚拟现实。但是具有多个光束的3D激光雷达非常昂贵，并且不能及时处理大量的测量数据。本文的目的是探索使用便宜的二维激光雷达现成的可能性，以高精度进行三维重建。最后，我们在本文中通过我们提出的度量来评估3D地图质量。 3D地图以两种方式构建，其中一种方式是在已知位置执行扫描。另一种方式是将二维激光雷达映射和定位部分放在手推车上，然后将手推车推到地面上。在评估之前，通过这些方法生成的地图会转换为八路图。这两个地图之间的相似性和差异性将通过这些度量以0到1的归一化值进行评估。建立的地图系统由几个模块化组件组成。 3D支架设计用于组装远程激光雷达，驱动器和电机。为imu和激光雷达设计了一个覆盖平台，它具有更短的射程和更高的精度，将用于实现2D SLAM。该软件堆叠在ROS上的不同软件包中。

##### URL
[https://arxiv.org/abs/1803.09167](https://arxiv.org/abs/1803.09167)

##### PDF
[https://arxiv.org/pdf/1803.09167](https://arxiv.org/pdf/1803.09167)

