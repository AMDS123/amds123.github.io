---
layout: post
title: "On-device Scalable Image-based Localization"
date: 2018-02-10 03:23:07
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Pose_Estimation
author: Ngoc-Trung Tran, Dang-Khoa Le Tan, Anh-Dzung Doan, Thanh-Toan Do, Tuan-Anh Bui, Ngai-Man Cheung
mathjax: true
---

* content
{:toc}

##### Abstract
We present the scalable design of an entire on-device system for large-scale urban localization. The proposed design integrates compact image retrieval and 2D-3D correspondence search to estimate the camera pose in a city region of extensive coverage. Our design is GPS agnostic and does not require the network connection. The system explores the use of an abundant dataset: Google Street View (GSV). In order to overcome the resource constraints of mobile devices, we carefully optimize the system design at every stage: we use state-of-the-art image retrieval to quickly locate candidate regions and limit candidate 3D points; we propose a new hashing-based approach for fast computation of 2D-3D correspondences and new one-many RANSAC for accurate pose estimation. The experiments are conducted on benchmark datasets for 2D-3D correspondence search and on a database of over 227K Google Street View (GSV) images for the overall system. Results show that our 2D-3D correspondence search achieves state-of-the-art performance on some benchmark datasets and our system can accurately and quickly localize mobile images; the median error is less than 4 meters and the processing time is averagely less than 10s on a typical mobile device.

##### Abstract (translated by Google)
我们提出了用于大规模城市本地化的整个设备上系统的可扩展设计。所提出的设计集成了紧凑图像检索和2D-3D对应搜索以估计在广泛覆盖的城市地区中的相机姿态。我们的设计是GPS不可知的，不需要网络连接。该系统探索使用丰富的数据集：谷歌街景（GSV）。为了克服移动设备的资源限制，我们在每个阶段仔细优化系统设计：我们使用最先进的图像检索功能来快速定位候选区域并限制候选3D点;我们提出了一种新的基于哈希的方法来快速计算2D-3D对应关系，并提出了新的许多RANSAC用于准确的姿态估计。实验是在基准数据集上进行2D-3D对应性搜索以及整个系统的超过227K Google Street View（GSV）图像的数据库。结果表明，我们的2D-3D通信搜索在某些基准数据集上实现了最先进的性能，并且我们的系统可以准确快速地定位移动图像;在典型的移动设备上，中值误差小于4米，处理时间平均小于10秒。

##### URL
[http://arxiv.org/abs/1802.03510](http://arxiv.org/abs/1802.03510)

##### PDF
[http://arxiv.org/pdf/1802.03510](http://arxiv.org/pdf/1802.03510)

