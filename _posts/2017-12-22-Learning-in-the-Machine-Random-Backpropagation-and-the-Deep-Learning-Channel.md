---
layout: post
title: "Learning in the Machine: Random Backpropagation and the Deep Learning Channel"
date: 2017-12-22 17:29:20
categories: arXiv_AI
tags: arXiv_AI Sparse Deep_Learning
author: Pierre Baldi, Peter Sadowski, Zhiqin Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Random backpropagation (RBP) is a variant of the backpropagation algorithm for training neural networks, where the transpose of the forward matrices are replaced by fixed random matrices in the calculation of the weight updates. It is remarkable both because of its effectiveness, in spite of using random matrices to communicate error information, and because it completely removes the taxing requirement of maintaining symmetric weights in a physical neural system. To better understand random backpropagation, we first connect it to the notions of local learning and learning channels. Through this connection, we derive several alternatives to RBP, including skipped RBP (SRPB), adaptive RBP (ARBP), sparse RBP, and their combinations (e.g. ASRBP) and analyze their computational complexity. We then study their behavior through simulations using the MNIST and CIFAR-10 bechnmark datasets. These simulations show that most of these variants work robustly, almost as well as backpropagation, and that multiplication by the derivatives of the activation functions is important. As a follow-up, we study also the low-end of the number of bits required to communicate error information over the learning channel. We then provide partial intuitive explanations for some of the remarkable properties of RBP and its variations. Finally, we prove several mathematical results, including the convergence to fixed points of linear chains of arbitrary length, the convergence to fixed points of linear autoencoders with decorrelated data, the long-term existence of solutions for linear systems with a single hidden layer and convergence in special cases, and the convergence to fixed points of non-linear chains, when the derivative of the activation functions is included.

##### Abstract (translated by Google)
随机反向传播（RBP）是用于训练神经网络的反向传播算法的一种变体，其中在计算权重更新时正向矩阵的转置被固定的随机矩阵替换。尽管使用随机矩阵来传递错误信息，并且因为它完全消除了在物理神经系统中维持对称权重的征税要求，所以它的效果是显着的。为了更好地理解随机反向传播，我们首先将其与本地学习和学习渠道的概念联系起来。通过这个连接，我们得到了几种RBP的替代方案，包括跳过的RBP（SRPB），自适应RBP（ARBP），稀疏RBP和它们的组合（例如ASRBP），并分析它们的计算复杂性。然后，我们通过使用MNIST和CIFAR-10 bechnmark数据集进行模拟来研究他们的行为。这些仿真表明，这些变体中的大多数变体的工作是稳健的，几乎和反向传播一样，并且激活函数的导数的乘法是重要的。作为后续，我们还研究在学习通道上传达错误信息所需的位数的低端。然后，我们对RBP及其变体的一些显着特性提供部分直观的解释。最后，我们证明了几个数学结果，包括任意长度的线性链的不动点的收敛性，线性自编码器与解相关数据的不动点的收敛性，具有单隐层的线性系统的解的长期存在性以及收敛性在特殊情况下，当包含激活函数的导数时，收敛到非线性链的固定点。

##### URL
[http://arxiv.org/abs/1612.02734](http://arxiv.org/abs/1612.02734)

##### PDF
[http://arxiv.org/pdf/1612.02734](http://arxiv.org/pdf/1612.02734)

