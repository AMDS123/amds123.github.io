---
layout: post
title: "VideoCapsuleNet: A Simplified Network for Action Detection"
date: 2018-05-21 16:28:47
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN CNN Classification Detection
author: Kevin Duarte, Yogesh S Rawat, Mubarak Shah
mathjax: true
---

* content
{:toc}

##### Abstract
The recent advances in Deep Convolutional Neural Networks (DCNNs) have shown extremely good results for video human action classification, however, action detection is still a challenging problem. The current action detection approaches follow a complex pipeline which involves multiple tasks such as tube proposals, optical flow, and tube classification. In this work, we present a more elegant solution for action detection based on the recently developed capsule network. We propose a 3D capsule network for videos, called VideoCapsuleNet: a unified network for action detection which can jointly perform pixel-wise action segmentation along with action classification. The proposed network is a generalization of capsule network from 2D to 3D, which takes a sequence of video frames as input. The 3D generalization drastically increases the number of capsules in the network, making capsule routing computationally expensive. We introduce capsule-pooling in the convolutional capsule layer to address this issue which makes the voting algorithm tractable. The routing-by-agreement in the network inherently models the action representations and various action characteristics are captured by the predicted capsules. This inspired us to utilize the capsules for action localization and the class-specific capsules predicted by the network are used to determine a pixel-wise localization of actions. The localization is further improved by parameterized skip connections with the convolutional capsule layers and the network is trained end-to-end with a classification as well as localization loss. The proposed network achieves sate-of-the-art performance on multiple action detection datasets including UCF-Sports, J-HMDB, and UCF-101 (24 classes) with an impressive ~20% improvement on UCF-101 and ~15% improvement on J-HMDB in terms of v-mAP scores.

##### Abstract (translated by Google)
深度卷积神经网络（DCNN）的最新进展已经显示出对于视频人类行为分类的非常好的结果，然而，动作检测仍然是一个具有挑战性的问题。目前的行动检测方法遵循复杂的管道，其涉及诸如管提议，光流和管分类等多项任务。在这项工作中，我们为基于最近开发的胶囊网络的动作检测提出了更优雅的解决方案。我们提出了一个称为VideoCapsuleNet的视频三维胶囊网络：一个统一的网络行动检测，可以联合执行像素明智的行动分割与行动分类。所提出的网络是从2D到3D的胶囊网络的推广，其将一系列视频帧作为输入。 3D通用化极大地增加了网络中胶囊的数量，使胶囊路由在计算上花费很大。我们在卷积胶囊层中引入胶囊池以解决这个问题，这使得投票算法易于处理。网络中的路由协议固有地模拟动作表示，并且各种动作特征由预测的胶囊捕获。这激励我们利用胶囊进行动作定位，并使用网络预测的类特定胶囊来确定动作的像素定位。通过卷积胶囊层的参数化跳过连接进一步改善了本地化，网络通过分类和本地化损失进行端对端培训。所提出的网络在包括UCF-Sports，J-HMDB和UCF-101（24类）在内的多种动作检测数据集上达到了最先进的性能，UCF-101的改进效果大大提高了〜20％，提高了约15％在v-mAP分数方面在J-HMDB上。

##### URL
[https://arxiv.org/abs/1805.08162](https://arxiv.org/abs/1805.08162)

##### PDF
[https://arxiv.org/pdf/1805.08162](https://arxiv.org/pdf/1805.08162)

