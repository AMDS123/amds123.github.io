---
layout: post
title: "Eigendecomposition-free Training of Deep Networks with Zero Eigenvalue-based Losses"
date: 2018-03-26 12:36:08
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Optimization Deep_Learning
author: Zheng Dang, Kwang Moo Yi, Yinlin Hu, Fei Wang, Pascal Fua, Mathieu Salzmann
mathjax: true
---

* content
{:toc}

##### Abstract
Many classical Computer Vision problems, such as essential matrix computation and pose estimation from 3D to 2D correspondences, can be solved by finding the eigenvector corresponding to the smallest, or zero, eigenvalue of a matrix representing a linear system. Incorporating this in deep learning frameworks would allow us to explicitly encode known notions of geometry, instead of having the network implicitly learn them from data. However, performing eigendecomposition within a network requires the ability to differentiate this operation. Unfortunately, while theoretically doable, this introduces numerical instability in the optimization process in practice. In this paper, we introduce an eigendecomposition-free approach to training a deep network whose loss depends on the eigenvector corresponding to a zero eigenvalue of a matrix predicted by the network. We demonstrate on several tasks, including keypoint matching and 3D pose estimation, that our approach is much more robust than explicit differentiation of the eigendecomposition, It has better convergence properties and yields state-of-the-art results on both tasks.

##### Abstract (translated by Google)
许多经典的计算机视觉问题，例如从3D到2D对应的基本矩阵计算和姿态估计，可以通过找到与代表线性系统的矩阵的最小或零特征值相对应的特征向量来解决。将它融合到深度学习框架中可以让我们明确地编码已知的几何概念，而不是让网络从数据中隐式地学习它们。但是，在网络中执行特征分解需要区分这种操作的能力。不幸的是，虽然理论上可行，但这在实践中引入了优化过程中的数值不稳定性。在本文中，我们引入了一种无特征分解的方法来训练一个深度网络，其损失取决于对应于网络预测矩阵的零特征值的特征向量。我们演示了几个任务，包括关键点匹配和三维姿态估计，我们的方法比本征分解的显式区分更加稳健，它具有更好的收敛性并且在两个任务上都能获得最新的结果。

##### URL
[https://arxiv.org/abs/1803.08071](https://arxiv.org/abs/1803.08071)

##### PDF
[https://arxiv.org/pdf/1803.08071](https://arxiv.org/pdf/1803.08071)

