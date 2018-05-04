---
layout: post
title: "Network Transplanting"
date: 2018-04-26 20:25:36
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Quanshi Zhang, Yu Yang, Ying Nian Wu, Song-Chun Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper focuses on a novel problem, i.e., transplanting a category-and-task-specific neural network to a generic, distributed network without strong supervision. Like playing LEGO blocks, incrementally constructing a generic network by asynchronously merging specific neural networks is a crucial bottleneck for deep learning. Suppose that the pre-trained specific network contains a module $f$ to extract features of the target category, and the generic network has a module $g$ for a target task, which is trained using other categories except for the target category. Instead of using numerous training samples to teach the generic network a new category, we aim to learn a small adapter module to connect $f$ and $g$ to accomplish the task on a target category in a weakly-supervised manner. The core challenge is to efficiently learn feature projections between the two connected modules. We propose a new distillation algorithm, which exhibited superior performance. Our method without training samples even significantly outperformed the baseline with 100 training samples.

##### Abstract (translated by Google)
本文着重讨论一个新的问题，即将一个类别和任务特定的神经网络移植到通用的分布式网络，而没有强有力的监督。就像玩乐高积木一样，通过异步合并特定的神经网络逐渐构建一个通用网络是深度学习的关键瓶颈。假设预先训练的特定网络包含一个模块$ f $来提取目标类别的特征，并且通用网络有一个用于目标任务的模块$ g $，该模块使用除目标类别之外的其他类别进行训练。我们的目标是学习一个小的适配器模块来连接$ f $和$ g $，以弱监督的方式完成目标类别的任务，而不是用大量的训练样本来教授通用网络。核心挑战是有效地学习两个连接模块之间的特征投影。我们提出了一种新的蒸馏算法，表现出优异的性能。我们没有训练样本的方法甚至在100个训练样本中显着优于基线。

##### URL
[https://arxiv.org/abs/1804.10272](https://arxiv.org/abs/1804.10272)

##### PDF
[https://arxiv.org/pdf/1804.10272](https://arxiv.org/pdf/1804.10272)

