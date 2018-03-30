---
layout: post
title: "Prioritized Multi-View Stereo Depth Map Generation Using Confidence Prediction"
date: 2018-03-22 12:21:21
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Christian Mostegel, Friedrich Fraundorfer, Horst Bischof
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we propose a novel approach to prioritize the depth map computation of multi-view stereo (MVS) to obtain compact 3D point clouds of high quality and completeness at low computational cost. Our prioritization approach operates before the MVS algorithm is executed and consists of two steps. In the first step, we aim to find a good set of matching partners for each view. In the second step, we rank the resulting view clusters (i.e. key views with matching partners) according to their impact on the fulfillment of desired quality parameters such as completeness, ground resolution and accuracy. Additional to geometric analysis, we use a novel machine learning technique for training a confidence predictor. The purpose of this confidence predictor is to estimate the chances of a successful depth reconstruction for each pixel in each image for one specific MVS algorithm based on the RGB images and the image constellation. The underlying machine learning technique does not require any ground truth or manually labeled data for training, but instead adapts ideas from depth map fusion for providing a supervision signal. The trained confidence predictor allows us to evaluate the quality of image constellations and their potential impact to the resulting 3D reconstruction and thus builds a solid foundation for our prioritization approach. In our experiments, we are thus able to reach more than 70% of the maximal reachable quality fulfillment using only 5% of the available images as key views. For evaluating our approach within and across different domains, we use two completely different scenarios, i.e. cultural heritage preservation and reconstruction of single family houses.

##### Abstract (translated by Google)
在这项工作中，我们提出了一种新颖的方法来优先处理多视点立体（MVS）的深度图计算，以低计算成本获得高质量和完整性的紧凑3D点云。我们的优先级排序方法在执行MVS算法之前运行，并由两个步骤组成。在第一步中，我们的目标是为每个视图找到一组好的匹配合作伙伴。在第二步中，我们根据它们对完成度，地面分辨率和准确度等所需质量参数的影响对结果视图集群（即具有匹配伙伴的关键视图）进行排名。除了几何分析之外，我们还使用一种新颖的机器学习技术来训练置信度预测器。该置信度预测器的目的是基于RGB图像和图像星座来估计针对一个特定MVS算法的每个图像中的每个像素的成功深度重建的机会。底层的机器学习技术不需要任何地面实况或手动标记的数据进行训练，而是调整深度图融合的想法以提供监督信号。训练的置信度预测器使我们能够评估图像星座的质量及其对三维重建的潜在影响，从而为我们的优先次序方法奠定坚实的基础。在我们的实验中，我们因此能够使用仅5％的可用图像作为关键视图达到超过70％的最大可达质量满足。为了评估我们在不同领域内和不同领域的方法，我们使用了两种完全不同的方案，即文化遗产保护和单户住宅重建。

##### URL
[https://arxiv.org/abs/1803.08323](https://arxiv.org/abs/1803.08323)

##### PDF
[https://arxiv.org/pdf/1803.08323](https://arxiv.org/pdf/1803.08323)

