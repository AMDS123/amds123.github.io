---
layout: post
title: "Real-time on-board obstacle avoidance for UAVs based on embedded stereo vision"
date: 2018-07-17 08:17:10
categories: arXiv_CV
tags: arXiv_CV Semi_Global Optimization Detection
author: Boitumelo Ruf, Sebastian Monka, Matthias Kollmann, Michael Grinberg
mathjax: true
---

* content
{:toc}

##### Abstract
In order to improve usability and safety, modern unmanned aerial vehicles (UAVs) are equipped with sensors to monitor the environment, such as laser-scanners and cameras. One important aspect in this monitoring process is to detect obstacles in the flight path in order to avoid collisions. Since a large number of consumer UAVs suffer from tight weight and power constraints, our work focuses on obstacle avoidance based on a lightweight stereo camera setup. We use disparity maps, which are computed from the camera images, to locate obstacles and to automatically steer the UAV around them. For disparity map computation we optimize the well-known semi-global matching (SGM) approach for the deployment on an embedded FPGA. The disparity maps are then converted into simpler representations, the so called U-/V-Maps, which are used for obstacle detection. Obstacle avoidance is based on a reactive approach which finds the shortest path around the obstacles as soon as they have a critical distance to the UAV. One of the fundamental goals of our work was the reduction of development costs by closing the gap between application development and hardware optimization. Hence, we aimed at using high-level synthesis (HLS) for porting our algorithms, which are written in C/C++, to the embedded FPGA. We evaluated our implementation of the disparity estimation on the KITTI Stereo 2015 benchmark. The integrity of the overall realtime reactive obstacle avoidance algorithm has been evaluated by using Hardware-in-the-Loop testing in conjunction with two flight simulators.

##### Abstract (translated by Google)
为了提高可用性和安全性，现代无人机（UAV）配备了用于监控环境的传感器，例如激光扫描仪和照相机。该监测过程的一个重要方面是检测飞行路径中的障碍物以避免碰撞。由于大量消费者无人机受到严格的重量和功率限制，我们的工作重点是基于轻量级立体摄像机设置的避障。我们使用从相机图像计算的视差图来定位障碍物并自动地控制它们周围的无人机。对于视差图计算，我们优化了众所周知的半全局匹配（SGM）方法，以便在嵌入式FPGA上进行部署。然后将视差图转换成更简单的表示，即所谓的U- / V-地图，其用于障碍物检测。避障是基于一种被动方法，一旦它们与无人机有一个临界距离，它就能找到障碍物周围的最短路径。我们工作的基本目标之一是通过缩小应用程序开发和硬件优化之间的差距来降低开发成本。因此，我们的目标是使用高级综合（HLS）将我们的算法（用C / C ++编写）移植到嵌入式FPGA中。我们评估了KITTI Stereo 2015基准测试中差异估计的实施情况。通过将硬件在环测试与两个飞行模拟器结合使用来评估整体实时反应式避障算法的完整性。

##### URL
[http://arxiv.org/abs/1807.06271](http://arxiv.org/abs/1807.06271)

##### PDF
[http://arxiv.org/pdf/1807.06271](http://arxiv.org/pdf/1807.06271)

