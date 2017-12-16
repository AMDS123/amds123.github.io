---
layout: post
title: "Joint Epipolar Tracking : Simultaneous optimization of epipolar geometry and feature correspondences"
date: 2017-03-15 10:30:21
categories: arXiv_CV
tags: arXiv_CV Sparse Pose_Estimation Tracking Optimization
author: Henry Bradler, Matthias Ochs, Rudolf Mester
mathjax: true
---

* content
{:toc}

##### Abstract
Traditionally, pose estimation is considered as a two step problem. First, feature correspondences are determined by direct comparison of image patches, or by associating feature descriptors. In a second step, the relative pose and the coordinates of corresponding points are estimated, most often by minimizing the reprojection error (RPE). RPE optimization is based on a loss function that is merely aware of the feature pixel positions but not of the underlying image intensities. In this paper, we propose a sparse direct method which introduces a loss function that allows to simultaneously optimize the unscaled relative pose, as well as the set of feature correspondences directly considering the image intensity values. Furthermore, we show how to integrate statistical prior information on the motion into the optimization process. This constructive inclusion of a Bayesian bias term is particularly efficient in application cases with a strongly predictable (short term) dynamic, e.g. in a driving scenario. In our experiments, we demonstrate that the JET algorithm we propose outperforms the classical reprojection error optimization on two synthetic datasets and on the KITTI dataset. The JET algorithm runs in real-time on a single CPU thread.

##### Abstract (translated by Google)
传统上，姿态估计被认为是两步问题。首先，通过直接比较图像块或通过关联特征描述符来确定特征对应。在第二步中，估计对应点的相对姿态和坐标，最经常通过最小化再投影误差（RPE）。 RPE优化是基于仅仅意识到特征像素位置而不是底层图像强度的损失函数。在本文中，我们提出了一种稀疏直接方法，它引入了一个损失函数，允许同时优化未缩放的相对位姿，以及直接考虑图像强度值的特征对应集。此外，我们展示了如何将运动的统计先验信息整合到优化过程中。贝叶斯偏倚项的这种建设性包含在具有强烈可预测（短期）动态的应用情况下尤其有效。在驾驶的情况下。在我们的实验中，我们证明了我们提出的JET算法优于两个合成数据集和KITTI数据集上经典的重投影误差优化。 JET算法在单个CPU线程上实时运行。

##### URL
[https://arxiv.org/abs/1703.05065](https://arxiv.org/abs/1703.05065)

##### PDF
[https://arxiv.org/pdf/1703.05065](https://arxiv.org/pdf/1703.05065)

