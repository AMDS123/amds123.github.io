---
layout: post
title: "On the Performance of ConvNet Features for Place Recognition"
date: 2015-07-29 01:56:54
categories: arXiv_CV
tags: arXiv_CV Face CNN Optimization Deep_Learning SLAM Recognition
author: Niko Sünderhauf, Feras Dayoub, Sareh Shirazi, Ben Upcroft, Michael Milford
mathjax: true
---

* content
{:toc}

##### Abstract
After the incredible success of deep learning in the computer vision domain, there has been much interest in applying Convolutional Network (ConvNet) features in robotic fields such as visual navigation and SLAM. Unfortunately, there are fundamental differences and challenges involved. Computer vision datasets are very different in character to robotic camera data, real-time performance is essential, and performance priorities can be different. This paper comprehensively evaluates and compares the utility of three state-of-the-art ConvNets on the problems of particular relevance to navigation for robots; viewpoint-invariance and condition-invariance, and for the first time enables real-time place recognition performance using ConvNets with large maps by integrating a variety of existing (locality-sensitive hashing) and novel (semantic search space partitioning) optimization techniques. We present extensive experiments on four real world datasets cultivated to evaluate each of the specific challenges in place recognition. The results demonstrate that speed-ups of two orders of magnitude can be achieved with minimal accuracy degradation, enabling real-time performance. We confirm that networks trained for semantic place categorization also perform better at (specific) place recognition when faced with severe appearance changes and provide a reference for which networks and layers are optimal for different aspects of the place recognition problem.

##### Abstract (translated by Google)
在计算机视觉领域的深度学习取得令人难以置信的成功之后，人们对在视觉导航和SLAM等机器人领域中应用卷积网络（ConvNet）特性产生了极大兴趣。不幸的是，这涉及到根本性的差异和挑战。计算机视觉数据集与机器人相机数据的性质非常不同，实时性能至关重要，性能优先级可能不同。本文综合评估和比较了三个最先进的通信网络在机器人导航问题上的实用性。视点不变性和条件不变性，并且首次通过集成各种现有的（局部敏感哈希）和新颖的（语义搜索空间划分）优化技术，使用具有大地图的ConvNet来实现实时地点识别性能。我们对四个现实世界的数据集进行了广泛的实验，这些数据集是为了评估每个具体挑战而进行的。结果表明，可以以最小的精度降级实现两个数量级的加速，从而实现实时性能。我们确认，受到语义地点分类训练的网络在面临严重的外观变化时，在（特定的）地点识别中也表现更好，并为地点识别问题的不同方面提供了最佳网络和层次的参考。

##### URL
[https://arxiv.org/abs/1501.04158](https://arxiv.org/abs/1501.04158)

##### PDF
[https://arxiv.org/pdf/1501.04158](https://arxiv.org/pdf/1501.04158)

