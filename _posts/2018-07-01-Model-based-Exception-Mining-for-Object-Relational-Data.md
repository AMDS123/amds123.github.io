---
layout: post
title: "Model-based Exception Mining for Object-Relational Data"
date: 2018-07-01 19:42:02
categories: arXiv_AI
tags: arXiv_AI Detection Relation
author: Fatemeh Riahi, Oliver Schulte
mathjax: true
---

* content
{:toc}

##### Abstract
This paper is based on a previous publication [29]. Our work extends exception mining and outlier detection to the case of object-relational data. Object-relational data represent a complex heterogeneous network [12], which comprises objects of different types, links among these objects, also of different types, and attributes of these links. This special structure prohibits a direct vectorial data representation. We follow the well-established Exceptional Model Mining framework, which leverages machine learning models for exception mining: A object is exceptional to the extent that a model learned for the object data differs from a model learned for the general population. Exceptional objects can be viewed as outliers. We apply stateof- the-art probabilistic modelling techniques for object-relational data that construct a graphical model (Bayesian network), which compactly represents probabilistic associations in the data. A new metric, derived from the learned object-relational model, quantifies the extent to which the individual association pattern of a potential outlier deviates from that of the whole population. The metric is based on the likelihood ratio of two parameter vectors: One that represents the population associations, and another that represents the individual associations. Our method is validated on synthetic datasets and on real-world data sets about soccer matches and movies. Compared to baseline methods, our novel transformed likelihood ratio achieved the best detection accuracy on all datasets.

##### Abstract (translated by Google)
本文基于之前的出版物[29]。我们的工作将异常挖掘和异常检测扩展到对象关系数据的情况。对象关系数据表示复杂的异构网络[12]，其包括不同类型的对象，这些对象之间的链接，不同类型的链接以及这些链接的属性。这种特殊结构禁止直接矢量数据表示。我们遵循完善的Exceptional Model Mining框架，该框架利用机器学习模型进行异常挖掘：对象是特殊的，以至于为对象数据学习的模型与为一般人群学习的模型不同。可以将特殊对象视为异常值。我们对构建图形模型（贝叶斯网络）的对象关系数据应用最先进的概率建模技术，该模型紧凑地表示数据中的概率关联。源自学习对象 - 关系模型的新度量标准量化了潜在异常值的个体关联模式与整个群体的个体关联模式的偏差程度。度量基于两个参数向量的似然比：一个表示人口关联，另一个表示个体关联。我们的方法在合成数据集和关于足球比赛和电影的真实世界数据集上得到验证。与基线方法相比，我们的新变换似然比在所有数据集上实现了最佳检测精度。

##### URL
[http://arxiv.org/abs/1807.00381](http://arxiv.org/abs/1807.00381)

##### PDF
[http://arxiv.org/pdf/1807.00381](http://arxiv.org/pdf/1807.00381)

