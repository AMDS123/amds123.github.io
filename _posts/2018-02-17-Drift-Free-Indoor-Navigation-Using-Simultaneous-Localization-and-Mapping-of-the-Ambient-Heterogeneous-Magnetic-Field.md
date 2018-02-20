---
layout: post
title: "Drift-Free Indoor Navigation Using Simultaneous Localization and Mapping of the Ambient Heterogeneous Magnetic Field"
date: 2018-02-17 07:07:10
categories: arXiv_RO
tags: arXiv_RO Optimization Detection SLAM
author: Jacky C.K. Chow
mathjax: true
---

* content
{:toc}

##### Abstract
In the absence of external reference position information (e.g. GNSS) SLAM has proven to be an effective method for indoor navigation. The positioning drift can be reduced with regular loop-closures and global relaxation as the backend, thus achieving a good balance between exploration and exploitation. Although vision-based systems like laser scanners are typically deployed for SLAM, these sensors are heavy, energy inefficient, and expensive, making them unattractive for wearables or smartphone applications. However, the concept of SLAM can be extended to non-optical systems such as magnetometers. Instead of matching features such as walls and furniture using some variation of the ICP algorithm, the local magnetic field can be matched to provide loop-closure and global trajectory updates in a Gaussian Process (GP) SLAM framework. With a MEMS-based inertial measurement unit providing a continuous trajectory, and the matching of locally distinct magnetic field maps, experimental results in this paper show that a drift-free navigation solution in an indoor environment with millimetre-level accuracy can be achieved. The GP-SLAM approach presented can be formulated as a maximum a posteriori estimation problem and it can naturally perform loop-detection, feature-to-feature distance minimization, global trajectory optimization, and magnetic field map estimation simultaneously. Spatially continuous features (i.e. smooth magnetic field signatures) are used instead of discrete feature correspondences (e.g. point-to-point) as in conventional vision-based SLAM. These position updates from the ambient magnetic field also provide enough information for calibrating the accelerometer and gyroscope bias in-use. The only restriction for this method is the need for magnetic disturbances (which is typically not an issue indoors); however, no assumptions are required for the general motion of the sensor.

##### Abstract (translated by Google)
在没有外部参考位置信息（例如GNSS）的情况下，SLAM已被证明是室内导航的有效方法。作为后端的定位闭环和全局放松可以减少定位漂移，从而实现勘探和开发之间的良好平衡。虽然基于视觉的系统（如激光扫描仪）通常用于SLAM，但这些传感器笨重，能源效率低下且价格昂贵，使其对可穿戴设备或智能手机应用程序不具吸引力。但是，SLAM的概念可以扩展到诸如磁力计之类的非光学系统。使用ICP算法的一些变化来匹配诸如墙壁和家具之类的特征，可以匹配局部磁场以在高斯过程（GP）SLAM框架中提供环路闭合和全局轨迹更新。通过基于MEMS的惯性测量单元提供连续的轨迹以及匹配局部不同的磁场地图，本文的实验结果表明，可以实现具有毫米级精度的室内环境中的无漂移导航解决方案。所提出的GP-SLAM方法可以被表述为最大后验估计问题，并且它可以自然地同时执行环路检测，特征 - 特征距离最小化，全局轨迹优化和磁场图估计。如在传统的基于视觉的SLAM中那样，使用空间上连续的特征（即平滑的磁场特征）来代替离散特征对应（例如，点对点）。这些来自环境磁场的位置更新也为校准使用中的加速度计和陀螺仪偏差提供了足够的信息。这种方法的唯一限制是需要磁干扰（这在室内通常不是问题）;然而，传感器的一般运动不需要假设。

##### URL
[http://arxiv.org/abs/1802.06199](http://arxiv.org/abs/1802.06199)

##### PDF
[http://arxiv.org/pdf/1802.06199](http://arxiv.org/pdf/1802.06199)

