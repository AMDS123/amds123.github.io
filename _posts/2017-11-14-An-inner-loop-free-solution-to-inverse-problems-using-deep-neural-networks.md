---
layout: post
title: "An inner-loop free solution to inverse problems using deep neural networks"
date: 2017-11-14 23:00:28
categories: arXiv_CV
tags: arXiv_CV Regularization CNN Inference Deep_Learning
author: Qi Wei, Kai Fan, Lawrence Carin, Katherine A. Heller
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new method that uses deep learning techniques to accelerate the popular alternating direction method of multipliers (ADMM) solution for inverse problems. The ADMM updates consist of a proximity operator, a least squares regression that includes a big matrix inversion, and an explicit solution for updating the dual variables. Typically, inner loops are required to solve the first two sub-minimization problems due to the intractability of the prior and the matrix inversion. To avoid such drawbacks or limitations, we propose an inner-loop free update rule with two pre-trained deep convolutional architectures. More specifically, we learn a conditional denoising auto-encoder which imposes an implicit data-dependent prior/regularization on ground-truth in the first sub-minimization problem. This design follows an empirical Bayesian strategy, leading to so-called amortized inference. For matrix inversion in the second sub-problem, we learn a convolutional neural network to approximate the matrix inversion, i.e., the inverse mapping is learned by feeding the input through the learned forward network. Note that training this neural network does not require ground-truth or measurements, i.e., it is data-independent. Extensive experiments on both synthetic data and real datasets demonstrate the efficiency and accuracy of the proposed method compared with the conventional ADMM solution using inner loops for solving inverse problems.

##### Abstract (translated by Google)
我们提出了一种新的方法，使用深度学习技术来加速流行的交替方向乘法器（ADMM）解决方案的逆问题。 ADMM更新包括一个接近度算子，一个包含大矩阵求逆的最小二乘回归，以及一个更新双变量的显式解决方案。通常，由于先验和矩阵求逆的困难性，需要内环来解决前两个子最小化问题。为了避免这些缺点或限制，我们提出了一个具有两个预训练深度卷积体系结构的内环免费更新规则。更具体地说，我们学习了一个有条件的去噪自动编码器，它在第一个子最小化问题中将一个隐式的数据相关的先验/正则化加到地面真值上。这种设计遵循经验贝叶斯策略，导致所谓的摊销推论。对于第二个子问题中的矩阵求逆，我们学习一个卷积神经网络来近似矩阵求逆，即逆向映射是通过学习前向网络馈送输入来学习的。请注意，训练这个神经网络不需要地面实况或测量，即它是数据无关的。对合成数据和真实数据集进行的大量实验证明了与使用内部环路来解决反演问题的传统ADMM解决方案相比，所提出的方法的效率和准确度。

##### URL
[https://arxiv.org/abs/1709.01841](https://arxiv.org/abs/1709.01841)

##### PDF
[https://arxiv.org/pdf/1709.01841](https://arxiv.org/pdf/1709.01841)

