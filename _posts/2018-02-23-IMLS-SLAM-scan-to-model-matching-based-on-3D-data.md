---
layout: post
title: "IMLS-SLAM: scan-to-model matching based on 3D data"
date: 2018-02-23 16:49:13
categories: arXiv_RO
tags: arXiv_RO Face SLAM
author: Jean-Emmanuel Deschaud
mathjax: true
---

* content
{:toc}

##### Abstract
The Simultaneous Localization And Mapping (SLAM) problem has been well studied in the robotics community, especially using mono, stereo cameras or depth sensors. 3D depth sensors, such as Velodyne LiDAR, have proved in the last 10 years to be very useful to perceive the environment in autonomous driving, but few methods exist that directly use these 3D data for odometry. We present a new low-drift SLAM algorithm based only on 3D LiDAR data. Our method relies on a scan-to-model matching framework. We first have a specific sampling strategy based on the LiDAR scans. We then define our model as the previous localized LiDAR sweeps and use the Implicit Moving Least Squares (IMLS) surface representation. We show experiments with the Velodyne HDL32 with only 0.40% drift over a 4 km acquisition without any loop closure (i.e., 16 m drift after 4 km). We tested our solution on the KITTI benchmark with a Velodyne HDL64 and ranked among the best methods (against mono, stereo and LiDAR methods) with a global drift of only 0.69%.

##### Abstract (translated by Google)
同步定位和映射（SLAM）问题在机器人领域得到了很好的研究，特别是使用单声道，立体相机或深度传感器。三维深度传感器，例如Velodyne LiDAR，在过去的10年中已被证明对于感知自动驾驶环境非常有用，但很少有直接将这些3D数据用于测距的方法。我们提出一种仅基于3D LiDAR数据的新的低漂移SLAM算法。我们的方法依赖于扫描到模型的匹配框架。我们首先有一个基于LiDAR扫描的特定采样策略。然后，我们将我们的模型定义为先前本地化的LiDAR扫描并使用隐式移动最小二乘（IMLS）表面表示。我们展示了Velodyne HDL32的实验，在没有任何环路闭合（即4公里后16米漂移）的情况下，在4公里采集时只有0.40％的漂移。我们使用Velodyne HDL64在KITTI基准测试上测试了我们的解决方案，并且在全球漂移仅为0.69％的情况下排名最佳方法（针对单声道，立体声和LiDAR方法）。

##### URL
[https://arxiv.org/abs/1802.08633](https://arxiv.org/abs/1802.08633)

##### PDF
[https://arxiv.org/pdf/1802.08633](https://arxiv.org/pdf/1802.08633)

