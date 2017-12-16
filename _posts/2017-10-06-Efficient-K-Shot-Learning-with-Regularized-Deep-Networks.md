---
layout: post
title: "Efficient K-Shot Learning with Regularized Deep Networks"
date: 2017-10-06 05:07:28
categories: arXiv_CV
tags: arXiv_CV Regularization Reinforcement_Learning CNN Optimization Classification
author: Donghyun Yoo, Haoqi Fan, Vishnu Naresh Boddeti, Kris M. Kitani
mathjax: true
---

* content
{:toc}

##### Abstract
Feature representations from pre-trained deep neural networks have been known to exhibit excellent generalization and utility across a variety of related tasks. Fine-tuning is by far the simplest and most widely used approach that seeks to exploit and adapt these feature representations to novel tasks with limited data. Despite the effectiveness of fine-tuning, itis often sub-optimal and requires very careful optimization to prevent severe over-fitting to small datasets. The problem of sub-optimality and over-fitting, is due in part to the large number of parameters used in a typical deep convolutional neural network. To address these problems, we propose a simple yet effective regularization method for fine-tuning pre-trained deep networks for the task of k-shot learning. To prevent overfitting, our key strategy is to cluster the model parameters while ensuring intra-cluster similarity and inter-cluster diversity of the parameters, effectively regularizing the dimensionality of the parameter search space. In particular, we identify groups of neurons within each layer of a deep network that shares similar activation patterns. When the network is to be fine-tuned for a classification task using only k examples, we propagate a single gradient to all of the neuron parameters that belong to the same group. The grouping of neurons is non-trivial as neuron activations depend on the distribution of the input data. To efficiently search for optimal groupings conditioned on the input data, we propose a reinforcement learning search strategy using recurrent networks to learn the optimal group assignments for each network layer. Experimental results show that our method can be easily applied to several popular convolutional neural networks and improve upon other state-of-the-art fine-tuning based k-shot learning strategies by more than10%

##### Abstract (translated by Google)
来自预先训练的深度神经网络的特征表示已知在各种相关任务中表现出极好的概括性和实用性。微调是迄今为止最简单和最广泛使用的方法，试图利用有限的数据来利用和调整这些特征表示以适应新的任务。尽管微调的有效性，它往往是次优的，需要非常小心的优化，以防止严重的过度拟合小数据集。次优和过拟合的问题部分是由于在典型的深卷积神经网络中使用的大量参数。为了解决这些问题，我们提出了一种简单而有效的正则化方法，用于微调预训练的深度网络，用于k-shot学习的任务。为了防止过拟合，我们的核心策略是在保证参数间的相似性和簇间多样性的同时对模型参数进行聚类，有效地规范参数搜索空间的维数。具体而言，我们确定在深度网络的每个层中具有相似激活模式的神经元组。当仅仅使用k个例子对网络进行细化以用于分类任务时，我们将单个梯度传播到属于相同组的所有神经元参数。神经元的分组是不平凡的，因为神经元激活取决于输入数据的分布。为了有效地搜索以输入数据为条件的最优分组，我们提出了一种使用递归网络的强化学习搜索策略来学习每个网络层的最优分组分配。实验结果表明，我们的方法可以很容易地应用到几个流行的卷积神经网络，并改善其他最先进的基于微调的k-shot学习策略超过10％

##### URL
[https://arxiv.org/abs/1710.02277](https://arxiv.org/abs/1710.02277)

##### PDF
[https://arxiv.org/pdf/1710.02277](https://arxiv.org/pdf/1710.02277)

