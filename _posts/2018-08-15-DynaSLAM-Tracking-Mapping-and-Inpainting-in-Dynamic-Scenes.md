---
layout: post
title: "DynaSLAM: Tracking, Mapping and Inpainting in Dynamic Scenes"
date: 2018-08-15 08:09:22
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Deep_Learning Detection SLAM
author: Berta Bescos, Jos&#xe9; M. F&#xe1;cil, Javier Civera, Jos&#xe9; Neira
mathjax: true
---

* content
{:toc}

##### Abstract
The assumption of scene rigidity is typical in SLAM algorithms. Such a strong assumption limits the use of most visual SLAM systems in populated real-world environments, which are the target of several relevant applications like service robotics or autonomous vehicles. In this paper we present DynaSLAM, a visual SLAM system that, building over ORB-SLAM2 [1], adds the capabilities of dynamic object detection and background inpainting. DynaSLAM is robust in dynamic scenarios for monocular, stereo and RGB-D configurations. We are capable of detecting the moving objects either by multi-view geometry, deep learning or both. Having a static map of the scene allows inpainting the frame background that has been occluded by such dynamic objects. We evaluate our system in public monocular, stereo and RGB-D datasets. We study the impact of several accuracy/speed trade-offs to assess the limits of the proposed methodology. DynaSLAM outperforms the accuracy of standard visual SLAM baselines in highly dynamic scenarios. And it also estimates a map of the static parts of the scene, which is a must for long-term applications in real-world environments.

##### Abstract (translated by Google)
场景刚度的假设在SLAM算法中是典型的。如此强烈的假设限制了大多数可视SLAM系统在人口密集的现实环境中的使用，这些环境是服务机器人或自动驾驶车辆等几个相关应用的目标。在本文中，我们介绍了DynaSLAM，一个可视SLAM系统，在ORB-SLAM2 [1]上构建，增加了动态对象检测和背景修复的功能。 DynaSLAM在单眼，立体和RGB-D配置的动态场景中非常强大。我们能够通过多视图几何，深度学习或两者来检测移动对象。具有场景的静态地图允许修复已被这些动态对象遮挡的帧背景。我们在公共单眼，立体和RGB-D数据集中评估我们的系统。我们研究了几种准确性/速度权衡的影响，以评估所提方法的局限性。 DynaSLAM在高度动态的场景中优于标准可视SLAM基线的准确性。它还估计了场景的静态部分的地图，这是在现实世界环境中长期应用的必要条件。

##### URL
[http://arxiv.org/abs/1806.05620](http://arxiv.org/abs/1806.05620)

##### PDF
[http://arxiv.org/pdf/1806.05620](http://arxiv.org/pdf/1806.05620)

