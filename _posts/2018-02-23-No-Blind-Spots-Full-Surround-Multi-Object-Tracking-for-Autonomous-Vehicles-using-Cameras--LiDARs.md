---
layout: post
title: "No Blind Spots: Full-Surround Multi-Object Tracking for Autonomous Vehicles using Cameras & LiDARs"
date: 2018-02-23 22:48:29
categories: arXiv_CV
tags: arXiv_CV Tracking Object_Tracking Detection
author: Akshay Rangesh, Mohan M. Trivedi
mathjax: true
---

* content
{:toc}

##### Abstract
Online multi-object tracking (MOT) is extremely important for high-level spatial reasoning and path planning for autonomous and highly-automated vehicles. In this paper, we present a modular framework for tracking multiple objects (vehicles), capable of accepting object proposals from different sensor modalities (vision and range) and a variable number of sensors, to produce continuous object tracks. This work is inspired by traditional tracking-by-detection approaches in computer vision, with some key differences - First, we track objects across multiple cameras and across different sensor modalities. This is done by fusing object proposals across sensors accurately and efficiently. Second, the objects of interest (targets) are tracked directly in the real world. This is a departure from traditional techniques where objects are simply tracked in the image plane. Doing so allows the tracks to be readily used by an autonomous agent for navigation and related tasks. 
 To verify the effectiveness of our approach, we test it on real world highway data collected from a heavily sensorized testbed capable of capturing full-surround information. We demonstrate that our framework is well-suited to track objects through entire maneuvers around the ego-vehicle, some of which take more than a few minutes to complete. We also leverage the modularity of our approach by comparing the effects of including/excluding different sensors, changing the total number of sensors, and the quality of object proposals on the final tracking result.

##### Abstract (translated by Google)
在线多目标跟踪（MOT）对于自主和高度自动化车辆的高级空间推理和路径规划非常重要。在本文中，我们提出了一个用于跟踪多个物体（车辆）的模块化框架，能够接受来自不同传感器模态（视觉和范围）以及可变数量传感器的物体建议，以生成连续的物体轨迹。这项工作受计算机视觉中传统的逐行检测方法的启发，主要区别在于：首先，我们跟踪多台摄像机和不同传感器模式下的物体。这是通过精确有效地融合传感器之间的对象提议来完成的。其次，感兴趣的对象（目标）直接在现实世界中跟踪。这与传统技术不同，在传统技术中，只需在图像平面中跟踪对象。这样做可让轨道容易被自主代理用于导航和相关任务。
 为了验证我们方法的有效性，我们测试了从能够捕获全环绕信息的高度感应测试平台收集的真实世界公路数据。我们证明我们的框架非常适合通过整个自我车辆的机动追踪物体，其中一些需要超过几分钟才能完成。我们还通过比较包含/排除不同传感器，改变传感器总数以及最终跟踪结果上的对象建议质量的影响，利用我们方法的模块化。

##### URL
[http://arxiv.org/abs/1802.08755](http://arxiv.org/abs/1802.08755)

##### PDF
[http://arxiv.org/pdf/1802.08755](http://arxiv.org/pdf/1802.08755)

