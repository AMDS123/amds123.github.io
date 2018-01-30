---
layout: post
title: "Robust Multi-subspace Analysis Using Novel Column L0-norm Constrained Matrix Factorization"
date: 2018-01-27 17:00:02
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Binghui Wang, Chuang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
We study the underlying structure of data (approximately) generated from a union of independent subspaces. Traditional methods learn only one subspace, failing to discover the multi-subspace structure, while state-of-the-art methods analyze the multi-subspace structure using data themselves as the dictionary, which cannot offer the explicit basis to span each subspace and are sensitive to errors via an indirect representation. Additionally, they also suffer from a high computational complexity, being quadratic or cubic to the sample size. To tackle all these problems, we propose a method, called Matrix Factorization with Column L0-norm constraint (MFC0), that can simultaneously learn the basis for each subspace, generate a direct sparse representation for each data sample, as well as removing errors in the data in an efficient way. Furthermore, we develop a first-order alternating direction algorithm, whose computational complexity is linear to the sample size, to stably and effectively solve the nonconvex objective function and non- smooth l0-norm constraint of MFC0. Experimental results on both synthetic and real-world datasets demonstrate that besides the superiority over traditional and state-of-the-art methods for subspace clustering, data reconstruction, error correction, MFC0 also shows its uniqueness for multi-subspace basis learning and direct sparse representation.

##### Abstract (translated by Google)
我们研究从独立子空间联合生成的数据（近似）的基本结构。传统的方法只学习一个子空间，不能发现多子空间结构，而先进的方法则是利用数据本身作为字典来分析多子空间结构，不能为每个子空间提供明确的基础，通过间接表示对错误敏感。此外，他们也遭受高计算复杂性，是样本大小的二次方或立方。为了解决所有这些问题，我们提出了一种称为矩阵分解的列L0范数约束（MFC0）方法，它可以同时学习每个子空间的基础，为每个数据样本生成一个直接的稀疏表示，数据以一种有效的方式。此外，我们开发了一种计算复杂度与样本大小成线性关系的一阶交替方向算法，以稳定有效地求解MFC0的非凸目标函数和非平滑l0范数约束。在合成数据集和现实世界数据集上的实验结果表明，除了比传统和现有的子空间聚类方法优越之外，数据重构，误差校正，MFC0还显示了其对于多子空间基础学习和直接稀疏表示。

##### URL
[http://arxiv.org/abs/1801.09111](http://arxiv.org/abs/1801.09111)

##### PDF
[http://arxiv.org/pdf/1801.09111](http://arxiv.org/pdf/1801.09111)

