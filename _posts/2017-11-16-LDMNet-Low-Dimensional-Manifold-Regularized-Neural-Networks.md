---
layout: post
title: "LDMNet: Low Dimensional Manifold Regularized Neural Networks"
date: 2017-11-16 18:48:01
categories: arXiv_CV
tags: arXiv_CV Regularization Face Recognition Face_Recognition
author: Wei Zhu, Qiang Qiu, Jiaji Huang, Robert Calderbank, Guillermo Sapiro, Ingrid Daubechies
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks have proved very successful on archetypal tasks for which large training sets are available, but when the training data are scarce, their performance suffers from overfitting. Many existing methods of reducing overfitting are data-independent, and their efficacy is often limited when the training set is very small. Data-dependent regularizations are mostly motivated by the observation that data of interest lie close to a manifold, which is typically hard to parametrize explicitly and often requires human input of tangent vectors. These methods typically only focus on the geometry of the input data, and do not necessarily encourage the networks to produce geometrically meaningful features. To resolve this, we propose a new framework, the Low-Dimensional-Manifold-regularized neural Network (LDMNet), which incorporates a feature regularization method that focuses on the geometry of both the input data and the output features. In LDMNet, we regularize the network by encouraging the combination of the input data and the output features to sample a collection of low dimensional manifolds, which are searched efficiently without explicit parametrization. To achieve this, we directly use the manifold dimension as a regularization term in a variational functional. The resulting Euler-Lagrange equation is a Laplace-Beltrami equation over a point cloud, which is solved by the point integral method without increasing the computational complexity. We demonstrate two benefits of LDMNet in the experiments. First, we show that LDMNet significantly outperforms widely-used network regularizers such as weight decay and DropOut. Second, we show that LDMNet can be designed to extract common features of an object imaged via different modalities, which proves to be very useful in real-world applications such as cross-spectral face recognition.

##### Abstract (translated by Google)
深度神经网络在大型训练集可用的原型任务上已经证明是非常成功的，但是当训练数据稀少时，其性能会受到过度拟合的影响。许多现有的减少过拟合的方法都是与数据无关的，而且当训练集非常小时，其功效通常是有限的。依赖于数据的正则化大部分是由于观察数据靠近一个流形，这通常难以明确参数化并且通常需要人类输入切向量。这些方法通常只关注输入数据的几何形状，并不一定会鼓励网络产生具有几何意义的特征。为了解决这个问题，我们提出了一个新的框架，低维流形正则化的神经网络（LDMNet），它结合了一个特征正则化方法，侧重于输入数据和输出特征的几何。在LDMNet中，我们通过鼓励输入数据和输出特征的组合来对网络进行正则化，以对低维流形的集合进行采样，这些低维流形在没有明确的参数化的情况下被有效地搜索。为了实现这一点，我们直接使用流形维数作为变分函数中的正则项。由此得到的欧拉 - 拉格朗日方程是点云上的拉普拉斯 - 贝尔特拉米（Laplace-Beltrami）方程，其通过点积分方法求解而不增加计算复杂度。我们在实验中证明了LDMNet的两个好处。首先，我们展示LDMNet显着优于广泛使用的网络正规化器，如重量衰减和DropOut。其次，我们展示了LDMNet可以被设计为通过不同的模式提取成像对象的共同特征，这证明在现实世界的应用中是非常有用的，例如交叉光谱人脸识别。

##### URL
[https://arxiv.org/abs/1711.06246](https://arxiv.org/abs/1711.06246)

##### PDF
[https://arxiv.org/pdf/1711.06246](https://arxiv.org/pdf/1711.06246)

