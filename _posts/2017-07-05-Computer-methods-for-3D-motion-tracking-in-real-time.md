---
layout: post
title: "Computer methods for 3D motion tracking in real-time"
date: 2017-07-05 10:07:19
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Tracking Optimization
author: Bogusław Rymut
mathjax: true
---

* content
{:toc}

##### Abstract
This thesis is devoted to marker-less 3D human motion tracking in calibrated and synchronized multicamera systems. Pose estimation is based on a 3D model, which is transformed into the image plane and then rendered. Owing to elaborated techniques the tracking of the full body has been achieved in real-time via dynamic optimization or dynamic Bayesian filtering. The objective function of a particle swarm optimization algorithm and the observation model of a particle filter are based on matching between the rendered 3D models in the required poses and image features representing the extracted person. In such an approach the main part of the computational overload is associated with the rendering of 3D models in hypothetical poses as well as determination of value of objective function. Effective methods for rendering of 3D models in real-time with support of OpenGL as well as parallel methods for determining the objective function on the GPU were developed. The elaborated solutions permit 3D tracking of full body motion in real-time.

##### Abstract (translated by Google)
本论文致力于在校准和同步多光子系统中进行无标记3D人体运动跟踪。姿态估计是基于一个三维模型，它被转换成图像平面，然后渲染。由于精心设计的技术，通过动态优化或动态贝叶斯过滤实时追踪全身。粒子群优化算法的目标函数和粒子滤波器的观测模型是基于所需姿态中呈现的3D模型与表示所提取人物的图像特征之间的匹配。在这种方法中，计算过载的主要部分与假设姿势下的3D模型的渲染以及目标函数的值的确定相关联。开发了支持OpenGL的实时渲染三维模型的有效方法以及确定GPU目标函数的并行方法。精心设计的解决方案可以实时跟踪全身运动。

##### URL
[https://arxiv.org/abs/1707.01745](https://arxiv.org/abs/1707.01745)

##### PDF
[https://arxiv.org/pdf/1707.01745](https://arxiv.org/pdf/1707.01745)

