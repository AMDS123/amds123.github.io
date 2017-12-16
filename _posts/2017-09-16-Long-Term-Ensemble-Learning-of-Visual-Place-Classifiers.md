---
layout: post
title: "Long-Term Ensemble Learning of Visual Place Classifiers"
date: 2017-09-16 06:52:20
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Transfer_Learning Classification
author: Xiaoxiao Fei, Kanji Tanaka, Yichu Fang, Akitaka Takayama
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of cross-season visual place classification (VPC) from a novel perspective of long-term map learning. Our goal is to enable transfer learning efficiently from one season to the next, at a small constant cost, and without wasting the robot's available long-term-memory by memorizing very large amounts of training data. To realize a good tradeoff between generalization and specialization abilities, we employ an ensemble of convolutional neural network (DCN) classifiers and consider the task of scheduling (when and which classifiers to retrain), given a previous season's DCN classifiers as the sole prior knowledge. We present a unified framework for retraining scheduling and discuss practical implementation strategies. Furthermore, we address the task of partitioning a robot's workspace into places to define place classes in an unsupervised manner, rather than using uniform partitioning, so as to maximize VPC performance. Experiments using the publicly available NCLT dataset revealed that retraining scheduling of a DCN classifier ensemble is crucial and performance is significantly increased by using planned scheduling.

##### Abstract (translated by Google)
本文从长期地图学习的角度出发，探讨了跨季节视觉地点分类（VPC）的问题。我们的目标是通过记忆非常大量的训练数据，以一个不变的成本，从一个赛季到下一个赛季高效地进行转移学习，而不会浪费机器人的长期记忆。为了实现泛化能力和专业化能力之间的良好平衡，我们采用卷积神经网络（DCN）分类器集合，并考虑调度任务（何时以及何种分类器进行再训练），以前一个赛季的DCN分类器作为唯一的先验知识。我们提出一个统一的再培训计划框架，并讨论实际的实施策略。此外，我们解决的任务是将机器人的工作空间划分为地点，以无监督的方式定义地点类别，而不是使用统一划分，从而最大化VPC的性能。使用公开可用的NCLT数据集的实验揭示了DCN分类器集合的再训练调度是至关重要的，并且通过使用计划的调度来显着提高性能。

##### URL
[https://arxiv.org/abs/1709.05470](https://arxiv.org/abs/1709.05470)

##### PDF
[https://arxiv.org/pdf/1709.05470](https://arxiv.org/pdf/1709.05470)

