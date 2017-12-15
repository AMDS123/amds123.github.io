---
layout: post
title: "Novelty Detection in MultiClass Scenarios with Incomplete Set of Class Labels"
date: 2016-05-15 16:44:15
categories: arXiv_CV
tags: arXiv_CV Detection
author: Nomi Vinokurov, Daphna Weinshall
mathjax: true
---

* content
{:toc}

##### Abstract
We address the problem of novelty detection in multiclass scenarios where some class labels are missing from the training set. Our method is based on the initial assignment of confidence values, which measure the affinity between a new test point and each known class. We first compare the values of the two top elements in this vector of confidence values. In the heart of our method lies the training of an ensemble of classifiers, each trained to discriminate known from novel classes based on some partition of the training data into presumed-known and presumednovel classes. Our final novelty score is derived from the output of this ensemble of classifiers. We evaluated our method on two datasets of images containing a relatively large number of classes - the Caltech-256 and Cifar-100 datasets. We compared our method to 3 alternative methods which represent commonly used approaches, including the one-class SVM, novelty based on k-NN, novelty based on maximal confidence, and the recent KNFST method. The results show a very clear and marked advantage for our method over all alternative methods, in an experimental setup where class labels are missing during training.

##### Abstract (translated by Google)
我们解决了多类场景中的新颖性检测问题，其中一些类标签在训练集中缺失。我们的方法是基于置信度值的初始分配，它测量新测试点和每个已知类别之间的亲和力。我们首先比较这个置信度值向量中两个顶部元素的值。我们方法的核心在于对分类器集合的训练，每个分类器都训练成根据将训练数据划分成假定已知的和假定的新的类别来区分已知类别和已知类别。我们最后的新颖性得分是从这个分类器集合的输出中导出的。我们对包含相对较多数量的图像的两个数据集（Caltech-256和Cifar-100数据集）评估了我们的方法。我们将该方法与代表常用方法的3种替代方法进行了比较，其中包括一类SVM，基于k-NN的新颖性，基于最大置信度的新颖性以及最近的KNFST方法。结果表明，我们的方法在所有替代方法中都有非常明显的优势，在培训期间班级标签丢失的实验设置中。

##### URL
[https://arxiv.org/abs/1604.06242](https://arxiv.org/abs/1604.06242)

##### PDF
[https://arxiv.org/pdf/1604.06242](https://arxiv.org/pdf/1604.06242)

