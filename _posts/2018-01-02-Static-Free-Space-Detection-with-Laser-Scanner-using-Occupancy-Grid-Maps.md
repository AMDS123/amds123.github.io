---
layout: post
title: "Static Free Space Detection with Laser Scanner using Occupancy Grid Maps"
date: 2018-01-02 10:35:05
categories: arXiv_RO
tags: arXiv_RO Detection
author: Hesham M. Eraqi, Jens Honer, Sebastian Zuther
mathjax: true
---

* content
{:toc}

##### Abstract
Drivable free space information is vital for autonomous vehicles that have to plan evasive maneuvers in real-time. In this paper, we present a new efficient method for environmental free space detection with laser scanner based on 2D occupancy grid maps (OGM) to be used for Advanced Driving Assistance Systems (ADAS) and Collision Avoidance Systems (CAS). Firstly, we introduce an enhanced inverse sensor model tailored for high-resolution laser scanners for building OGM. It compensates the unreflected beams and deals with the ray casting to grid cells accuracy and computational effort problems. Secondly, we introduce the 'vehicle on a circle for grid maps' map alignment algorithm that allows building more accurate local maps by avoiding the computationally expensive inaccurate operations of image sub-pixel shifting and rotation. The resulted grid map is more convenient for ADAS features than existing methods, as it allows using less memory sizes, and hence, results into a better real-time performance. Thirdly, we present an algorithm to detect what we call the 'in-sight edges'. These edges guarantee modeling the free space area with a single polygon of a fixed number of vertices regardless the driving situation and map complexity. The results from real world experiments show the effectiveness of our approach.

##### Abstract (translated by Google)
可自由驾驶的空间信息对于必须实时计划回避动作的自动驾驶汽车至关重要。在本文中，我们提出了一种基于二维占用网格图（OGM）的激光扫描仪用于高级驾驶辅助系统（ADAS）和防撞系统（CAS）的环境自由空间检测的新方法。首先，我们介绍一种针对高分辨率激光扫描仪量身定制的增强型反向传感器模型，用于建立OGM。它补偿未反射的光束，并处理光线投射到网格单元的精度和计算量的问题。其次，我们引入了“网格地图上的车辆”地图对齐算法，该算法允许通过避免图像子像素移位和旋转的计算上昂贵的不准确操作来构建更准确的局部地图。结果网格地图比现有的方法更方便ADAS功能，因为它允许使用较少的内存大小，因此，导致更好的实时性能。第三，我们提出一个算法来检测我们所说的“视线边缘”。这些边保证了用固定数量的顶点的单个多边形建模自由空间区域，而不管驾驶情况和地图复杂度如何。真实世界的实验结果显示了我们方法的有效性。

##### URL
[http://arxiv.org/abs/1801.00600](http://arxiv.org/abs/1801.00600)

##### PDF
[http://arxiv.org/pdf/1801.00600](http://arxiv.org/pdf/1801.00600)

