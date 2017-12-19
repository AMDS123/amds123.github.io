---
layout: post
title: "F-SVM: Combination of Feature Transformation and SVM Learning via Convex Relaxation"
date: 2015-04-20 12:36:50
categories: arXiv_CV
tags: arXiv_CV Face Gradient_Descent
author: Xiaohe Wu, Wangmeng Zuo, Yuanyuan Zhu, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
The generalization error bound of support vector machine (SVM) depends on the ratio of radius and margin, while standard SVM only considers the maximization of the margin but ignores the minimization of the radius. Several approaches have been proposed to integrate radius and margin for joint learning of feature transformation and SVM classifier. However, most of them either require the form of the transformation matrix to be diagonal, or are non-convex and computationally expensive. In this paper, we suggest a novel approximation for the radius of minimum enclosing ball (MEB) in feature space, and then propose a convex radius-margin based SVM model for joint learning of feature transformation and SVM classifier, i.e., F-SVM. An alternating minimization method is adopted to solve the F-SVM model, where the feature transformation is updatedvia gradient descent and the classifier is updated by employing the existing SVM solver. By incorporating with kernel principal component analysis, F-SVM is further extended for joint learning of nonlinear transformation and classifier. Experimental results on the UCI machine learning datasets and the LFW face datasets show that F-SVM outperforms the standard SVM and the existing radius-margin based SVMs, e.g., RMM, R-SVM+ and R-SVM+{\mu}.

##### Abstract (translated by Google)
支持向量机（SVM）的广义误差界取决于半径和边界的比值，而标准支持向量机只考虑边界的最大化，而忽略半径的最小化。已经提出了多种方法来整合半径和边缘来进行特征变换和SVM分类器的联合学习。然而，它们中的大多数或者要求变换矩阵的形式是对角的，或者是非凸的并且在计算上是昂贵的。本文提出了一种特征空间中最小包围球（MEB）半径的新近似方法，然后提出了一种基于凸半径 - 边缘的SVM模型，用于特征变换与SVM分类器联合学习，即F-SVM。采用交替最小化方法求解F-SVM模型，通过梯度下降更新特征变换，采用现有的SVM求解器对分类器进行更新。通过与核主成分分析相结合，进一步扩展了F-SVM的非线性变换与分类器的联合学习。在UCI机器学习数据集和LFW人脸数据集上的实验结果表明，F-SVM优于标准SVM和现有的基于半径边缘的SVM，例如RMM，R-SVM +和R-SVM + {\ mu}。

##### URL
[https://arxiv.org/abs/1504.05035](https://arxiv.org/abs/1504.05035)

##### PDF
[https://arxiv.org/pdf/1504.05035](https://arxiv.org/pdf/1504.05035)

