---
layout: post
title: "Jointly learning relevant subgraph patterns and nonlinear models of their indicators"
date: 2018-07-09 06:56:22
categories: arXiv_AI
tags: arXiv_AI Attention Classification
author: Ryo Shirakawa, Yusei Yokoyama, Fumiya Okazaki, Ichigaku Takigawa
mathjax: true
---

* content
{:toc}

##### Abstract
Classification and regression in which the inputs are graphs of arbitrary size and shape have been paid attention in various fields such as computational chemistry and bioinformatics. Subgraph indicators are often used as the most fundamental features, but the number of possible subgraph patterns are intractably large due to the combinatorial explosion. We propose a novel efficient algorithm to jointly learn relevant subgraph patterns and nonlinear models of their indicators. Previous methods for such joint learning of subgraph features and models are based on search for single best subgraph features with specific pruning and boosting procedures of adding their indicators one by one, which result in linear models of subgraph indicators. In contrast, the proposed approach is based on directly learning regression trees for graph inputs using a newly derived bound of the total sum of squares for data partitions by a given subgraph feature, and thus can learn nonlinear models through standard gradient boosting. An illustrative example we call the Graph-XOR problem to consider nonlinearity, numerical experiments with real datasets, and scalability comparisons to naive approaches using explicit pattern enumeration are also presented.

##### Abstract (translated by Google)
输入是任意大小和形状的图形的分类和回归在诸如计算化学和生物信息学的各个领域中受到关注。子图指标通常被用作最基本的特征，但由于组合爆炸，可能的子图模式的数量难以处理。我们提出了一种新颖的有效算法，共同学习相关的子图模式和指标的非线性模型。用于子图特征和模型的这种联合学习的先前方法基于搜索单个最佳子图特征，其具有逐个添加其指示符的特定修剪和增强过程，这导致子图指示符的线性模型。相反，所提出的方法基于使用由给定子图特征对数据分区的总平方和的新导出边界直接学习图输入的回归树，因此可以通过标准梯度增强来学习非线性模型。我们还将一个示例性示例称为Graph-XOR问题，以考虑非线性，使用真实数据集进行数值实验，以及使用显式模式枚举与初始方法进行可伸缩性比较。

##### URL
[http://arxiv.org/abs/1807.02963](http://arxiv.org/abs/1807.02963)

##### PDF
[http://arxiv.org/pdf/1807.02963](http://arxiv.org/pdf/1807.02963)

