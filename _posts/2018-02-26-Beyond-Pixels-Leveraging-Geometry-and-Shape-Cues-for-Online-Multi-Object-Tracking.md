---
layout: post
title: "Beyond Pixels: Leveraging Geometry and Shape Cues for Online Multi-Object Tracking"
date: 2018-02-26 13:53:16
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Object_Tracking Optimization Quantitative Detection
author: Sarthak Sharma, Junaid Ahmed Ansari, J. Krishna Murthy, K. Madhava Krishna
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces geometry and object shape and pose costs for multi-object tracking in urban driving scenarios. Using images from a monocular camera alone, we devise pairwise costs for object tracks, based on several 3D cues such as object pose, shape, and motion. The proposed costs are agnostic to the data association method and can be incorporated into any optimization framework to output the pairwise data associations. These costs are easy to implement, can be computed in real-time, and complement each other to account for possible errors in a tracking-by-detection framework. We perform an extensive analysis of the designed costs and empirically demonstrate consistent improvement over the state-of-the-art under varying conditions that employ a range of object detectors, exhibit a variety in camera and object motions, and, more importantly, are not reliant on the choice of the association framework. We also show that, by using the simplest of associations frameworks (two-frame Hungarian assignment), we surpass the state-of-the-art in multi-object-tracking on road scenes. More qualitative and quantitative results can be found at the following URL: https://junaidcs032.github.io/Geometry_ObjectShape_MOT/.

##### Abstract (translated by Google)
本文介绍了城市驾驶场景中的多物体跟踪的几何形状和物体形状以及姿态成本。根据单眼相机单独使用的图像，我们根据几个3D提示（如对象姿势，形状和运动）为对象轨迹设计成对成本。建议的成本与数据关联方法无关，可以并入任何优化框架以输出成对数据关联。这些成本很容易实现，可以实时计算，并相互补充以解决逐个检测框架中可能出现的错误。我们对设计成本进行了广泛的分析，并凭借在各种条件下采用一系列物体探测器，展现各种相机和物体运动，以及更重要的是不依赖于关联框架的选择。我们还表明，通过使用最简单的关联框架（两帧匈牙利分配），我们超越了道路场景多目标跟踪的最新技术。更多定性和定量结果可以在以下网址找到：https://junaidcs032.github.io/Geometry_ObjectShape_MOT/。

##### URL
[http://arxiv.org/abs/1802.09298](http://arxiv.org/abs/1802.09298)

##### PDF
[http://arxiv.org/pdf/1802.09298](http://arxiv.org/pdf/1802.09298)

