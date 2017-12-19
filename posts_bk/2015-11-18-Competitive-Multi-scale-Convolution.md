---
layout: post
title: "Competitive Multi-scale Convolution"
date: 2015-11-18 01:19:00
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Zhibin Liao, Gustavo Carneiro
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we introduce a new deep convolutional neural network (ConvNet) module that promotes competition among a set of multi-scale convolutional filters. This new module is inspired by the inception module, where we replace the original collaborative pooling stage (consisting of a concatenation of the multi-scale filter outputs) by a competitive pooling represented by a maxout activation unit. This extension has the following two objectives: 1) the selection of the maximum response among the multi-scale filters prevents filter co-adaptation and allows the formation of multiple sub-networks within the same model, which has been shown to facilitate the training of complex learning problems; and 2) the maxout unit reduces the dimensionality of the outputs from the multi-scale filters. We show that the use of our proposed module in typical deep ConvNets produces classification results that are either better than or comparable to the state of the art on the following benchmark datasets: MNIST, CIFAR-10, CIFAR-100 and SVHN.

##### Abstract (translated by Google)
在本文中，我们介绍一种新的深度卷积神经网络（ConvNet）模块，它可以促进一组多尺度卷积滤波器之间的竞争。这个新的模块受启发模块的启发，在这个模块中，我们用由maxout激活单元表示的竞争池代替原始的协作池阶段（由多级过滤器输出串联组成）。该扩展具有以下两个目标：1）在多尺度滤波器中选择最大响应防止了滤波器的协同适应，并且允许在同一模型内形成多个子网络，已经显示出，这有助于训练复杂的学习问题; 2）最大单位降低了多尺度滤波器输出的维数。我们表明，在典型的深度网络中使用我们提出的模块，可以产生分类结果，这些分类结果要比以下的基准数据集MNIST，CIFAR-10，CIFAR-100和SVHN的技术水平好或可比。

##### URL
[https://arxiv.org/abs/1511.05635](https://arxiv.org/abs/1511.05635)

##### PDF
[https://arxiv.org/pdf/1511.05635](https://arxiv.org/pdf/1511.05635)

