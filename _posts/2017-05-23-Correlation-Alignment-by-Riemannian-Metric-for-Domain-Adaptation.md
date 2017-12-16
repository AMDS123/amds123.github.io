---
layout: post
title: "Correlation Alignment by Riemannian Metric for Domain Adaptation"
date: 2017-05-23 11:08:48
categories: arXiv_CV
tags: arXiv_CV Relation
author: Pietro Morerio, Vittorio Murino
mathjax: true
---

* content
{:toc}

##### Abstract
Domain adaptation techniques address the problem of reducing the sensitivity of machine learning methods to the so-called domain shift, namely the difference between source (training) and target (test) data distributions. In particular, unsupervised domain adaptation assumes no labels are available in the target domain. To this end, aligning second order statistics (covariances) of target and source domains have proven to be an effective approach ti fill the gap between the domains. However, covariance matrices do not form a subspace of the Euclidean space, but live in a Riemannian manifold with non-positive curvature, making the usual Euclidean metric suboptimal to measure distances. In this paper, we extend the idea of training a neural network with a constraint on the covariances of the hidden layer features, by rigorously accounting for the curved structure of the manifold of symmetric positive definite matrices. The resulting loss function exploits a theoretically sound geodesic distance on such manifold. Results show indeed the suboptimal nature of the Euclidean distance. This makes us able to perform better than previous approaches on the standard Office dataset, a benchmark for domain adaptation techniques.

##### Abstract (translated by Google)
领域适应技术解决了降低机器学习方法对所谓的领域转换的敏感性的问题，即源（训练）和目标（测试）数据分布之间的差异。特别是，无监督的域适应假定目标域中没有标签可用。为此，调整目标域和源域的二阶统计量（协方差）已被证明是一种有效的方法，填补了域之间的差距。然而协方差矩阵并不构成欧几里得空间的一个子空间，而是生活在一个黎曼流形中，具有非正曲率，使得通常的欧几里德度量不是最优的来衡量距离。本文通过严格考虑对称正定矩阵流形的曲面结构，扩展了对隐层特征协方差约束的神经网络的训练思想。由此产生的损失函数在这种流形上利用了理论上的测地距离。结果确实显示了欧几里得距离的次优性质。这使我们能够在标准的Office数据集上执行比以前更好的方法，这是领域适应技术的基准。

##### URL
[https://arxiv.org/abs/1705.08180](https://arxiv.org/abs/1705.08180)

##### PDF
[https://arxiv.org/pdf/1705.08180](https://arxiv.org/pdf/1705.08180)

