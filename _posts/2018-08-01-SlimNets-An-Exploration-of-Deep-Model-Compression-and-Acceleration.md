---
layout: post
title: "SlimNets: An Exploration of Deep Model Compression and Acceleration"
date: 2018-08-01 18:28:12
categories: arXiv_AI
tags: arXiv_AI Knowledge
author: Ini Oguntola, Subby Olubeko, Christopher Sweeney
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks have achieved increasingly accurate results on a wide variety of complex tasks. However, much of this improvement is due to the growing use and availability of computational resources (e.g use of GPUs, more layers, more parameters, etc). Most state-of-the-art deep networks, despite performing well, over-parameterize approximate functions and take a significant amount of time to train. With increased focus on deploying deep neural networks on resource constrained devices like smart phones, there has been a push to evaluate why these models are so resource hungry and how they can be made more efficient. This work evaluates and compares three distinct methods for deep model compression and acceleration: weight pruning, low rank factorization, and knowledge distillation. Comparisons on VGG nets trained on CIFAR10 show that each of the models on their own are effective, but that the true power lies in combining them. We show that by combining pruning and knowledge distillation methods we can create a compressed network 85 times smaller than the original, all while retaining 96% of the original model's accuracy.

##### Abstract (translated by Google)
深度神经网络在各种复杂任务上取得了越来越准确的结果。然而，这种改进的大部分是由于计算资源的使用和可用性的增加（例如使用GPU，更多层，更多参数等）。尽管表现良好，大多数最先进的深度网络都会过度参数化近似函数并花费大量时间进行训练。随着人们越来越关注在智能手机等资源受限设备上部署深度神经网络，人们一直在努力评估为什么这些模型如此资源匮乏以及如何提高它们的效率。这项工作评估和比较深度模型压缩和加速的三种不同方法：重量修剪，低秩分解和知识蒸馏。在CIFAR10上训练的VGG网络的比较表明，每个模型本身都是有效的，但真正的力量在于它们的组合。我们表明，通过结合修剪和知识蒸馏方法，我们可以创建比原始尺寸小85倍的压缩网络，同时保留96％的原始模型精度。

##### URL
[http://arxiv.org/abs/1808.00496](http://arxiv.org/abs/1808.00496)

##### PDF
[http://arxiv.org/pdf/1808.00496](http://arxiv.org/pdf/1808.00496)

