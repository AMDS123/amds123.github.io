---
layout: post
title: "Tracking Persons-of-Interest via Unsupervised Representation Adaptation"
date: 2017-10-05 17:58:28
categories: arXiv_CV
tags: arXiv_CV Face Tracking Embedding CNN
author: Shun Zhang, Jia-Bin Huang, Jongwoo Lim, Yihong Gong, Jinjun Wang, Narendra Ahuja, Ming-Hsuan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-face tracking in unconstrained videos is a challenging problem as faces of one person often appear drastically different in multiple shots due to significant variations in scale, pose, expression, illumination, and make-up. Existing multi-target tracking methods often use low-level features which are not sufficiently discriminative for identifying faces with such large appearance variations. In this paper, we tackle this problem by learning discriminative, video-specific face representations using convolutional neural networks (CNNs). Unlike existing CNN-based approaches which are only trained on large-scale face image datasets offline, we use the contextual constraints to generate a large number of training samples for a given video, and further adapt the pre-trained face CNN to specific videos using discovered training samples. Using these training samples, we optimize the embedding space so that the Euclidean distances correspond to a measure of semantic face similarity via minimizing a triplet loss function. With the learned discriminative features, we apply the hierarchical clustering algorithm to link tracklets across multiple shots to generate trajectories. We extensively evaluate the proposed algorithm on two sets of TV sitcoms and YouTube music videos, analyze the contribution of each component, and demonstrate significant performance improvement over existing techniques.

##### Abstract (translated by Google)
无约束视频中的多面孔跟踪是一个具有挑战性的问题，因为一个人的面孔由于尺度，姿势，表情，照明和化妆方面的显着变化而经常在多张照片中显得截然不同。现有的多目标跟踪方法通常使用低级特征，这些特征对于识别具有如此大的外观变化的人脸而言不具有足够的区分性。在本文中，我们通过使用卷积神经网络（CNN）学习视频特定的人脸表征来解决这个问题。与现有的仅基于大规模人脸图像数据集离线训练的基于CNN的方法不同，我们使用上下文约束条件为给定的视频生成大量的训练样本，并进一步将预先训练的人脸CNN调整为使用特定的视频发现了训练样本。使用这些训练样本，我们优化嵌入空间，使欧几里得距离通过最小化三重损失函数对应于语义面部相似度的度量。利用学习的判别特征，我们应用层次聚类算法来连接多个镜头的轨迹以产生轨迹。我们对两套电视连续剧和YouTube音乐视频的算法进行了广泛的评估，分析了每个组件的贡献，并展示了相对于现有技术的显着的性能改进。

##### URL
[https://arxiv.org/abs/1710.02139](https://arxiv.org/abs/1710.02139)

##### PDF
[https://arxiv.org/pdf/1710.02139](https://arxiv.org/pdf/1710.02139)

