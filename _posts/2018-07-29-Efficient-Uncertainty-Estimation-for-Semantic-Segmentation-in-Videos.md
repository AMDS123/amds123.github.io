---
layout: post
title: "Efficient Uncertainty Estimation for Semantic Segmentation in Videos"
date: 2018-07-29 10:38:00
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Deep_Learning Prediction
author: Po-Yu Huang, Wan-Ting Hsu, Chun-Yueh Chiu, Ting-Fan Wu, Min Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Uncertainty estimation in deep learning becomes more important recently. A deep learning model can't be applied in real applications if we don't know whether the model is certain about the decision or not. Some literature proposes the Bayesian neural network which can estimate the uncertainty by Monte Carlo Dropout (MC dropout). However, MC dropout needs to forward the model $N$ times which results in $N$ times slower. For real-time applications such as a self-driving car system, which needs to obtain the prediction and the uncertainty as fast as possible, so that MC dropout becomes impractical. In this work, we propose the region-based temporal aggregation (RTA) method which leverages the temporal information in videos to simulate the sampling procedure. Our RTA method with Tiramisu backbone is 10x faster than the MC dropout with Tiramisu backbone ($N=5$). Furthermore, the uncertainty estimation obtained by our RTA method is comparable to MC dropout's uncertainty estimation on pixel-level and frame-level metrics.

##### Abstract (translated by Google)
最近，深度学习中的不确定性评估变得更加重要。如果我们不知道模型是否确定决策，则深度学习模型不能应用于实际应用中。一些文献提出了贝叶斯神经网络，它可以通过蒙特卡洛压降（MC dropout）来估计不确定性。但是，MC丢失需要将模型转发$ N $次，这会导致$ N $次慢。对于需要尽可能快地获得预测和不确定性的实时应用，例如自动驾驶汽车系统，使得MC丢失变得不切实际。在这项工作中，我们提出了基于区域的时间聚合（RTA）方法，该方法利用视频中的时间信息来模拟采样过程。我们使用提拉米苏主干的RTA方法比使用提拉米苏主干的MC丢失快10倍（$ N = 5 $）。此外，通过我们的RTA方法获得的不确定性估计与MC丢失对像素级和帧级度量的不确定性估计相当。

##### URL
[http://arxiv.org/abs/1807.11037](http://arxiv.org/abs/1807.11037)

##### PDF
[http://arxiv.org/pdf/1807.11037](http://arxiv.org/pdf/1807.11037)

