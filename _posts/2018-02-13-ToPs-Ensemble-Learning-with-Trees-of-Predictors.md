---
layout: post
title: "ToPs: Ensemble Learning with Trees of Predictors"
date: 2018-02-13 14:50:36
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Jinsung Yoon, William R. Zame, Mihaela van der Schaar
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new approach to ensemble learning. Our approach constructs a tree of subsets of the feature space and associates a predictor (predictive model) - determined by training one of a given family of base learners on an endogenously determined training set - to each node of the tree; we call the resulting object a tree of predictors. The (locally) optimal tree of predictors is derived recursively; each step involves jointly optimizing the split of the terminal nodes of the previous tree and the choice of learner and training set (hence predictor) for each set in the split. The feature vector of a new instance determines a unique path through the optimal tree of predictors; the final prediction aggregates the predictions of the predictors along this path. We derive loss bounds for the final predictor in terms of the Rademacher complexity of the base learners. We report the results of a number of experiments on a variety of datasets, showing that our approach provides statistically significant improvements over state-of-the-art machine learning algorithms, including various ensemble learning methods. Our approach works because it allows us to endogenously create more complex learners - when needed - and endogenously match both the learner and the training set to the characteristics of the dataset while still avoiding over-fitting.

##### Abstract (translated by Google)
我们提出了一种新的集成学习方法。我们的方法构造了特征空间子集的一棵树，并将一个预测器（预测模型）与树的每个节点相关联，该预测器通过训练给定的基础学习者之一在内生确定的训练集上确定;我们把结果对象称为预测器树。 （局部）最佳的预测器树是递归导出的;每个步骤包括联合优化先前树的终端节点的分裂以及分裂中每个集合的学习者和训练集（因此预测器）的选择。新实例的特征向量通过最佳预测树确定唯一路径;最终预测汇总了沿着这条路径的预测因子的预测。我们根据基础学习者的Rademacher复杂度得出最终预测值的损失界限。我们在各种数据集上报告了大量实验的结果，表明我们的方法提供了超过最先进的机器学习算法（包括各种集成学习方法）的显着改进。我们的方法是可行的，因为它可以让我们在需要时内生地创建更复杂的学习者，并且内在地匹配学习者和训练集以适应数据集的特征，同时避免过度拟合。

##### URL
[http://arxiv.org/abs/1706.01396](http://arxiv.org/abs/1706.01396)

##### PDF
[http://arxiv.org/pdf/1706.01396](http://arxiv.org/pdf/1706.01396)

