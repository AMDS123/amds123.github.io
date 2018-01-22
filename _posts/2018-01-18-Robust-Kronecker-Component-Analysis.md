---
layout: post
title: "Robust Kronecker Component Analysis"
date: 2018-01-18 18:01:50
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Mehdi Bahri, Yannis Panagakis, Stefanos Zafeiriou
mathjax: true
---

* content
{:toc}

##### Abstract
Dictionary learning and component analysis models are fundamental in learning compact representations that are relevant to a given task (feature extraction, dimensionality reduction, denoising, etc.). The model complexity is encoded by means of specific structure, such as sparsity, low-rankness, or nonnegativity. Unfortunately, approaches like K-SVD - that learn dictionaries for sparse coding via Singular Value Decomposition (SVD) - are hard to scale to high-volume and high-dimensional visual data, and fragile in the presence of outliers. Conversely, robust component analysis methods such as the Robust Principle Component Analysis (RPCA) are able to recover low-complexity (e.g., low-rank) representations from data corrupted with noise of unknown magnitude and support, but do not provide a dictionary that respects the structure of the data (e.g., images), and also involve expensive computations. In this paper, we propose a novel Kronecker-decomposable component analysis model, coined as Robust Kronecker Component Analysis (RKCA), that combines ideas from sparse dictionary learning and robust component analysis. RKCA has several appealing properties, including robustness to gross corruption; it can be used for low-rank modeling, and leverages separability to solve significantly smaller problems. We design an efficient learning algorithm by drawing links with a restricted form of tensor factorization, and analyze its optimality and low-rankness properties. The effectiveness of the proposed approach is demonstrated on real-world applications, namely background subtraction and image denoising and completion, by performing a thorough comparison with the current state of the art.

##### Abstract (translated by Google)
字典学习和分量分析模型是学习与给定任务（特征提取，降维，去噪等）相关的紧凑表示的基础。模型的复杂性是通过特定的结构进行编码的，如稀疏性，低秩性或非负性。不幸的是，像K-SVD这样的通过奇异值分解（SVD）学习字典来进行稀疏编码的方法难以扩展到高容量和高维度的视觉数据，并且在存在异常值的情况下是脆弱的。相反，强健的组件分析方法，如鲁棒主成分分析（RPCA），能够从数据量和支持度不明的数据中恢复出低复杂度（例如低秩）的表示，但是不提供一个尊重的字典数据的结构（例如图像），并且还涉及昂贵的计算。在本文中，我们提出了一种新的Kronecker可分解的组件分析模型，被称为鲁棒Kronecker组件分析（RKCA），它结合了稀疏字典学习和强大的组件分析的思想。 RKCA有几个有吸引力的属性，包括粗暴的腐败;它可以用于低级建模，并利用分离性来解决显着较小的问题。我们设计了一种有效的学习算法，通过绘制具有限制形式的张量分解的链接，并分析其最优性和低秩性。所提出的方法的有效性通过与现有技术进行彻底的比较而在现实世界的应用中被证实，即背景减除和图像去噪和完成。

##### URL
[http://arxiv.org/abs/1801.06432](http://arxiv.org/abs/1801.06432)

##### PDF
[http://arxiv.org/pdf/1801.06432](http://arxiv.org/pdf/1801.06432)

