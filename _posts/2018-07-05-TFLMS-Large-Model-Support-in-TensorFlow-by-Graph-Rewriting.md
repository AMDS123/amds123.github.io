---
layout: post
title: "TFLMS: Large Model Support in TensorFlow by Graph Rewriting"
date: 2018-07-05 14:56:39
categories: arXiv_AI
tags: arXiv_AI Segmentation
author: Tung D. Le, Haruki Imai, Yasushi Negishi, Kiyokuni Kawachiya
mathjax: true
---

* content
{:toc}

##### Abstract
While accelerators such as GPUs have limited memory, deep neural networks are becoming larger and will not fit with the memory limitation of accelerators for training. We propose an approach to tackle this problem by rewriting the computational graph of a neural network, in which swap-out and swap-in operations are inserted to temporarily store intermediate results on CPU memory. In particular, we first revise the concept of a computational graph by defining a concrete semantics for variables in a graph. We then formally show how to derive swap-out and swap-in operations from an existing graph and present rules to optimize the graph. To realize our approach, we developed a module in TensorFlow, named TFLMS. TFLMS is published as a pull request in the TensorFlow repository for contributing to the TensorFlow community. With TFLMS, we were able to train ResNet-50 and 3DUnet with 4.7x and 2x larger batch size, respectively. In particular, we were able to train 3DUNet using images of size of $192^3$ for image segmentation, which, without TFLMS, had been done only by dividing the images to smaller images, which affects the accuracy.

##### Abstract (translated by Google)
虽然诸如GPU之类的加速器具有有限的存储器，但是深度神经网络变得越来越大并且不适合用于训练的加速器的存储器限制。我们提出了一种通过重写神经网络的计算图来解决这个问题的方法，其中插入了换出和交换操作以将中间结果临时存储在CPU存储器上。特别是，我们首先通过为图中的变量定义具体语义来修改计算图的概念。然后，我们正式展示如何从现有图形中导出换出和交换操作，并提供规则来优化图形。为了实现我们的方法，我们在TensorFlow中开发了一个名为TFLMS的模块。 TFLMS在TensorFlow存储库中作为拉取请求发布，用于为TensorFlow社区做出贡献。通过TFLMS，我们能够分别以4.7倍和2倍的批量大小训练ResNet-50和3DUnet。特别是，我们能够使用尺寸为$ 192 ^ 3 $的图像训练3DUNet进行图像分割，没有TFLMS，只能通过将图像分割成较小的图像来完成，这会影响精度。

##### URL
[http://arxiv.org/abs/1807.02037](http://arxiv.org/abs/1807.02037)

##### PDF
[http://arxiv.org/pdf/1807.02037](http://arxiv.org/pdf/1807.02037)

