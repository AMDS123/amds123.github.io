---
layout: post
title: "Transformationally Identical and Invariant Convolutional Neural Networks through Symmetric Element Operators"
date: 2018-06-10 11:16:36
categories: arXiv_CV
tags: arXiv_CV CNN
author: ShihChung B. Lo, Matthew T. Freedman, Seong K. Mun, Shuo Gu
mathjax: true
---

* content
{:toc}

##### Abstract
Mathematically speaking, a transformationally invariant operator, such as a transformationally identical (TI) matrix kernel (i.e., K= T{K}), commutes with the transformation (T{.}) itself when they operate on the first operand matrix. We found that by consistently applying the same type of TI kernels in a convolutional neural networks (CNN) system, the commutative property holds throughout all layers of convolution processes with and without involving an activation function and/or a 1D convolution across channels within a layer. We further found that any CNN possessing the same TI kernel property for all convolution layers followed by a flatten layer with weight sharing among their transformation corresponding elements would output the same result for all transformation versions of the original input vector. In short, CNN[ Vi ] = CNN[ T{Vi} ] providing every K = T{K} in CNN, where Vi denotes input vector and CNN[.] represents the whole CNN process as a function of input vector that produces an output vector. With such a transformationally identical CNN (TI-CNN) system, each transformation, that is not associated with a predefined TI used in data augmentation, would inherently include all of its corresponding transformation versions of the input vector for the training. Hence the use of same TI property for every kernel in the CNN would serve as an orientation or a translation independent training guide in conjunction with the error-backpropagation during the training. This TI kernel property is desirable for applications requiring a highly consistent output result from corresponding transformation versions of an input. Several C programming routines are provided to facilitate interested parties of using the TI-CNN technique which is expected to produce a better generalization performance than its ordinary CNN counterpart.

##### Abstract (translated by Google)
从数学上讲，诸如变换相同（TI）矩阵内核（即，K = T {K}）的变换不变算子当它们在第一操作数矩阵上操作时与变换（T {。}）交换。我们发现，通过在卷积神经网络（CNN）系统中始终如一地应用相同类型的TI内核，交换属性在整个卷积过程中都可以保持，而且不涉及层间通道的激活函数和/或1D卷积。我们进一步发现，对于所有卷积层具有相同TI内核特性的CNN，然后在它们的变换相应元素之间具有权重共享的变平层，将对原始输入矢量的所有变换版本输出相同的结果。简而言之，CNN [Vi] = CNN [T {Vi}]在CNN中提供每个K = T {K}，其中Vi表示输入向量，CNN [。]表示整个CNN过程作为输入向量的函数，输出矢量。利用这种变换相同的CNN（TI-CNN）系统，与数据增强中使用的预定义TI无关的每个变换将固有地包括其用于训练的输入矢量的所有相应变换版本。因此，对于CNN中的每个内核，使用相同的TI属性将作为定向或独立于翻译的培训指南，与训练期间的错误反向传播一起使用。此TI内核属性对于需要来自输入的相应转换版本的高度一致的输出结果的应用程序而言是理想的。提供了几个C编程例程以便于感兴趣的各方使用TI-CNN技术，该技术有望产生比其普通CNN副本更好的泛化性能。

##### URL
[http://arxiv.org/abs/1806.03636](http://arxiv.org/abs/1806.03636)

##### PDF
[http://arxiv.org/pdf/1806.03636](http://arxiv.org/pdf/1806.03636)

