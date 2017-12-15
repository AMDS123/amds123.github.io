---
layout: post
title: "Compression of Deep Neural Networks on the Fly"
date: 2016-03-18 09:33:01
categories: arXiv_CV
tags: arXiv_CV Regularization Recognition
author: Guillaume Soulié, Vincent Gripon, Maëlys Robert
mathjax: true
---

* content
{:toc}

##### Abstract
Thanks to their state-of-the-art performance, deep neural networks are increasingly used for object recognition. To achieve these results, they use millions of parameters to be trained. However, when targeting embedded applications the size of these models becomes problematic. As a consequence, their usage on smartphones or other resource limited devices is prohibited. In this paper we introduce a novel compression method for deep neural networks that is performed during the learning phase. It consists in adding an extra regularization term to the cost function of fully-connected layers. We combine this method with Product Quantization (PQ) of the trained weights for higher savings in storage consumption. We evaluate our method on two data sets (MNIST and CIFAR10), on which we achieve significantly larger compression rates than state-of-the-art methods.

##### Abstract (translated by Google)
由于其最先进的性能，深度神经网络越来越多地用于物体识别。为了达到这些结果，他们使用数百万个参数进行训练。但是，在定位嵌入式应用程序时，这些模型的大小会变得有问题。因此，禁止在智能手机或其他资源有限的设备上使用。在本文中，我们介绍一种新的在学习阶段执行的深度神经网络压缩方法。它包括为完全连接层的成本函数增加额外的正则化项。我们将这种方法与经过训练的权重的产品量化（PQ）相结合，以节省更多的存储消耗。我们在两个数据集（MNIST和CIFAR10）上评估我们的方法，在这两个数据集上我们实现了比最先进的方法显着更大的压缩率。

##### URL
[https://arxiv.org/abs/1509.08745](https://arxiv.org/abs/1509.08745)

##### PDF
[https://arxiv.org/pdf/1509.08745](https://arxiv.org/pdf/1509.08745)

