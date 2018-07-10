---
layout: post
title: "Tournament Based Ranking CNN for the Cataract grading"
date: 2018-07-07 12:40:32
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Dohyeun Kim, Tae Joon Jun, Daeyoung Kim, Youngsub Eom
mathjax: true
---

* content
{:toc}

##### Abstract
Solving the classification problem, unbalanced number of dataset among the classes often causes performance degradation. Especially when some classes dominate the other classes with its large number of datasets, trained model shows low performance in identifying the dominated classes. This is common case when it comes to medical dataset. Because the case with a serious degree is not quite usual, there are imbalance in number of dataset between severe case and normal cases of diseases. Also, there is difficulty in precisely identifying grade of medical data because of vagueness between them. To solve these problems, we propose new architecture of convolutional neural network named Tournament based Ranking CNN which shows remarkable performance gain in identifying dominated classes while trading off very small accuracy loss in dominating classes. Our Approach complemented problems that occur when method of Ranking CNN that aggregates outputs of multiple binary neural network models is applied to medical data. By having tournament structure in aggregating method and using very deep pretrained binary models, our proposed model recorded 68.36% of exact match accuracy, while Ranking CNN recorded 53.40%, pretrained Resnet recorded 56.12% and CNN with linear regression recorded 57.48%. As a result, our proposed method is applied efficiently to cataract grading which have ordinal labels with imbalanced number of data among classes, also can be applied further to medical problems which have similar features to cataract and similar dataset configuration.

##### Abstract (translated by Google)
解决分类问题时，类之间数据集的数量不平衡通常会导致性能下降。特别是当某些类通过其大量数据集主导其他类时，训练有素的模型在识别主导类时表现出较低的性能。这是医疗数据集的常见情况。由于严重程度的病例并不常见，严重病例和正常病例之间的数据集数量不平衡。而且，由于它们之间的模糊性，难以精确地识别医学数据的等级。为了解决这些问题，我们提出了基于排名CNN的卷积神经网络的新体系结构，其在识别支配类中表现出显着的性能增益，同时在主导类中消除非常小的准确度损失。我们的方法补充了将聚合多个二元神经网络模型输出的CNN排序方法应用于医疗数据时出现的问题。通过聚合方法中的锦标赛结构和使用非常深的预训练二元模型，我们提出的模型记录了68.36％的精确匹配准确度，而排名CNN记录了53.40％，预训练的Resnet记录了56.12％，CNN的线性回归记录了57.48％。因此，我们提出的方法被有效地应用于白内障分级，其具有类别之间具有不平衡数据的序数标签，还可以进一步应用于具有与白内障相似的特征和类似数据集配置的医学问题。

##### URL
[http://arxiv.org/abs/1807.02657](http://arxiv.org/abs/1807.02657)

##### PDF
[http://arxiv.org/pdf/1807.02657](http://arxiv.org/pdf/1807.02657)

