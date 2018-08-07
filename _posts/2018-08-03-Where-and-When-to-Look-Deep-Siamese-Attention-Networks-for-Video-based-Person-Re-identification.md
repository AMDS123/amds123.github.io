---
layout: post
title: "Where-and-When to Look: Deep Siamese Attention Networks for Video-based Person Re-identification"
date: 2018-08-03 01:07:03
categories: arXiv_CV
tags: arXiv_CV Re-identification Attention Person_Re-identification CNN
author: Lin Wu, Yang Wang, Junbin Gao, Xue Li
mathjax: true
---

* content
{:toc}

##### Abstract
Video-based person re-identification (re-id) is a central application in surveillance systems with significant concern in security. Matching persons across disjoint camera views in their video fragments is inherently challenging due to the large visual variations and uncontrolled frame rates. There are two steps crucial to person re-id, namely discriminative feature learning and metric learning. However, existing approaches consider the two steps independently, and they do not make full use of the temporal and spatial information in videos. In this paper, we propose a Siamese attention architecture that jointly learns spatiotemporal video representations and their similarity metrics. The network extracts local convolutional features from regions of each frame, and enhance their discriminative capability by focusing on distinct regions when measuring the similarity with another pedestrian video. The attention mechanism is embedded into spatial gated recurrent units to selectively propagate relevant features and memorize their spatial dependencies through the network. The model essentially learns which parts (\emph{where}) from which frames (\emph{when}) are relevant and distinctive for matching persons and attaches higher importance therein. The proposed Siamese model is end-to-end trainable to jointly learn comparable hidden representations for paired pedestrian videos and their similarity value. Extensive experiments on three benchmark datasets show the effectiveness of each component of the proposed deep network while outperforming state-of-the-art methods.

##### Abstract (translated by Google)
基于视频的人员重新识别（re-id）是监控系统中的一个核心应用，在安全性方面非常重要。由于大的视觉变化和不受控制的帧速率，在他们的视频片段中跨越不相交的摄像机视图匹配的人本身具有挑战性。人员重新评估有两个关键步骤，即歧视性特征学习和度量学习。然而，现有方法独立地考虑这两个步骤，并且它们没有充分利用视频中的时间和空间信息。在本文中，我们提出了一种暹罗注意力架构，它共同学习时空视频表示及其相似性度量。网络从每个帧的区域提取局部卷积特征，并且在测量与另一个行人视频的相似性时通过关注不同区域来增强它们的辨别能力。注意机制嵌入到空间门控循环单元中，以选择性地传播相关特征并通过网络记忆它们的空间依赖性。该模型基本上了解哪些部分（\ emph {where}）与哪些框架（\ emph {when}）相关并且与人匹配并在其中具有更高的重要性。拟议的Siamese模型是端到端的可训练的，以共同学习配对的行人视频及其相似性值的可比隐藏表示。对三个基准数据集的大量实验显示了所提出的深度网络的每个组成部分的有效性，同时优于最先进的方法。

##### URL
[https://arxiv.org/abs/1808.01911](https://arxiv.org/abs/1808.01911)

##### PDF
[https://arxiv.org/pdf/1808.01911](https://arxiv.org/pdf/1808.01911)

