---
layout: post
title: 'Gradient Descent Learns One-hidden-layer CNN: Don't be Afraid of Spurious Local Minima'
date: 2017-12-03 15:00:35
categories: arXiv_CV
tags: arXiv_CV CNN Gradient_Descent
author: Simon S. Du, Jason D. Lee, Yuandong Tian, Barnabas Poczos, Aarti Singh
---

* content
{:toc}

##### Abstract
We consider the problem of learning a one-hidden-layer neural network with non-overlapping convolutional layer and ReLU activation function, i.e., $f(\mathbf{Z}; \mathbf{w}, \mathbf{a}) = \sum_j a_j\sigma(\mathbf{w}^\top\mathbf{Z}_j)$, in which both the convolutional weights $\mathbf{w}$ and the output weights $\mathbf{a}$ are parameters to be learned. We prove that with Gaussian input $\mathbf{Z}$, there is a spurious local minimum that is not a global mininum. Surprisingly, in the presence of local minimum, starting from randomly initialized weights, gradient descent with weight normalization can still be proven to recover the true parameters with constant probability (which can be boosted to arbitrarily high accuracy with multiple restarts). We also show that with constant probability, the same procedure could also converge to the spurious local minimum, showing that the local minimum plays a non-trivial role in the dynamics of gradient descent. Furthermore, a quantitative analysis shows that the gradient descent dynamics has two phases: it starts off slow, but converges much faster after several iterations.

##### Abstract (translated by Google)
我们考虑学习具有非重叠卷积层和ReLU激活函数的一个隐藏层神经网络的问题，即$ f（\ mathbf {Z}; \ mathbf {w}，\ mathbf {a}）= \ sum_j a_j \西格马（\ mathbf {瓦特} ^ \顶部\ mathbf {Z} _j）$，其中两个卷积权重$ \ mathbf {瓦特} $和输出权$ \ mathbf {A} $是参数是学到了。我们用高斯输入$ \ mathbf {Z} $来证明，有一个伪随机局部最小值不是全局最小值。令人惊讶的是，在存在局部最小值的情况下，从随机初始化权重开始，具有权重归一化的梯度下降仍然可以证明以恒定的概率恢复真实参数（其可以通过多次重启被提升到任意高精度）。我们还表明，以一定的概率，同样的过程也可以收敛到虚假局部最小值，表明局部最小值在梯度下降的动力学中起着不重要的作用。此外，定量分析表明，梯度下降动力学有两个阶段：它开始慢，但几次迭代后收敛速度更快。

##### URL
[http://arxiv.org/abs/1712.00779](http://arxiv.org/abs/1712.00779)

