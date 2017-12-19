---
layout: post
title: "Labeling the Features Not the Samples: Efficient Video Classification with Minimal Supervision"
date: 2015-12-01 23:24:12
categories: arXiv_CV
tags: arXiv_CV Sparse Knowledge Video_Classification Classification Recognition
author: Marius Leordeanu, Alexandra Radu, Shumeet Baluja, Rahul Sukthankar
mathjax: true
---

* content
{:toc}

##### Abstract
Feature selection is essential for effective visual recognition. We propose an efficient joint classifier learning and feature selection method that discovers sparse, compact representations of input features from a vast sea of candidates, with an almost unsupervised formulation. Our method requires only the following knowledge, which we call the \emph{feature sign}---whether or not a particular feature has on average stronger values over positive samples than over negatives. We show how this can be estimated using as few as a single labeled training sample per class. Then, using these feature signs, we extend an initial supervised learning problem into an (almost) unsupervised clustering formulation that can incorporate new data without requiring ground truth labels. Our method works both as a feature selection mechanism and as a fully competitive classifier. It has important properties, low computational cost and excellent accuracy, especially in difficult cases of very limited training data. We experiment on large-scale recognition in video and show superior speed and performance to established feature selection approaches such as AdaBoost, Lasso, greedy forward-backward selection, and powerful classifiers such as SVM.

##### Abstract (translated by Google)
特征选择对有效的视觉识别至关重要。我们提出了一个有效的联合分类器学习和特征选择方法，发现来自广阔候选人的输入特征的稀疏，紧凑的表示，几乎无监督的表述。我们的方法只需要以下知识，我们称之为“特征符号”---一个特定特征的平均值是否比正面样本的平均值要强一些。我们展示了如何使用每个类的单个标记的训练样本来估计这一点。然后，使用这些特征符号，我们将初始监督学习问题扩展成（几乎）无监督的聚类形式，可以合并新的数据而不需要地面真实标签。我们的方法既可以作为特征选择机制，也可以作为完全竞争的分类器。它具有重要的性质，低的计算成本和出色的准确性，特别是在训练数据非常有限的困难情况下。我们在视频中进行了大规模的识别实验，并且展示了优秀的速度和性能，以建立AdaBoost，Lasso，贪婪前后选择以及强大的分类器如SVM等特征选择方法。

##### URL
[https://arxiv.org/abs/1512.00517](https://arxiv.org/abs/1512.00517)

##### PDF
[https://arxiv.org/pdf/1512.00517](https://arxiv.org/pdf/1512.00517)

