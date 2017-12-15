---
layout: post
title: "Input Switched Affine Networks: An RNN Architecture Designed for Interpretability"
date: 2017-06-12 20:29:48
categories: arXiv_CL
tags: arXiv_CL RNN Prediction
author: Jakob N. Foerster, Justin Gilmer, Jan Chorowski, Jascha Sohl-Dickstein, David Sussillo
mathjax: true
---

* content
{:toc}

##### Abstract
There exist many problem domains where the interpretability of neural network models is essential for deployment. Here we introduce a recurrent architecture composed of input-switched affine transformations - in other words an RNN without any explicit nonlinearities, but with input-dependent recurrent weights. This simple form allows the RNN to be analyzed via straightforward linear methods: we can exactly characterize the linear contribution of each input to the model predictions; we can use a change-of-basis to disentangle input, output, and computational hidden unit subspaces; we can fully reverse-engineer the architecture's solution to a simple task. Despite this ease of interpretation, the input switched affine network achieves reasonable performance on a text modeling tasks, and allows greater computational efficiency than networks with standard nonlinearities.

##### Abstract (translated by Google)
神经网络模型的可解释性对于部署是必不可少的。在这里我们介绍一个由输入切换仿射变换构成的循环体系结构 - 换句话说，RNN没有任何显式非线性，但是与输入相关的递归权重。这种简单的形式允许RNN通过直接的线性方法进行分析：我们可以准确地表征每个输入对模型预测的线性贡献;我们可以使用基础变化来分解输入，输出和计算隐藏单元子空间;我们可以将体系结构的解决方案完全反向工程，以完成简单的任务。尽管易于解释，但输入切换仿射网络在文本建模任务上实现了合理的性能，并且比具有标准非线性的网络具有更高的计算效率。

##### URL
[https://arxiv.org/abs/1611.09434](https://arxiv.org/abs/1611.09434)

##### PDF
[https://arxiv.org/pdf/1611.09434](https://arxiv.org/pdf/1611.09434)

