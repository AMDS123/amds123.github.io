---
layout: post
title: "Long-term Correlation Tracking using Multi-layer Hybrid Features in Sparse and Dense Environments"
date: 2018-09-06 12:48:02
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
在稀疏和拥挤的环境中跟踪感兴趣的目标是一个具有挑战性的问题，尚未在文献中成功解决。在本文中，我们提出了一种新的长期视觉跟踪算法，学习判别相关滤波器并使用在线分类器来跟踪稀疏和拥挤视频序列中感兴趣的目标。首先，我们学习使用卷积神经网络（CNN）和传统手工制作功能的多层混合的翻译相关滤波器。我们结合了较低卷积层的优点，它保留了更多的空间细节以实现精确定位，以及更高的卷积层，它编码语义信息以处理外观变化，然后将它们与定向梯度直方图（HOG）和颜色命名传统特征相结合。其次，我们提供了一个重新检测模块，通过使用手工设计的功能在最自信的帧上训练增量（在线）SVM，克服由于长期遮挡导致的跟踪失败。仅当对象的相关响应低于某个预定阈值时才激活该重新检测模块。这生成高分检测提议，其使用高斯混合概率假设密度（GM-PHD）滤波器在时间上过滤，以通过将其他检测提议移除为杂波来找到具有最大权重作为目标状态估计的检测提议。最后，我们学习了一个比例相关滤波器，用于通过使用HOG特征在估计或重新检测的位置周围构建目标金字塔来估计目标的比例。我们对稀疏和密集数据集进行了大量实验，结果表明我们的方法明显优于最先进的方法。

##### URL
[http://arxiv.org/abs/1705.11175](http://arxiv.org/abs/1705.11175)

##### PDF
[http://arxiv.org/pdf/1705.11175](http://arxiv.org/pdf/1705.11175)

