---
layout: post
title: "Self-Supervised Video Hashing with Hierarchical Binary Auto-encoder"
date: 2018-02-07 04:31:19
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Jingkuan Song, Hanwang Zhang, Xiangpeng Li, Lianli Gao, Meng Wang, Richang Hong
mathjax: true
---

* content
{:toc}

##### Abstract
Existing video hash functions are built on three isolated stages: frame pooling, relaxed learning, and binarization, which have not adequately explored the temporal order of video frames in a joint binary optimization model, resulting in severe information loss. In this paper, we propose a novel unsupervised video hashing framework dubbed Self-Supervised Video Hashing (SSVH), that is able to capture the temporal nature of videos in an end-to-end learning-to-hash fashion. We specifically address two central problems: 1) how to design an encoder-decoder architecture to generate binary codes for videos; and 2) how to equip the binary codes with the ability of accurate video retrieval. We design a hierarchical binary autoencoder to model the temporal dependencies in videos with multiple granularities, and embed the videos into binary codes with less computations than the stacked architecture. Then, we encourage the binary codes to simultaneously reconstruct the visual content and neighborhood structure of the videos. Experiments on two real-world datasets (FCVID and YFCC) show that our SSVH method can significantly outperform the state-of-the-art methods and achieve the currently best performance on the task of unsupervised video retrieval.

##### Abstract (translated by Google)
现有的视频哈希函数建立在三个孤立的阶段：帧合并，放松学习和二值化，没有充分地探索联合二进制优化模型中视频帧的时间顺序，导致严重的信息损失。在本文中，我们提出了一种称为自监督视频散列（SSVH）的新型无监督视频哈希框架，它能够以端到端的学习哈希方式捕捉视频的时间特性。我们具体解决了两个中心问题：1）如何设计编码器 - 解码器架构来生成视频的二进制码; 2）如何配置二进制码具有准确的视频检索能力。我们设计了一个分层二进制自动编码器来对多个粒度的视频中的时间依赖性进行建模，并将视频嵌入到比堆栈体系结构更少的计算量的二进制代码中。然后，我们鼓励二进制代码同时重建视频的视觉内容和邻域结构。在两个真实世界的数据集（FCVID和YFCC）上的实验表明，我们的SSVH方法可以显着地胜过最先进的方法，并实现当前在无监督视频检索任务中的最佳性能。

##### URL
[https://arxiv.org/abs/1802.02305](https://arxiv.org/abs/1802.02305)

##### PDF
[https://arxiv.org/pdf/1802.02305](https://arxiv.org/pdf/1802.02305)

