---
layout: post
title: "From Hashing to CNNs: Training BinaryWeight Networks via Hashing"
date: 2018-02-08 07:51:41
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Inference
author: Qinghao Hu, Peisong Wang, Jian Cheng
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural networks (CNNs) have shown appealing performance on various computer vision tasks in recent years. This motivates people to deploy CNNs to realworld applications. However, most of state-of-art CNNs require large memory and computational resources, which hinders the deployment on mobile devices. Recent studies show that low-bit weight representation can reduce much storage and memory demand, and also can achieve efficient network inference. To achieve this goal, we propose a novel approach named BWNH to train Binary Weight Networks via Hashing. In this paper, we first reveal the strong connection between inner-product preserving hashing and binary weight networks, and show that training binary weight networks can be intrinsically regarded as a hashing problem. Based on this perspective, we propose an alternating optimization method to learn the hash codes instead of directly learning binary weights. Extensive experiments on CIFAR10, CIFAR100 and ImageNet demonstrate that our proposed BWNH outperforms current state-of-art by a large margin.

##### Abstract (translated by Google)
深卷积神经网络（CNNs）近年来在各种计算机视觉任务中表现出了令人满意的性能。这激励人们将CNN部署到现实世界的应用程序。但是，大多数先进的CNN需要大量的内存和计算资源，这阻碍了在移动设备上的部署。最近的研究表明，低位权重表示可以减少大量的存储和内存需求，也可以实现高效的网络推理。为实现这一目标，我们提出了一种新的方法，称为BWNH，通过哈希训练二进制权重网络。在本文中，我们首先揭示了内积保持哈希与二进制权重网络之间的紧密联系，并且表明训练二进制权重网络本质上可以看作是一个哈希问题。基于这个观点，我们提出了一种交替优化方法来学习哈希码，而不是直接学习二进制权重。在CIFAR10，CIFAR100和ImageNet上进行的大量实验表明，我们提出的BWNH比目前的技术水平高出很多。

##### URL
[http://arxiv.org/abs/1802.02733](http://arxiv.org/abs/1802.02733)

##### PDF
[http://arxiv.org/pdf/1802.02733](http://arxiv.org/pdf/1802.02733)

