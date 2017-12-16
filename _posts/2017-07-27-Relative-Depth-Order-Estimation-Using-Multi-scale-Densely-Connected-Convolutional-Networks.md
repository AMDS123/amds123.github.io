---
layout: post
title: "Relative Depth Order Estimation Using Multi-scale Densely Connected Convolutional Networks"
date: 2017-07-27 10:19:13
categories: arXiv_CV
tags: arXiv_CV CNN
author: Ruoxi Deng, Tianqi Zhao, Chunhua Shen, Shengjun Liu
mathjax: true
---

* content
{:toc}

##### Abstract
We study the problem of estimating the relative depth order of point pairs in a monocular image. Recent advances mainly focus on using deep convolutional neural networks (DCNNs) to learn and infer the ordinal information from multiple contextual information of the points pair such as global scene context, local contextual information, and the locations. However, it remains unclear how much each context contributes to the task. To address this, we first examine the contribution of each context cue [1], [2] to the performance in the context of depth order estimation. We find out the local context surrounding the points pair contributes the most and the global scene context helps little. Based on the findings, we propose a simple method, using a multi-scale densely-connected network to tackle the task. Instead of learning the global structure, we dedicate to explore the local structure by learning to regress from regions of multiple sizes around the point pairs. Moreover, we use the recent densely connected network [3] to encourage substantial feature reuse as well as deepen our network to boost the performance. We show in experiments that the results of our approach is on par with or better than the state-of-the-art methods with the benefit of using only a small number of training data.

##### Abstract (translated by Google)
我们研究估计单眼图像中点对的相对深度阶的问题。最近的进展主要集中在使用深度卷积神经网络（DCNN）来从点对的多个上下文信息（例如全局场景上下文，局部上下文信息和位置）中学习和推断有序信息。然而，目前还不清楚每种情况对这项任务的贡献。为了解决这个问题，我们首先检查每个上下文提示[1]，[2]对深度序列估计的性能的贡献。我们发现点对的本地环境贡献最大，全球场景环境的帮助不大。根据研究结果，我们提出了一个简单的方法，使用多尺度密集连接网络来处理任务。我们不是学习全球结构，而是致力于通过学习从点对周围的多个大小的区域回归来探索局部结构。此外，我们使用最近的密集连接的网络[3]来鼓励实质性的特征重用，并且深化我们的网络以提高性能。我们在实验中表明，我们的方法的结果与仅使用少量训练数据的优点相比甚至优于最先进的方法。

##### URL
[https://arxiv.org/abs/1707.08063](https://arxiv.org/abs/1707.08063)

##### PDF
[https://arxiv.org/pdf/1707.08063](https://arxiv.org/pdf/1707.08063)

