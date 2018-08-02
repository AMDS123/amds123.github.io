---
layout: post
title: "Depth Estimation via Affinity Learned with Convolutional Spatial Propagation Network"
date: 2018-08-01 03:23:06
categories: arXiv_CV
tags: arXiv_CV Sparse Embedding CNN Prediction
author: Xinjing Cheng, Peng Wang, Ruigang Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Depth estimation from a single image is a fundamental problem in computer vision. In this paper, we propose a simple yet effective convolutional spatial propagation network (CSPN) to learn the affinity matrix for depth prediction. Specifically, we adopt an efficient linear propagation model, where the propagation is performed with a manner of recurrent convolutional operation, and the affinity among neighboring pixels is learned through a deep convolutional neural network (CNN). We apply the designed CSPN to two depth estimation tasks given a single image: (1) To refine the depth output from state-of-the-art (SOTA) existing methods; and (2) to convert sparse depth samples to a dense depth map by embedding the depth samples within the propagation procedure. The second task is inspired by the availability of LIDARs that provides sparse but accurate depth measurements. We experimented the proposed CSPN over two popular benchmarks for depth estimation, i.e. NYU v2 and KITTI, where we show that our proposed approach improves in not only quality (e.g., 30% more reduction in depth error), but also speed (e.g., 2 to 5 times faster) than prior SOTA methods.

##### Abstract (translated by Google)
来自单个图像的深度估计是计算机视觉中的基本问题。在本文中，我们提出了一种简单而有效的卷积空间传播网络（CSPN）来学习深度预测的亲和度矩阵。具体地，我们采用有效的线性传播模型，其中以递归卷积运算的方式执行传播，并且通过深度卷积神经网络（CNN）学习相邻像素之间的亲和度。在给定单个图像的情况下，我们将设计的CSPN应用于两个深度估计任务：（1）改进现有技术（SOTA）现有方法的深度输出; （2）通过在传播过程中嵌入深度样本，将稀疏深度样本转换为密集深度图。第二项任务的灵感来自LIDAR的可用性，它提供了稀疏但精确的深度测量。我们在两个流行的深度估算基准上进行了实验CSPN的实验，即NYU v2和KITTI，我们展示了我们提出的方法不仅提高了质量（例如，深度误差减少了30％），而且提高了速度（例如，2）比以前的SOTA方法快5倍。

##### URL
[https://arxiv.org/abs/1808.00150](https://arxiv.org/abs/1808.00150)

##### PDF
[https://arxiv.org/pdf/1808.00150](https://arxiv.org/pdf/1808.00150)

