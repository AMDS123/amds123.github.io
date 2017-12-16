---
layout: post
title: "Monocular Visual Odometry for an Unmanned Sea-Surface Vehicle"
date: 2017-07-19 10:39:29
categories: arXiv_CV
tags: arXiv_CV Face SLAM
author: George Terzakis, Riccardo Polvara, Sanjay Sharma, Phil Culverhouse, Robert Sutton
mathjax: true
---

* content
{:toc}

##### Abstract
We tackle the problem of localizing an autonomous sea-surface vehicle in river estuarine areas using monocular camera and angular velocity input from an inertial sensor. Our method is challenged by two prominent drawbacks associated with the environment, which are typically not present in standard visual simultaneous localization and mapping (SLAM) applications on land (or air): a) Scene depth varies significantly (from a few meters to several kilometers) and, b) In conjunction to the latter, there exists no ground plane to provide features with enough disparity based on which to reliably detect motion. To that end, we use the IMU orientation feedback in order to re-cast the problem of visual localization without the mapping component, although the map can be implicitly obtained from the camera pose estimates. We find that our method produces reliable odometry estimates for trajectories several hundred meters long in the water. To compare the visual odometry estimates with GPS based ground truth, we interpolate the trajectory with splines on a common parameter and obtain position error in meters recovering an optimal affine transformation between the two splines.

##### Abstract (translated by Google)
我们利用单目摄像机和惯性传感器的角速度输入来解决在河口地区定位自主海面车辆的问题。我们的方法受到与环境有关的两个显着缺点的挑战，这些缺点通常不存在于陆地（或空中）的标准视觉同时定位和映射（SLAM）应用中：a）场景深度变化显着（从几米到几公里）和b）与后者相结合，不存在提供具有足够差异的特征以便可靠地检测运动的地平面。为此，我们使用IMU方向反馈来重新构造没有映射分量的视觉定位问题，虽然地图可以隐含地从相机姿态估计中获得。我们发现，我们的方法可以为几百米长的水上航迹提供可靠的测距估计。为了将视觉测距估计与基于GPS的地面实况进行比较，我们在具有共同参数的样条上插入轨迹，并以米为单位获得位置误差，以恢复两个样条之间的最佳仿射变换。

##### URL
[https://arxiv.org/abs/1707.04444](https://arxiv.org/abs/1707.04444)

##### PDF
[https://arxiv.org/pdf/1707.04444](https://arxiv.org/pdf/1707.04444)

