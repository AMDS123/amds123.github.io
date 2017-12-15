---
layout: post
title: "Incremental Real-Time Multibody VSLAM with Trajectory Optimization Using Stereo Camera"
date: 2016-08-02 23:03:19
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation Optimization SLAM Relation
author: N Dinesh Reddy, Iman Abbasnejad, Sheetal Reddy, Amit Kumar Mondal, Vindhya Devalla
mathjax: true
---

* content
{:toc}

##### Abstract
Real time outdoor navigation in highly dynamic environments is an crucial problem. The recent literature on real time static SLAM don't scale up to dynamic outdoor environments. Most of these methods assume moving objects as outliers or discard the information provided by them. We propose an algorithm to jointly infer the camera trajectory and the moving object trajectory simultaneously. In this paper, we perform a sparse scene flow based motion segmentation using a stereo camera. The segmented objects motion models are used for accurate localization of the camera trajectory as well as the moving objects. We exploit the relationship between moving objects for improving the accuracy of the poses. We formulate the poses as a factor graph incorporating all the constraints. We achieve exact incremental solution by solving a full nonlinear optimization problem in real time. The evaluation is performed on the challenging KITTI dataset with multiple moving cars.Our method outperforms the previous baselines in outdoor navigation.

##### Abstract (translated by Google)
在高度动态环境下的实时室外导航是一个关键问题。最近关于实时静态SLAM的文献没有扩展到动态的室外环境。这些方法大多假定移动对象为异常值或丢弃它们提供的信息。我们提出了一个算法来同时联合推断摄像机轨迹和运动物体轨迹。在本文中，我们使用立体相机执行基于稀疏场景流的运动分割。分段物体运动模型用于相机轨迹以及运动物体的精确定位。我们利用移动物体之间的关系来提高姿态的准确性。我们将姿势作为包含所有约束的因子图来制定。我们通过实时求解完全非线性优化问题来实现精确的增量式解决方案。评估是在具有挑战性的KITTI数据集与多个移动汽车上进行的。我们的方法胜过以前的室外导航基线。

##### URL
[https://arxiv.org/abs/1608.01024](https://arxiv.org/abs/1608.01024)

##### PDF
[https://arxiv.org/pdf/1608.01024](https://arxiv.org/pdf/1608.01024)

