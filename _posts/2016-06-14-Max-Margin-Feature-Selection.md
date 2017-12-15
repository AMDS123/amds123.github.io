---
layout: post
title: "Max-Margin Feature Selection"
date: 2016-06-14 19:05:01
categories: arXiv_CV
tags: arXiv_CV Sparse Optimization
author: Yamuna Prasad, Dinesh Khandelwal, K. K. Biswas
mathjax: true
---

* content
{:toc}

##### Abstract
Many machine learning applications such as in vision, biology and social networking deal with data in high dimensions. Feature selection is typically employed to select a subset of features which im- proves generalization accuracy as well as reduces the computational cost of learning the model. One of the criteria used for feature selection is to jointly minimize the redundancy and maximize the rele- vance of the selected features. In this paper, we formulate the task of feature selection as a one class SVM problem in a space where features correspond to the data points and instances correspond to the dimensions. The goal is to look for a representative subset of the features (support vectors) which describes the boundary for the region where the set of the features (data points) exists. This leads to a joint optimization of relevance and redundancy in a principled max-margin framework. Additionally, our formulation enables us to leverage existing techniques for optimizing the SVM objective resulting in highly computationally efficient solutions for the task of feature selection. Specifically, we employ the dual coordinate descent algorithm (Hsieh et al., 2008), originally proposed for SVMs, for our formulation. We use a sparse representation to deal with data in very high dimensions. Experiments on seven publicly available benchmark datasets from a variety of domains show that our approach results in orders of magnitude faster solutions even while retaining the same level of accuracy compared to the state of the art feature selection techniques.

##### Abstract (translated by Google)
许多机器学习应用程序，如视觉，生物和社交网络处理高维数据。通常采用特征选择来选择提高泛化精度的特征子集，并降低学习模型的计算成本。用于特征选择的标准之一是共同最小化冗余度并且最大化所选特征的相关性。在本文中，我们将特征选择的任务作为一个类中的SVM问题，在特征对应于数据点和实例对应于维度的空间中。目标是寻找描述特征（数据点）存在的区域的边界的特征（支持向量）的代表性子集。这导致了在原则性的最大边界框架中的相关性和冗余度的联合优化。此外，我们的配方使我们能够利用现有技术来优化SVM目标，从而为特征选择任务提供高度计算效率的解决方案。具体而言，我们采用最初为SVM提出的双坐标下降算法（Hsieh et al。，2008）。我们使用稀疏表示来处理非常高维度的数据。对来自不同领域的七个公开可用的基准数据集进行的实验表明，与现有技术的特征选择技术相比，我们的方法即使在保持相同的准确度水平的情况下也能以更快的速度得到数量级的解决方案。

##### URL
[https://arxiv.org/abs/1606.04506](https://arxiv.org/abs/1606.04506)

##### PDF
[https://arxiv.org/pdf/1606.04506](https://arxiv.org/pdf/1606.04506)

