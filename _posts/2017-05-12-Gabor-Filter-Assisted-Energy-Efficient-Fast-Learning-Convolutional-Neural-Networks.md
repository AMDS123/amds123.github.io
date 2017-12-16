---
layout: post
title: "Gabor Filter Assisted Energy Efficient Fast Learning Convolutional Neural Networks"
date: 2017-05-12 20:50:51
categories: arXiv_CV
tags: arXiv_CV Face CNN Classification Detection Face_Detection Recognition
author: Syed Shakib Sarwar, Priyadarshini Panda, Kaushik Roy
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks (CNN) are being increasingly used in computer vision for a wide range of classification and recognition problems. However, training these large networks demands high computational time and energy requirements; hence, their energy-efficient implementation is of great interest. In this work, we reduce the training complexity of CNNs by replacing certain weight kernels of a CNN with Gabor filters. The convolutional layers use the Gabor filters as fixed weight kernels, which extracts intrinsic features, with regular trainable weight kernels. This combination creates a balanced system that gives better training performance in terms of energy and time, compared to the standalone CNN (without any Gabor kernels), in exchange for tolerable accuracy degradation. We show that the accuracy degradation can be mitigated by partially training the Gabor kernels, for a small fraction of the total training cycles. We evaluated the proposed approach on 4 benchmark applications. Simple tasks like face detection and character recognition (MNIST and TiCH), were implemented using LeNet architecture. While a more complex task of object recognition (CIFAR10) was implemented on a state of the art deep CNN (Network in Network) architecture. The proposed approach yields 1.31-1.53x improvement in training energy in comparison to conventional CNN implementation. We also obtain improvement up to 1.4x in training time, up to 2.23x in storage requirements, and up to 2.2x in memory access energy. The accuracy degradation suffered by the approximate implementations is within 0-3% of the baseline.

##### Abstract (translated by Google)
卷积神经网络（CNN）正被越来越多地用于计算机视觉领域，用于广泛的分类和识别问题。但是，培训这些大型网络需要高计算时间和能量需求;因此，他们的节能实施是非常有意义的。在这项工作中，我们通过用Gabor滤波器替换CNN的某些权重核来降低CNN的训练复杂度。卷积层使用Gabor滤波器作为固定权重的内核，提取固有特征，并使用常规的可训练权重核。与单独的CNN（没有任何Gabor核）相比，这种组合创建了一个平衡的系统，在能量和时间方面提供了更好的训练性能，以换取可接受的精度下降。我们表明，精度的退化可以通过部分训练Gabor核心来缓解，这是整个训练周期的一小部分。我们评估了4个基准应用程序的建议方法。诸如人脸检测和字符识别（MNIST和TiCH）之类的简单任务使用LeNet架构来实现。在CNN（Network in Network，网络网络）体系结构中实施更复杂的目标识别任务（CIFAR10）。与传统的CNN实施相比，所提出的方法在训练能量上产生1.31-1.53​​倍的提高。在培训时间方面我们也获得了1.4倍的提升，存储需求达到2.23倍，存储器访问能量达到2.2倍。近似实现所遭受的精度下降在基线的0-3％范围内。

##### URL
[https://arxiv.org/abs/1705.04748](https://arxiv.org/abs/1705.04748)

##### PDF
[https://arxiv.org/pdf/1705.04748](https://arxiv.org/pdf/1705.04748)

