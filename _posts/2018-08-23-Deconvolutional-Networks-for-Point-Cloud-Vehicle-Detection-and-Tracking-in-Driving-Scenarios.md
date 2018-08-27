---
layout: post
title: "Deconvolutional Networks for Point-Cloud Vehicle Detection and Tracking in Driving Scenarios"
date: 2018-08-23 20:30:04
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking CNN Object_Tracking Classification Deep_Learning Detection
author: Victor Vaquero, Ivan del Pino, Francesc Moreno-Noguer, Joan Sol&#xe0;, Alberto Sanfeliu, Juan Andrade-Cetto
mathjax: true
---

* content
{:toc}

##### Abstract
Vehicle detection and tracking is a core ingredient for developing autonomous driving applications in urban scenarios. Recent image-based Deep Learning (DL) techniques are obtaining breakthrough results in these perceptive tasks. However, DL research has not yet advanced much towards processing 3D point clouds from lidar range-finders. These sensors are very common in autonomous vehicles since, despite not providing as semantically rich information as images, their performance is more robust under harsh weather conditions than vision sensors. In this paper we present a full vehicle detection and tracking system that works with 3D lidar information only. Our detection step uses a Convolutional Neural Network (CNN) that receives as input a featured representation of the 3D information provided by a Velodyne HDL-64 sensor and returns a per-point classification of whether it belongs to a vehicle or not. The classified point cloud is then geometrically processed to generate observations for a multi-object tracking system implemented via a number of Multi-Hypothesis Extended Kalman Filters (MH-EKF) that estimate the position and velocity of the surrounding vehicles. The system is thoroughly evaluated on the KITTI tracking dataset, and we show the performance boost provided by our CNN-based vehicle detector over a standard geometric approach. Our lidar-based approach uses about a 4% of the data needed for an image-based detector with similarly competitive results.

##### Abstract (translated by Google)
车辆检测和跟踪是在城市场景中开发自动驾驶应用的核心要素。最近基于图像的深度学习（DL）技术正在这些敏锐的任务中获得突破性的成果。然而，DL研究尚未在激光雷达测距仪处理3D点云方面取得多大进展。这些传感器在自动驾驶车辆中非常常见，因为尽管没有像图像那样提供语义丰富的信息，但它们在恶劣天气条件下的性能比视觉传感器更强。在本文中，我们提出了一个完整的车辆检测和跟踪系统，仅使用3D激光雷达信息。我们的检测步骤使用卷积神经网络（CNN），其接收由Velodyne HDL-64传感器提供的3D信息的特征表示作为输入，并返回其是否属于车辆的每点分类。然后对分类的点云进行几何处理，以生成通过多个假设扩展卡尔曼滤波器（MH-EKF）实现的多目标跟踪系统的观测，该多假设扩展卡尔曼滤波器估计周围车辆的位置和速度。该系统在KITTI跟踪数据集上进行了全面评估，我们展示了基于CNN的车辆探测器在标准几何方法上提供的性能提升。我们基于激光雷达的方法使用基于图像的探测器所需数据的大约4％，具有相似的竞争结果。

##### URL
[http://arxiv.org/abs/1808.07935](http://arxiv.org/abs/1808.07935)

##### PDF
[http://arxiv.org/pdf/1808.07935](http://arxiv.org/pdf/1808.07935)

