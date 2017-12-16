---
layout: post
title: "End-to-end Flow Correlation Tracking with Spatial-temporal Attention"
date: 2017-11-14 16:59:36
categories: arXiv_CV
tags: arXiv_CV Knowledge Attention Tracking CNN Deep_Learning Relation
author: Zheng Zhu, Wei Wu, Wei Zou, Junjie Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Discriminative correlation filters (DCF) with deep convolutional features have achieved favorable performance in recent tracking benchmarks. However, most of existing DCF trackers only consider appearance features of current frame, and hardly benefit from motion and inter-frame information. The lack of temporal information degrades the tracking performance during challenges such as partial occlusion and deformation. In this work, we focus on making use of the rich flow information in consecutive frames to improve the feature representation and the tracking accuracy. Firstly, individual components, including optical flow estimation, feature extraction, aggregation and correlation filter tracking are formulated as special layers in network. To the best of our knowledge, this is the first work to jointly train flow and tracking task in a deep learning framework. Then the historical feature maps at predefined intervals are warped and aggregated with current ones by the guiding of flow. For adaptive aggregation, we propose a novel spatial-temporal attention mechanism. Extensive experiments are performed on four challenging tracking datasets: OTB2013, OTB2015, VOT2015 and VOT2016, and the proposed method achieves superior results on these benchmarks.

##### Abstract (translated by Google)
具有深卷积特征的判别相关滤波器（DCF）在最近的跟踪基准中取得了良好的性能。然而现有的DCF跟踪器大多只考虑当前帧的外观特征，很难从运动和帧间信息中受益。时间信息的缺乏在诸如部分遮挡和变形的挑战期间降低了跟踪性能。在这项工作中，我们专注于利用连续帧中丰富的流信息来改善特征表示和跟踪精度。首先，将光流估计，特征提取，聚合和相关滤波跟踪等各个组成部分制定为网络中的特殊层次。就我们所知，这是第一个在深度学习框架下联合训练流程和跟踪任务的工作。然后，通过流量的引导，以预定义的时间间隔对历史特征地图进行扭曲和聚合。对于自适应聚合，我们提出了一种新颖的时空关注机制。对四个具有挑战性的跟踪数据集进行了大量实验：OTB2013，OTB2015，VOT2015和VOT2016，并且所提出的方法在这些基准上取得了优异的结果。

##### URL
[https://arxiv.org/abs/1711.01124](https://arxiv.org/abs/1711.01124)

##### PDF
[https://arxiv.org/pdf/1711.01124](https://arxiv.org/pdf/1711.01124)

