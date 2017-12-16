---
layout: post
title: "Vertical Landing for Micro Air Vehicles using Event-Based Optical Flow"
date: 2017-11-13 09:33:33
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Bas J. Pijnacker Hordijk, Kirk Y.W. Scheper, Guido C.H.E. de Croon
mathjax: true
---

* content
{:toc}

##### Abstract
Small flying robots can perform landing maneuvers using bio-inspired optical flow by maintaining a constant divergence. However, optical flow is typically estimated from frame sequences recorded by standard miniature cameras. This requires processing full images on-board, limiting the update rate of divergence measurements, and thus the speed of the control loop and the robot. Event-based cameras overcome these limitations by only measuring pixel-level brightness changes at microsecond temporal accuracy, hence providing an efficient mechanism for optical flow estimation. This paper presents, to the best of our knowledge, the first work integrating event-based optical flow estimation into the control loop of a flying robot. We extend an existing 'local plane fitting' algorithm to obtain an improved and more computationally efficient optical flow estimation method, valid for a wide range of optical flow velocities. This method is validated for real event sequences. In addition, a method for estimating the divergence from event-based optical flow is introduced, which accounts for the aperture problem. The developed algorithms are implemented in a constant divergence landing controller on-board of a quadrotor. Experiments show that, using event-based optical flow, accurate divergence estimates can be obtained over a wide range of speeds. This enables the quadrotor to perform very fast landing maneuvers.

##### Abstract (translated by Google)
小型飞行机器人可以通过保持恒定的发散性，使用生物启发式光流进行着陆演习。然而，光流量通常是由标准微型摄像机记录的帧序列估算的。这就要求在板上处理完整的图像，限制发散度测量的更新率，从而限制控制回路和机器人的速度。基于事件的摄像机通过仅以微秒的时间精度测量像素级亮度变化来克服这些限制，从而为光流估计提供有效的机制。本文提出，据我们所知，第一个工作集成基于事件的光学流量估计到飞行机器人的控制回路。我们扩展现有的“局部平面拟合”算法，以获得改进的和更有计算效率的光流估计方法，适用于宽范围的光流速度。这个方法被验证为真实的事件序列。另外，引入了用于估计与基于事件的光流发散的方法，其考虑了孔径问题。所开发的算法在四旋翼飞行器的恒定发散着陆控制器中实现。实验表明，使用基于事件的光流，可以在很宽的速度范围内获得精确的散度估计。这使得四旋翼飞行器能够执行非常快速的着陆操纵。

##### URL
[https://arxiv.org/abs/1702.00061](https://arxiv.org/abs/1702.00061)

##### PDF
[https://arxiv.org/pdf/1702.00061](https://arxiv.org/pdf/1702.00061)

