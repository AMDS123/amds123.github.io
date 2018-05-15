---
layout: post
title: "Unsupervised Intuitive Physics from Visual Observations"
date: 2018-05-14 09:41:23
categories: arXiv_AI
tags: arXiv_AI Salient Knowledge CNN
author: Sebastien Ehrhardt, Aron Monszpart, Niloy Mitra, Andrea Vedaldi
mathjax: true
---

* content
{:toc}

##### Abstract
While learning models of intuitive physics is an increasingly active area of research, current approaches still fall short of natural intelligences in one important regard: they require external supervision, such as explicit access to physical states, at training and sometimes even at test times. Some authors have relaxed such requirements by supplementing the model with an handcrafted physical simulator. Still, the resulting methods are unable to automatically learn new complex environments and to understand physical interactions within them. In this work, we demonstrated for the first time learning such predictors directly from raw visual observations and without relying on simulators. We do so in two steps: first, we learn to track mechanically-salient objects in videos using causality and equivariance, two unsupervised learning principles that do not require auto-encoding. Second, we demonstrate that the extracted positions are sufficient to successfully train visual motion predictors that can take the underlying environment into account. We validate our predictors on synthetic datasets; then, we introduce a new dataset, ROLL4REAL, consisting of real objects rolling on complex terrains (pool table, elliptical bowl, and random height-field). We show that in all such cases it is possible to learn reliable extrapolators of the object trajectories from raw videos alone, without any form of external supervision and with no more prior knowledge than the choice of a convolutional neural network architecture.

##### Abstract (translated by Google)
虽然直觉物理学习模型是一个日益活跃的研究领域，但目前的方法在一个重要方面仍然缺乏自然智能：它们需要外部监督，例如明确访问物理状态，在培训中，有时甚至在测试时间。一些作者通过用手工物理模拟器补充模型来放宽这些要求。但是，最终的方法无法自动学习新的复杂环境并理解其中的物理交互。在这项工作中，我们第一次直接从原始视觉观察中直接学习这些预测因子，而不依赖模拟器。我们分两步进行：首先，我们学习使用因果关系和等式来跟踪视频中的机械显着对象，这两个无监督学习原则不需要自动编码。其次，我们证明提取的位置足以成功训练可考虑底层环境的视觉运动预测器。我们验证了合成数据集的预测结果;然后，我们引入一个新的数据集ROLL4REAL，它由在复杂的地形（台球桌，椭圆形碗和随机高度场）上滚动的真实物体组成。我们表明，在所有这些情况下，可以单独从原始视频中学习对象轨迹的可靠外推器，而不需要任何外部监督形式，并且没有比卷积神经网络架构的选择更多的先验知识。

##### URL
[https://arxiv.org/abs/1805.05086](https://arxiv.org/abs/1805.05086)

##### PDF
[https://arxiv.org/pdf/1805.05086](https://arxiv.org/pdf/1805.05086)

