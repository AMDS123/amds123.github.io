---
layout: post
title: "Generalizing the Convolution Operator in Convolutional Neural Networks"
date: 2017-07-14 10:16:25
categories: arXiv_CV
tags: arXiv_CV CNN
author: Kamaledin Ghiasi-Shirazi
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks have become a main tool for solving many machine vision and machine learning problems. A major element of these networks is the convolution operator which essentially computes the inner product between a weight vector and the vectorized image patches extracted by sliding a window in the image planes of the previous layer. In this paper, we propose two classes of surrogate functions for the inner product operation inherent in the convolution operator and so attain two generalizations of the convolution operator. The first one is the class of positive definite kernel functions where their application is justified by the kernel trick. The second one is the class of similarity measures defined based on a distance function. We justify this by tracing back to the basic idea behind the neocognitron which is the ancestor of CNNs. Both methods are then further generalized by allowing a monotonically increasing function to be applied subsequently. Like any trainable parameter in a neural network, the template pattern and the parameters of the kernel/distance function are trained with the back-propagation algorithm. As an aside, we use the proposed framework to justify the use of sine activation function in CNNs. Our experiments on the MNIST dataset show that the performance of ordinary CNNs can be achieved by generalized CNNs based on weighted L1/L2 distances, proving the applicability of the proposed generalization of the convolutional neural networks.

##### Abstract (translated by Google)
卷积神经网络已成为解决许多机器视觉和机器学习问题的主要工具。这些网络的主要元素是卷积算子，其本质上是计算权重向量与通过在前一层的图像平面中滑动窗口而提取的矢量化图像块之间的内积。在本文中，我们提出了两类卷积算子中内积运算的替代函数，从而得到了卷积算子的两个推广。第一个是内核技巧证明它们的应用是正确的内核函数的类。第二个是基于距离函数定义的一类相似性度量。我们通过追溯到CNN的祖先neocognitron背后的基本思想来证明这一点。然后通过允许随后应用单调增加的函数来进一步推广这两种方法。像神经网络中的任何可训练参数一样，模板模式和核/距离函数的参数都是用反向传播算法训练的。另外，我们使用提出的框架来证明在CNN中使用正弦激活函数是正确的。我们在MNIST数据集上的实验表明，通过基于加权的L1 / L2距离的广义CNNs可以实现普通CNN的性能，证明了所提出的卷积神经网络泛化的适用性。

##### URL
[https://arxiv.org/abs/1707.09864](https://arxiv.org/abs/1707.09864)

##### PDF
[https://arxiv.org/pdf/1707.09864](https://arxiv.org/pdf/1707.09864)

