---
layout: post
title: "NDDR-CNN: Layer-wise Feature Fusing in Multi-Task CNN by Neural Discriminative Dimensionality Reduction"
date: 2018-01-25 07:38:52
categories: arXiv_CV
tags: arXiv_CV CNN
author: Yuan Gao, Qi She, Jiayi Ma, Mingbo Zhao, Wei Liu, Alan L. Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art Convolutional Neural Network (CNN) benefits a lot from multi-task learning (MTL), which learns multiple related tasks simultaneously to obtain shared or mutually related representations for different tasks. The most widely-used MTL CNN structure is based on an empirical or heuristic split on a specific layer (e.g., the last convolutional layer) to minimize different task-specific losses. However, this heuristic sharing/splitting strategy may be harmful to the final performance of one or multiple tasks. In this paper, we propose a novel CNN structure for MTL, which enables automatic feature fusing at every layer. Specifically, we first concatenate features from different tasks according to their channel dimension, and then formulate the feature fusing problem as discriminative dimensionality reduction. We show that this discriminative dimensionality reduction can be done by 1x1 Convolution, Batch Normalization, and Weight Decay in one CNN, which we refer to as Neural Discriminative Dimensionality Reduction (NDDR). We perform ablation analysis in details for different configurations in training the network. The experiments carried out on different network structures and different task sets demonstrate the promising performance and desirable generalizability of our proposed method.

##### Abstract (translated by Google)
最先进的卷积神经网络（CNN）从多任务学习（MTL）中受益匪浅，它可以同时学习多个相关任务，以获得不同任务的共享或相互关联的表示。最广泛使用的MTL CNN结构基于特定层（例如，最后一个卷积层）上的经验或启发式分割来最小化不同的任务特定损失。但是，这种启发式共享/拆分策略可能会对一个或多个任务的最终性能造成危害。在本文中，我们提出了一种新颖的MTN CNN结构，可以实现各层的自动特征融合。具体来说，我们首先根据不同的任务的信道维度来连接不同的任务，然后将特征融合问题作为区分维数约简。我们表明，这种有区别的降维可以通过1x1卷积，批量标准化和重量衰减在一个CNN中完成，我们称之为神经鉴别降维（NDDR）。我们在训练网络中对不同的配置进行详细的消融分析。在不同的网络结构和不同的任务集上进行的实验证明了我们提出的方法具有良好的性能和理想的推广能力。

##### URL
[http://arxiv.org/abs/1801.08297](http://arxiv.org/abs/1801.08297)

##### PDF
[http://arxiv.org/pdf/1801.08297](http://arxiv.org/pdf/1801.08297)

