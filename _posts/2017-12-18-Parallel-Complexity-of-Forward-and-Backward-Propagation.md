---
layout: post
title: "Parallel Complexity of Forward and Backward Propagation"
date: 2017-12-18 18:46:51
categories: arXiv_AI
tags: arXiv_AI RNN
author: Maxim Naumov
mathjax: true
---

* content
{:toc}

##### Abstract
We show that the forward and backward propagation can be formulated as a solution of lower and upper triangular systems of equations. For standard feedforward (FNNs) and recurrent neural networks (RNNs) the triangular systems are always block bi-diagonal, while for a general computation graph (directed acyclic graph) they can have a more complex triangular sparsity pattern. We discuss direct and iterative parallel algorithms that can be used for their solution and interpreted as different ways of performing model parallelism. Also, we show that for FNNs and RNNs with $k$ layers and $\tau$ time steps the backward propagation can be performed in parallel in O($\log k$) and O($\log k \log \tau$) steps, respectively. Finally, we outline the generalization of this technique using Jacobians that potentially allows us to handle arbitrary layers.

##### Abstract (translated by Google)
我们表明，向前和向后的传播可以被形成为一个上下三角方程组的解。对于标准前馈（FNN）和递归神经网络（RNN），三角形系统总是块双对角线，而对于一般计算图（有向无环图），它们可以具有更复杂的三角形稀疏模式。我们讨论可用于解决方案的直接和迭代并行算法，并将其解释为执行模型并行的不同方式。此外，我们还表明，对于具有$ k $图层和$ \ tau $时间步长的FNN和RNN，反向传播可以在O（$ \ log k $）和O（$ \ log k \ log \ tau $ ）步骤，分别。最后，我们概述了使用雅可比矩阵的这种技术的泛化，它可能允许我们处理任意的图层。

##### URL
[http://arxiv.org/abs/1712.06577](http://arxiv.org/abs/1712.06577)

##### PDF
[http://arxiv.org/pdf/1712.06577](http://arxiv.org/pdf/1712.06577)

