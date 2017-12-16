---
layout: post
title: "Learning Linear Dynamical Systems with High-Order Tensor Data for Skeleton based Action Recognition"
date: 2017-01-14 02:07:23
categories: arXiv_CV
tags: arXiv_CV Sparse Action_Recognition Classification Recognition
author: Wenwen Ding, Kai Liu
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, there has been renewed interest in developing methods for skeleton-based human action recognition. A skeleton sequence can be naturally represented as a high-order tensor time series. In this paper, we model and analyze tensor time series with Linear Dynamical System (LDS) which is the most common for encoding spatio-temporal time-series data in various disciplines dut to its relative simplicity and efficiency. However, the traditional LDS treats the latent and observation state at each frame of video as a column vector. Such a vector representation fails to take into account the curse of dimensionality as well as valuable structural information with human action. Considering this fact, we propose generalized Linear Dynamical System (gLDS) for modeling tensor observation in the time series and employ Tucker decomposition to estimate the LDS parameters as action descriptors. Therefore, an action can be represented as a subspace corresponding to a point on a Grassmann manifold. Then we perform classification using dictionary learning and sparse coding over Grassmann manifold. Experiments on MSR Action3D Dataset, UCF Kinect Dataset and Northwestern-UCLA Multiview Action3D Dataset demonstrate that our proposed method achieves superior performance to the state-of-the-art algorithms.

##### Abstract (translated by Google)
近年来，人们开始重新研究基于骨架的人类行为识别方法。骨架序列可以自然地表示为高阶张量时间序列。本文利用线性动力系统（LDS）对张量时间序列进行建模和分析，线性动力系统（LDS）是最为常见的编码各学科时空序列数据的方法，其相对简单和高效。然而，传统的LDS将每帧视频的潜在观察状态视为列向量。这种向量表示没有考虑维度的诅咒以及有人的行为的有价值的结构信息。考虑到这一事实，我们提出了广义线性动力系统（gLDS），用于时间序列的张量观测建模，并采用Tucker分解来估计LDS参数作为动作描述符。因此，一个动作可以表示为一个对应于Grassmann流形上一个点的子空间。然后用Grassmann流形上的字典学习和稀疏编码进行分类。 MSR动作三维数据集，UCF Kinect数据集和西北UCLA多视图动作三维数据集的实验表明，我们提出的方法实现了最先进的算法优越的性能。

##### URL
[https://arxiv.org/abs/1701.03869](https://arxiv.org/abs/1701.03869)

##### PDF
[https://arxiv.org/pdf/1701.03869](https://arxiv.org/pdf/1701.03869)

