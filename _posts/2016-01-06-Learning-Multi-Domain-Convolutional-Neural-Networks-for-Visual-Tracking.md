---
layout: post
title: "Learning Multi-Domain Convolutional Neural Networks for Visual Tracking"
date: 2016-01-06 06:14:53
categories: arXiv_CV
tags: arXiv_CV Tracking CNN Classification
author: Hyeonseob Nam, Bohyung Han
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel visual tracking algorithm based on the representations from a discriminatively trained Convolutional Neural Network (CNN). Our algorithm pretrains a CNN using a large set of videos with tracking ground-truths to obtain a generic target representation. Our network is composed of shared layers and multiple branches of domain-specific layers, where domains correspond to individual training sequences and each branch is responsible for binary classification to identify the target in each domain. We train the network with respect to each domain iteratively to obtain generic target representations in the shared layers. When tracking a target in a new sequence, we construct a new network by combining the shared layers in the pretrained CNN with a new binary classification layer, which is updated online. Online tracking is performed by evaluating the candidate windows randomly sampled around the previous target state. The proposed algorithm illustrates outstanding performance compared with state-of-the-art methods in existing tracking benchmarks.

##### Abstract (translated by Google)
我们提出了一种新颖的视觉跟踪算法的基础上表示从一个歧视训练卷积神经网络（CNN）。我们的算法使用大量视频追踪地面真值来预先训练CNN，以获得通用的目标表示。我们的网络由共享层和特定领域层的多个分支组成，其中领域对应于单独的训练序列，并且每个分支负责二进制分类以识别每个领域中的目标。我们针对每个域迭代地训练网络以获得共享层中的通用目标表示。当以新序列跟踪目标时，我们通过将预训练的CNN中的共享层与新的在线更新的二元分类层相结合来构建新的网络。通过评估在前一个目标状态周围随机采样的候选窗口来进行在线跟踪。与现有跟踪基准中的最新方法相比，所提出的算法表现出优异的性能。

##### URL
[https://arxiv.org/abs/1510.07945](https://arxiv.org/abs/1510.07945)

##### PDF
[https://arxiv.org/pdf/1510.07945](https://arxiv.org/pdf/1510.07945)

