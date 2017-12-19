---
layout: post
title: "A novel multivariate performance optimization method based on sparse coding and hyper-predictor learning"
date: 2015-07-31 12:14:35
categories: arXiv_CV
tags: arXiv_CV Sparse Optimization Prediction
author: Jiachen Yanga, Zhiyong Dinga, Fei Guoa, Huogen Wanga, Nick Hughesb
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we investigate the problem of optimization multivariate performance measures, and propose a novel algorithm for it. Different from traditional machine learning methods which optimize simple loss functions to learn prediction function, the problem studied in this paper is how to learn effective hyper-predictor for a tuple of data points, so that a complex loss function corresponding to a multivariate performance measure can be minimized. We propose to present the tuple of data points to a tuple of sparse codes via a dictionary, and then apply a linear function to compare a sparse code against a give candidate class label. To learn the dictionary, sparse codes, and parameter of the linear function, we propose a joint optimization problem. In this problem, the both the reconstruction error and sparsity of sparse code, and the upper bound of the complex loss function are minimized. Moreover, the upper bound of the loss function is approximated by the sparse codes and the linear function parameter. To optimize this problem, we develop an iterative algorithm based on descent gradient methods to learn the sparse codes and hyper-predictor parameter alternately. Experiment results on some benchmark data sets show the advantage of the proposed methods over other state-of-the-art algorithms.

##### Abstract (translated by Google)
在本文中，我们研究了优化多元性能测度的问题，并提出了一种新的算法。与传统的优化简单损失函数学习预测函数的机器学习方法不同，本文研究的问题是如何学习一个数据点元组的有效超预测器，从而使一个与多元性能指标对应的复杂损失函数被最小化。我们建议将数据点的元组通过字典呈现给稀疏代码元组，然后应用线性函数将稀疏代码与给定候选类标签进行比较。为了学习字典，稀疏编码和线性函数的参数，我们提出一个联合优化问题。在这个问题中，稀疏码的重构误差和稀疏性以及复合损失函数的上界都被最小化。此外，损失函数的上界由稀疏码和线性函数参数近似。为了优化这个问题，我们开发了一种基于下降梯度方法的迭代算法来交替地学习稀疏码和超预测参数。在一些基准数据集上的实验结果显示了所提出的方法优于其他最先进的算法的优点。

##### URL
[https://arxiv.org/abs/1507.08847](https://arxiv.org/abs/1507.08847)

##### PDF
[https://arxiv.org/pdf/1507.08847](https://arxiv.org/pdf/1507.08847)

