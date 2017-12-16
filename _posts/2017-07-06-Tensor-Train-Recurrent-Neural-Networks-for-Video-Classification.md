---
layout: post
title: "Tensor-Train Recurrent Neural Networks for Video Classification"
date: 2017-07-06 13:43:14
categories: arXiv_CV
tags: arXiv_CV Video_Classification RNN Classification
author: Yinchong Yang, Denis Krompass, Volker Tresp
mathjax: true
---

* content
{:toc}

##### Abstract
The Recurrent Neural Networks and their variants have shown promising performances in sequence modeling tasks such as Natural Language Processing. These models, however, turn out to be impractical and difficult to train when exposed to very high-dimensional inputs due to the large input-to-hidden weight matrix. This may have prevented RNNs' large-scale application in tasks that involve very high input dimensions such as video modeling; current approaches reduce the input dimensions using various feature extractors. To address this challenge, we propose a new, more general and efficient approach by factorizing the input-to-hidden weight matrix using Tensor-Train decomposition which is trained simultaneously with the weights themselves. We test our model on classification tasks using multiple real-world video datasets and achieve competitive performances with state-of-the-art models, even though our model architecture is orders of magnitude less complex. We believe that the proposed approach provides a novel and fundamental building block for modeling high-dimensional sequential data with RNN architectures and opens up many possibilities to transfer the expressive and advanced architectures from other domains such as NLP to modeling high-dimensional sequential data.

##### Abstract (translated by Google)
递归神经网络及其变体在自然语言处理等顺序建模任务中表现出有前途的性能。然而，这些模型由于大的输入 - 隐藏权重矩阵而暴露于非常高维输入的情况下变得不切实际且难以训练。这可能妨碍了RNN在涉及很高输入维度的任务（如视频建模）中的大规模应用;目前的方法使用各种特征提取器来减小输入尺寸。为了解决这个挑战，我们提出了一种新的，更一般的和有效的方法，通过使用与权重本身同时训练的张量 - 列车分解来分解输入 - 隐藏权重矩阵。我们使用多个真实世界的视频数据集来测试我们的分类任务模型，并使用最先进的模型来实现竞争性的表现，即使我们的模型架构的复杂程度要低一个数量级。我们相信，所提出的方法提供了一个新的和基本的构建模块，用RNN架构建模高维时序数据，并开辟了许多可能性，从其他领域，如NLP表达式和高级体系结构转移到建模高维时序数据。

##### URL
[https://arxiv.org/abs/1707.01786](https://arxiv.org/abs/1707.01786)

##### PDF
[https://arxiv.org/pdf/1707.01786](https://arxiv.org/pdf/1707.01786)

