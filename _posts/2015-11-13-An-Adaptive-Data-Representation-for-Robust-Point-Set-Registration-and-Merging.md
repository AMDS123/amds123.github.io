---
layout: post
title: "An Adaptive Data Representation for Robust Point-Set Registration and Merging"
date: 2015-11-13 11:23:40
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Dylan Campbell, Lars Petersson
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a framework for rigid point-set registration and merging using a robust continuous data representation. Our point-set representation is constructed by training a one-class support vector machine with a Gaussian radial basis function kernel and subsequently approximating the output function with a Gaussian mixture model. We leverage the representation's sparse parametrisation and robustness to noise, outliers and occlusions in an efficient registration algorithm that minimises the L2 distance between our support vector--parametrised Gaussian mixtures. In contrast, existing techniques, such as Iterative Closest Point and Gaussian mixture approaches, manifest a narrower region of convergence and are less robust to occlusions and missing data, as demonstrated in the evaluation on a range of 2D and 3D datasets. Finally, we present a novel algorithm, GMMerge, that parsimoniously and equitably merges aligned mixture models, allowing the framework to be used for reconstruction and mapping.

##### Abstract (translated by Google)
本文提出了一个刚性点集合注册和合并使用一个健壮的连续数据表示框架。我们的点集表示是通过训练具有高斯径向基函数核的单类支持向量机，然后用高斯混合模型逼近输出函数来构造的。我们利用表示的稀疏参数化和鲁棒性噪声，异常值和遮挡在一个有效的配准算法，最小化我们的支持向量参数高斯混合之间的L2距离。相比之下，现有的技术，如迭代最近点和高斯混合方法，表现出更窄的收敛区域，并且对于遮挡和缺失数据的稳健性较差，如对二维和三维数据集的评估所证明的那样。最后，我们提出了一种新的算法，GMMerge，简化和公平合并对齐的混合模型，允许框架用于重建和映射。

##### URL
[https://arxiv.org/abs/1511.04240](https://arxiv.org/abs/1511.04240)

##### PDF
[https://arxiv.org/pdf/1511.04240](https://arxiv.org/pdf/1511.04240)

