---
layout: post
title: "All You Need is Beyond a Good Init: Exploring Better Solution for Training Extremely Deep Convolutional Neural Networks with Orthonormality and Modulation"
date: 2017-04-10 02:12:29
categories: arXiv_CV
tags: arXiv_CV CNN Optimization
author: Di Xie, Jiang Xiong, Shiliang Pu
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural network is difficult to train and this predicament becomes worse as the depth increases. The essence of this problem exists in the magnitude of backpropagated errors that will result in gradient vanishing or exploding phenomenon. We show that a variant of regularizer which utilizes orthonormality among different filter banks can alleviate this problem. Moreover, we design a backward error modulation mechanism based on the quasi-isometry assumption between two consecutive parametric layers. Equipped with these two ingredients, we propose several novel optimization solutions that can be utilized for training a specific-structured (repetitively triple modules of Conv-BNReLU) extremely deep convolutional neural network (CNN) WITHOUT any shortcuts/ identity mappings from scratch. Experiments show that our proposed solutions can achieve distinct improvements for a 44-layer and a 110-layer plain networks on both the CIFAR-10 and ImageNet datasets. Moreover, we can successfully train plain CNNs to match the performance of the residual counterparts. Besides, we propose new principles for designing network structure from the insights evoked by orthonormality. Combined with residual structure, we achieve comparative performance on the ImageNet dataset.

##### Abstract (translated by Google)
深度神经网络很难训练，随着深度的增加，这种困境会变得更糟。这个问题的实质存在于反向传播误差的大小，这将导致梯度消失或爆炸现象。我们表明，正规化使用不同的滤波器银行之间正规化的变种可以缓解这个问题。此外，我们设计了一个基于两个连续参数层之间的准等距假设的后向误差调制机制。配备这两个成分，我们提出了几个新的优化解决方案，可用于训练特定结构（Conv-BNReLU的重复三重模块）极深卷积神经网络（CNN），无需从头开始任何快捷方式/身份映射。实验表明，我们提出的解决方案可以在CIFAR-10和ImageNet数据集上实现44层和110层平原网络的明显改进。此外，我们可以成功培训平原CNN，以配合残余对手的表现。另外，我们从正交性引发的观点提出了网络结构设计的新原则。结合剩余结构，我们在ImageNet数据集上实现了比较性能。

##### URL
[https://arxiv.org/abs/1703.01827](https://arxiv.org/abs/1703.01827)

##### PDF
[https://arxiv.org/pdf/1703.01827](https://arxiv.org/pdf/1703.01827)

