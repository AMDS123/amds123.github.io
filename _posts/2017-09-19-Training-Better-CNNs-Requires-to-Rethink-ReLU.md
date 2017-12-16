---
layout: post
title: "Training Better CNNs Requires to Rethink ReLU"
date: 2017-09-19 04:27:56
categories: arXiv_CV
tags: arXiv_CV CNN
author: Gangming Zhao, Zhaoxiang Zhang, Jingdong Wang, He Guan
mathjax: true
---

* content
{:toc}

##### Abstract
With the rapid development of Deep Convolutional Neural Networks (DCNNs), numerous works focus on designing better network architectures (i.e., AlexNet, VGG, Inception, ResNet and DenseNet etc.). Nevertheless, all these networks have the same characteristic: each convolutional layer is followed by an activation layer, a Rectified Linear Unit (ReLU) layer is the most used among them. In this work, we argue that the paired module with 1:1 convolution and ReLU ratio is not the best choice since it may result in poor generalization ability. Thus, we try to investigate the more suitable convolution and ReLU ratio for exploring the better network architectures. Specifically, inspired by Leaky ReLU, we focus on adopting the proportional module with N:M (N$>$M) convolution and ReLU ratio to design the better networks. From the perspective of ensemble learning, Leaky ReLU can be considered as an ensemble of networks with different convolution and ReLU ratio. We find that the proportional module with N:M (N$>$M) convolution and ReLU ratio can help networks acquire the better performance, through the analysis of a simple Leaky ReLU model. By utilizing the proportional module with N:M (N$>$M) convolution and ReLU ratio, many popular networks can form more rich representations in models, since the N:M (N$>$M) proportional module can utilize information more effectively. Furthermore, we apply this module in diverse DCNN models to explore whether is the N:M (N$>$M) convolution and ReLU ratio indeed more effective. From our experimental results, we can find that such a simple yet effective method achieves better performance in different benchmarks with various network architectures and the experimental results verify that the superiority of the proportional module.

##### Abstract (translated by Google)
随着深度卷积神经网络（DCNNs）的快速发展，许多着作集中在设计更好的网络架构（即AlexNet，VGG，Inception，ResNet和DenseNet等）上。尽管如此，所有这些网络都具有相同的特性：每个卷积层后面都有一个激活层，其中最常用的是整流线性单元（ReLU）层。在这项工作中，我们认为，1：1卷积和ReLU比率的配对模块并不是最好的选择，因为它可能导致较差的泛化能力。因此，我们试图研究更合适的卷积和ReLU比率来探索更好的网络架构。具体来说，在Leaky ReLU的启发下，我们着重于采用N：M（N $> $ M）卷积和ReLU比例的比例模块来设计更好的网络。从集成学习的角度来看，Leaky ReLU可以看作是一个具有不同卷积和ReLU比率的网络集合。我们发现，通过分析一个简单的Leaky ReLU模型，N（M $ N $> $ M）卷积和ReLU比例的比例模块可以帮助网络获得更好的性能。通过利用N：M（N $> $ M）卷积和ReLU比例的比例模块，许多流行网络可以在模型中形成更丰富的表示，因为N：M（N $> $ M）比例模块可以更多地利用信息有效。此外，我们将这个模块应用于不同的DCNN模型，以探索N：M（N $> $ M）卷积和ReLU比率是否确实更有效。从我们的实验结果可以看出，这种简单而有效的方法在各种网络结构的不同基准下都取得了较好的性能，实验结果验证了比例模块的优越性。

##### URL
[https://arxiv.org/abs/1709.06247](https://arxiv.org/abs/1709.06247)

##### PDF
[https://arxiv.org/pdf/1709.06247](https://arxiv.org/pdf/1709.06247)

