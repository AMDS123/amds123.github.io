---
layout: post
title: "Deep Ordinal Regression Network for Monocular Depth Estimation"
date: 2018-06-06 22:36:23
categories: arXiv_CV
tags: arXiv_CV CNN
author: Huan Fu, Mingming Gong, Chaohui Wang, Kayhan Batmanghelich, Dacheng Tao
mathjax: true
---

* content
{:toc}

##### Abstract
Monocular depth estimation, which plays a crucial role in understanding 3D scene geometry, is an ill-posed problem. Recent methods have gained significant improvement by exploring image-level information and hierarchical features from deep convolutional neural networks (DCNNs). These methods model depth estimation as a regression problem and train the regression networks by minimizing mean squared error, which suffers from slow convergence and unsatisfactory local solutions. Besides, existing depth estimation networks employ repeated spatial pooling operations, resulting in undesirable low-resolution feature maps. To obtain high-resolution depth maps, skip-connections or multi-layer deconvolution networks are required, which complicates network training and consumes much more computations. To eliminate or at least largely reduce these problems, we introduce a spacing-increasing discretization (SID) strategy to discretize depth and recast depth network learning as an ordinal regression problem. By training the network using an ordinary regression loss, our method achieves much higher accuracy and \dd{faster convergence in synch}. Furthermore, we adopt a multi-scale network structure which avoids unnecessary spatial pooling and captures multi-scale information in parallel. 
 The method described in this paper achieves state-of-the-art results on four challenging benchmarks, i.e., KITTI [17], ScanNet [9], Make3D [50], and NYU Depth v2 [42], and win the 1st prize in Robust Vision Challenge 2018. Code has been made available at: https://github.com/hufu6371/DORN.

##### Abstract (translated by Google)
单眼深度估计在理解3D场景几何中起着至关重要的作用，是一个不适合的问题。最近的方法通过探索来自深度卷积神经网络（DCNN）的图像级信息和分层特征而获得显着改善。这些方法将深度估计作为回归问题进行建模，并通过最小化均方误差来训练回归网络，其中收敛缓慢且局部解决方案不令人满意。此外，现有的深度估计网络采用重复的空间池操作，导致不合需要的低分辨率特征地图。为了获得高分辨率的深度图，需要跳过连接或多层去卷积网络，这使得网络训练变得复杂并且消耗更多的计算量。为消除或至少在很大程度上减少这些问题，我们引入了一种间距增加离散化（SID）策略来将深度和重铸深度网络学习作为序数回归问题进行离散化。通过使用普通回归损失对网络进行训练，我们的方法实现了更高的准确性和\ dd {更快的同步收敛}。此外，我们采用了多尺度网络结构，避免了不必要的空间合并，并行捕获多尺度信息。
 本文描述的方法在KITTI [17]，ScanNet [9]，Make3D [50]和NYU Depth v2 [42]四个具有挑战性的基准测试中达到了最新的结果，并获得了一等奖在强健视力挑战2018年。代码已经提供：https：//github.com/hufu6371/DORN。

##### URL
[http://arxiv.org/abs/1806.02446](http://arxiv.org/abs/1806.02446)

##### PDF
[http://arxiv.org/pdf/1806.02446](http://arxiv.org/pdf/1806.02446)

