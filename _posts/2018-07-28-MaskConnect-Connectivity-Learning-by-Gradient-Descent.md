---
layout: post
title: "MaskConnect: Connectivity Learning by Gradient Descent"
date: 2018-07-28 00:41:53
categories: arXiv_CV
tags: arXiv_CV Image_Classification Classification Gradient_Descent
author: Karim Ahmed, Lorenzo Torresani
mathjax: true
---

* content
{:toc}

##### Abstract
Although deep networks have recently emerged as the model of choice for many computer vision problems, in order to yield good results they often require time-consuming architecture search. To combat the complexity of design choices, prior work has adopted the principle of modularized design which consists in defining the network in terms of a composition of topologically identical or similar building blocks (a.k.a. modules). This reduces architecture search to the problem of determining the number of modules to compose and how to connect such modules. Again, for reasons of design complexity and training cost, previous approaches have relied on simple rules of connectivity, e.g., connecting each module to only the immediately preceding module or perhaps to all of the previous ones. Such simple connectivity rules are unlikely to yield the optimal architecture for the given problem. 
 In this work we remove these predefined choices and propose an algorithm to learn the connections between modules in the network. Instead of being chosen a priori by the human designer, the connectivity is learned simultaneously with the weights of the network by optimizing the loss function of the end task using a modified version of gradient descent. We demonstrate our connectivity learning method on the problem of multi-class image classification using two popular architectures: ResNet and ResNeXt. Experiments on four different datasets show that connectivity learning using our approach yields consistently higher accuracy compared to relying on traditional predefined rules of connectivity. Furthermore, in certain settings it leads to significant savings in number of parameters.

##### Abstract (translated by Google)
尽管深度网络最近已成为许多计算机视觉问题的首选模型，但为了产生良好的结果，它们通常需要耗时的架构搜索。为了克服设计选择的复杂性，先前的工作采用了模块化设计的原理，其中包括根据拓扑相同或相似的构建块（a.k.a.模块）的组合来定义网络。这将架构搜索减少到确定要组成的模块数量以及如何连接这些模块的问题。同样，出于设计复杂性和培训成本的原因，先前的方法依赖于简单的连接规则，例如，将每个模块仅连接到紧接在前的模块或者可能连接到所有先前的模块。这种简单的连接规则不太可能产生给定问题的最优架构。
 在这项工作中，我们删除了这些预定义的选择，并提出了一种算法来学习网络中模块之间的连接。不是由人类设计者先验地选择，而是通过使用梯度下降的修改版本优化终端任务的损失函数来与网络的权重同时学习连通性。我们使用两种流行的体系结构（ResNet和ResNeXt）演示了关于多类图像分类问题的连通性学习方法。对四个不同数据集的实验表明，与依赖传统的预定义连接规则相比，使用我们的方法进行连通性学习可以获得始终如一的更高精度。此外，在某些设置中，它可以显着节省参数数量。

##### URL
[http://arxiv.org/abs/1807.11473](http://arxiv.org/abs/1807.11473)

##### PDF
[http://arxiv.org/pdf/1807.11473](http://arxiv.org/pdf/1807.11473)

