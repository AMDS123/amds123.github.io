---
layout: post
title: 'Bidirectional Multirate Reconstruction for Temporal Modeling in Videos'
date: 2017-12-06 08:02:43
categories: arXiv_CV
tags: arXiv_CV Video_Caption Caption Detection
author: Linchao Zhu, Zhongwen Xu, Yi Yang
---

* content
{:toc}

##### Abstract
Despite the recent success of neural networks in image feature learning, a major problem in the video domain is the lack of sufficient labeled data for learning to model temporal information. In this paper, we propose an unsupervised temporal modeling method that learns from untrimmed videos. The speed of motion varies constantly, e.g., a man may run quickly or slowly. We therefore train a Multirate Visual Recurrent Model (MVRM) by encoding frames of a clip with different intervals. This learning process makes the learned model more capable of dealing with motion speed variance. Given a clip sampled from a video, we use its past and future neighboring clips as the temporal context, and reconstruct the two temporal transitions, i.e., present$\rightarrow$past transition and present$\rightarrow$future transition, reflecting the temporal information in different views. The proposed method exploits the two transitions simultaneously by incorporating a bidirectional reconstruction which consists of a backward reconstruction and a forward reconstruction. We apply the proposed method to two challenging video tasks, i.e., complex event detection and video captioning, in which it achieves state-of-the-art performance. Notably, our method generates the best single feature for event detection with a relative improvement of 10.4% on the MEDTest-13 dataset and achieves the best performance in video captioning across all evaluation metrics on the YouTube2Text dataset.

##### Abstract (translated by Google)
尽管神经网络最近在图像特征学习中取得了成功，但视频领域的一个主要问题是缺乏足够的标记数据来学习对时间信息进行建模。在本文中，我们提出了一个无监督的时间建模方法，从未修剪的视频学习。运动的速度是不断变化的，例如，一个人可能跑得很快或者很慢。因此，我们通过编码具有不同间隔的剪辑的帧来训练多速率视觉递归模型（MVRM）。这个学习过程使得学习模型更有能力处理运动速度的变化。给定从视频中采样的剪辑，我们使用其过去和未来的相邻剪辑作为时间上下文，并重构两个时间转换，即呈现$ \ rightarrow $过渡并呈现$ \ rightarrow $ future转换，反映时间信息在不同的意见。所提出的方法同时利用两个转换，包括一个双向重建，包括一个向后重建和一个正向重建。我们将所提出的方法应用于两个具有挑战性的视频任务，即复杂的事件检测和视频字幕，其中实现了最先进的性能。值得注意的是，我们的方法为事件检测生成了最好的单一特征，在MEDTest-13数据集上相对提高了10.4％，并在YouTube2Text数据集上的所有评估指标中实现了最佳的视频字幕性能。

##### URL
[https://arxiv.org/abs/1611.09053](https://arxiv.org/abs/1611.09053)

