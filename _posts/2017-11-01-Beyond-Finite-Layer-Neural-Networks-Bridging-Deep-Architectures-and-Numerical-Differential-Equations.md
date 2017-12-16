---
layout: post
title: "Beyond Finite Layer Neural Networks: Bridging Deep Architectures and Numerical Differential Equations"
date: 2017-11-01 09:19:19
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Yiping Lu, Aoxiao Zhong, Quanzheng Li, Bin Dong
mathjax: true
---

* content
{:toc}

##### Abstract
In our work, we bridge deep neural network design with numerical differential equations. We show that many effective networks, such as ResNet, PolyNet, FractalNet and RevNet, can be interpreted as different numerical discretizations of differential equations. This finding brings us a brand new perspective on the design of effective deep architectures. We can take advantage of the rich knowledge in numerical analysis to guide us in designing new and potentially more effective deep networks. As an example, we propose a linear multi-step architecture (LM-architecture) which is inspired by the linear multi-step method solving ordinary differential equations. The LM-architecture is an effective structure that can be used on any ResNet-like networks. In particular, we demonstrate that LM-ResNet and LM-ResNeXt (i.e. the networks obtained by applying the LM-architecture on ResNet and ResNeXt respectively) can achieve noticeably higher accuracy than ResNet and ResNeXt on both CIFAR and ImageNet with comparable numbers of trainable parameters. In particular, on both CIFAR and ImageNet, LM-ResNet/LM-ResNeXt can significantly compress ($>50$\%) the original networks while maintaining a similar performance. This can be explained mathematically using the concept of modified equation from numerical analysis. Last but not least, we also establish a connection between stochastic control and noise injection in the training process which helps to improve generalization of the networks. Furthermore, by relating stochastic training strategy with stochastic dynamic system, we can easily apply stochastic training to the networks with the LM-architecture. As an example, we introduced stochastic depth to LM-ResNet and achieve significant improvement over the original LM-ResNet on CIFAR10.

##### Abstract (translated by Google)
在我们的工作中，我们将深度神经网络设计与数值微分方程相桥接。我们证明许多有效的网络，如ResNet，PolyNet，FractalNet和RevNet可以解释为微分方程的不同数值离散。这个发现给我们带来了有效深层架构设计的全新视角。我们可以利用丰富的数值分析知识来指导我们设计新的，更有效的深层网络。作为一个例子，我们提出了一个线性多步骤架构（LM-架构），它受到求解常微分方程的线性多步法的启发。 LM架构是一个有效的结构，可以在任何类似ResNet的网络上使用。特别是，我们证明LM-ResNet和LM-ResNeXt（即通过在ResNet和ResNeXt上分别应用LM架构获得的网络）可以实现比ResNet和ResNeXt在CIFAR和ImageNet上明显更高的精度，具有相当数量的可训练参数。尤其是在CIFAR和ImageNet上，LM-ResNet / LM-ResNeXt可以大幅压缩（$> 50 $ \％）原始网络，同时保持相似的性能。这可以用数值分析的修正方程的概念在数学上解释。最后但同样重要的是，我们还在训练过程中建立了随机控制和噪声注入之间的联系，有助于提高网络的泛化能力。此外，通过将随机训练策略与随机动态系统相关联，可以容易地将随机训练应用于具有LM架构的网络。例如，我们将随机深度引入LM-ResNet，并在CIFAR10上实现了比原来的LM-ResNet更大的改进。

##### URL
[https://arxiv.org/abs/1710.10121](https://arxiv.org/abs/1710.10121)

##### PDF
[https://arxiv.org/pdf/1710.10121](https://arxiv.org/pdf/1710.10121)

