---
layout: post
title: "Representational Distance Learning for Deep Neural Networks"
date: 2016-11-07 18:37:05
categories: arXiv_CV
tags: arXiv_CV Transfer_Learning Classification Gradient_Descent
author: Patrick McClure, Nikolaus Kriegeskorte
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks (DNNs) provide useful models of visual representational transformations. We present a method that enables a DNN (student) to learn from the internal representational spaces of a reference model (teacher), which could be another DNN or, in the future, a biological brain. Representational spaces of the student and the teacher are characterized by representational distance matrices (RDMs). We propose representational distance learning (RDL), a stochastic gradient descent method that drives the RDMs of the student to approximate the RDMs of the teacher. We demonstrate that RDL is competitive with other transfer learning techniques for two publicly available benchmark computer vision datasets (MNIST and CIFAR-100), while allowing for architectural differences between student and teacher. By pulling the student's RDMs towards those of the teacher, RDL significantly improved visual classification performance when compared to baseline networks that did not use transfer learning. In the future, RDL may enable combined supervised training of deep neural networks using task constraints (e.g. images and category labels) and constraints from brain-activity measurements, so as to build models that replicate the internal representational spaces of biological brains.

##### Abstract (translated by Google)
深度神经网络（DNN）提供了有用的视觉表示变换模型。我们提出一种方法，使DNN（学生）能够从一个参考模型（教师）的内部表征空间学习，这个模型可能是另一个DNN，或者将来是一个生物脑。学生和教师的表征空间由表征距离矩阵（RDMs）表征。我们提出代表性远程学习（RDL），这是一种随机梯度下降法，它驱动学生的RDM来逼近教师的RDM。我们证明RDL与其他两种公开提供的基准计算机视觉数据集（MNIST和CIFAR-100）的转换学习技术相比具有竞争性，同时允许学生和教师之间的体系结构差异。通过将学生的RDM拉向教师的RDM，与不使用转移学习的基线网络相比，RDL显着提高了视觉分类性能。将来，RDL可以使用任务约束（例如图像和类别标签）和来自大脑活动测量的约束来实现深度神经网络的组合监督训练，从而构建复制生物脑内部表征空间的模型。

##### URL
[https://arxiv.org/abs/1511.03979](https://arxiv.org/abs/1511.03979)

##### PDF
[https://arxiv.org/pdf/1511.03979](https://arxiv.org/pdf/1511.03979)

