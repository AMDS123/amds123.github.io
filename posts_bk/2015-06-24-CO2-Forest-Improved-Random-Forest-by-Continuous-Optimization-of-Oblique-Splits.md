---
layout: post
title: "CO2 Forest: Improved Random Forest by Continuous Optimization of Oblique Splits"
date: 2015-06-24 21:23:43
categories: arXiv_CV
tags: arXiv_CV Face Optimization Classification Gradient_Descent
author: Mohammad Norouzi, Maxwell D. Collins, David J. Fleet, Pushmeet Kohli
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel algorithm for optimizing multivariate linear threshold functions as split functions of decision trees to create improved Random Forest classifiers. Standard tree induction methods resort to sampling and exhaustive search to find good univariate split functions. In contrast, our method computes a linear combination of the features at each node, and optimizes the parameters of the linear combination (oblique) split functions by adopting a variant of latent variable SVM formulation. We develop a convex-concave upper bound on the classification loss for a one-level decision tree, and optimize the bound by stochastic gradient descent at each internal node of the tree. Forests of up to 1000 Continuously Optimized Oblique (CO2) decision trees are created, which significantly outperform Random Forest with univariate splits and previous techniques for constructing oblique trees. Experimental results are reported on multi-class classification benchmarks and on Labeled Faces in the Wild (LFW) dataset.

##### Abstract (translated by Google)
我们提出了一种新的算法来优化多元线性阈值函数作为决策树的分裂函数来创建改进的随机森林分类器。标准树的归纳方法采取抽样和穷举搜索来找到好的单变量分裂函数。相反，我们的方法计算每个节点上的特征的线性组合，并且通过采用潜变量SVM公式的变体来优化线性组合（倾斜）分裂函数的参数。我们针对一级决策树的分类损失开发了一个凸凹上界，并且在树的每个内部节点处通过随机梯度下降来优化边界。多达1000个连续优化的森林（二氧化碳）决策树创建，这显着胜过随机森林与单变量分裂和以前的技术构建斜树。实验结果报告在多类分类基准和野外标记人脸（LFW）数据集中。

##### URL
[https://arxiv.org/abs/1506.06155](https://arxiv.org/abs/1506.06155)

##### PDF
[https://arxiv.org/pdf/1506.06155](https://arxiv.org/pdf/1506.06155)

