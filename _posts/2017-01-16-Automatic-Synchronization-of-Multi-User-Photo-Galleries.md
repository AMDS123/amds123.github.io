---
layout: post
title: "Automatic Synchronization of Multi-User Photo Galleries"
date: 2017-01-16 11:19:49
categories: arXiv_CV
tags: arXiv_CV CNN
author: E. Sansone, K. Apostolidis, N. Conci, G. Boato, V. Mezaris, F.G.B. De Natale
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we address the issue of photo galleries synchronization, where pictures related to the same event are collected by different users. Existing solutions to address the problem are usually based on unrealistic assumptions, like time consistency across photo galleries, and often heavily rely on heuristics, limiting therefore the applicability to real-world scenarios. We propose a solution that achieves better generalization performance for the synchronization task compared to the available literature. The method is characterized by three stages: at first, deep convolutional neural network features are used to assess the visual similarity among the photos; then, pairs of similar photos are detected across different galleries and used to construct a graph; eventually, a probabilistic graphical model is used to estimate the temporal offset of each pair of galleries, by traversing the minimum spanning tree extracted from this graph. The experimental evaluation is conducted on four publicly available datasets covering different types of events, demonstrating the strength of our proposed method. A thorough discussion of the obtained results is provided for a critical assessment of the quality in synchronization.

##### Abstract (translated by Google)
在本文中，我们解决了照片画廊同步的问题，与同一事件相关的图片被不同的用户收集。解决问题的现有解决方案通常基于不切实际的假设，如照片画廊的时间一致性，往往严重依赖启发式，因此限制了现实世界场景的适用性。与现有文献相比，我们提出了一种解决方案，可以为同步任务实现更好的泛化性能。该方法具有三个阶段特征：首先，利用深卷积神经网络特征来评估图片间的视觉相似度;然后，在不同的画廊之间检测到成对的相似照片，并用于构建图表;最终，通过遍历从该图提取的最小生成树，使用概率图模型来估计每一对画廊的时间偏移。实验评估是在四个公开可用的数据集上进行的，涉及不同类型的事件，证明了我们提出的方法的强度。对获得的结果进行全面讨论，以便对同步质量进行关键评估。

##### URL
[https://arxiv.org/abs/1608.06770](https://arxiv.org/abs/1608.06770)

##### PDF
[https://arxiv.org/pdf/1608.06770](https://arxiv.org/pdf/1608.06770)

