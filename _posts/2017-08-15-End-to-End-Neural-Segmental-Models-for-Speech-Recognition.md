---
layout: post
title: "End-to-End Neural Segmental Models for Speech Recognition"
date: 2017-08-15 16:29:05
categories: arXiv_CL
tags: arXiv_CL Review Speech_Recognition RNN Prediction Recognition
author: Hao Tang, Liang Lu, Lingpeng Kong, Kevin Gimpel, Karen Livescu, Chris Dyer, Noah A. Smith, Steve Renals
mathjax: true
---

* content
{:toc}

##### Abstract
Segmental models are an alternative to frame-based models for sequence prediction, where hypothesized path weights are based on entire segment scores rather than a single frame at a time. Neural segmental models are segmental models that use neural network-based weight functions. Neural segmental models have achieved competitive results for speech recognition, and their end-to-end training has been explored in several studies. In this work, we review neural segmental models, which can be viewed as consisting of a neural network-based acoustic encoder and a finite-state transducer decoder. We study end-to-end segmental models with different weight functions, including ones based on frame-level neural classifiers and on segmental recurrent neural networks. We study how reducing the search space size impacts performance under different weight functions. We also compare several loss functions for end-to-end training. Finally, we explore training approaches, including multi-stage vs. end-to-end training and multitask training that combines segmental and frame-level losses.

##### Abstract (translated by Google)
分段模型是用于序列预测的基于帧的模型的替代方案，其中假设的路径权重基于整个分段分数而不是一次一帧。神经节段模型是使用基于神经网络的权重函数的节段模型。神经节段模型已经在语音识别方面取得了有竞争力的结果，并且在一些研究中已经探索了它们的端到端训练。在这项工作中，我们回顾了神经节段模型，它可以被看作是由一个基于神经网络的声学编码器和一个有限状态传感器解码器组成的。我们研究具有不同权重函数的端到端分段模型，包括基于帧级神经分类器和分段递归神经网络的模型。我们研究如何减少搜索空间大小在不同的权重函数下影响性能。我们还比较了几种端到端培训的损失函数。最后，我们探讨了培训方法，包括多阶段与端到端的培训以及结合了分段和框架级损失的多任务培训。

##### URL
[https://arxiv.org/abs/1708.00531](https://arxiv.org/abs/1708.00531)

##### PDF
[https://arxiv.org/pdf/1708.00531](https://arxiv.org/pdf/1708.00531)

