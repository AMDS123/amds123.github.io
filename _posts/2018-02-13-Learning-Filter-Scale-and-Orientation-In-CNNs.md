---
layout: post
title: "Learning Filter Scale and Orientation In CNNs"
date: 2018-02-13 19:45:21
categories: arXiv_CV
tags: arXiv_CV CNN
author: Ilker Cam, F. Boray Tek
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks have many hyperparameters such as the filter size, number of filters, and pooling size, which require manual tuning. Though deep stacked structures are able to create multi-scale and hierarchical representations, manually fixed filter sizes limit the scale of representations that can be learned in a single convolutional layer. 
 This paper introduces a new adaptive filter model that allows variable scale and orientation. The scale and orientation parameters of filters can be learned using back propagation. Therefore, in a single convolution layer, we can create filters of different scale and orientation that can adapt to small or large features and objects. The proposed model uses a relatively large base size (grid) for filters. In the grid, a differentiable function acts as an envelope for the filters. The envelope function guides effective filter scale and shape/orientation by masking the filter weights before the convolution. Therefore, only the weights in the envelope are updated during training. 
 In this work, we employed a multivariate (2D) Gaussian as the envelope function and showed that it can grow, shrink, or rotate by updating its covariance matrix during back propagation training . We tested the new filter model on MNIST, MNIST-cluttered, and CIFAR-10 and compared the results with the networks that used conventional convolution layers. The results demonstrate that the new model can effectively learn and produce filters of different scales and orientations in a single layer. Moreover, the experiments show that the adaptive convolution layers perform equally; or better, especially when data includes objects of varying scale and noisy backgrounds.

##### Abstract (translated by Google)
卷积神经网络有许多超参数，如过滤器大小，过滤器数量和池大小，这些都需要手动调整。尽管深层堆叠结构能够创建多尺度和分层表示，但手动固定的过滤器大小限制了可以在单个卷积层中学习的表示的范围。
 本文介绍了一种新的自适应滤波器模型，它允许可变比例和方向。可以使用反向传播来学习滤波器的比例和方向参数。因此，在单个卷积图层中，我们可以创建不同比例和方向的滤镜，以适应小或大的特征和对象。所提出的模型对于滤波器使用相对较大的基本尺寸（网格）。在网格中，可微函数充当过滤器的包络。通过在卷积之前遮盖滤光片重量，包络功能可指导有效的滤光片比例和形状/方向。因此，训练期间只更新信封中的权重。
 在这项工作中，我们采用多元（2D）高斯函数作为包络函数，并且表明它可以通过在反向传播训练期间更新其协方差矩阵来增长，缩小或旋转。我们在MNIST，MNIST-cluttered和CIFAR-10上测试了新的滤波器模型，并将结果与​​使用常规卷积层的网络进行了比较。结果表明，新模型可以有效地学习和生产单层不同尺度和方向的滤波器。而且，实验表明自适应卷积层性能相同;或更好，特别是当数据包含具有不同比例和嘈杂背景的物体时。

##### URL
[http://arxiv.org/abs/1803.00388](http://arxiv.org/abs/1803.00388)

##### PDF
[http://arxiv.org/pdf/1803.00388](http://arxiv.org/pdf/1803.00388)

