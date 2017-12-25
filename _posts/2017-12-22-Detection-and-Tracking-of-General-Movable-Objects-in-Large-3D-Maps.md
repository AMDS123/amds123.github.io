---
layout: post
title: "Detection and Tracking of General Movable Objects in Large 3D Maps"
date: 2017-12-22 11:53:52
categories: arXiv_CV
tags: arXiv_CV Tracking Detection
author: Nils Bore, Johan Ekekrantz, Patric Jensfelt, John Folkesson
mathjax: true
---

* content
{:toc}

##### Abstract
This paper studies the problem of detection and tracking of general objects with long-term dynamics, observed by a mobile robot moving in a large environment. A key problem is that due to the environment scale, it can only observe a subset of the objects at any given time. Since some time passes between observations of objects in different places, the objects might be moved when the robot is not there. We propose a model for this movement in which the objects typically only move locally, but with some small probability they jump longer distances, through what we call global motion. For filtering, we decompose the posterior over local and global movements into two linked processes. The posterior over the global movements and measurement associations is sampled, while we track the local movement analytically using Kalman filters. This novel filter is evaluated on point cloud data gathered autonomously by a mobile robot over an extended period of time. We show that tracking jumping objects is feasible, and that the proposed probabilistic treatment outperforms previous methods when applied to real world data. The key to efficient probabilistic tracking in this scenario is focused sampling of the object posteriors.

##### Abstract (translated by Google)
本文研究移动机器人在大环境中移动所观察到的具有长期动态特性的一般物体的检测和跟踪问题。一个关键的问题是，由于环境的规模，它只能在任何给定的时间观察对象的一个​​子集。由于在不同地点观察物体之间经过一段时间，当机器人不在那里时，物体可能会移动。我们为这个运动提出了一个模型，在这个模型中，物体通常只在局部移动，但是有一些小概率，他们通过我们所说的全局运动跳得更远。为了过滤，我们将局部和全局运动的后验分解成两个连接的过程。全球运动和测量协会的后验是采样，而我们使用卡尔曼滤波器分析跟踪局部运动。这种新颖的过滤器是在移动机器人长时间自主收集的点云数据上评估的。我们表明跟踪跳跃对象是可行的，并且所提出的概率处理在应用于现实世界数据时优于先前的方法。在这种情况下高效的概率跟踪的关键是对对象后验的重点抽样。

##### URL
[https://arxiv.org/abs/1712.08409](https://arxiv.org/abs/1712.08409)

##### PDF
[https://arxiv.org/pdf/1712.08409](https://arxiv.org/pdf/1712.08409)

