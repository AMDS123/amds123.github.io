---
layout: post
title: "Decoupled Learning for Factorial Marked Temporal Point Processes"
date: 2018-01-21 11:13:29
categories: arXiv_AI
tags: arXiv_AI Sparse
author: Weichang Wu, Junchi Yan, Xiaokang Yang, Hongyuan Zha
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces the factorial marked temporal point process model and presents efficient learning methods. In conventional (multi-dimensional) marked temporal point process models, event is often encoded by a single discrete variable i.e. a marker. In this paper, we describe the factorial marked point processes whereby time-stamped event is factored into multiple markers. Accordingly the size of the infectivity matrix modeling the effect between pairwise markers is in power order w.r.t. the number of the discrete marker space. We propose a decoupled learning method with two learning procedures: i) directly solving the model based on two techniques: Alternating Direction Method of Multipliers and Fast Iterative Shrinkage-Thresholding Algorithm; ii) involving a reformulation that transforms the original problem into a Logistic Regression model for more efficient learning. Moreover, a sparse group regularizer is added to identify the key profile features and event labels. Empirical results on real world datasets demonstrate the efficiency of our decoupled and reformulated method. The source code is available online.

##### Abstract (translated by Google)
本文介绍了时间点因子过程模型，并提出了有效的学习方法。在常规（多维）标记时间点过程模型中，事件通常由单个离散变量即标记编码。在本文中，我们描述了时间标记事件被分解成多个标记的阶乘标记点过程。因此，模拟成对标记之间效应的传染性矩阵的大小按照功率顺序w.r.t.离散标记空间的数量。我们提出了一种解耦学习的方法，有两个学习过程：i）基于两种技术直接求解模型：乘子交替方向法和快速迭代收缩阈值算法; ii）涉及将原始问题转化为Logistic回归模型以更有效地学习的重构。此外，还增加了一个稀疏群体正规化者来识别关键配置文件特征和事件标签。对现实世界数据集的实证结果证明了我们的解耦和重构方法的有效性。源代码在线提供。

##### URL
[https://arxiv.org/abs/1801.06805](https://arxiv.org/abs/1801.06805)

##### PDF
[https://arxiv.org/pdf/1801.06805](https://arxiv.org/pdf/1801.06805)

