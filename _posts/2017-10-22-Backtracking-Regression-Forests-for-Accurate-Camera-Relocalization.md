---
layout: post
title: "Backtracking Regression Forests for Accurate Camera Relocalization"
date: 2017-10-22 15:43:26
categories: arXiv_CV
tags: arXiv_CV Tracking Optimization Prediction Detection
author: Lili Meng, Jianhui Chen, Frederick Tung, James J. Little, Julien Valentin, Clarence W. de Silva
mathjax: true
---

* content
{:toc}

##### Abstract
Camera relocalization plays a vital role in many robotics and computer vision tasks, such as global localization, recovery from tracking failure, and loop closure detection. Recent random forests based methods directly predict 3D world locations for 2D image locations to guide the camera pose optimization. During training, each tree greedily splits the samples to minimize the spatial variance. However, these greedy splits often produce uneven sub-trees in training or incorrect 2D-3D correspondences in testing. To address these problems, we propose a sample-balanced objective to encourage equal numbers of samples in the left and right sub-trees, and a novel backtracking scheme to remedy the incorrect 2D-3D correspondence predictions. Furthermore, we extend the regression forests based methods to use local features in both training and testing stages for outdoor RGB-only applications. Experimental results on publicly available indoor and outdoor datasets demonstrate the efficacy of our approach, which shows superior or on-par accuracy with several state-of-the-art methods.

##### Abstract (translated by Google)
相机重新定位在许多机器人和计算机视觉任务中起着至关重要的作用，如全局定位，跟踪失败恢复以及闭环检测。最近的基于随机森林的方法直接预测2D图像位置的3D世界位置以指导相机姿态优化。在训练过程中，每棵树贪婪地分割样本以最小化空间变化。然而，这些贪婪的分裂在训练中经常产生不均匀的亚树，或者在测试中产生不正确的2D-3D对应。为了解决这些问题，我们提出了一个样本均衡的目标，以鼓励左右子树中的样本数相等，并采用一种新的回溯方案来纠正不正确的2D-3D对应预测。此外，我们扩展了基于回归森林的方法，以便在室外RGB纯应用的训练和测试阶段使用局部特征。在公开可用的室内和室外数据集上的实验结果证明了我们的方法的有效性，其显示了几种最先进的方法的优越性或准确性。

##### URL
[https://arxiv.org/abs/1710.07965](https://arxiv.org/abs/1710.07965)

##### PDF
[https://arxiv.org/pdf/1710.07965](https://arxiv.org/pdf/1710.07965)

