---
layout: post
title: "Real-Time Dense Mapping for Self-driving Vehicles using Fisheye Cameras"
date: 2018-09-17 11:23:44
categories: arXiv_RO
tags: arXiv_RO Object_Detection Detection
author: Zhaopeng Cui, Lionel Heng, Ye Chuan Yeo, Andreas Geiger, Marc Pollefeys, Torsten Sattler
mathjax: true
---

* content
{:toc}

##### Abstract
We present a real-time dense geometric mapping algorithm for large-scale environments. Unlike existing methods which use pinhole cameras, our implementation is based on fisheye cameras which have larger field of view and benefit some other tasks including Visual-Inertial Odometry, localization and object detection around vehicles. Our algorithm runs on in-vehicle PCs at 15 Hz approximately, enabling vision-only 3D scene perception for self-driving vehicles. For each synchronized set of images captured by multiple cameras, we first compute a depth map for a reference camera using plane-sweeping stereo. To maintain both accuracy and efficiency, while accounting for the fact that fisheye images have a rather low resolution, we recover the depths using multiple image resolutions. We adopt the fast object detection framework YOLOv3 to remove potentially dynamic objects. At the end of the pipeline, we fuse the fisheye depth images into the truncated signed distance function (TSDF) volume to obtain a 3D map. We evaluate our method on large-scale urban datasets, and results show that our method works well even in complex environments.

##### Abstract (translated by Google)
我们提出了一种适用于大规模环境的实时密集几何映射算法。与使用针孔摄像机的现有方法不同，我们的实施基于鱼眼摄像机，其具有更大的视野并且有益于一些其他任务，包括视觉惯性测距，车辆周围的定位和物体检测。我们的算法以大约15 Hz的速度在车载PC上运行，为自动驾驶车辆实现仅视觉3D场景感知。对于由多个摄像机捕获的每个同步图像集，我们首先使用平面扫描立体声计算参考摄像机的深度图。为了保持准确性和效率，同时考虑到鱼眼图像具有相当低的分辨率，我们使用多个图像分辨率恢复深度。我们采用快速对象检测框架YOLOv3来删除潜在的动态对象。在管道的末端，我们将鱼眼深度图像融合到截断的带符号距离函数（TSDF）体积中以获得3D图。我们在大规模城市数据集上评估我们的方法，结果表明我们的方法即使在复杂的环境中也能很好地工作。

##### URL
[http://arxiv.org/abs/1809.06132](http://arxiv.org/abs/1809.06132)

##### PDF
[http://arxiv.org/pdf/1809.06132](http://arxiv.org/pdf/1809.06132)

