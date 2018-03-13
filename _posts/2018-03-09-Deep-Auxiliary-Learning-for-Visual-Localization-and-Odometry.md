---
layout: post
title: "Deep Auxiliary Learning for Visual Localization and Odometry"
date: 2018-03-09 11:56:57
categories: arXiv_RO
tags: arXiv_RO CNN Inference Deep_Learning
author: Abhinav Valada, Noha Radwan, Wolfram Burgard
mathjax: true
---

* content
{:toc}

##### Abstract
Localization is an indispensable component of a robot's autonomy stack that enables it to determine where it is in the environment, essentially making it a precursor for any action execution or planning. Although convolutional neural networks have shown promising results for visual localization, they are still grossly outperformed by state-of-the-art local feature-based techniques. In this work, we propose VLocNet, a new convolutional neural network architecture for 6-DoF global pose regression and odometry estimation from consecutive monocular images. Our multitask model incorporates hard parameter sharing, thus being compact and enabling real-time inference, in addition to being end-to-end trainable. We propose a novel loss function that utilizes auxiliary learning to leverage relative pose information during training, thereby constraining the search space to obtain consistent pose estimates. We evaluate our proposed VLocNet on indoor as well as outdoor datasets and show that even our single task model exceeds the performance of state-of-the-art deep architectures for global localization, while achieving competitive performance for visual odometry estimation. Furthermore, we present extensive experimental evaluations utilizing our proposed Geometric Consistency Loss that show the effectiveness of multitask learning and demonstrate that our model is the first deep learning technique to be on par with, and in some cases outperforms state-of-the-art SIFT-based approaches.

##### Abstract (translated by Google)
本地化是机器人自治栈不可缺少的组成部分，它使它能够确定它在环境中的位置，实质上使它成为任何行动执行或规划的前兆。尽管卷积神经网络在视觉定位方面显示出了有希望的结果，但它们仍然通过最先进的基于本地特征的技术而大大超越。在这项工作中，我们提出VLocNet，一种新的卷积神经网络架构，用于从连续单目图像中进行6-DoF全局姿态回归和测距估计。我们的多任务模型融合了难以分享的参数，因此除了可以进行端到端的可训练之外，还可以实现紧凑的实时推断。我们提出了一种新的损失函数，利用辅助学习在训练期间利用相对姿态信息，从而约束搜索空间以获得一致的姿态估计。我们评估了我们在室内和室外数据集上提出的VLocNet，并表明，即使我们的单一任务模型也超过了用于全球本地化的最先进深层架构的性能，同时实现视觉测距估计的竞争性能。此外，我们提出了广泛的实验评估利用我们提出的几何一致性损失，显示了多任务学习的有效性，并证明我们的模型是第一个深入的学习技术，可以与之相提并论，并且在某些情况下胜过了最先进的SIFT基于方法。

##### URL
[http://arxiv.org/abs/1803.03642](http://arxiv.org/abs/1803.03642)

##### PDF
[http://arxiv.org/pdf/1803.03642](http://arxiv.org/pdf/1803.03642)

