---
layout: post
title: "Video Jigsaw: Unsupervised Learning of Spatiotemporal Context for Video Action Recognition"
date: 2018-08-22 18:18:44
categories: arXiv_CV
tags: arXiv_CV Tracking Action_Recognition Transfer_Learning Recognition
author: Unaiza Ahsan, Rishi Madhok, Irfan Essa
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a self-supervised learning method to jointly reason about spatial and temporal context for video recognition. Recent self-supervised approaches have used spatial context [9, 34] as well as temporal coherency [32] but a combination of the two requires extensive preprocessing such as tracking objects through millions of video frames [59] or computing optical flow to determine frame regions with high motion [30]. We propose to combine spatial and temporal context in one self-supervised framework without any heavy preprocessing. We divide multiple video frames into grids of patches and train a network to solve jigsaw puzzles on these patches from multiple frames. So the network is trained to correctly identify the position of a patch within a video frame as well as the position of a patch over time. We also propose a novel permutation strategy that outperforms random permutations while significantly reducing computational and memory constraints. We use our trained network for transfer learning tasks such as video activity recognition and demonstrate the strength of our approach on two benchmark video action recognition datasets without using a single frame from these datasets for unsupervised pretraining of our proposed video jigsaw network.

##### Abstract (translated by Google)
我们提出了一种自我监督的学习方法来共同推理视频识别的空间和时间背景。最近的自我监督方法使用了空间背景[9,34]以及时间一致性[32]，但两者的结合需要广泛的预处理，例如通过数百万个视频帧跟踪对象[59]或计算光流以确定帧高运动区域[30]。我们建议在一个自我监督的框架中结合空间和时间上下文，而不需要任何繁重的预处理。我们将多个视频帧划分为补丁网格并训练网络以解决来自多个帧的这些补丁上的拼图游戏。因此，网络经过训练，可以正确识别视频帧内补丁的位置以及补丁随时间的位置。我们还提出了一种新颖的置换策略，其优于随机排列，同时显着减少计算和内存约束。我们使用经过训练的网络进行视频活动识别等转移学习任务，并在两个基准视频动作识别数据集上展示我们的方法的优势，而无需使用这些数据集中的单个帧来进行我们提出的视频拼图网络的无监督预训练。

##### URL
[http://arxiv.org/abs/1808.07507](http://arxiv.org/abs/1808.07507)

##### PDF
[http://arxiv.org/pdf/1808.07507](http://arxiv.org/pdf/1808.07507)

