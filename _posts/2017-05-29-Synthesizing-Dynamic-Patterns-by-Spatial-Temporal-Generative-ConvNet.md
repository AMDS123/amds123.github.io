---
layout: post
title: "Synthesizing Dynamic Patterns by Spatial-Temporal Generative ConvNet"
date: 2017-05-29 23:26:38
categories: arXiv_CV
tags: arXiv_CV
author: Jianwen Xie, Song-Chun Zhu, Ying Nian Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Video sequences contain rich dynamic patterns, such as dynamic texture patterns that exhibit stationarity in the temporal domain, and action patterns that are non-stationary in either spatial or temporal domain. We show that a spatial-temporal generative ConvNet can be used to model and synthesize dynamic patterns. The model defines a probability distribution on the video sequence, and the log probability is defined by a spatial-temporal ConvNet that consists of multiple layers of spatial-temporal filters to capture spatial-temporal patterns of different scales. The model can be learned from the training video sequences by an "analysis by synthesis" learning algorithm that iterates the following two steps. Step 1 synthesizes video sequences from the currently learned model. Step 2 then updates the model parameters based on the difference between the synthesized video sequences and the observed training sequences. We show that the learning algorithm can synthesize realistic dynamic patterns.

##### Abstract (translated by Google)
视频序列包含丰富的动态模式，例如在时域中表现出平稳性的动态纹理模式，以及在空域或时域中非平稳的动作模式。我们表明，一个时空生成ConvNet可以用来建模和综合动态模式。该模型定义了视频序列的概率分布，对数概率由空间 - 时间ConvNet定义，该空间 - 时间ConvNet由多层空间 - 时间滤波器组成，以捕获不同尺度的空间 - 时间模式。通过“分析合成”学习算法可以从训练视频序列中学习模型，迭代以下两个步骤。步骤1从当前学习的模型合成视频序列。步骤2然后基于合成的视频序列和观察到的训练序列之间的差异来更新模型参数。我们表明，学习算法可以合成逼真的动态模式。

##### URL
[https://arxiv.org/abs/1606.00972](https://arxiv.org/abs/1606.00972)

##### PDF
[https://arxiv.org/pdf/1606.00972](https://arxiv.org/pdf/1606.00972)

