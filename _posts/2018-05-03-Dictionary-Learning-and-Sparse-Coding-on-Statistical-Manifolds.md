---
layout: post
title: "Dictionary Learning and Sparse Coding on Statistical Manifolds"
date: 2018-05-03 22:00:38
categories: arXiv_CV
tags: arXiv_CV Sparse Classification
author: Rudrasis Chakraborty, Monami Banerjee, Baba C. Vemuri
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel information theoretic framework for dictionary learning (DL) and sparse coding (SC) on a statistical manifold (the manifold of probability distributions). Unlike the traditional DL and SC framework, our new formulation does not explicitly incorporate any sparsity inducing norm in the cost function being optimized but yet yields sparse codes. Our algorithm approximates the data points on the statistical manifold (which are probability distributions) by the weighted Kullback-Leibeler center/mean (KL-center) of the dictionary atoms. The KL-center is defined as the minimizer of the maximum KL-divergence between itself and members of the set whose center is being sought. Further, we prove that the weighted KL-center is a sparse combination of the dictionary atoms. This result also holds for the case when the KL-divergence is replaced by the well known Hellinger distance. From an applications perspective, we present an extension of the aforementioned framework to the manifold of symmetric positive definite matrices (which can be identified with the manifold of zero mean gaussian distributions), $\mathcal{P}_n$. We present experiments involving a variety of dictionary-based reconstruction and classification problems in Computer Vision. Performance of the proposed algorithm is demonstrated by comparing it to several state-of-the-art methods in terms of reconstruction and classification accuracy as well as sparsity of the chosen representation.

##### Abstract (translated by Google)
在本文中，我们在统计流形（概率分布的流形）上提出了一种用于字典学习（DL）和稀疏编码（SC）的新型信息理论框架。与传统的DL和SC框架不同，我们的新公式没有明确地将正在优化的成本函数中的稀疏诱导规范并入，但却产生了稀疏代码。我们的算法通过字典原子的加权Kullback-Leibeler中心/平均值（KL中心）来近似统计流形上的数据点（其是概率分布）。吉隆坡中心被定义为最大限度的KL-分歧与其中心正在寻找的成员之间的最小化。此外，我们证明加权KL中心是字典原子的稀疏组合。这个结果也适用于KL-散度被众所周知的海林格距离所取代的情况。从应用的角度来看，我们将上述框架扩展到对称正定矩阵（可以用零均值高斯分布的流形来确定），$ \ mathcal {P} _n $。我们提出涉及计算机视觉中各种基于字典的重建和分类问题的实验。所提出的算法的性能通过将其与几种最先进的方法在重建和分类准确性以及所选表示的稀疏性方面进行比较来证明。

##### URL
[http://arxiv.org/abs/1805.02505](http://arxiv.org/abs/1805.02505)

##### PDF
[http://arxiv.org/pdf/1805.02505](http://arxiv.org/pdf/1805.02505)

