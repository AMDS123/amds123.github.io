---
layout: post
title: "Boundary Optimizing Network"
date: 2018-01-08 19:02:44
categories: arXiv_CV
tags: arXiv_CV Classification
author: Marco Singh, Akshay Pai
mathjax: true
---

* content
{:toc}

##### Abstract
Despite all the success that deep neural networks have seen in classifying certain datasets, the challenge of finding optimal solutions that generalize well still remains. In this paper, we propose the Boundary Optimizing Network (BON), a new approach to generalization for deep neural networks when used for supervised learning. Given a classification network, we propose to use a collaborative generative network that produces new synthetic data points in the form of perturbations of original data points. In this way, we create a data support around each original data point which prevents decision boundaries to pass too close to the original data points, i.e. prevents overfitting. To prevent catastrophic forgetting during training, we propose to use a variation of Memory Aware Synapses to optimize the generative networks. On the Iris dataset, we show that the BON algorithm creates better decision boundaries when compared to a network regularized by the popular dropout scheme.

##### Abstract (translated by Google)
尽管深度神经网络在对某些数据集进行分类时看到了所有的成功，但找到最佳解决方案的挑战依然存在。在本文中，我们提出边界优化网络（BON），这是一种深度神经网络用于监督学习的新方法。给定分类网络，我们建议使用协作生成网络，以原始数据点的扰动形式产生新的合成数据点。这样，我们在每个原始数据点周围创建一个数据支持，防止决策边界过于靠近原始数据点，即防止过度拟合。为了防止培训期间的灾难性遗忘，我们建议使用Memory Aware Synapses的变体来优化生成网络。在Iris数据集上，我们展示了BON算法创建更好的决策边界相比，由流行的退路计划正规化的网络。

##### URL
[http://arxiv.org/abs/1801.02642](http://arxiv.org/abs/1801.02642)

##### PDF
[http://arxiv.org/pdf/1801.02642](http://arxiv.org/pdf/1801.02642)

