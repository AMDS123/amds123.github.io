---
layout: post
title: "Class Subset Selection for Transfer Learning using Submodularity"
date: 2018-03-30 21:36:59
categories: arXiv_CV
tags: arXiv_CV Image_Classification Transfer_Learning Classification
author: Varun Manjunatha, Srikumar Ramalingam, Tim K. Marks, Larry Davis
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, it is common practice to extract fully-connected layer (fc) features that were learned while performing image classification on a source dataset, such as ImageNet, and apply them generally to a wide range of other tasks. The general usefulness of some large training datasets for transfer learning is not yet well understood, and raises a number of questions. For example, in the context of transfer learning, what is the role of a specific class in the source dataset, and how is the transferability of fc features affected when they are trained using various subsets of the set of all classes in the source dataset? In this paper, we address the question of how to select an optimal subset of the set of classes, subject to a budget constraint, that will more likely generate good features for other tasks. To accomplish this, we use a submodular set function to model the accuracy achievable on a new task when the features have been learned on a given subset of classes of the source dataset. An optimal subset is identified as the set that maximizes this submodular function. The maximization can be accomplished using an efficient greedy algorithm that comes with guarantees on the optimality of the solution. We empirically validate our submodular model by successfully identifying subsets of classes that produce good features for new tasks.

##### Abstract (translated by Google)
近年来，通常的做法是提取在源数据集（如ImageNet）上执行图像分类时学到的全连接图层（fc）特征，并将其应用于广泛的其他任务。一些大型培训数据集对转移学习的普遍有用性尚未得到很好的理解，并提出了一些问题。例如，在传递学习的背景下，源数据集中特定类别的作用是什么，当使用源数据集中所有类别集合的各种子集对它们进行训练时，fc特征的可转移性如何受到影响？在本文中，我们讨论如何根据预算约束来选择类集合中的最优子集，这将更有可能为其他任务生成好的特性。为了实现这个目的，我们使用子模块集函数来模拟在源数据集的给定子集上学习了特征时新任务可实现的精度。最佳子集被识别为使该子模块功能最大化的集合。可以使用有效的贪婪算法来实现最大化，该算法具有解决方案最优性的保证。我们通过成功识别产生用于新任务的良好特征的类的子集来验证我们的子模块模型。

##### URL
[http://arxiv.org/abs/1804.00060](http://arxiv.org/abs/1804.00060)

##### PDF
[http://arxiv.org/pdf/1804.00060](http://arxiv.org/pdf/1804.00060)

