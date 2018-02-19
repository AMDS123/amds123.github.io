---
layout: post
title: "Mixed Precision Training"
date: 2018-02-15 20:04:02
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN CNN RNN Deep_Learning
author: Paulius Micikevicius, Sharan Narang, Jonah Alben, Gregory Diamos, Erich Elsen, David Garcia, Boris Ginsburg, Michael Houston, Oleksii Kuchaiev, Ganesh Venkatesh, Hao Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks have enabled progress in a wide variety of applications. Growing the size of the neural network typically results in improved accuracy. As model sizes grow, the memory and compute requirements for training these models also increases. We introduce a technique to train deep neural networks using half precision floating point numbers. In our technique, weights, activations and gradients are stored in IEEE half-precision format. Half-precision floating numbers have limited numerical range compared to single-precision numbers. We propose two techniques to handle this loss of information. Firstly, we recommend maintaining a single-precision copy of the weights that accumulates the gradients after each optimizer step. This single-precision copy is rounded to half-precision format during training. Secondly, we propose scaling the loss appropriately to handle the loss of information with half-precision gradients. We demonstrate that this approach works for a wide variety of models including convolution neural networks, recurrent neural networks and generative adversarial networks. This technique works for large scale models with more than 100 million parameters trained on large datasets. Using this approach, we can reduce the memory consumption of deep learning models by nearly 2x. In future processors, we can also expect a significant computation speedup using half-precision hardware units.

##### Abstract (translated by Google)
深度神经网络已经在各种应用中取得了进展。增加神经网络的大小通常会提高准确度。随着模型规模的增长，培训这些模型的内存和计算需求也随之增加。我们介绍一种使用半精度浮点数训练深度神经网络的技术。在我们的技术中，权重，激活和梯度以IEEE半精度格式存储。与单精度数字相比，半精度浮点数字的数值范围有限。我们提出两种技术来处理这种信息丢失。首先，我们建议在每个优化器步骤之后保留一个累加梯度的权重的单精度副本。这种单精度副本在训练期间四舍五入为半精度格式。其次，我们提出适当的比例损失来处理半精度梯度信息的损失。我们证明这种方法适用于各种各样的模型，包括卷积神经网络，递归神经网络和生成敌对网络。该技术适用于在大型数据集上训练超过1亿个参数的大型模型。使用这种方法，我们可以将深度学习模型的内存消耗减少近2倍。在未来的处理器中，我们还可以期望使用半精度硬件单元进行显着的计算加速。

##### URL
[http://arxiv.org/abs/1710.03740](http://arxiv.org/abs/1710.03740)

##### PDF
[http://arxiv.org/pdf/1710.03740](http://arxiv.org/pdf/1710.03740)

