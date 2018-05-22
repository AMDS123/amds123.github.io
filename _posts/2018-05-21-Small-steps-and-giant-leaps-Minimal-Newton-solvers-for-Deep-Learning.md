---
layout: post
title: "Small steps and giant leaps: Minimal Newton solvers for Deep Learning"
date: 2018-05-21 14:54:28
categories: arXiv_CV
tags: arXiv_CV Deep_Learning Gradient_Descent
author: João F. Henriques, Sebastien Ehrhardt, Samuel Albanie, Andrea Vedaldi
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a fast second-order method that can be used as a drop-in replacement for current deep learning solvers. Compared to stochastic gradient descent (SGD), it only requires two additional forward-mode automatic differentiation operations per iteration, which has a computational cost comparable to two standard forward passes and is easy to implement. Our method addresses long-standing issues with current second-order solvers, which invert an approximate Hessian matrix every iteration exactly or by conjugate-gradient methods, a procedure that is both costly and sensitive to noise. Instead, we propose to keep a single estimate of the gradient projected by the inverse Hessian matrix, and update it once per iteration. This estimate has the same size and is similar to the momentum variable that is commonly used in SGD. No estimate of the Hessian is maintained. We first validate our method, called CurveBall, on small problems with known closed-form solutions (noisy Rosenbrock function and degenerate 2-layer linear networks), where current deep learning solvers seem to struggle. We then train several large models on CIFAR and ImageNet, including ResNet and VGG-f networks, where we demonstrate faster convergence with no hyperparameter tuning. Code is available.

##### Abstract (translated by Google)
我们提出了一种快速的二阶方法，可以用作当前深度学习求解器的直接替代方法。与随机梯度下降（SGD）相比，每次迭代只需要两个额外的正向模式自动微分操作，其运算成本可与两个标准正向通道相比并且易于实现。我们的方法利用当前的二阶求解器解决了长期存在的问题，该求解器每次迭代精确地反演近似的Hessian矩阵，或者通过共轭梯度方法反演，该过程既昂贵又对噪声敏感。相反，我们建议保留逆Hessian矩阵投影的梯度的单个估计，并在每次迭代中更新一次。这个估计具有相同的规模，与SGD中常用的动量变量类似。没有估计Hessian是维持的。我们首先验证我们的方法，称为CurveBall，用已知的封闭形式解决方案（噪声Rosenbrock函数和退化的2层线性网络）的小问题，当前深度学习解算器似乎挣扎。然后，我们在CIFAR和ImageNet上培训了几个大型模型，包括ResNet和VGG-f网络，我们展示了更快的收敛性，没有超参数调整。代码可用。

##### URL
[https://arxiv.org/abs/1805.08095](https://arxiv.org/abs/1805.08095)

##### PDF
[https://arxiv.org/pdf/1805.08095](https://arxiv.org/pdf/1805.08095)

