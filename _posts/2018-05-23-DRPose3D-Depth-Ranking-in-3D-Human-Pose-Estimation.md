---
layout: post
title: "DRPose3D: Depth Ranking in 3D Human Pose Estimation"
date: 2018-05-23 06:05:48
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN Classification
author: Min Wang, Xipeng Chen, Wentao Liu, Chen Qian, Liang Lin, Lizhuang Ma
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a two-stage depth ranking based method (DRPose3D) to tackle the problem of 3D human pose estimation. Instead of accurate 3D positions, the depth ranking can be identified by human intuitively and learned using the deep neural network more easily by solving classification problems. Moreover, depth ranking contains rich 3D information. It prevents the 2D-to-3D pose regression in two-stage methods from being ill-posed. In our method, firstly, we design a Pairwise Ranking Convolutional Neural Network (PRCNN) to extract depth rankings of human joints from images. Secondly, a coarse-to-fine 3D Pose Network(DPNet) is proposed to estimate 3D poses from both depth rankings and 2D human joint locations. Additionally, to improve the generality of our model, we introduce a statistical method to augment depth rankings. Our approach outperforms the state-of-the-art methods in the Human3.6M benchmark for all three testing protocols, indicating that depth ranking is an essential geometric feature which can be learned to improve the 3D pose estimation.

##### Abstract (translated by Google)
在本文中，我们提出了一种基于两阶段深度排序的方法（DRPose3D）来解决三维人体姿态估计问题。深度排名可以通过直观的人类识别，并通过解决分类问题更容易地使用深度神经网络进行学习，而不是精确的三维位置。而且，深度排名包含丰富的3D信息。它可以防止两阶段方法中的二维到三维姿态回归不适宜。在我们的方法中，首先，我们设计了一个成对排序卷积神经网络（PRCNN），从图像中提取人体关节的深度排序。其次，提出了从粗到细的三维姿态网络（DPNet），用于根据深度排序和二维人类关节位置来估计三维姿态。另外，为了提高我们模型的一般性，我们引入了统计方法来增加深度排名。我们的方法胜过了所有三种测试协议的Human3.6M基准测试中最先进的方法，表明深度排名是可以学习改进三维姿态估计的基本几何特征。

##### URL
[http://arxiv.org/abs/1805.08973](http://arxiv.org/abs/1805.08973)

##### PDF
[http://arxiv.org/pdf/1805.08973](http://arxiv.org/pdf/1805.08973)

