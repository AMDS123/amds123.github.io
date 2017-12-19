---
layout: post
title: "Understanding learned CNN features through Filter Decoding with Substitution"
date: 2015-11-17 10:15:48
categories: arXiv_CV
tags: arXiv_CV Image_Caption CNN
author: Ivet Rafegas, Maria Vanrell
mathjax: true
---

* content
{:toc}

##### Abstract
In parallel with the success of CNNs to solve vision problems, there is a growing interest in developing methodologies to understand and visualize the internal representations of these networks. How the responses of a trained CNN encode the visual information is a fundamental question both for computer and human vision research. Image representations provided by the first convolutional layer as well as the resolution change provided by the max-polling operation are easy to understand, however, as soon as a second and further convolutional layers are added in the representation, any intuition is lost. A usual way to deal with this problem has been to define deconvolutional networks that somehow allow to explore the internal representations of the most important activations towards the image space, where deconvolution is assumed as a convolution with the transposed filter. However, this assumption is not the best approximation of an inverse convolution. In this paper we propose a new assumption based on filter substitution to reverse the encoding of a convolutional layer. This provides us with a new tool to directly visualize any CNN single neuron as a filter in the first layer, this is in terms of the image space.

##### Abstract (translated by Google)
与CNN解决视觉问题的成功并行，人们越来越有兴趣开发方法来理解和可视化这些网络的内部表示。一个训练有素的CNN如何对视觉信息进行编码是计算机和人类视觉研究的一个基本问题。由第一卷积层提供的图像表示以及由最大轮询操作提供的分辨率变化是容易理解的，然而，一旦在表示中添加了第二和更多卷积层，任何直觉都丧失了。处理这个问题的通常方法是定义去卷积网络，以某种方式允许探索对于图像空间的最重要激活的内部表示，其中去卷积被假定为与移调滤波器的卷积。但是，这个假设不是逆卷积的最佳近似。在本文中，我们提出了一种基于滤波器替代的新假设来反转卷积层的编码。这为我们提供了一个新的工具，可以将任何CNN单神经元直接可视化为第一层中的滤波器，这就是图像空间。

##### URL
[https://arxiv.org/abs/1511.05084](https://arxiv.org/abs/1511.05084)

##### PDF
[https://arxiv.org/pdf/1511.05084](https://arxiv.org/pdf/1511.05084)

