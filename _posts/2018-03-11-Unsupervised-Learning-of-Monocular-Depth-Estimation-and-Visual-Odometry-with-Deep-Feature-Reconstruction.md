---
layout: post
title: "Unsupervised Learning of Monocular Depth Estimation and Visual Odometry with Deep Feature Reconstruction"
date: 2018-03-11 03:56:29
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Huangying Zhan, Ravi Garg, Chamara Saroj Weerasekera, Kejie Li, Harsh Agarwal, Ian Reid
mathjax: true
---

* content
{:toc}

##### Abstract
Despite learning based methods showing promising results in single view depth estimation and visual odometry, most existing approaches treat the tasks in a supervised manner. Recent approaches to single view depth estimation explore the possibility of learning without full supervision via minimizing photometric error. In this paper, we explore the use of stereo sequences for learning depth and visual odometry. The use of stereo sequences enables the use of both spatial (between left-right pairs) and temporal (forward backward) photometric warp error, and constrains the scene depth and camera motion to be in a common, real-world scale. At test time our framework is able to estimate single view depth and two-view odometry from a monocular sequence. We also show how we can improve on a standard photometric warp loss by considering a warp of deep features. We show through extensive experiments that: (i) jointly training for single view depth and visual odometry improves depth prediction because of the additional constraint imposed on depths and achieves competitive results for visual odometry; (ii) deep feature-based warping loss improves upon simple photometric warp loss for both single view depth estimation and visual odometry. Our method outperforms existing learning based methods on the KITTI driving dataset in both tasks. The source code is available at this https URL

##### Abstract (translated by Google)
尽管基于学习的方法在单视点深度估计和视觉测距中显示出有希望的结果，但是大多数现有方法以监督的方式处理任务。最近的单视点深度估算方法通过最小化光度误差来探索在没有完全监督的情况下进行学习的可能性。在本文中，我们探讨了使用立体声序列进行学习深度和视觉测距。使用立体声序列可以同时使用空间（左右对之间）和时间（向后）光度测量误差，并将场景深度和相机运动限制在常见的真实世界范围内。在测试时间，我们的框架能够从单眼序列中估计单视图深度和双视图测距。我们还展示了如何通过考虑深层特征的扭曲来改进标准光度测量的扭曲损失。我们通过广泛的实验表明：（i）由于对深度施加的附加约束并实现视觉测距的竞争结果，因此单视点深度和视觉测距的联合训练改善了深度预测; （ii）单视点深度估计和视觉测距中的简单光度歪曲损失改善了基于深度特征的翘曲损失。我们的方法在两项任务中均优于现有基于KITTI驾驶数据集的学习方法。源代码可在此https网址获得

##### URL
[https://arxiv.org/abs/1803.03893](https://arxiv.org/abs/1803.03893)

##### PDF
[https://arxiv.org/pdf/1803.03893](https://arxiv.org/pdf/1803.03893)

