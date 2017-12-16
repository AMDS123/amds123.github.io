---
layout: post
title: "Efficient Branching Cascaded Regression for Face Alignment under Significant Head Rotation"
date: 2016-11-10 04:53:39
categories: arXiv_CV
tags: arXiv_CV Face
author: Brandon M. Smith, Charles R. Dyer
mathjax: true
---

* content
{:toc}

##### Abstract
Despite much interest in face alignment in recent years, the large majority of work has focused on near-frontal faces. Algorithms typically break down on profile faces, or are too slow for real-time applications. In this work we propose an efficient approach to face alignment that can handle 180 degrees of head rotation in a unified way (e.g., without resorting to view-based models) using 2D training data. The foundation of our approach is cascaded shape regression (CSR), which has emerged recently as the leading strategy. We propose a generalization of conventional CSRs that we call branching cascaded regression (BCR). Conventional CSRs are single-track; that is, they progress from one cascade level to the next in a straight line, with each regressor attempting to fit the entire dataset. We instead split the regression problem into two or more simpler ones after each cascade level. Intuitively, each regressor can then operate on a simpler objective function (i.e., with fewer conflicting gradient directions). Within the BCR framework, we model and infer pose-related landmark visibility and face shape simultaneously using Structured Point Distribution Models (SPDMs). We propose to learn task-specific feature mapping functions that are adaptive to landmark visibility, and that use SPDM parameters as regression targets instead of 2D landmark coordinates. Additionally, we introduce a new in-the-wild dataset of profile faces to validate our approach.

##### Abstract (translated by Google)
尽管近年来对脸部对齐感兴趣很多，但大部分的工作都集中在正面。算法通常在配置文件面上出现故障，或者对于实时应用程序来说太慢。在这项工作中，我们提出了一种有效的面对齐方法，可以使用2D训练数据以统一的方式处理180度的头部旋转（例如，不诉诸于基于视图的模型）。我们的方法的基础是最近出现的作为领先策略的级联形状回归（CSR）。我们提出传统CSR的概括，我们称之为分支级联回归（BCR）。传统的企业社会责任是单一的;也就是说，他们从一个级联层级到下一个级联层级，每个回归层尝试拟合整个数据集。我们在每个级联级别之后将回归问题分解成两个或更多更简单的问题。直观上，每个回归器然后可以在更简单的目标函数上操作（即，具有较少冲突的梯度方向）。在BCR框架内，我们使用结构点分布模型（SPDM）同时建模和推断与姿势相关的界标可见性和面形。我们建议学习适用于地标可见性的特定于任务的特征映射函数，并将SPDM参数用作回归目标而不是2D地标坐标。另外，我们引入一个新的在配置文件面的野外数据集来验证我们的方法。

##### URL
[https://arxiv.org/abs/1611.01584](https://arxiv.org/abs/1611.01584)

##### PDF
[https://arxiv.org/pdf/1611.01584](https://arxiv.org/pdf/1611.01584)

