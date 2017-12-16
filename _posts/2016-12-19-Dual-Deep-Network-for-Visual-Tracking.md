---
layout: post
title: "Dual Deep Network for Visual Tracking"
date: 2016-12-19 06:01:30
categories: arXiv_CV
tags: arXiv_CV Regularization Object_Detection Tracking Quantitative Detection
author: Zhizhen Chi, Hongyang Li, Huchuan Lu, Ming-Hsuan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Visual tracking addresses the problem of identifying and localizing an unknown target in a video given the target specified by a bounding box in the first frame. In this paper, we propose a dual network to better utilize features among layers for visual tracking. It is observed that features in higher layers encode semantic context while its counterparts in lower layers are sensitive to discriminative appearance. Thus we exploit the hierarchical features in different layers of a deep model and design a dual structure to obtain better feature representation from various streams, which is rarely investigated in previous work. To highlight geometric contours of the target, we integrate the hierarchical feature maps with an edge detector as the coarse prior maps to further embed local details around the target. To leverage the robustness of our dual network, we train it with random patches measuring the similarities between the network activation and target appearance, which serves as a regularization to enforce the dual network to focus on target object. The proposed dual network is updated online in a unique manner based on the observation that the target being tracked in consecutive frames should share more similar feature representations than those in the surrounding background. It is also found that for a target object, the prior maps can help further enhance performance by passing message into the output maps of the dual network. Therefore, an independent component analysis with reference algorithm (ICA-R) is employed to extract target context using prior maps as guidance. Online tracking is conducted by maximizing the posterior estimate on the final maps with stochastic and periodic update. Quantitative and qualitative evaluations on two large-scale benchmark data sets show that the proposed algorithm performs favourably against the state-of-the-arts.

##### Abstract (translated by Google)
视觉追踪解决了给定由第一帧中的边界框指定的目标在视频中识别和本地化未知目标的问题。在本文中，我们提出了一个双重网络，以更好地利用层之间的特征进行视觉跟踪。据观察，较高层中的特征编码语义上下文，而较低层中的特征对辨别性外观敏感。因此，我们利用深层模型不同层次的层次特征，设计一个双重结构，以获得更好的来自各个流的特征表示，这在以前的工作中很少被调查。为了突出目标的几何轮廓，我们将阶层特征图与边缘检测器集成为粗略的先验图，以进一步在目标周围嵌入局部细节。为了充分利用双重网络的稳健性，我们用随机补丁来测量网络激活和目标外观之间的相似性，作为一个正规化来强化双重网络，把重点放在目标对象上。所提出的双网络以独特的方式在线更新，基于观察到连续帧中的目标被跟踪的目标应当共享比周围背景更多的相似特征表示。还发现对于目标对象，先前的映射可以通过将消息传递到双网络的输出映射中来帮助进一步提高性能。因此，利用参考算法（ICA-R）进行独立分量分析，以先验映射为指导，提取目标背景。在线跟踪是通过随机和定期更新最大化最终地图上的后验估计来进行的。对两个大型基准数据集进行的定量和定性评估表明，所提出的算法对于现有技术水平有利。

##### URL
[https://arxiv.org/abs/1612.06053](https://arxiv.org/abs/1612.06053)

##### PDF
[https://arxiv.org/pdf/1612.06053](https://arxiv.org/pdf/1612.06053)

