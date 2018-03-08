---
layout: post
title: "Fast Cylinder and Plane Extraction from Depth Cameras for Visual Odometry"
date: 2018-03-06 19:07:45
categories: arXiv_CV
tags: arXiv_CV GAN Face Optimization
author: Pedro F. Proen&#xe7;a, Yang Gao
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents CAPE, a method to extract planes and cylinder segments from organized point clouds, which processes 640x480 depth images on a single CPU core at an average of 300 Hz, by operating on a grid of planar cells. While, compared to state-of-the-art plane extraction, the latency of CAPE is more consistent and 4-10 times faster, depending on the scene, we also demonstrate empirically that applying CAPE to visual odometry can improve trajectory estimation on scenes made of cylindrical surfaces (e.g. tunnels), whereas using a plane extraction approach that is not curve-aware deteriorates performance on these scenes. 
 To use these geometric primitives in visual odometry, we propose extending a probabilistic RGB-D odometry framework based on points, lines and planes to cylinder primitives. Following this framework, CAPE runs on fused depth maps and the parameters of cylinders are modelled probabilistically to account for uncertainty and weight accordingly the pose optimization residuals.

##### Abstract (translated by Google)
本文介绍了CAPE，一种从组织点云中提取平面和圆柱段的方法，该方法通过对平面单元网格进行操作，可在单个CPU内核上以平均300 Hz的频率处理640x480深度图像。虽然与现有技术的平面提取相比，CAPE的延迟更加一致并且速度提高了4-10倍，这取决于场景，我们还凭经验证明将CAPE应用于视觉测距可以改善场景中的轨迹估计圆柱表面（例如隧道），而使用非曲线感知的平面提取方法会降低这些场景的性能。
 为了在视觉测距中使用这些几何图元，我们提出基于点，线和平面向圆柱体基元扩展概率RGB-D测距框架。在这个框架之后，CAPE运行在融合的深度图上，并且柱面的参数被概率建模以相应地解决姿势优化残差的不确定性和重量。

##### URL
[http://arxiv.org/abs/1803.02380](http://arxiv.org/abs/1803.02380)

##### PDF
[http://arxiv.org/pdf/1803.02380](http://arxiv.org/pdf/1803.02380)

