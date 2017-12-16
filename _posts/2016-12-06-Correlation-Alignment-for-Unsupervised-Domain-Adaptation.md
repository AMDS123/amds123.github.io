---
layout: post
title: "Correlation Alignment for Unsupervised Domain Adaptation"
date: 2016-12-06 18:31:57
categories: arXiv_CV
tags: arXiv_CV Relation
author: Baochen Sun, Jiashi Feng, Kate Saenko
mathjax: true
---

* content
{:toc}

##### Abstract
In this chapter, we present CORrelation ALignment (CORAL), a simple yet effective method for unsupervised domain adaptation. CORAL minimizes domain shift by aligning the second-order statistics of source and target distributions, without requiring any target labels. In contrast to subspace manifold methods, it aligns the original feature distributions of the source and target domains, rather than the bases of lower-dimensional subspaces. It is also much simpler than other distribution matching methods. CORAL performs remarkably well in extensive evaluations on standard benchmark datasets. We first describe a solution that applies a linear transformation to source features to align them with target features before classifier training. For linear classifiers, we propose to equivalently apply CORAL to the classifier weights, leading to added efficiency when the number of classifiers is small but the number and dimensionality of target examples are very high. The resulting CORAL Linear Discriminant Analysis (CORAL-LDA) outperforms LDA by a large margin on standard domain adaptation benchmarks. Finally, we extend CORAL to learn a nonlinear transformation that aligns correlations of layer activations in deep neural networks (DNNs). The resulting Deep CORAL approach works seamlessly with DNNs and achieves state-of-the-art performance on standard benchmark datasets. Our code is available at:~\url{this https URL}

##### Abstract (translated by Google)
在本章中，我们提出CORRALAL ALIGN（CORAL），一种简单而有效的无监督域自适应方法。 CORAL通过对齐源和目标分布的二阶统计来最小化域偏移，而不需要任何目标标签。与子空间流形方法相反，它将原始和目标域的原始特征分布对齐，而不是低维子空间的基础。它也比其他分布匹配方法简单得多。 CORAL在标准基准数据集的广泛评估中表现出色。我们首先描述一个解决方案，将线性变换应用于源特征，以在分类器训练之前将其与目标特征对齐。对于线性分类器，我们建议等效地将CORAL应用于分类器权重，从而在分类器数目小但目标例子的数量和维数非常高时增加效率。由此产生的CORAL线性判别分析（CORAL-LDA）在标准域适应基准上优于LDA。最后，我们扩展CORAL以学习一个非线性变换，以对齐深度神经网络（DNN）中层激活的相关性。由此产生的Deep CORAL方法与DNN无缝协作，在标准基准数据集上实现了最先进的性能。我们的代码可在〜\ url {this https URL}

##### URL
[https://arxiv.org/abs/1612.01939](https://arxiv.org/abs/1612.01939)

##### PDF
[https://arxiv.org/pdf/1612.01939](https://arxiv.org/pdf/1612.01939)

