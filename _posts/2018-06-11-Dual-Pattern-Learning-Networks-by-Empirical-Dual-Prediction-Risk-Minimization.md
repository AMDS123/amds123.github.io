---
layout: post
title: "Dual Pattern Learning Networks by Empirical Dual Prediction Risk Minimization"
date: 2018-06-11 11:00:58
categories: arXiv_CV
tags: arXiv_CV Regularization Image_Classification Classification Prediction
author: Haimin Zhang, Min Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Motivated by the observation that humans can learn patterns from two given images at one time, we propose a dual pattern learning network architecture in this paper. Unlike conventional networks, the proposed architecture has two input branches and two loss functions. Instead of minimizing the empirical risk of a given dataset, dual pattern learning networks is trained by minimizing the empirical dual prediction loss. We show that this can improve the performance for single image classification. This architecture forces the network to learn discriminative class-specific features by analyzing and comparing two input images. In addition, the dual input structure allows the network to have a considerably large number of image pairs, which can help address the overfitting issue due to limited training data. Moreover, we propose to associate each input branch with a random interest value for learning corresponding image during training. This method can be seen as a stochastic regularization technique, and can further lead to generalization performance improvement. State-of-the-art deep networks can be adapted to dual pattern learning networks without increasing the same number of parameters. Extensive experiments on CIFAR-10, CIFAR- 100, FI-8, Google commands dataset, and MNIST demonstrate that our DPLNets exhibit better performance than original networks. The experimental results on subsets of CIFAR- 10, CIFAR-100, and MNIST demonstrate that dual pattern learning networks have good generalization performance on small datasets.

##### Abstract (translated by Google)
受到人们可以同时从两幅给定图像中学习模式的观察的启发，我们在本文中提出了一种双模式学习网络体系结构。与传统网络不同，所提出的架构具有两个输入分支和两个丢失功能。不是最小化给定数据集的经验风险，而是通过最小化经验双重预测损失来训练双模式学习网络。我们证明这可以提高单个图像分类的性能。这种架构迫使网络通过分析和比较两个输入图像来学习歧视性的特定类别特征。另外，双输入结构允许网络具有相当多的图像对，这可以帮助解决由于有限的训练数据而导致的过度配合问题。此外，我们建议将每个输入分支与一个随机兴趣值相关联，以便在训练期间学习相应的图像。这种方法可以看作是随机正则化技术，可以进一步提高泛化性能。最先进的深度网络可以适应双模式学习网络，而不会增加相同数量的参数。在CIFAR-10，CIFAR-100，FI-8，Google命令数据集和MNIST上的大量实验表明，我们的DPLNets比原始网络表现出更好的性能。 CIFAR-10，CIFAR-100和MNIST子集的实验结果表明，双模式学习网络在小数据集上具有良好的泛化性能。

##### URL
[http://arxiv.org/abs/1806.03902](http://arxiv.org/abs/1806.03902)

##### PDF
[http://arxiv.org/pdf/1806.03902](http://arxiv.org/pdf/1806.03902)

