---
layout: post
title: "Matching neural paths: transfer from recognition to correspondence search"
date: 2017-11-05 22:33:22
categories: arXiv_CV
tags: arXiv_CV CNN Prediction Recognition
author: Nikolay Savinov, Lubor Ladicky, Marc Pollefeys
mathjax: true
---

* content
{:toc}

##### Abstract
Many machine learning tasks require finding per-part correspondences between objects. In this work we focus on low-level correspondences - a highly ambiguous matching problem. We propose to use a hierarchical semantic representation of the objects, coming from a convolutional neural network, to solve this ambiguity. Training it for low-level correspondence prediction directly might not be an option in some domains where the ground-truth correspondences are hard to obtain. We show how transfer from recognition can be used to avoid such training. Our idea is to mark parts as "matching" if their features are close to each other at all the levels of convolutional feature hierarchy (neural paths). Although the overall number of such paths is exponential in the number of layers, we propose a polynomial algorithm for aggregating all of them in a single backward pass. The empirical validation is done on the task of stereo correspondence and demonstrates that we achieve competitive results among the methods which do not use labeled target domain data.

##### Abstract (translated by Google)
许多机器学习任务需要查找对象之间的每部分对应关系。在这项工作中，我们专注于低层次的对应 - 一个高度模糊的匹配问题。我们建议使用来自卷积神经网络的对象的​​分层语义表示来解决这种模糊性。直接对低层次的对应关系进行训练可能不会成为一些难以获得基础真相对应的领域的选择。我们展示了如何使用识别转换来避免这种培训。我们的想法是如果在卷积特征层次（神经路径）的所有层次上它们的特征彼此接近，则将这些部分标记为“匹配”。虽然这些路径的总数是层数的指数，我们提出了一个多项式算法，在一个单一的反向通道聚合他们的所有。经验验证是在立体对应任务上进行的，并证明我们在不使用标注目标域数据的方法中取得竞争结果。

##### URL
[https://arxiv.org/abs/1705.08272](https://arxiv.org/abs/1705.08272)

##### PDF
[https://arxiv.org/pdf/1705.08272](https://arxiv.org/pdf/1705.08272)

