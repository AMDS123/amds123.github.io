---
layout: post
title: "Understanding Deep Neural Networks with Rectified Linear Units"
date: 2018-02-28 02:23:47
categories: arXiv_AI
tags: arXiv_AI
author: Raman Arora, Amitabh Basu, Poorya Mianjy, Anirbit Mukherjee
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we investigate the family of functions representable by deep neural networks (DNN) with rectified linear units (ReLU). We give an algorithm to train a ReLU DNN with one hidden layer to *global optimality* with runtime polynomial in the data size albeit exponential in the input dimension. Further, we improve on the known lower bounds on size (from exponential to super exponential) for approximating a ReLU deep net function by a shallower ReLU net. Our gap theorems hold for smoothly parametrized families of "hard" functions, contrary to countable, discrete families known in the literature. An example consequence of our gap theorems is the following: for every natural number $k$ there exists a function representable by a ReLU DNN with $k^2$ hidden layers and total size $k^3$, such that any ReLU DNN with at most $k$ hidden layers will require at least $\frac{1}{2}k^{k+1}-1$ total nodes. Finally, for the family of $\mathbb{R}^n\to \mathbb{R}$ DNNs with ReLU activations, we show a new lowerbound on the number of affine pieces, which is larger than previous constructions in certain regimes of the network architecture and most distinctively our lowerbound is demonstrated by an explicit construction of a *smoothly parameterized* family of functions attaining this scaling. Our construction utilizes the theory of zonotopes from polyhedral theory.

##### Abstract (translated by Google)
在本文中，我们研究了具有整型线性单元（ReLU）的深层神经网络（DNN）可表示的函数族。我们给出了一种算法来训练带有一个隐含层的ReLU DNN到*全局最优性*，其运行时多项式的数据尺寸尽管在输入维度上是指数型的。此外，我们改进了已知的尺寸下限（从指数到超指数），以便通过更浅的ReLU网络逼近ReLU深层网络函数。我们的差距定理适用于顺利参数化的“硬”功能家族，与文献中已知的可数离散族相反。我们的间隙定理的一个例子结果如下：对于每个自然数$ k $，存在一个函数，该函数可以由具有$ k ^ 2 $隐藏层的ReLU DNN和总大小$ k ^ 3 $表示，使得任何ReLU DNN与最多$ k $隐藏层将需要至少$ \ frac {1} {2} k ^ {k + 1} -1 $个节点。最后，对于具有ReLU激活的$ \ mathbb {R} $ n \到\ mathbb {R} $ DNNs的家族，我们在仿射件的数量上显示出新的下限，这大于先前在某些制度下网络体系结构以及最明显的我们的下限是通过明确构建实现这种缩放的平滑参数化函数系列来演示的。我们的建筑利用了多面体理论中的zonotopes理论。

##### URL
[http://arxiv.org/abs/1611.01491](http://arxiv.org/abs/1611.01491)

##### PDF
[http://arxiv.org/pdf/1611.01491](http://arxiv.org/pdf/1611.01491)

