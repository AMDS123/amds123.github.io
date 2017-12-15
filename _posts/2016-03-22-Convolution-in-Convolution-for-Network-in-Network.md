---
layout: post
title: "Convolution in Convolution for Network in Network"
date: 2016-03-22 12:33:11
categories: arXiv_CV
tags: arXiv_CV Sparse CNN Recognition
author: Yanwei Pang, Manli Sun, Xiaoheng Jiang, Xuelong Li
mathjax: true
---

* content
{:toc}

##### Abstract
Network in Netwrok (NiN) is an effective instance and an important extension of Convolutional Neural Network (CNN) consisting of alternating convolutional layers and pooling layers. Instead of using a linear filter for convolution, NiN utilizes shallow MultiLayer Perceptron (MLP), a nonlinear function, to replace the linear filter. Because of the powerfulness of MLP and $ 1\times 1 $ convolutions in spatial domain, NiN has stronger ability of feature representation and hence results in better recognition rate. However, MLP itself consists of fully connected layers which give rise to a large number of parameters. In this paper, we propose to replace dense shallow MLP with sparse shallow MLP. One or more layers of the sparse shallow MLP are sparely connected in the channel dimension or channel-spatial domain. The proposed method is implemented by applying unshared convolution across the channel dimension and applying shared convolution across the spatial dimension in some computational layers. The proposed method is called CiC. Experimental results on the CIFAR10 dataset, augmented CIFAR10 dataset, and CIFAR100 dataset demonstrate the effectiveness of the proposed CiC method.

##### Abstract (translated by Google)
网络中的网络（NiN）是由交替卷积层和汇聚层组成的卷积神经网络（CNN）的有效实例和重要扩展。 NiN不使用线性滤波器进行卷积，而是利用非线性函数浅层多层感知器（MultiPayer Perceptron，MLP）来代替线性滤波器。由于MLP和$ 1 \ times 1 $卷积在空间域的强大性，NiN具有更强的特征表示能力，因此识别率更高。然而，MLP本身由完全连接的层组成，这产生了大量的参数。在本文中，我们建议用稀疏浅MLP代替密集的浅层MLP。稀疏浅MLP的一个或多个层在信道维度或信道空间域中是空间连接的。所提出的方法通过在信道维度上应用非共享卷积并且在一些计算层中在空间维度上应用共享卷积来实现。所提出的方法被称为CiC。在CIFAR10数据集，增强的CIFAR10数据集和CIFAR100数据集上的实验结果证明了所提出的CiC方法的有效性。

##### URL
[https://arxiv.org/abs/1603.06759](https://arxiv.org/abs/1603.06759)

##### PDF
[https://arxiv.org/pdf/1603.06759](https://arxiv.org/pdf/1603.06759)

