---
layout: post
title: "FReLU: Flexible Rectified Linear Units for Improving Convolutional Neural Networks"
date: 2018-01-29 07:07:42
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification
author: Suo Qiu, Xiangmin Xu, Bolun Cai
mathjax: true
---

* content
{:toc}

##### Abstract
Rectified linear unit (ReLU) is a widely used activation function for deep convolutional neural networks. However, because of the zero-hard rectification, ReLU networks miss the benefits from negative values. In this paper, we propose a novel activation function called \emph{flexible rectified linear unit (FReLU)} to further explore the effects of negative values. By redesigning the rectified point of ReLU as a learnable parameter, FReLU expands the states of the activation output. When the network is successfully trained, FReLU tends to converge to a negative value, which improves the expressiveness and thus the performance. Furthermore, FReLU is designed to be simple and effective without exponential functions to maintain low cost computation. For being able to easily used in various network architectures, FReLU does not rely on strict assumptions by self-adaption. We evaluate FReLU on three standard image classification datasets, including CIFAR-10, CIFAR-100, and ImageNet. Experimental results show that the proposed method achieves fast convergence and higher performances on both plain and residual networks.

##### Abstract (translated by Google)
整流线性单元（ReLU）是深度卷积神经网络广泛使用的激活函数。但是，由于零难解决，反垄断网络错失了消极价值的好处。在本文中，我们提出了一种叫做\ emph {flexible rectified linear unit（FReLU）}的新型激活函数来进一步探讨负值的影响。通过将ReLU的整流点重新设计为可学习参数，FReLU扩展了激活输出的状态。当网络训练成功时，FReLU倾向于收敛到负值，从而提高了表现力，从而提高了表现。此外，FReLU被设计成简单而有效的，没有指数函数来维持低成本计算。为了能够方便地在各种网络架构中使用，FReLU不依赖于自适应的严格假设。我们在三个标准图像分类数据集（包括CIFAR-10，CIFAR-100和ImageNet）上评估FReLU。实验结果表明，所提出的方法在平坦网络和残余网络上都能实现快速收敛和更高的性能。

##### URL
[http://arxiv.org/abs/1706.08098](http://arxiv.org/abs/1706.08098)

##### PDF
[http://arxiv.org/pdf/1706.08098](http://arxiv.org/pdf/1706.08098)

