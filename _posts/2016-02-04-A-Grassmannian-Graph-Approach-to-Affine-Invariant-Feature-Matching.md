---
layout: post
title: "A Grassmannian Graph Approach to Affine Invariant Feature Matching"
date: 2016-02-04 05:18:52
categories: arXiv_CV
tags: arXiv_CV GAN Relation
author: Mark Moyou, John Corring, Adrian Peter, Anand Rangarajan
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we present a novel and practical approach to address one of the longstanding problems in computer vision: 2D and 3D affine invariant feature matching. Our Grassmannian Graph (GrassGraph) framework employs a two stage procedure that is capable of robustly recovering correspondences between two unorganized, affinely related feature (point) sets. The first stage maps the feature sets to an affine invariant Grassmannian representation, where the features are mapped into the same subspace. It turns out that coordinate representations extracted from the Grassmannian differ by an arbitrary orthonormal matrix. In the second stage, by approximating the Laplace-Beltrami operator (LBO) on these coordinates, this extra orthonormal factor is nullified, providing true affine-invariant coordinates which we then utilize to recover correspondences via simple nearest neighbor relations. The resulting GrassGraph algorithm is empirically shown to work well in non-ideal scenarios with noise, outliers, and occlusions. Our validation benchmarks use an unprecedented 440,000+ experimental trials performed on 2D and 3D datasets, with a variety of parameter settings and competing methods. State-of-the-art performance in the majority of these extensive evaluations confirm the utility of our method.

##### Abstract (translated by Google)
在这项工作中，我们提出了一种新颖和实用的方法来解决计算机视觉中长期存在的问题之一：二维和三维仿射不变特征匹配。我们的Grassmannian图（GrassGraph）框架采用两阶段程序，能够强有力地恢复两个无组织的，仿射相关的特征（点）集之间的对应关系。第一阶段将特征集映射为仿射不变Grassmannian表示，其中特征映射到相同的子空间。事实证明，从Grassmannian中提取的坐标表示不同于任意的正交矩阵。在第二阶段，通过在这些坐标上近似拉普拉斯 - 贝尔特拉米算子（LBO），这个额外的正交因子被取消，提供了真正的仿射不变坐标，然后我们利用这个坐标来通过简单的最近邻关系恢复对应关系。由此产生的GrassGraph算法在经验上表现出在噪声，异常值和遮挡的非理想情况下很好地工作。我们的验证基准使用了前所未有的在二维和三维数据集上进行的440,000多个实验性试验，并提供了多种参数设置和竞争方法。在大多数广泛的评估中，最先进的性能证实了我们方法的实用性。

##### URL
[https://arxiv.org/abs/1601.07648](https://arxiv.org/abs/1601.07648)

##### PDF
[https://arxiv.org/pdf/1601.07648](https://arxiv.org/pdf/1601.07648)

