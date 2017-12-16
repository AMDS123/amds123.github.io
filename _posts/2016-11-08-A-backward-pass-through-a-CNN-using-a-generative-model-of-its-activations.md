---
layout: post
title: "A backward pass through a CNN using a generative model of its activations"
date: 2016-11-08 23:18:50
categories: arXiv_CV
tags: arXiv_CV CNN Inference
author: Huayan Wang, Anna Chen, Yi Liu, Dileep George, D. Scott Phoenix
mathjax: true
---

* content
{:toc}

##### Abstract
Neural networks have shown to be a practical way of building a very complex mapping between a pre-specified input space and output space. For example, a convolutional neural network (CNN) mapping an image into one of a thousand object labels is approaching human performance in this particular task. However the mapping (neural network) does not automatically lend itself to other forms of queries, for example, to detect/reconstruct object instances, to enforce top-down signal on ambiguous inputs, or to recover object instances from occlusion. One way to address these queries is a backward pass through the network that fuses top-down and bottom-up information. In this paper, we show a way of building such a backward pass by defining a generative model of the neural network's activations. Approximate inference of the model would naturally take the form of a backward pass through the CNN layers, and it addresses the aforementioned queries in a unified framework.

##### Abstract (translated by Google)
已经证明神经网络是在预先指定的输入空间和输出空间之间建立非常复杂的映射的实际方法。例如，卷积神经网络（CNN）将图像映射到千个对象标签中的一个，正在接近这个特定任务中的人类表现。然而，映射（神经网络）不会自动适用于其他形式的查询，例如，检测/重建对象实例，在模糊输入上执行自顶向下信号，或从遮挡恢复对象实例。解决这些查询的一种方法是通过网络的反向传递来融合自顶向下和自下而上的信息。在本文中，我们通过定义一个神经网络激活的生成模型来展示一种建立这种反向传递的方法。模型的近似推理自然会采用CNN层的反向传递的形式，并且在一个统一的框架中解决上述查询。

##### URL
[https://arxiv.org/abs/1611.02767](https://arxiv.org/abs/1611.02767)

##### PDF
[https://arxiv.org/pdf/1611.02767](https://arxiv.org/pdf/1611.02767)

