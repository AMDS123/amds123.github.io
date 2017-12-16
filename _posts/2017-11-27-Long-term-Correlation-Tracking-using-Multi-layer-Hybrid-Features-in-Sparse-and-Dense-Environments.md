---
layout: post
title: "Long-term Correlation Tracking using Multi-layer Hybrid Features in Sparse and Dense Environments"
date: 2017-11-27 14:54:39
categories: arXiv_CV
tags: arXiv_CV Sparse Tracking CNN Detection Relation
author: Nathanael L. Baisa, Deepayan Bhowmik, Andrew Wallace
mathjax: true
---

* content
{:toc}

##### Abstract
Tracking a target of interest in both sparse and crowded environments is a challenging problem, not yet successfully addressed in the literature. In this paper, we propose a new long-term visual tracking algorithm, learning discriminative correlation filters and using an online classifier, to track a target of interest in both sparse and crowded video sequences. First, we learn a translation correlation filter using a multi-layer hybrid of convolutional neural networks (CNN) and traditional hand-crafted features. We combine advantages of both the lower convolutional layer which retains more spatial details for precise localization and the higher convolutional layer which encodes semantic information for handling appearance variations, and then integrate these with histogram of oriented gradients (HOG) and color-naming traditional features. Second, we include a re-detection module for overcoming tracking failures due to long-term occlusions by training an incremental (online) SVM on the most confident frames using hand-engineered features. This re-detection module is activated only when the correlation response of the object is below some pre-defined threshold. This generates high score detection proposals which are temporally filtered using a Gaussian mixture probability hypothesis density (GM-PHD) filter to find the detection proposal with the maximum weight as the target state estimate by removing the other detection proposals as clutter. Finally, we learn a scale correlation filter for estimating the scale of a target by constructing a target pyramid around the estimated or re-detected position using the HOG features. We carry out extensive experiments on both sparse and dense data sets which show that our method significantly outperforms state-of-the-art methods.

##### Abstract (translated by Google)
在稀疏和拥挤的环境中跟踪感兴趣的目标是一个具有挑战性的问题，在文献中尚未成功解决。在本文中，我们提出了一个新的长期视觉跟踪算法，学习歧视相关滤波器，并使用在线分类器，跟踪稀疏和拥挤的视频序列的兴趣目标。首先，我们学习使用卷积神经网络（CNN）和传统手工特征的多层混合的平移相关滤波器。我们将保留更多空间细节的较低卷积层和精确定位的较高卷积层的优点结合起来，编码处理外观变化的语义信息的较高卷积层，然后将其与面向梯度直方图（HOG）和颜色命名传统特征相结合。其次，我们还包括一个重新检测模块，通过使用手工设计的特征在最自信的帧上训练增量（在线）SVM，克服由于长期遮挡导致的跟踪失败。该重新检测模块仅在对象的相关响应低于某个预定义的阈值时被激活。这产生了高分检测建议，其使用高斯混合概率假设密度（GM-PHD）滤波器进行时间滤波，以通过将其他检测建议作为杂波去除，将具有最大权重的检测建议作为目标状态估计。最后，我们学习了一个尺度相关滤波器，用于通过使用HOG特征在估计或重新检测的位置周围构建目标金字塔来估计目标的尺度。我们对稀疏和密集数据集进行了广泛的实验，这些数据表明我们的方法明显优于最先进的方法。

##### URL
[https://arxiv.org/abs/1705.11175](https://arxiv.org/abs/1705.11175)

##### PDF
[https://arxiv.org/pdf/1705.11175](https://arxiv.org/pdf/1705.11175)

