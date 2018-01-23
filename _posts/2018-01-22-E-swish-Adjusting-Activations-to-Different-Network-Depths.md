---
layout: post
title: "E-swish: Adjusting Activations to Different Network Depths"
date: 2018-01-22 15:40:29
categories: arXiv_CV
tags: arXiv_CV
author: Eric Alcaide
mathjax: true
---

* content
{:toc}

##### Abstract
Activation functions have a notorious impact on neural networks on both training and testing the models against the desired problem. Currently, the most used activation function is the Rectified Linear Unit (ReLU). This paper introduces a new and novel activation function, closely related with the new activation $Swish = x * sigmoid(x)$ (Ramachandran et al., 2017) which generalizes it. We call the new activation $E-swish = \beta x * sigmoid(x)$. We show that E-swish outperforms many other well-known activations including both ReLU and Swish. For example, using E-swish provided 1.5% and 4.6% accuracy improvements on Cifar10 and Cifar100 respectively for the WRN 10-2 when compared to ReLU and 0.35% and 0.6% respectively when compared to Swish. The code to reproduce all our experiments can be found at this https URL

##### Abstract (translated by Google)
激活功能在神经网络上对训练和测试模型反对期望的问题具有臭名昭着的影响。目前，最常用的激活功能是整流线性单元（ReLU）。本文介绍了一种新的激活函数，与新推出的激活函数$ Swish = x * sigmoid（x）$（Ramachandran et al。，2017）相关。我们称新的激活$ E-swish = \ beta x * sigmoid（x）$。我们发现E-swish比其他许多着名的激活方式（包括ReLU和Swish）都要优秀。例如，相对于ReLU，使用E-swish分别为Cifar10和Cifar100分别提供了1.5％和4.6％的准确性提高，与ReWU相比分别提高了0.35％和0.6％。重现所有实验的代码可以在https网址找到

##### URL
[https://arxiv.org/abs/1801.07145](https://arxiv.org/abs/1801.07145)

##### PDF
[https://arxiv.org/pdf/1801.07145](https://arxiv.org/pdf/1801.07145)

