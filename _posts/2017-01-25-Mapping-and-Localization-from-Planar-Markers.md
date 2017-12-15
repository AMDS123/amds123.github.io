---
layout: post
title: "Mapping and Localization from Planar Markers"
date: 2017-01-25 08:33:27
categories: arXiv_CV
tags: arXiv_CV Object_Detection Optimization Detection SLAM
author: Rafael Muñoz-Salinas, Manuel J. Marín-Jimenez, Enrique Yeguas-Bolivar, Rafael Medina-Carnicer
mathjax: true
---

* content
{:toc}

##### Abstract
Squared planar markers are a popular tool for fast, accurate and robust camera localization, but its use is frequently limited to a single marker, or at most, to a small set of them for which their relative pose is known beforehand. Mapping and localization from a large set of planar markers is yet a scarcely treated problem in favour of keypoint-based approaches. However, while keypoint detectors are not robust to rapid motion, large changes in viewpoint, or significant changes in appearance, fiducial markers can be robustly detected under a wider range of conditions. This paper proposes a novel method to simultaneously solve the problems of mapping and localization from a set of squared planar markers. First, a quiver of pairwise relative marker poses is created, from which an initial pose graph is obtained. The pose graph may contain small pairwise pose errors, that when propagated, leads to large errors. Thus, we distribute the rotational and translational error along the basis cycles of the graph so as to obtain a corrected pose graph. Finally, we perform a global pose optimization by minimizing the reprojection errors of the planar markers in all observed frames. The experiments conducted show that our method performs better than Structure from Motion and visual SLAM techniques.

##### Abstract (translated by Google)
平面平面标记是用于快速，准确和稳健的相机定位的常用工具，但是其使用经常局限于单个标记，或者至多局限于预先知晓其相对姿态的一小组标记。从大量的平面标记映射和定位到基于关键点的方法仍然是一个几乎没有处理的问题。然而，虽然关键点检测器对于快速运动不稳健，视点的大的变化或外观的显着变化，但是可以在更宽范围的条件下稳健地检测基准标记。本文提出了一种同时解决平面平面标记集映射和定位问题的新方法。首先，创建一个成对的相对标记姿势，从中获得初始姿态图。姿态图可能包含小的成对姿势误差，在传播时会导致较大的误差。因此，我们沿着图的基本周期分布旋转和平移误差，以便获得校正的姿态图。最后，我们通过最小化所有观察帧中平面标记的重投影误差来执行全局姿态优化。进行的实验表明，我们的方法表现比运动和视觉SLAM技术结构更好。

##### URL
[https://arxiv.org/abs/1606.00151](https://arxiv.org/abs/1606.00151)

##### PDF
[https://arxiv.org/pdf/1606.00151](https://arxiv.org/pdf/1606.00151)

