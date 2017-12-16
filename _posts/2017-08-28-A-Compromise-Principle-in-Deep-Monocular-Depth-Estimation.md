---
layout: post
title: "A Compromise Principle in Deep Monocular Depth Estimation"
date: 2017-08-28 10:51:35
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Huan Fu, Mingming Gong, Chaohui Wang, Dacheng Tao
mathjax: true
---

* content
{:toc}

##### Abstract
Monocular depth estimation, which plays a key role in understanding 3D scene geometry, is fundamentally an ill-posed problem. Existing methods based on deep convolutional neural networks (DCNNs) have examined this problem by learning convolutional networks to estimate continuous depth maps from monocular images. However, we find that training a network to predict a high spatial resolution continuous depth map often suffers from poor local solutions. In this paper, we hypothesize that achieving a compromise between spatial and depth resolutions can improve network training. Based on this "compromise principle", we propose a regression-classification cascaded network (RCCN), which consists of a regression branch predicting a low spatial resolution continuous depth map and a classification branch predicting a high spatial resolution discrete depth map. The two branches form a cascaded structure allowing the classification and regression branches to benefit from each other. By leveraging large-scale raw training datasets and some data augmentation strategies, our network achieves top or state-of-the-art results on the NYU Depth V2, KITTI, and Make3D benchmarks.

##### Abstract (translated by Google)
单眼深度估计在理解三维场景几何中扮演着重要的角色，根本上是一个不适合的问题。基于深度卷积神经网络（DCNNs）的现有方法已经通过学习卷积网络来从单眼图像估计连续深度图来检查这个问题。然而，我们发现，训练一个网络来预测高空间分辨率的连续深度图通常会遇到较差的局部解决方案。在本文中，我们假设在空间和深度分辨率之间达成妥协可以改善网络训练。基于这一“妥协原则”，我们提出了一种回归分级级联网络（RCCN），它由一个预测低空间分辨率连续深度图的回归分支和一个预测高空间分辨率离散深度图的分类分支组成。这两个分支形成一个级联结构，允许分类和回归分支相互受益。通过利用大规模原始训练数据集和一些数据增强策略，我们的网络在纽约大学深度V2，KITTI和Make3D基准测试中获得了最高或最先进的成果。

##### URL
[https://arxiv.org/abs/1708.08267](https://arxiv.org/abs/1708.08267)

##### PDF
[https://arxiv.org/pdf/1708.08267](https://arxiv.org/pdf/1708.08267)

