---
layout: post
title: "CrescendoNet: A Simple Deep Convolutional Neural Network with Ensemble Behavior"
date: 2017-10-30 18:35:01
categories: arXiv_CV
tags: arXiv_CV CNN
author: Xiang Zhang, Nishant Vishwamitra, Hongxin Hu, Feng Luo
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a new deep convolutional neural network, CrescendoNet, by stacking simple building blocks without residual connections. Each Crescendo block contains independent convolution paths with increased depths. The numbers of convolution layers and parameters are only increased linearly in Crescendo blocks. In experiments, CrescendoNet with only 15 layers outperforms almost all networks without residual connections on benchmark datasets, CIFAR10, CIFAR100, and SVHN. Given sufficient amount of data as in SVHN dataset, CrescendoNet with 15 layers and 4.1M parameters can match the performance of DenseNet-BC with 250 layers and 15.3M parameters. CrescendoNet provides a new way to construct high performance deep convolutional neural networks without residual connections. Moreover, through investigating the behavior and performance of subnetworks in CrescendoNet, we note that the high performance of CrescendoNet may come from its implicit ensemble behavior, which differs from the FractalNet that is also a deep convolutional neural network without residual connections. Furthermore, the independence between paths in CrescendoNet allows us to introduce a new path-wise training procedure, which can reduce the memory needed for training.

##### Abstract (translated by Google)
我们引入了一个新的深度卷积神经网络CrescendoNet，它通过堆叠简单的积木而没有剩余连接。每个Crescendo块包含增加深度的独立卷积路径。卷积层和参数的数量仅在Crescendo块中线性增加。在实验中，只有15层的CrescendoNet在基准数据集CIFAR10，CIFAR100和SVHN上几乎胜过几乎所有没有剩余连接的网络。如SVHN数据集中所提供的数据量充足，具有15层和4.1M参数的CrescendoNet可以与DenseNet-BC的性能相匹配，具有250层和15.3M的参数。 CrescendoNet提供了一种构建高性能深度卷积神经网络的新方法，不存在剩余连接。此外，通过研究CrescendoNet中子网络的行为和性能，我们注意到CrescendoNet的高性能可能来自其隐式集合行为，它不同于也是没有剩余连接的深度卷积神经网络的分形网络。此外，CrescendoNet中的路径之间的独立性使我们能够引入一个新的路径训练过程，这可以减少训练所需的内存。

##### URL
[https://arxiv.org/abs/1710.11176](https://arxiv.org/abs/1710.11176)

##### PDF
[https://arxiv.org/pdf/1710.11176](https://arxiv.org/pdf/1710.11176)

