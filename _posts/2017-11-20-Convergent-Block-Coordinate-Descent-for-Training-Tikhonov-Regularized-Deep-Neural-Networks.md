---
layout: post
title: "Convergent Block Coordinate Descent for Training Tikhonov Regularized Deep Neural Networks"
date: 2017-11-20 15:04:45
categories: arXiv_CV
tags: arXiv_CV Optimization Gradient_Descent
author: Ziming Zhang, Matthew Brand
mathjax: true
---

* content
{:toc}

##### Abstract
By lifting the ReLU function into a higher dimensional space, we develop a smooth multi-convex formulation for training feed-forward deep neural networks (DNNs). This allows us to develop a block coordinate descent (BCD) training algorithm consisting of a sequence of numerically well-behaved convex optimizations. Using ideas from proximal point methods in convex analysis, we prove that this BCD algorithm will converge globally to a stationary point with R-linear convergence rate of order one. In experiments with the MNIST database, DNNs trained with this BCD algorithm consistently yielded better test-set error rates than identical DNN architectures trained via all the stochastic gradient descent (SGD) variants in the Caffe toolbox.

##### Abstract (translated by Google)
通过将ReLU函数提升到更高维空间，我们开发了一个用于训练前馈深度神经网络（DNN）的平滑多凸表达式。这使我们能够开发一个由一系列数值良好的凸优化组成的块坐标下降（BCD）训练算法。利用凸分析中近点方法的思想，证明了这种BCD算法将在全局收敛于一阶R-线性收敛速度的平稳点。在MNIST数据库的实验中，使用这种BCD算法训练的DNN与Caffe工具箱中的所有随机梯度下降（SGD）变体训练的相同DNN体系结构相比，始终产生更好的测试集错误率。

##### URL
[https://arxiv.org/abs/1711.07354](https://arxiv.org/abs/1711.07354)

##### PDF
[https://arxiv.org/pdf/1711.07354](https://arxiv.org/pdf/1711.07354)

