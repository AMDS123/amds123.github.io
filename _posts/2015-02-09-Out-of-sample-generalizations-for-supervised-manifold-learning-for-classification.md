---
layout: post
title: "Out-of-sample generalizations for supervised manifold learning for classification"
date: 2015-02-09 09:56:57
categories: arXiv_CV
tags: arXiv_CV Regularization Face Embedding Classification
author: Elif Vural, Christine Guillemot
mathjax: true
---

* content
{:toc}

##### Abstract
Supervised manifold learning methods for data classification map data samples residing in a high-dimensional ambient space to a lower-dimensional domain in a structure-preserving way, while enhancing the separation between different classes in the learned embedding. Most nonlinear supervised manifold learning methods compute the embedding of the manifolds only at the initially available training points, while the generalization of the embedding to novel points, known as the out-of-sample extension problem in manifold learning, becomes especially important in classification applications. In this work, we propose a semi-supervised method for building an interpolation function that provides an out-of-sample extension for general supervised manifold learning algorithms studied in the context of classification. The proposed algorithm computes a radial basis function (RBF) interpolator that minimizes an objective function consisting of the total embedding error of unlabeled test samples, defined as their distance to the embeddings of the manifolds of their own class, as well as a regularization term that controls the smoothness of the interpolation function in a direction-dependent way. The class labels of test data and the interpolation function parameters are estimated jointly with a progressive procedure. Experimental results on face and object images demonstrate the potential of the proposed out-of-sample extension algorithm for the classification of manifold-modeled data sets.

##### Abstract (translated by Google)
对存在于高维空间的数据分类地图数据样本进行有监督的流形学习方法，保留结构的方式保存到低维域，同时增强了学习嵌入中不同类别之间的分离。大多数非线性有监督流形学习方法仅在最初可用的训练点处计算流形的嵌入，而嵌入到新点的泛化（称为流形学习中的样本外扩展问题）在分类应用中变得尤为重要。在这项工作中，我们提出了一个半监督的方法来建立一个插值函数，为分类中研究的一般监督流形学习算法提供了一个样本外扩展。所提出的算法计算径向基函数（RBF）插值器，其将由未标记测试样本的总嵌入误差构成的目标函数最小化，定义为它们到它们自己类流形的嵌入的距离，以及正则化项以取决于方向的方式控制插值函数的平滑度。测试数据的类别标签和插值函数参数与渐进过程一起估计。人脸图像和目标图像的实验结果证明了所提出的样本外样本扩展算法在流形模型数据集分类方面的潜力。

##### URL
[https://arxiv.org/abs/1502.02410](https://arxiv.org/abs/1502.02410)

##### PDF
[https://arxiv.org/pdf/1502.02410](https://arxiv.org/pdf/1502.02410)

