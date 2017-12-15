---
layout: post
title: "Deep multi-scale video prediction beyond mean square error"
date: 2016-02-26 22:10:30
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge Tracking CNN RNN Prediction
author: Michael Mathieu, Camille Couprie, Yann LeCun
mathjax: true
---

* content
{:toc}

##### Abstract
Learning to predict future images from a video sequence involves the construction of an internal representation that models the image evolution accurately, and therefore, to some degree, its content and dynamics. This is why pixel-space video prediction may be viewed as a promising avenue for unsupervised feature learning. In addition, while optical flow has been a very studied problem in computer vision for a long time, future frame prediction is rarely approached. Still, many vision applications could benefit from the knowledge of the next frames of videos, that does not require the complexity of tracking every pixel trajectories. In this work, we train a convolutional network to generate future frames given an input sequence. To deal with the inherently blurry predictions obtained from the standard Mean Squared Error (MSE) loss function, we propose three different and complementary feature learning strategies: a multi-scale architecture, an adversarial training method, and an image gradient difference loss function. We compare our predictions to different published results based on recurrent neural networks on the UCF101 dataset

##### Abstract (translated by Google)
学习从视频序列中预测未来的图像需要构建一个内部表示，从而精确地模拟图像的演变过程，从而在一定程度上对其内容和动态进行建模。这就是为什么像素空间视频预测可能被看作是无监督特征学习的有希望的途径。另外，虽然光流长期以来一直是计算机视觉领域一个非常研究的问题，但未来的帧预测几乎没有涉及到。尽管如此，许多视觉应用程序可以从下一帧视频的知识中受益，而不需要追踪每个像素轨迹的复杂性。在这项工作中，我们训练一个卷积网络，在给定输入序列的情况下生成未来的帧。为了处理从标准均方误差（MSE）损失函数获得的内在模糊的预测，我们提出了三种不同的和互补的特征学习策略：多尺度结构，对抗训练方法和图像梯度差损失函数。我们将我们的预测与基于UCF101数据集上递归神经网络的不同发表结果进行比较

##### URL
[https://arxiv.org/abs/1511.05440](https://arxiv.org/abs/1511.05440)

##### PDF
[https://arxiv.org/pdf/1511.05440](https://arxiv.org/pdf/1511.05440)

