---
layout: post
title: "An information theoretic formulation of the Dictionary Learning and Sparse Coding Problems on Statistical Manifolds"
date: 2017-02-03 12:28:52
categories: arXiv_CV
tags: arXiv_CV Sparse Classification Gradient_Descent
author: Rudrasis Chakraborty, Monami Banerjee, Victoria Crawford, Baba C. Vemuri
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we propose a novel information theoretic framework for dictionary learning (DL) and sparse coding (SC) on a statistical manifold (the manifold of probability distributions). Unlike the traditional DL and SC framework, our new formulation {\it does not explicitly incorporate any sparsity inducing norm in the cost function but yet yields SCs}. Moreover, we extend this framework to the manifold of symmetric positive definite matrices, $\mathcal{P}_n$. Our algorithm approximates the data points, which are probability distributions, by the weighted Kullback-Leibeler center (KL-center) of the dictionary atoms. The KL-center is the minimizer of the maximum KL-divergence between the unknown center and members of the set whose center is being sought. Further, {\it we proved that this KL-center is a sparse combination of the dictionary atoms}. Since, the data reside on a statistical manifold, the data fidelity term can not be as simple as in the case of the vector-space data. We therefore employ the geodesic distance between the data and a sparse approximation of the data element. This cost function is minimized using an acceleterated gradient descent algorithm. An extensive set of experimental results show the effectiveness of our proposed framework. We present several experiments involving a variety of classification problems in Computer Vision applications. Further, we demonstrate the performance of our algorithm by comparing it to several state-of-the-art methods both in terms of classification accuracy and sparsity.

##### Abstract (translated by Google)
在这项工作中，我们提出了一个统计流形（概率分布的流形）上的字典学习（DL）和稀疏编码（SC）的新的信息理论框架。与传统的DL和SC框架不同，我们的新的公式并没有在成本函数中明确纳入任何稀疏诱导规范，而是产生了SCs。此外，我们将这个框架扩展到对称正定矩阵$ \ mathcal {P} _n $。我们的算法通过字典原子的加权Kullback-Leibeler中心（KL中心）近似数据点，即概率分布。吉隆坡中心是未知中心与正在寻找中心的成员之间最大KL分歧的最小值。而且，我们证明了这个KL中心是字典原子的稀疏组合。由于数据驻留在统计流形上，因此数据保真度不能像向量空间数据那样简单。因此，我们使用数据和数据元素的稀疏近似之间的测地距离。使用加速梯度下降算法将该成本函数最小化。大量的实验结果表明了我们提出的框架的有效性。我们提出了涉及计算机视觉应用中的各种分类问题的几个实验。此外，我们通过将其与几种最先进的方法在分类准确性和稀疏性方面进行比较来证明我们算法的性能。

##### URL
[https://arxiv.org/abs/1604.06939](https://arxiv.org/abs/1604.06939)

##### PDF
[https://arxiv.org/e-print/1604.06939](https://arxiv.org/e-print/1604.06939)

