---
layout: post
title: "A Two-Stage Subspace Trust Region Approach for Deep Neural Network Training"
date: 2018-05-23 21:12:48
categories: arXiv_CV
tags: arXiv_CV Gradient_Descent
author: Viacheslav Dudar, Giovanni Chierchia, Emilie Chouzenoux, Jean-Christophe Pesquet, Vladimir Semenov
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we develop a novel second-order method for training feed-forward neural nets. At each iteration, we construct a quadratic approximation to the cost function in a low-dimensional subspace. We minimize this approximation inside a trust region through a two-stage procedure: first inside the embedded positive curvature subspace, followed by a gradient descent step. This approach leads to a fast objective function decay, prevents convergence to saddle points, and alleviates the need for manually tuning parameters. We show the good performance of the proposed algorithm on benchmark datasets.

##### Abstract (translated by Google)
在本文中，我们开发了一种新的训练前馈神经网络的二阶方法。在每次迭代中，我们构造低维子空间中成本函数的二次近似。我们通过两阶段程序使信赖区域内的这种近似最小化：首先在嵌入正曲率子空间内，然后是梯度下降步骤。这种方法导致快速的目标函数衰减，防止收敛到鞍点，并减少手动调整参数的需要。我们在基准数据集上展示了所提出的算法的良好性能。

##### URL
[http://arxiv.org/abs/1805.09430](http://arxiv.org/abs/1805.09430)

##### PDF
[http://arxiv.org/pdf/1805.09430](http://arxiv.org/pdf/1805.09430)

