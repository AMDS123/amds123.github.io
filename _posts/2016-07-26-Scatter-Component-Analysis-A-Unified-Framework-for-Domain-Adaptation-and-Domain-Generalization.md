---
layout: post
title: "Scatter Component Analysis: A Unified Framework for Domain Adaptation and Domain Generalization"
date: 2016-07-26 21:35:08
categories: arXiv_CV
tags: arXiv_CV Represenation_Learning Optimization Classification Recognition
author: Muhammad Ghifary, David Balduzzi, W. Bastiaan Kleijn, Mengjie Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses classification tasks on a particular target domain in which labeled training data are only available from source domains different from (but related to) the target. Two closely related frameworks, domain adaptation and domain generalization, are concerned with such tasks, where the only difference between those frameworks is the availability of the unlabeled target data: domain adaptation can leverage unlabeled target information, while domain generalization cannot. We propose Scatter Component Analyis (SCA), a fast representation learning algorithm that can be applied to both domain adaptation and domain generalization. SCA is based on a simple geometrical measure, i.e., scatter, which operates on reproducing kernel Hilbert space. SCA finds a representation that trades between maximizing the separability of classes, minimizing the mismatch between domains, and maximizing the separability of data; each of which is quantified through scatter. The optimization problem of SCA can be reduced to a generalized eigenvalue problem, which results in a fast and exact solution. Comprehensive experiments on benchmark cross-domain object recognition datasets verify that SCA performs much faster than several state-of-the-art algorithms and also provides state-of-the-art classification accuracy in both domain adaptation and domain generalization. We also show that scatter can be used to establish a theoretical generalization bound in the case of domain adaptation.

##### Abstract (translated by Google)
本文针对特定目标域上的分类任务，其中标记的训练数据只能从与目标不同（但与之相关）的源域获得。两个密切相关的框架，领域适应和领域泛化，都与这些任务有关，这些框架之间的唯一区别是未标记的目标数据的可用性：领域适应可以利用未标记的目标信息，而领域泛化不能。我们提出散布分量分析（SCA），一种快速表示学习算法，可以应用于域适应和域泛化。 SCA是基于一个简单的几何测量，即散射，它在再生核Hilbert空间上进行操作。 SCA发现一个表示，它在最大化类的可分性，最小化域之间的不匹配以及最大化数据的可分性之间进行交换;每一个都是通过分散来量化的。 SCA的优化问题可以归结为广义特征值问题，从而得到快速而精确的解。基准跨域对象识别数据集的全面实验验证了SCA的执行速度远远超过几种最先进的算法，并在域适应和域泛化中提供了最先进的分类准确性。我们还表明，在领域适应的情况下，可以使用分散来建立一个理论泛化界。

##### URL
[https://arxiv.org/abs/1510.04373](https://arxiv.org/abs/1510.04373)

##### PDF
[https://arxiv.org/pdf/1510.04373](https://arxiv.org/pdf/1510.04373)

