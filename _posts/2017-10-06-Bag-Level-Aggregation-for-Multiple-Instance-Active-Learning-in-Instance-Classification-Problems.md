---
layout: post
title: "Bag-Level Aggregation for Multiple Instance Active Learning in Instance Classification Problems"
date: 2017-10-06 20:58:15
categories: arXiv_CV
tags: arXiv_CV Classification Recognition
author: Marc-André Carbonneau, Eric Granger, Ghyslain Gagnon
mathjax: true
---

* content
{:toc}

##### Abstract
A growing number of applications, e.g. video surveillance and medical image analysis, require training recognition systems from large amounts of weakly annotated data while some targeted interactions with a domain expert are allowed to improve the training process. In such cases, active learning (AL) can reduce labeling costs for training a classifier by querying the expert to provide the labels of most informative instances. This paper focuses on AL methods for instance classification problems in multiple instance learning (MIL), where data is arranged into sets, called bags, that are weakly labeled. Most AL methods focus on single instance learning problems. These methods are not suitable for MIL problems because they cannot account for the bag structure of data. In this paper, new methods for bag-level aggregation of instance informativeness are proposed for multiple instance active learning (MIAL). The \textit{aggregated informativeness} method identifies the most informative instances based on classifier uncertainty, and queries bags incorporating the most information. The other proposed method, called \textit{cluster-based aggregative sampling}, clusters data hierarchically in the instance space. The informativeness of instances is assessed by considering bag labels, inferred instance labels, and the proportion of labels that remain to be discovered in clusters. Both proposed methods significantly outperform reference methods in extensive experiments using benchmark data from several application domains. Results indicate that using an appropriate strategy to address MIAL problems yields a significant reduction in the number of queries needed to achieve the same level of performance as single instance AL methods.

##### Abstract (translated by Google)
越来越多的应用程序，例如视频监控和医学图像分析，需要从大量弱注释数据中获取训练识别系统，同时允许与领域专家进行有针对性的交互，以改善训练过程。在这种情况下，主动学习（AL）可以通过查询专家来提供最有信息的实例的标签来降低用于训练分类器的标签成本。本文重点介绍AL方法在多实例学习（MIL）中的实例分类问题，其中数据被排列成集合，被称为袋，被弱标记。大多数AL方法关注单个实例学习问题。这些方法不适合MIL问题，因为它们不能解释数据的包结构。针对多实例主动学习（MIAL），提出了实例信息量袋级聚合的新方法。 \ textit {聚合信息性}方法基于分类器不确定性来识别最有信息的实例，并查询包含最多信息的包。另一种被称为\ textit {基于聚类的聚合采样}的方法在实例空间中分层地聚集数据。实例的信息量通过考虑行李标签，推断的实例标签以及在集群中待发现的标签的比例来评估。在广泛的实验中，两种提出的方​​法都比使用来自几个应用领域的基准数据的参考方法显着地好结果表明，使用适当的策略来解决MIAL问题会大大减少查询所需的查询数量，以达到与单实例AL方法相同的性能水平。

##### URL
[https://arxiv.org/abs/1710.02584](https://arxiv.org/abs/1710.02584)

##### PDF
[https://arxiv.org/pdf/1710.02584](https://arxiv.org/pdf/1710.02584)

