---
layout: post
title: "MAGMA: Multi-level accelerated gradient mirror descent algorithm for large-scale convex composite minimization"
date: 2016-07-14 13:33:21
categories: arXiv_CV
tags: arXiv_CV Face Optimization Recognition Face_Recognition
author: Vahan Hovhannisyan, Panos Parpas, Stefanos Zafeiriou
mathjax: true
---

* content
{:toc}

##### Abstract
Composite convex optimization models arise in several applications, and are especially prevalent in inverse problems with a sparsity inducing norm and in general convex optimization with simple constraints. The most widely used algorithms for convex composite models are accelerated first order methods, however they can take a large number of iterations to compute an acceptable solution for large-scale problems. In this paper we propose to speed up first order methods by taking advantage of the structure present in many applications and in image processing in particular. Our method is based on multi-level optimization methods and exploits the fact that many applications that give rise to large scale models can be modelled using varying degrees of fidelity. We use Nesterov's acceleration techniques together with the multi-level approach to achieve $\mathcal{O}(1/\sqrt{\epsilon})$ convergence rate, where $\epsilon$ denotes the desired accuracy. The proposed method has a better convergence rate than any other existing multi-level method for convex problems, and in addition has the same rate as accelerated methods, which is known to be optimal for first-order methods. Moreover, as our numerical experiments show, on large-scale face recognition problems our algorithm is several times faster than the state of the art.

##### Abstract (translated by Google)
复合凸优化模型在几个应用中出现，特别是在稀疏诱导范数的反问题和普通的约束简单的凸优化问题中普遍存在。用于凸面复合模型的最广泛使用的算法是加速的一阶方法，但是它们可以花费大量的迭代来计算大规模问题的可接受的解决方案。在本文中，我们提出通过利用许多应用中特别是图像处理中的结构来加速一阶方法。我们的方法是基于多层次的优化方法，并利用了这样一个事实，即许多引起大规模模型的应用程序可以使用不同程度的保真度建模。我们使用Nesterov的加速技术和多级方法来实现$ \ mathcal {O}（1 / \ sqrt {）} $收敛速度，其中$ \ epsilon $表示期望的精度。所提出的方法比任何其他现有的用于凸问题的多级方法具有更好的收敛速度，并且与已知对于一阶方法最优化的加速方法相同。而且，正如我们的数值实验所显示的那样，对于大规模的人脸识别问题，我们的算法比现有技术快几倍。

##### URL
[https://arxiv.org/abs/1509.05715](https://arxiv.org/abs/1509.05715)

##### PDF
[https://arxiv.org/pdf/1509.05715](https://arxiv.org/pdf/1509.05715)

