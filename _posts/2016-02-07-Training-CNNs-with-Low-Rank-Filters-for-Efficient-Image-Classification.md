---
layout: post
title: "Training CNNs with Low-Rank Filters for Efficient Image Classification"
date: 2016-02-07 21:23:19
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification
author: Yani Ioannou, Duncan Robertson, Jamie Shotton, Roberto Cipolla, Antonio Criminisi
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new method for creating computationally efficient convolutional neural networks (CNNs) by using low-rank representations of convolutional filters. Rather than approximating filters in previously-trained networks with more efficient versions, we learn a set of small basis filters from scratch; during training, the network learns to combine these basis filters into more complex filters that are discriminative for image classification. To train such networks, a novel weight initialization scheme is used. This allows effective initialization of connection weights in convolutional layers composed of groups of differently-shaped filters. We validate our approach by applying it to several existing CNN architectures and training these networks from scratch using the CIFAR, ILSVRC and MIT Places datasets. Our results show similar or higher accuracy than conventional CNNs with much less compute. Applying our method to an improved version of VGG-11 network using global max-pooling, we achieve comparable validation accuracy using 41% less compute and only 24% of the original VGG-11 model parameters; another variant of our method gives a 1 percentage point increase in accuracy over our improved VGG-11 model, giving a top-5 center-crop validation accuracy of 89.7% while reducing computation by 16% relative to the original VGG-11 model. Applying our method to the GoogLeNet architecture for ILSVRC, we achieved comparable accuracy with 26% less compute and 41% fewer model parameters. Applying our method to a near state-of-the-art network for CIFAR, we achieved comparable accuracy with 46% less compute and 55% fewer parameters.

##### Abstract (translated by Google)
我们提出了一种利用卷积滤波器的低秩表示来创建计算效率高的卷积神经网络（CNN）的新方法。我们不是用先前训练过的网络中更高效的版本来近似滤波器，而是从零开始学习一组小的基本滤波器;在训练期间，网络学习将这些基础滤波器组合成对图像分类具有区别性的更复杂的滤波器。为了训练这样的网络，使用新颖的权重初始化方案。这允许有效地初始化由不同形状的滤波器组成的卷积层中的连接权重。我们验证我们的方法，将其应用于多个现有的CNN架构，并使用CIFAR，ILSVRC和MIT Places数据集从头开始对这些网络进行培训。我们的结果显示与传统的CNN相似或更高的精确度，计算量更少。将我们的方法应用到使用全局最大池的VGG-11网络的改进版本中，我们实现了可比较的验证准确性，计算量仅为原来的41％，而原始VGG-11模型参数只有24％;我们的方法的另一个变体比我们改进的VGG-11模型提高了1个百分点的精度，相对于原来的VGG-11模型，前5个中心作物的验证准确率为89.7％，同时减少了16％的计算量。将我们的方法应用于ILSVRC的GoogLeNet架构，我们实现了相当的准确性，计算量减少了26％，模型参数减少了41％。将我们的方法应用于CIFAR的近乎最先进的网络，我们实现了相当的准确性，计算量减少了46％，参数减少了55％。

##### URL
[https://arxiv.org/abs/1511.06744](https://arxiv.org/abs/1511.06744)

##### PDF
[https://arxiv.org/pdf/1511.06744](https://arxiv.org/pdf/1511.06744)

