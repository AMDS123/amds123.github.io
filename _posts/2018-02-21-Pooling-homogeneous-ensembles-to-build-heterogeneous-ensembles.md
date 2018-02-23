---
layout: post
title: "Pooling homogeneous ensembles to build heterogeneous ensembles"
date: 2018-02-21 13:17:42
categories: arXiv_AI
tags: arXiv_AI Prediction
author: Maryam Sabzevari, Gonzalo Mart&#xed;nez-Mu&#xf1;oz, Alberto Su&#xe1;rez
mathjax: true
---

* content
{:toc}

##### Abstract
In ensemble methods, the outputs of a collection of diverse classifiers are combined in the expectation that the global prediction be more accurate than the individual ones. Heterogeneous ensembles consist of predictors of different types, which are likely to have different biases. If these biases are complementary, the combination of their decisions is beneficial. In this work, a family of heterogeneous ensembles is built by pooling classifiers from M homogeneous ensembles of different types of size T. Depending on the fraction of base classifiers of each type, a particular heterogeneous combination in this family is represented by a point in a regular simplex in M dimensions. The M vertices of this simplex represent the different homogeneous ensembles. A displacement away from one of these vertices effects a smooth transformation of the corresponding homogeneous ensemble into a heterogeneous one. The optimal composition of such heterogeneous ensemble can be determined using cross-validation or, if bootstrap samples are used to build the individual classifiers, out-of-bag data. An empirical analysis of such combinations of bootstraped ensembles composed of neural networks, SVMs, and random trees (i.e. from a standard random forest) illustrates the gains that can be achieved by this heterogeneous ensemble creation method.

##### Abstract (translated by Google)
在集合方法中，不同分类器集合的输出结合在一起，期望全局预测比单个分类器更准确。异构综合体由不同类型的预测因子组成，这些预测因子可能有不同的偏差。如果这些偏见是互补的，那么他们的决定相结合是有益的。在这项工作中，通过汇集来自M个不同类型尺寸T的齐次集合中的分类器来构建一个异构集合族。根据每种类型的基本分类器的比例，这个家族中的特定异构组合通过M维普通单形。这个单纯形的M个顶点表示不同的同构集合。离开这些顶点之一的位移会导致相应均匀集合的平滑变换成为非均匀集合。这种异质集合的最佳组合可以使用交叉验证来确定，或者如果引导样本用于构建单个分类器，则可以使用外包数据。对由神经网络，支持向量机和随机树（即来自标准随机森林）构成的自举合奏组合的经验分析说明了这种异构合奏创作方法可以获得的收益。

##### URL
[http://arxiv.org/abs/1802.07877](http://arxiv.org/abs/1802.07877)

##### PDF
[http://arxiv.org/pdf/1802.07877](http://arxiv.org/pdf/1802.07877)

