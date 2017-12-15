---
layout: post
title: "Piecewise convexity of artificial neural networks"
date: 2016-12-28 06:39:01
categories: arXiv_CV
tags: arXiv_CV Regularization Speech_Recognition Optimization Gradient_Descent Recognition
author: Blaine Rister, Daniel L Rubin
mathjax: true
---

* content
{:toc}

##### Abstract
Although artificial neural networks have shown great promise in applications including computer vision and speech recognition, there remains considerable practical and theoretical difficulty in optimizing their parameters. The seemingly unreasonable success of gradient descent methods in minimizing these non-convex functions remains poorly understood. In this work we offer some theoretical guarantees for networks with piecewise affine activation functions, which have in recent years become the norm. We prove three main results. Firstly, that the network is piecewise convex as a function of the input data. Secondly, that the network, considered as a function of the parameters in a single layer, all others held constant, is again piecewise convex. Finally, that the network as a function of all its parameters is piecewise multi-convex, a generalization of biconvexity. From here we characterize the local minima and stationary points of the training objective, showing that they minimize certain subsets of the parameter space. We then analyze the performance of two optimization algorithms on multi-convex problems: gradient descent, and a method which repeatedly solves a number of convex sub-problems. We prove necessary convergence conditions for the first algorithm and both necessary and sufficient conditions for the second, after introducing regularization to the objective. Finally, we remark on the remaining difficulty of the global optimization problem. Under the squared error objective, we show that by varying the training data, a single rectifier neuron admits local minima arbitrarily far apart, both in objective value and parameter space.

##### Abstract (translated by Google)
尽管人工神经网络在包括计算机视觉和语音识别在内的应用中已经显示出很大的希望，梯度下降方法在最小化这些非凸函数方面的看似不合理的成功仍然知之甚少。在这项工作中，我们为具有分段仿射激活功能的网络提供了一些理论上的保证，这些功能近年来已经成为常态。我们证明了三个主要结果。首先，网络是分段凸的作为输入数据的函数。其次，被认为是单层参数函数的网络，其他所有网络都保持不变，再次是分段凸的。最后，网络作为其所有参数的函数是分段多凸的，双凸性的推广。从这里我们表征训练目标的局部最小值和平稳点，表明它们最小化参数空间的某些子集。然后，我们分析两个优化算法在多凸问题上的性能：梯度下降和反复求解多个凸子问题的方法。在第二种算法的正则化引入后，证明了第一种算法的必要收敛条件和第二种算法的充要条件。最后，我们谈论全局优化问题的其余难点。在平方误差目标下，我们表明，通过改变训练数据，单个整流器神经元允许在目标值和参数空间上任意相距很远的局部最小值。

##### URL
[https://arxiv.org/abs/1607.04917](https://arxiv.org/abs/1607.04917)

##### PDF
[https://arxiv.org/pdf/1607.04917](https://arxiv.org/pdf/1607.04917)

