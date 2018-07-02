---
layout: post
title: "Theory IIIb: Generalization in Deep Networks"
date: 2018-06-29 12:39:08
categories: arXiv_AI
tags: arXiv_AI Regularization Classification Gradient_Descent
author: Tomaso Poggio, Qianli Liao, Brando Miranda, Andrzej Banburski, Xavier Boix, Jack Hidary
mathjax: true
---

* content
{:toc}

##### Abstract
A main puzzle of deep neural networks (DNNs) revolves around the apparent absence of "overfitting", defined in this paper as follows: the expected error does not get worse when increasing the number of neurons or of iterations of gradient descent. This is surprising because of the large capacity demonstrated by DNNs to fit randomly labeled data and the absence of explicit regularization. Recent results by Srebro et al. provide a satisfying solution of the puzzle for linear networks used in binary classification. They prove that minimization of loss functions such as the logistic, the cross-entropy and the exp-loss yields asymptotic, "slow" convergence to the maximum margin solution for linearly separable datasets, independently of the initial conditions. Here we prove a similar result for nonlinear multilayer DNNs near zero minima of the empirical loss. The result holds for exponential-type losses but not for the square loss. In particular, we prove that the weight matrix at each layer of a deep network converges to a minimum norm solution up to a scale factor (in the separable case). Our analysis of the dynamical system corresponding to gradient descent of a multilayer network suggests a simple criterion for ranking the generalization performance of different zero minimizers of the empirical loss.

##### Abstract (translated by Google)
深度神经网络（DNN）的主要难题围绕明显缺乏“过度拟合”，本文定义如下：当增加神经元数量或梯度下降迭代时，预期误差不会变得更糟。这是令人惊讶的，因为DNN表现出的大容量适合随机标记的数据和没有明确的正则化。 Srebro等人最近的结果。为二元分类中使用的线性网络提供令人满意的解决方案。他们证明了损失函数的最小化，例如逻辑，交叉熵和exp-loss，产生了线性可分数据集的最大边际解的渐近“缓慢”收敛，与初始条件无关。在这里我们证明了非线性多层DNNs在经验损失的零最小值附近的类似结果。结果适用于指数型损失，但不适用于平方损失。特别地，我们证明了深度网络的每一层的权重矩阵收敛到最小范数解，直到比例因子（在可分离的情况下）。我们对与多层网络的梯度下降相对应的动力系统的分析提出了一个简单的标准，用于对经验损失的不同零最小化的泛化性能进行排序。

##### URL
[http://arxiv.org/abs/1806.11379](http://arxiv.org/abs/1806.11379)

##### PDF
[http://arxiv.org/pdf/1806.11379](http://arxiv.org/pdf/1806.11379)

