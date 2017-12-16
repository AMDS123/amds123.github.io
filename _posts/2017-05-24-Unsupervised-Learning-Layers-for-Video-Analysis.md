---
layout: post
title: "Unsupervised Learning Layers for Video Analysis"
date: 2017-05-24 18:22:41
categories: arXiv_CV
tags: arXiv_CV CNN
author: Liang Zhao, Yang Wang, Yi Yang, Wei Xu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents two unsupervised learning layers (UL layers) for label-free video analysis: one for fully connected layers, and the other for convolutional ones. The proposed UL layers can play two roles: they can be the cost function layer for providing global training signal; meanwhile they can be added to any regular neural network layers for providing local training signals and combined with the training signals backpropagated from upper layers for extracting both slow and fast changing features at layers of different depths. Therefore, the UL layers can be used in either pure unsupervised or semi-supervised settings. Both a closed-form solution and an online learning algorithm for two UL layers are provided. Experiments with unlabeled synthetic and real-world videos demonstrated that the neural networks equipped with UL layers and trained with the proposed online learning algorithm can extract shape and motion information from video sequences of moving objects. The experiments demonstrated the potential applications of UL layers and online learning algorithm to head orientation estimation and moving object localization.

##### Abstract (translated by Google)
本文提出了两个无监督学习层（UL层）用于无标签视频分析：一个用于完全连接的层，另一个用于卷积。所提出的UL层可以扮演两个角色：它们可以是用于提供全局训练信号的成本函数层;同时可以添加到任何规则的神经网络层，提供本地训练信号，并结合上层反向传播的训练信号，提取不同深度层次的慢速和快速变化特征。因此，UL层可以用于纯粹的无监督或半监督的设置。提供了用于两个UL层的闭合解决方案和在线学习算法。对未标记的合成视频和现实世界的视频的实验表明，配备有UL层并利用所提出的在线学习算法训练的神经网络可以从运动对象的视频序列中提取形状和运动信息。实验证明了UL层和在线学习算法在头部定位估计和移动物体定位中的潜在应用。

##### URL
[https://arxiv.org/abs/1705.08918](https://arxiv.org/abs/1705.08918)

##### PDF
[https://arxiv.org/pdf/1705.08918](https://arxiv.org/pdf/1705.08918)

