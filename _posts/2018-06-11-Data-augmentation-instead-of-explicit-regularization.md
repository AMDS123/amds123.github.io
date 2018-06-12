---
layout: post
title: "Data augmentation instead of explicit regularization"
date: 2018-06-11 08:10:18
categories: arXiv_CV
tags: arXiv_CV Regularization CNN Gradient_Descent
author: Alex Hern&#xe1;ndez-Garc&#xed;a, Peter K&#xf6;nig
mathjax: true
---

* content
{:toc}

##### Abstract
Modern deep artificial neural networks have achieved impressive results through models with very large capacity---compared to the number of training examples---that control overfitting with the help of different forms of regularization. Regularization can be implicit, as is the case of stochastic gradient descent and parameter sharing in convolutional layers, or explicit. Most common explicit regularization techniques, such as weight decay and dropout, reduce the effective capacity of the model and typically require the use of deeper and wider architectures to compensate for the reduced capacity. Although these techniques have been proven successful in terms of improved generalization, they seem to waste capacity. In contrast, data augmentation techniques do not reduce the effective capacity and improve generalization by increasing the number of training examples. In this paper we systematically analyze the effect of data augmentation on some popular architectures and conclude that data augmentation alone---without any other explicit regularization techniques---can achieve the same performance or higher as regularized models, especially when training with fewer examples, and exhibits much higher adaptability to changes in the architecture.

##### Abstract (translated by Google)
现代深层人工神经网络通过大容量模型取得了令人瞩目的成果 - 与训练样例的数量相比，这些样例通过不同形式的正则化来控制过度拟合。正则化可以是隐式的，就像卷积层中的随机梯度下降和参数共享一样，或者是明确的。最常见的显式正则化技术（如重量衰减和丢失）会降低模型的有效容量，并且通常需要使用更深更宽的体系结构来补偿容量减小。虽然这些技术在改进泛化方面已被证明是成功的，但它们似乎浪费了容量。相比之下，数据增强技术不会通过增加培训示例的数量来降低有效容量并改进泛化。在本文中，我们系统地分析了数据增强对一些流行体系结构的影响，并得出结论：单独数据增强 - 没有任何其他显式正则化技术 - 可以达到与正则化模型相同的性能或更高，尤其是在使用较少示例进行训练时，并且对架构变化具有更高的适应性。

##### URL
[http://arxiv.org/abs/1806.03852](http://arxiv.org/abs/1806.03852)

##### PDF
[http://arxiv.org/pdf/1806.03852](http://arxiv.org/pdf/1806.03852)

