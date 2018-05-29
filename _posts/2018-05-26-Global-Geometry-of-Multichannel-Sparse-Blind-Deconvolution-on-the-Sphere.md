---
layout: post
title: "Global Geometry of Multichannel Sparse Blind Deconvolution on the Sphere"
date: 2018-05-26 07:04:18
categories: arXiv_CV
tags: arXiv_CV Sparse CNN Optimization Gradient_Descent
author: Yanjun Li, Yoram Bresler
mathjax: true
---

* content
{:toc}

##### Abstract
Multichannel blind deconvolution is the problem of recovering an unknown signal $f$ and multiple unknown channels $x_i$ from convolutional measurements $y_i=x_i \circledast f$ ($i=1,2,\dots,N$). We consider the case where the $x_i$'s are sparse, and convolution with $f$ is invertible. Our nonconvex optimization formulation solves for a filter $h$ on the unit sphere that produces sparse output $y_i\circledast h$. Under some technical assumptions, we show that all local minima of the objective function correspond to the inverse filter of $f$ up to an inherent sign and shift ambiguity, and all saddle points have strictly negative curvatures. This geometric structure allows successful recovery of $f$ and $x_i$ using a simple manifold gradient descent algorithm with random initialization. Our theoretical findings are complemented by numerical experiments, which demonstrate superior performance of the proposed approach over the previous methods.

##### Abstract (translated by Google)
多通道盲反卷积是从卷积测量$ y_i = x_i \ circledast f $（$ i = 1,2，\ dots，N $）中恢复未知信号$ f $和多个未知通道$ x_i $的问题。我们考虑$ x_i $是稀疏的情况，并且$ f $的卷积是可逆的。我们的非凸优化公式解决了单位球上的滤波器$ h $产生稀疏输出$ y_i \ circledast h $的问题。在一些技术假设下，我们证明了目标函数的所有局部最小值对应于$ f $的逆滤波器，直到固有符号和移位模糊，并且所有的鞍点都有严格的负曲率。这种几何结构允许使用随机初始化的简单流形梯度下降算法成功恢复$ f $和$ x_i $。我们的理论研究结果得到了数值实验的补充，证明了所提出方法优于以前方法的优越性能。

##### URL
[http://arxiv.org/abs/1805.10437](http://arxiv.org/abs/1805.10437)

##### PDF
[http://arxiv.org/pdf/1805.10437](http://arxiv.org/pdf/1805.10437)

