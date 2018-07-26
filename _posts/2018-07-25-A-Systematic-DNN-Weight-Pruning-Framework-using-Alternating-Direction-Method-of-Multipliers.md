---
layout: post
title: "A Systematic DNN Weight Pruning Framework using Alternating Direction Method of Multipliers"
date: 2018-07-25 16:52:02
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Gradient_Descent
author: Tianyun Zhang, Shaokai Ye, Kaiqi Zhang, Jian Tang, Wujie Wen, Makan Fardad, Yanzhi Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Weight pruning methods for deep neural networks (DNNs) have been investigated recently, but prior work in this area is mainly heuristic, iterative pruning, thereby lacking guarantees on the weight reduction ratio and convergence time. To mitigate these limitations, we present a systematic weight pruning framework of DNNs using the alternating direction method of multipliers (ADMM). We first formulate the weight pruning problem of DNNs as a nonconvex optimization problem with combinatorial constraints specifying the sparsity requirements, and then adopt the ADMM framework for systematic weight pruning. By using ADMM, the original nonconvex optimization problem is decomposed into two subproblems that are solved iteratively. One of these subproblems can be solved using stochastic gradient descent, the other can be solved analytically. Besides, our method achieves a fast convergence rate. 
 The weight pruning results are very promising and consistently outperform the prior work. On the LeNet-5 model for the MNIST data set, we achieve 71.2 times weight reduction without accuracy loss. On the AlexNet model for the ImageNet data set, we achieve 21 times weight reduction without accuracy loss. When we focus on the convolutional layer pruning for computation reductions, we can reduce the total computation by five times compared with the prior work (achieving a total of 13.4 times weight reduction in convolutional layers). Our models and codes are released at https://github.com/KaiqiZhang/admm-pruning

##### Abstract (translated by Google)
最近已经研究了深度神经网络（DNN）的重量修剪方法，但是该领域的先前工作主要是启发式，迭代修剪，因此缺乏对减重率和收敛时间的保证。为了减轻这些限制，我们使用交替方向乘法器（ADMM）提出了DNN的系统权重修剪框架。我们首先将DNN的权重修剪问题描述为非凸优化问题，其中组合约束指定了稀疏性要求，然后采用ADMM框架进行系统权重修剪。通过使用ADMM，原始的非凸优化问题被分解为迭代求解的两个子问题。其中一个子问题可以使用随机梯度下降来解决，另一个可以通过分析求解。此外，我们的方法实现了快速的收敛速度。
 重量修剪结果非常有前途，并且始终优于先前的工作。在用于MNIST数据集的LeNet-5模型中，我们实现了71.2倍的重量减轻而没有精度损失。在ImageNet数据集的AlexNet模型上，我们实现了21倍的重量减轻而没有精度损失。当我们专注于卷积层修剪以进行计算减少时，与先前的工作相比，我们可以将总计算量减少五倍（在卷积层中实现总重量减少13.4倍）。我们的模型和代码发布于https://github.com/KaiqiZhang/admm-pruning

##### URL
[http://arxiv.org/abs/1804.03294](http://arxiv.org/abs/1804.03294)

##### PDF
[http://arxiv.org/pdf/1804.03294](http://arxiv.org/pdf/1804.03294)

