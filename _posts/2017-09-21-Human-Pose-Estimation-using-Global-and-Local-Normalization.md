---
layout: post
title: "Human Pose Estimation using Global and Local Normalization"
date: 2017-09-21 09:13:31
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN Detection
author: Ke Sun, Cuiling Lan, Junliang Xing, Wenjun Zeng, Dong Liu, Jingdong Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we address the problem of estimating the positions of human joints, i.e., articulated pose estimation. Recent state-of-the-art solutions model two key issues, joint detection and spatial configuration refinement, together using convolutional neural networks. Our work mainly focuses on spatial configuration refinement by reducing variations of human poses statistically, which is motivated by the observation that the scattered distribution of the relative locations of joints e.g., the left wrist is distributed nearly uniformly in a circular area around the left shoulder) makes the learning of convolutional spatial models hard. We present a two-stage normalization scheme, human body normalization and limb normalization, to make the distribution of the relative joint locations compact, resulting in easier learning of convolutional spatial models and more accurate pose estimation. In addition, our empirical results show that incorporating multi-scale supervision and multi-scale fusion into the joint detection network is beneficial. Experiment results demonstrate that our method consistently outperforms state-of-the-art methods on the benchmarks.

##### Abstract (translated by Google)
在本文中，我们解决估计人体关节位置的问题，即关节姿态估计。最近的最先进的解决方案模型两个关键问题，联合检测和空间配置细化，一起使用卷积神经网络。我们的工作主要集中在通过减少人体姿态的统计上的变化来实现空间构型的细化，这是由于观察到关节的相对位置的分散分布（例如左手腕几乎均匀地分布在左肩周围的圆形区域）使卷积空间模型的学习变得困难。我们提出了一个两阶段归一化方案，即人体归一化和肢体规范化，使得相对联合位置的分布紧凑，从而更容易学习卷积空间模型，更准确地进行姿态估计。此外，我们的实证结果表明，将多尺度监督和多尺度融合纳入联合检测网络是有益的。实验结果表明，我们的方法始终优于基准测试中的最新方法。

##### URL
[https://arxiv.org/abs/1709.07220](https://arxiv.org/abs/1709.07220)

##### PDF
[https://arxiv.org/pdf/1709.07220](https://arxiv.org/pdf/1709.07220)

