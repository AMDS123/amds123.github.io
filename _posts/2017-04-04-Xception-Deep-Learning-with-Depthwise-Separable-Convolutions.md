---
layout: post
title: "Xception: Deep Learning with Depthwise Separable Convolutions"
date: 2017-04-04 18:40:27
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification Deep_Learning
author: François Chollet
mathjax: true
---

* content
{:toc}

##### Abstract
We present an interpretation of Inception modules in convolutional neural networks as being an intermediate step in-between regular convolution and the depthwise separable convolution operation (a depthwise convolution followed by a pointwise convolution). In this light, a depthwise separable convolution can be understood as an Inception module with a maximally large number of towers. This observation leads us to propose a novel deep convolutional neural network architecture inspired by Inception, where Inception modules have been replaced with depthwise separable convolutions. We show that this architecture, dubbed Xception, slightly outperforms Inception V3 on the ImageNet dataset (which Inception V3 was designed for), and significantly outperforms Inception V3 on a larger image classification dataset comprising 350 million images and 17,000 classes. Since the Xception architecture has the same number of parameters as Inception V3, the performance gains are not due to increased capacity but rather to a more efficient use of model parameters.

##### Abstract (translated by Google)
我们将卷积神经网络中的初始模块的解释作为介于常规卷积和深度可分卷积运算（深度卷积之后是逐点卷积）之间的中间步骤。就此而言，深度可分离的卷积可以被理解为具有最大数量的塔的先启模块。这一观察导致我们提出了一种新颖的深度卷积神经网络架构，其中Inception模块已经被深度可分卷积代替。我们发现这个名为Xception的体系结构在ImageNet数据集（Inception V3的设计目的）上稍微胜过了Inception V3，在包含3.5亿个图像和17,000个类的更大的图像分类数据集上，它的性能明显优于Inception V3。由于Xception架构具有与Inception V3相同的参数数量，因此性能增益不是由于容量增加，而是由于更高效地使用模型参数。

##### URL
[https://arxiv.org/abs/1610.02357](https://arxiv.org/abs/1610.02357)

##### PDF
[https://arxiv.org/pdf/1610.02357](https://arxiv.org/pdf/1610.02357)

