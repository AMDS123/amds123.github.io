---
layout: post
title: "On the Importance of Normalisation Layers in Deep Learning with Piecewise Linear Activation Units"
date: 2015-11-01 06:44:10
categories: arXiv_CV
tags: arXiv_CV Regularization Classification Deep_Learning
author: Zhibin Liao, Gustavo Carneiro
mathjax: true
---

* content
{:toc}

##### Abstract
Deep feedforward neural networks with piecewise linear activations are currently producing the state-of-the-art results in several public datasets. The combination of deep learning models and piecewise linear activation functions allows for the estimation of exponentially complex functions with the use of a large number of subnetworks specialized in the classification of similar input examples. During the training process, these subnetworks avoid overfitting with an implicit regularization scheme based on the fact that they must share their parameters with other subnetworks. Using this framework, we have made an empirical observation that can improve even more the performance of such models. We notice that these models assume a balanced initial distribution of data points with respect to the domain of the piecewise linear activation function. If that assumption is violated, then the piecewise linear activation units can degenerate into purely linear activation units, which can result in a significant reduction of their capacity to learn complex functions. Furthermore, as the number of model layers increases, this unbalanced initial distribution makes the model ill-conditioned. Therefore, we propose the introduction of batch normalisation units into deep feedforward neural networks with piecewise linear activations, which drives a more balanced use of these activation units, where each region of the activation function is trained with a relatively large proportion of training samples. Also, this batch normalisation promotes the pre-conditioning of very deep learning models. We show that by introducing maxout and batch normalisation units to the network in network model results in a model that produces classification results that are better than or comparable to the current state of the art in CIFAR-10, CIFAR-100, MNIST, and SVHN datasets.

##### Abstract (translated by Google)
具有分段线性激活的深度前馈神经网络目前正在几个公共数据集中产生最新的结果。深度学习模型和分段线性激活函数的结合允许使用专门用于类似输入例子分类的大量子网络来估计指数复杂函数。在训练过程中，这些子网络避免过度拟合一个隐式正则化方案，因为它们必须与其他子网络共享参数。使用这个框架，我们做了一个经验观察，可以提高这些模型的性能。我们注意到，这些模型假设数据点相对于分段线性激活函数的区域是平衡的初始分布。如果这种假设被违背，那么分段线性激活单元可退化为纯线性激活单元，这会导致其学习复杂功能的能力显着降低。此外，随着模型层数的增加，这种不平衡的初始分布使模型处于病态。因此，我们建议将批量归一化单元引入具有分段线性激活的深度前馈神经网络，从而驱动这些激活单元的更均衡的使用，其中激活函数的每个区域都用相对大比例的训练样本进行训练。此外，这批批准正常化促进了非常深入的学习模式的预处理。我们表明，通过在网络模型结果中引入maxout和批量标准化单元，产生的分类结果优于或相当于CIFAR-10，CIFAR-100，MNIST和SVHN数据集。

##### URL
[https://arxiv.org/abs/1508.00330](https://arxiv.org/abs/1508.00330)

##### PDF
[https://arxiv.org/pdf/1508.00330](https://arxiv.org/pdf/1508.00330)

