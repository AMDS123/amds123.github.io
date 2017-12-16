---
layout: post
title: "Quad-networks: unsupervised learning to rank for interest point detection"
date: 2017-04-10 21:15:18
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Quantitative Detection
author: Nikolay Savinov, Akihito Seki, Lubor Ladicky, Torsten Sattler, Marc Pollefeys
mathjax: true
---

* content
{:toc}

##### Abstract
Several machine learning tasks require to represent the data using only a sparse set of interest points. An ideal detector is able to find the corresponding interest points even if the data undergo a transformation typical for a given domain. Since the task is of high practical interest in computer vision, many hand-crafted solutions were proposed. In this paper, we ask a fundamental question: can we learn such detectors from scratch? Since it is often unclear what points are "interesting", human labelling cannot be used to find a truly unbiased solution. Therefore, the task requires an unsupervised formulation. We are the first to propose such a formulation: training a neural network to rank points in a transformation-invariant manner. Interest points are then extracted from the top/bottom quantiles of this ranking. We validate our approach on two tasks: standard RGB image interest point detection and challenging cross-modal interest point detection between RGB and depth images. We quantitatively show that our unsupervised method performs better or on-par with baselines.

##### Abstract (translated by Google)
几个机器学习任务只需要使用一组稀疏的兴趣点来表示数据。即使数据经历了对于给定域的典型变换，理想的检测器也能够找到相应的兴趣点。由于这项任务对计算机视觉具有很高的实际意义，因此提出了许多手工解决方案。在本文中，我们提出一个基本的问题：我们能从零开始学习这种探测器吗？由于人们常常不清楚什么是“有趣的”，人类的标签不能用来找到真正的无偏见的解决方案。因此，这个任务需要一个无监督的表述。我们是第一个提出这样一个公式：训练神经网络以转换不变的方式排列点。然后从该排名的顶部/底部分位数中提取兴趣点。我们在两项任务中验证了我们的方法：标准RGB图像兴趣点检测和RGB和深度图像之间具有挑战性的跨模态兴趣点检测。我们在数量上表明，我们的无监督方法执行更好或与基线相提并论。

##### URL
[https://arxiv.org/abs/1611.07571](https://arxiv.org/abs/1611.07571)

##### PDF
[https://arxiv.org/pdf/1611.07571](https://arxiv.org/pdf/1611.07571)

