---
layout: post
title: "Supervised multiview learning based on simultaneous learning of multiview intact and single view classifier"
date: 2016-01-09 11:50:46
categories: arXiv_CV
tags: arXiv_CV Regularization Optimization Classification Gradient_Descent
author: Qingjun Wang, Haiyan Lv, Jun Yue, Eugene Mitchell
mathjax: true
---

* content
{:toc}

##### Abstract
Multiview learning problem refers to the problem of learning a classifier from multiple view data. In this data set, each data points is presented by multiple different views. In this paper, we propose a novel method for this problem. This method is based on two assumptions. The first assumption is that each data point has an intact feature vector, and each view is obtained by a linear transformation from the intact vector. The second assumption is that the intact vectors are discriminative, and in the intact space, we have a linear classifier to separate the positive class from the negative class. We define an intact vector for each data point, and a view-conditional transformation matrix for each view, and propose to reconstruct the multiple view feature vectors by the product of the corresponding intact vectors and transformation matrices. Moreover, we also propose a linear classifier in the intact space, and learn it jointly with the intact vectors. The learning problem is modeled by a minimization problem, and the objective function is composed of a Cauchy error estimator-based view-conditional reconstruction term over all data points and views, and a classification error term measured by hinge loss over all the intact vectors of all the data points. Some regularization terms are also imposed to different variables in the objective function. The minimization problem is solve by an iterative algorithm using alternate optimization strategy and gradient descent algorithm. The proposed algorithm shows it advantage in the compression to other multiview learning algorithms on benchmark data sets.

##### Abstract (translated by Google)
多视图学习问题是指从多个视图数据中学习分类器的问题。在这个数据集中，每个数据点是由多个不同的视图呈现的。在本文中，我们提出了一个新的方法来解决这个问题。这种方法基于两个假设。第一个假设是每个数据点都有一个完整的特征向量，每个视图都是从完整向量的线性变换得到的。第二个假设是，完整的向量是有区别的，在完整的空间中，我们有一个线性分类器来将正类和负类分开。我们为每个数据点定义了一个完整的矢量，并为每个视图定义了一个视图 - 条件变换矩阵，并且提出了用相应的完整矢量和变换矩阵的乘积来重构多视点特征矢量。此外，我们还在完整的空间中提出了一个线性分类器，并与完整的矢量共同学习。学习问题由最小化问题建模，目标函数由基于柯西误差估计器的所有数据点和视图的条件重构项组成，以及通过铰链损失测量的所有数据点和视图的分类错误项组成所有的数据点。一些正则化术语也被赋予了目标函数中的不同变量。最小化问题是通过使用交替优化策略和梯度下降算法的迭代算法来解决的。所提出的算法显示了其在基准数据集上的其他多视图学习算法的压缩优势。

##### URL
[https://arxiv.org/abs/1601.02098](https://arxiv.org/abs/1601.02098)

##### PDF
[https://arxiv.org/pdf/1601.02098](https://arxiv.org/pdf/1601.02098)

