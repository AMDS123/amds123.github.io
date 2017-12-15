---
layout: post
title: "Discriminative Sparse Neighbor Approximation for Imbalanced Learning"
date: 2016-02-03 06:22:14
categories: arXiv_CV
tags: arXiv_CV Sparse Classification Deep_Learning Prediction
author: Chen Huang, Chen Change Loy, Xiaoou Tang
mathjax: true
---

* content
{:toc}

##### Abstract
Data imbalance is common in many vision tasks where one or more classes are rare. Without addressing this issue conventional methods tend to be biased toward the majority class with poor predictive accuracy for the minority class. These methods further deteriorate on small, imbalanced data that has a large degree of class overlap. In this study, we propose a novel discriminative sparse neighbor approximation (DSNA) method to ameliorate the effect of class-imbalance during prediction. Specifically, given a test sample, we first traverse it through a cost-sensitive decision forest to collect a good subset of training examples in its local neighborhood. Then we generate from this subset several class-discriminating but overlapping clusters and model each as an affine subspace. From these subspaces, the proposed DSNA iteratively seeks an optimal approximation of the test sample and outputs an unbiased prediction. We show that our method not only effectively mitigates the imbalance issue, but also allows the prediction to extrapolate to unseen data. The latter capability is crucial for achieving accurate prediction on small dataset with limited samples. The proposed imbalanced learning method can be applied to both classification and regression tasks at a wide range of imbalance levels. It significantly outperforms the state-of-the-art methods that do not possess an imbalance handling mechanism, and is found to perform comparably or even better than recent deep learning methods by using hand-crafted features only.

##### Abstract (translated by Google)
数据不平衡在许多视觉任务中很常见，其中一个或多个类别是罕见的。如果不解决这个问题，传统的方法往往会偏向于大多数阶级，对少数阶级预测准确性差。这些方法进一步恶化了小的，不平衡的数据，这些数据有很大程度的类重叠。在本研究中，我们提出了一种新的判别性稀疏邻域逼近（DSNA）方法来改善预测过程中类不平衡的影响。具体来说，给定一个测试样本，我们首先遍历它通过一个成本敏感的决策森林，以收集当地邻居的一个很好的子集的训练实例。然后，我们从这个子集中产生几个类分类但是重叠的聚类，并且将它们分别作为仿射子空间来建模。从这些子空间中，所提出的DSNA迭代地寻找测试样本的最佳近似并且输出无偏预测。我们表明，我们的方法不仅有效地减轻了不平衡问题，而且允许预测外推到不可见的数据。后一种能力对于在有限样本的小数据集上实现准确预测至关重要。所提出的不平衡学习方法可以在广泛的不平衡水平上应用于分类和回归任务。它明显优于不具有不平衡处理机制的最先进的方法，并且通过仅使用手工特征而被发现与近来的深度学习方法相比甚至更好。

##### URL
[https://arxiv.org/abs/1602.01197](https://arxiv.org/abs/1602.01197)

##### PDF
[https://arxiv.org/pdf/1602.01197](https://arxiv.org/pdf/1602.01197)

