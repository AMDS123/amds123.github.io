---
layout: post
title: "SemanticFusion: Dense 3D Semantic Mapping with Convolutional Neural Networks"
date: 2016-09-28 14:32:45
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Prediction SLAM
author: John McCormac, Ankur Handa, Andrew Davison, Stefan Leutenegger
mathjax: true
---

* content
{:toc}

##### Abstract
Ever more robust, accurate and detailed mapping using visual sensing has proven to be an enabling factor for mobile robots across a wide variety of applications. For the next level of robot intelligence and intuitive user interaction, maps need extend beyond geometry and appearence - they need to contain semantics. We address this challenge by combining Convolutional Neural Networks (CNNs) and a state of the art dense Simultaneous Localisation and Mapping (SLAM) system, ElasticFusion, which provides long-term dense correspondence between frames of indoor RGB-D video even during loopy scanning trajectories. These correspondences allow the CNN's semantic predictions from multiple view points to be probabilistically fused into a map. This not only produces a useful semantic 3D map, but we also show on the NYUv2 dataset that fusing multiple predictions leads to an improvement even in the 2D semantic labelling over baseline single frame predictions. We also show that for a smaller reconstruction dataset with larger variation in prediction viewpoint, the improvement over single frame segmentation increases. Our system is efficient enough to allow real-time interactive use at frame-rates of approximately 25Hz.

##### Abstract (translated by Google)
使用视觉感应的更强大，准确和详细的映射已经被证明是移动机器人在各种应用中的启用因素。对于下一级机器人智能和直观的用户交互，地图需要超越几何和外观 - 它们需要包含语义。我们通过结合卷积神经网络（CNN）和先进的密集同时定位和映射（SLAM）系统ElasticFusion来解决这一挑战，ElasticFusion在室内RGB-D视频帧之间提供了长期密集的对应，即使在扫描轨迹。这些对应关系允许CNN从多个角度的语义预测被概率地融合成一张地图。这不仅产生了有用的语义3D地图，而且我们还在NYUv2数据集上显示，即使在基线单帧预测的2D语义标记上，融合多个预测也导致改进。我们还表明，对于预测观点变化较大的较小重建数据集，单帧分割的改进增加。我们的系统足够高效，可以以大约25Hz的帧率实时交互使用。

##### URL
[https://arxiv.org/abs/1609.05130](https://arxiv.org/abs/1609.05130)

##### PDF
[https://arxiv.org/pdf/1609.05130](https://arxiv.org/pdf/1609.05130)

