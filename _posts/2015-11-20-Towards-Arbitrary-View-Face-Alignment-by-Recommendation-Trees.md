---
layout: post
title: "Towards Arbitrary-View Face Alignment by Recommendation Trees"
date: 2015-11-20 15:01:21
categories: arXiv_CV
tags: arXiv_CV Face Pose_Estimation Relation Recommendation
author: Shizhan Zhu, Cheng Li, Chen Change Loy, Xiaoou Tang
mathjax: true
---

* content
{:toc}

##### Abstract
Learning to simultaneously handle face alignment of arbitrary views, e.g. frontal and profile views, appears to be more challenging than we thought. The difficulties lay in i) accommodating the complex appearance-shape relations exhibited in different views, and ii) encompassing the varying landmark point sets due to self-occlusion and different landmark protocols. Most existing studies approach this problem via training multiple viewpoint-specific models, and conduct head pose estimation for model selection. This solution is intuitive but the performance is highly susceptible to inaccurate head pose estimation. In this study, we address this shortcoming through learning an Ensemble of Model Recommendation Trees (EMRT), which is capable of selecting optimal model configuration without prior head pose estimation. The unified framework seamlessly handles different viewpoints and landmark protocols, and it is trained by optimising directly on landmark locations, thus yielding superior results on arbitrary-view face alignment. This is the first study that performs face alignment on the full AFLWdataset with faces of different views including profile view. State-of-the-art performances are also reported on MultiPIE and AFW datasets containing both frontaland profile-view faces.

##### Abstract (translated by Google)
学习同时处理任意视图的脸部对齐，例如正面和剖面视图，似乎比我们想象的更具挑战性。困难在于：1）适应不同观点展现的复杂的外观形状关系; 2）由于自我遮挡和不同的地标协议，涵盖不同的界标点集。大多数现有的研究通过训练多个视点特定的模型来解决这个问题，并进行头部姿态估计以用于模型选择。该解决方案非常直观，但性能很容易受到不准确的头部姿态估计的影响。在这项研究中，我们通过学习模型推荐树（EMRT）的集合来解决这个缺点，该集合能够在没有事先头部姿态估计的情况下选择最优模型配置。统一的框架可以无缝地处理不同的视点和地标协议，并且通过直接在地标位置进行优化来训练，从而在任意视角人脸对齐方面产生出色的效果。这是第一个在完整的AFLW数据集上进行脸部对齐的研究，脸部包含不同的视图，包括配置文件视图。在MultiPIE和AFW数据集上也报道了最先进的表现，这些数据集包含了frontaland剖面图。

##### URL
[https://arxiv.org/abs/1511.06627](https://arxiv.org/abs/1511.06627)

##### PDF
[https://arxiv.org/pdf/1511.06627](https://arxiv.org/pdf/1511.06627)

