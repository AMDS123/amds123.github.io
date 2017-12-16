---
layout: post
title: "ArtTrack: Articulated Multi-person Tracking in the Wild"
date: 2017-05-09 09:56:46
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Tracking CNN Inference Detection Relation
author: Eldar Insafutdinov, Mykhaylo Andriluka, Leonid Pishchulin, Siyu Tang, Evgeny Levinkov, Bjoern Andres, Bernt Schiele
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose an approach for articulated tracking of multiple people in unconstrained videos. Our starting point is a model that resembles existing architectures for single-frame pose estimation but is substantially faster. We achieve this in two ways: (1) by simplifying and sparsifying the body-part relationship graph and leveraging recent methods for faster inference, and (2) by offloading a substantial share of computation onto a feed-forward convolutional architecture that is able to detect and associate body joints of the same person even in clutter. We use this model to generate proposals for body joint locations and formulate articulated tracking as spatio-temporal grouping of such proposals. This allows to jointly solve the association problem for all people in the scene by propagating evidence from strong detections through time and enforcing constraints that each proposal can be assigned to one person only. We report results on a public MPII Human Pose benchmark and on a new MPII Video Pose dataset of image sequences with multiple people. We demonstrate that our model achieves state-of-the-art results while using only a fraction of time and is able to leverage temporal information to improve state-of-the-art for crowded scenes.

##### Abstract (translated by Google)
在这篇论文中，我们提出了一种在无约束视频中对多个人进行连接跟踪的方法。我们的出发点是与单帧姿态估计的现有体系结构相似的模型，但速度更快。我们通过两种方式来实现这一点：（1）通过简化和稀疏身体部分关系图并利用最近的方法进行更快的推理，以及（2）通过将大量计算卸载到前馈卷积体系结构上，即使在杂乱无章的情况下也能检测出同一个人的身体关节。我们使用这个模型来生成身体关节位置的建议，并制定明确的跟踪作为这些建议的时空分组。这允许联合解决场景中所有人的关联问题，通过强大的检测传播证据到时间，并强制约束每个提议只能分配给一个人。我们报告了一个公共MPII人体姿态基准和一个新的多人MPII视频姿势数据集的结果。我们证明，我们的模型在仅使用一小部分时间的情况下实现了最先进的结果，并且能够利用时间信息来改善拥挤场景的最新状态。

##### URL
[https://arxiv.org/abs/1612.01465](https://arxiv.org/abs/1612.01465)

##### PDF
[https://arxiv.org/pdf/1612.01465](https://arxiv.org/pdf/1612.01465)

