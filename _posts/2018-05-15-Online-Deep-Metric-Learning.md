---
layout: post
title: "Online Deep Metric Learning"
date: 2018-05-15 01:10:18
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Wenbin Li, Jing Huo, Yinghuan Shi, Yang Gao, Lei Wang, Jiebo Luo
mathjax: true
---

* content
{:toc}

##### Abstract
Metric learning learns a metric function from training data to calculate the similarity or distance between samples. From the perspective of feature learning, metric learning essentially learns a new feature space by feature transformation (e.g., Mahalanobis distance metric). However, traditional metric learning algorithms are shallow, which just learn one metric space (feature transformation). Can we further learn a better metric space from the learnt metric space? In other words, can we learn metric progressively and nonlinearly like deep learning by just using the existing metric learning algorithms? To this end, we present a hierarchical metric learning scheme and implement an online deep metric learning framework, namely ODML. Specifically, we take one online metric learning algorithm as a metric layer, followed by a nonlinear layer (i.e., ReLU), and then stack these layers modelled after the deep learning. The proposed ODML enjoys some nice properties, indeed can learn metric progressively and performs superiorly on some datasets. Various experiments with different settings have been conducted to verify these properties of the proposed ODML.

##### Abstract (translated by Google)
度量学习从训练数据中学习度量函数以计算样本之间的相似度或距离。从特征学习的角度来看，度量学习本质上是通过特征变换（例如Mahalanobis距离度量）来学习一个新的特征空间。然而，传统的度量学习算法很浅，只学习一个度量空间（特征变换）。我们能否从学习的度量空间中进一步学习更好的度量空间？换句话说，我们是否可以通过使用现有的度量学习算法来逐步学习和非线性地学习度量？为此，我们提出了一个层次度量学习方案，并实现了一个在线深度度量学习框架，即ODML。具体而言，我们采用一个在线度量学习算法作为度量层，然后是非线性层（即，ReLU），然后在深度学习之后对这些层建模。建议的ODML具有一些很好的属性，确实可以逐步学习度量，并在某些数据集上表现优越。已经进行了不同设置的各种实验来验证所提议的ODML的这些性质。

##### URL
[http://arxiv.org/abs/1805.05510](http://arxiv.org/abs/1805.05510)

##### PDF
[http://arxiv.org/pdf/1805.05510](http://arxiv.org/pdf/1805.05510)

