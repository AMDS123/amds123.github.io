---
layout: post
title: "CondenseNet: An Efficient DenseNet using Learned Group Convolutions"
date: 2017-11-25 09:34:12
categories: arXiv_CV
tags: arXiv_CV CNN
author: Gao Huang, Shichen Liu, Laurens van der Maaten, Kilian Q. Weinberger
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks are increasingly used on mobile devices, where computational resources are limited. In this paper we develop CondenseNet, a novel network architecture with unprecedented efficiency. It combines dense connectivity between layers with a mechanism to remove unused connections. The dense connectivity facilitates feature re-use in the network, whereas learned group convolutions remove connections between layers for which this feature re-use is superfluous. At test time, our model can be implemented using standard grouped convolutions - allowing for efficient computation in practice. Our experiments demonstrate that CondenseNets are much more efficient than stateof-the-art compact convolutional networks such as MobileNets and ShuffleNets.

##### Abstract (translated by Google)
深度神经网络越来越多地用在计算资源有限的移动设备上。在本文中，我们开发了CondenseNet，这是一种前所未有的高效网络架构。它结合了层之间的密集连接，并使用一种机制去除未使用的连接。密集的连通性有利于网络中的特征重用，而学习到的组卷积消除了该特征重用的层之间的连接是多余的。在测试时间，我们的模型可以使用标准的分组卷积来实现 - 在实践中允许有效的计算。我们的实验证明，CondenseNets比MobileNets和ShuffleNets等先进的紧凑卷积网络高效得多。

##### URL
[https://arxiv.org/abs/1711.09224](https://arxiv.org/abs/1711.09224)

##### PDF
[https://arxiv.org/pdf/1711.09224](https://arxiv.org/pdf/1711.09224)

