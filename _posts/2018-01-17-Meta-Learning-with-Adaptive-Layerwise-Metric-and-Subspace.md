---
layout: post
title: "Meta-Learning with Adaptive Layerwise Metric and Subspace"
date: 2018-01-17 05:34:08
categories: arXiv_CV
tags: arXiv_CV Classification Gradient_Descent
author: Yoonho Lee, Seungjin Choi
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in meta-learning demonstrate that deep representations combined with the gradient descent method have sufficient capacity to approximate any learning algorithm. A promising approach is the model-agnostic meta-learning (MAML) which embeds gradient descent into the meta-learner. It optimizes for the initial parameters of the learner to warm-start the gradient descent updates, such that new tasks can be solved using a small number of examples. In this paper we elaborate the gradient-based meta-learning, developing two new schemes. First, we present a feedforward neural network, referred to as T-net, where the linear transformation between two adjacent layers is decomposed as T W such that W is learned by task-specific learners and the transformation T, which is shared across tasks, is meta-learned to speed up the convergence of gradient updates for task-specific learners. Second, we present MT-net where gradient updates in the T-net are guided by a binary mask M that is meta-learned, restricting the updates to be performed in a subspace. Empirical results demonstrate that our method is less sensitive to the choice of initial learning rates than existing meta-learning methods, and achieves the state-of-the-art or comparable performance on few-shot classification and regression tasks.

##### Abstract (translated by Google)
元学习的最新进展表明，深度表示与梯度下降法相结合，有足够的能力近似任何学习算法。一种很有前途的方法是模式不可知的元学习（MAML），它将梯度下降嵌入到元学习者中。它优化了学习者的初始参数以热启动梯度下降更新，从而使用少量的例子就可以解决新的任务。在本文中，我们详细阐述了基于渐变的元学习，开发两个新的方案。首先，我们提出一个前馈神经网络，称为T-net，其中两个相邻层之间的线性变换被分解为TW，使得W由任务特定的学习者学习，并且在任务之间共享的变换T是元学习来加速特定任务学习者渐变更新的收敛。其次，我们提出了MT-net，其中T网中的梯度更新由被元学习的二进制掩码M引导，限制更新在子空间中执行。实证结果表明，我们的方法对初始学习率的选择比现有的元学习方法更不敏感，并且在少数分类和回归任务上达到了最先进或可比较的性能。

##### URL
[http://arxiv.org/abs/1801.05558](http://arxiv.org/abs/1801.05558)

##### PDF
[http://arxiv.org/pdf/1801.05558](http://arxiv.org/pdf/1801.05558)

