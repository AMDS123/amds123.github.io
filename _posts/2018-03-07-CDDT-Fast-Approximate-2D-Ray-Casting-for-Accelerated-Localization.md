---
layout: post
title: "CDDT: Fast Approximate 2D Ray Casting for Accelerated Localization"
date: 2018-03-07 19:00:34
categories: arXiv_RO
tags: arXiv_RO
author: Corey Walsh, Sertac Karaman
mathjax: true
---

* content
{:toc}

##### Abstract
Localization is an essential component for autonomous robots. A well-established localization approach combines ray casting with a particle filter, leading to a computationally expensive algorithm that is difficult to run on resource-constrained mobile robots. We present a novel data structure called the Compressed Directional Distance Transform for accelerating ray casting in two dimensional occupancy grid maps. Our approach allows online map updates, and near constant time ray casting performance for a fixed size map, in contrast with other methods which exhibit poor worst case performance. Our experimental results show that the proposed algorithm approximates the performance characteristics of reading from a three dimensional lookup table of ray cast solutions while requiring two orders of magnitude less memory and precomputation. This results in a particle filter algorithm which can maintain 2500 particles with 61 ray casts per particle at 40Hz, using a single CPU thread onboard a mobile robot.

##### Abstract (translated by Google)
本地化是自主机器人的重要组成部分。一种成熟的本地化方法将光线投射与粒子滤波器相结合，导致计算上昂贵的算法难以在资源受限的移动机器人上运行。我们提出了一种新的数据结构，称为压缩方向距离变换，用于在二维占用网格地图中加速光线投射。我们的方法允许在线地图更新，以及对于固定尺寸的地图的接近恒定时间的光线投射性能，与表现出差的最差情况性能的其他方法相比。我们的实验结果表明，所提出的算法近似于从光线投射解的三维查找表读取的性能特征，同时需要两个数量级的内存和预计算。这产生了一种粒子滤波算法，该算法使用移动机器人上的单个CPU线程，可以在40Hz下以每个粒子61个射线束来维持2500个粒子。

##### URL
[http://arxiv.org/abs/1705.01167](http://arxiv.org/abs/1705.01167)

##### PDF
[http://arxiv.org/pdf/1705.01167](http://arxiv.org/pdf/1705.01167)

