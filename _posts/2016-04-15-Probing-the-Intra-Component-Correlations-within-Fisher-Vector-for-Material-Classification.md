---
layout: post
title: "Probing the Intra-Component Correlations within Fisher Vector for Material Classification"
date: 2016-04-15 12:55:00
categories: arXiv_CV
tags: arXiv_CV Image_Caption Classification Relation
author: Xiaopeng Hong, Xianbiao Qi, Guoying Zhao, Matti Pietikäinen
mathjax: true
---

* content
{:toc}

##### Abstract
Fisher vector (FV) has become a popular image representation. One notable underlying assumption of the FV framework is that local descriptors are well decorrelated within each cluster so that the covariance matrix for each Gaussian can be simplified to be diagonal. Though the FV usually relies on the Principal Component Analysis (PCA) to decorrelate local features, the PCA is applied to the entire training data and hence it only diagonalizes the \textit{universal} covariance matrix, rather than those w.r.t. the local components. As a result, the local decorrelation assumption is usually not supported in practice. To relax this assumption, this paper proposes a completed model of the Fisher vector, which is termed as the Completed Fisher vector (CFV). The CFV is a more general framework of the FV, since it encodes not only the variances but also the correlations of the whitened local descriptors. The CFV thus leads to improved discriminative power. We take the task of material categorization as an example and experimentally show that: 1) the CFV outperforms the FV under all parameter settings; 2) the CFV is robust to the changes in the number of components in the mixture; 3) even with a relatively small visual vocabulary the CFV still works well on two challenging datasets.

##### Abstract (translated by Google)
费舍尔矢量（FV）已经成为流行的图像表示。 FV框架的一个值得注意的基本假设是局部描述符在每个聚类内都很好地解相关，所以每个高斯的协方差矩阵可以简化为对角线。尽管FV通常依赖于主成分分析（PCA）来解相关局部特征，但是PCA被应用于整个训练数据，因此它只对角化了全文协方差矩阵，而不是那些w.r.t.本地组件。结果，实际上通常不支持局部去相关假设。为了放宽这个假设，本文提出了一个完整的Fisher向量模型，称为完全费希尔向量（CFV）。 CFV是FV的一个更一般的框架，因为它不仅编码变化，而且编码变白的局部描述符的相关性。 CFV因此导致改善的判别力。以材料分类为例，实验表明：1）在所有参数设置下，CFV均优于FV; 2）CFV对混合物中组分数量的变化是强有力的; 3）即使有一个相对较小的视觉词汇CFV仍然适用于两个具有挑战性的数据集。

##### URL
[https://arxiv.org/abs/1604.04473](https://arxiv.org/abs/1604.04473)

##### PDF
[https://arxiv.org/pdf/1604.04473](https://arxiv.org/pdf/1604.04473)

