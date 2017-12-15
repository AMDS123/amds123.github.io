---
layout: post
title: "Learning Dense Correspondence via 3D-guided Cycle Consistency"
date: 2016-04-18 23:50:40
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Tinghui Zhou, Philipp Krähenbühl, Mathieu Aubry, Qixing Huang, Alexei A. Efros
mathjax: true
---

* content
{:toc}

##### Abstract
Discriminative deep learning approaches have shown impressive results for problems where human-labeled ground truth is plentiful, but what about tasks where labels are difficult or impossible to obtain? This paper tackles one such problem: establishing dense visual correspondence across different object instances. For this task, although we do not know what the ground-truth is, we know it should be consistent across instances of that category. We exploit this consistency as a supervisory signal to train a convolutional neural network to predict cross-instance correspondences between pairs of images depicting objects of the same category. For each pair of training images we find an appropriate 3D CAD model and render two synthetic views to link in with the pair, establishing a correspondence flow 4-cycle. We use ground-truth synthetic-to-synthetic correspondences, provided by the rendering engine, to train a ConvNet to predict synthetic-to-real, real-to-real and real-to-synthetic correspondences that are cycle-consistent with the ground-truth. At test time, no CAD models are required. We demonstrate that our end-to-end trained ConvNet supervised by cycle-consistency outperforms state-of-the-art pairwise matching methods in correspondence-related tasks.

##### Abstract (translated by Google)
区分深度学习方法已经显示了人类标记的基本事实丰富的问题​​的令人印象深刻的结果，但标签很难或不可能获得的任务呢？本文解决了一个这样的问题：在不同的对象实例之间建立密集的视觉对应。对于这个任务，虽然我们不知道什么是事实根据，但是我们知道这个事实应该是一致的。我们利用这种一致性作为监督信号来训练卷积神经网络来预测描绘同一类别的对象的图像对之间的跨实例对应关系。对于每一对训练图像，我们找到一个合适的三维CAD模型，并呈现两个合成视图链接到一对，建立一个对应流程4个周期。我们使用由渲染引擎提供的地面真实合成到合成对应来训练ConvNet，以预测与地面周期一致的合成到真实，真实到真实和真实到合成的对应关系-真相。在测试时间，不需要CAD模型。我们证明，我们的端到端训练的ConvNet在循环一致性监督下胜过对应相关任务中最先进的成对匹配方法。

##### URL
[https://arxiv.org/abs/1604.05383](https://arxiv.org/abs/1604.05383)

##### PDF
[https://arxiv.org/pdf/1604.05383](https://arxiv.org/pdf/1604.05383)

