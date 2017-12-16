---
layout: post
title: "The Shallow End: Empowering Shallower Deep-Convolutional Networks through Auxiliary Outputs"
date: 2017-04-23 12:01:57
categories: arXiv_CV
tags: arXiv_CV CNN
author: Yong Guo, Mingkui Tan, Qingyao Wu, Jian Chen, Anton Van Den Hengel, Qinfeng Shi
mathjax: true
---

* content
{:toc}

##### Abstract
The depth is one of the key factors behind the great success of convolutional neural networks (CNNs), with the gradient vanishing issue having been largely addressed by various nets, e.g. ResNet. However, when the depth goes very deep, the supervision information from the loss function will vanish due to the long backpropagation path, especially for those shallow layers. This means that intermediate layers receive less supervision information and will lead to redundancy in models. As a result, the model becomes very redundant and the over-fitting issue may happen. To address this, we propose a model, called AuxNet, by introducing auxiliary outputs at intermediate layers. Different from existing approaches, we propose a Multi-path training method to propagate not only gradients but also sufficient supervision informationfrommultipleauxiliaryoutputs. TheproposedAuxNetwithmulti-pathtrainingmethodgivesrisetomorecompact networks which outperform their very deep equivalent (i.e. ResNet). For example, AuxNet with 44 layers performs better than the ResNet equivalent with 110 layers on several benchmark data sets, i.e. CIFAR-10, CIFAR-100 and SVHN.

##### Abstract (translated by Google)
深度是卷积神经网络（CNNs）巨大成功背后的关键因素之一，其中梯度消失问题已经在很大程度上被各种网络所解决。 RESNET。但当深度很深时，由于反向传播路径长，损失函数的监督信息就会消失，特别是那些浅层。这意味着中间层接收较少的监督信息，并会导致模型冗余。结果，模型变得非常冗余，可能会发生过度的问题。为了解决这个问题，我们通过在中间层引入辅助输出来提出一个名为AuxNet的模型。与现有的方法不同，我们提出了一种多路径训练方法，不仅可以传播梯度，而且可以传输多种辅助输出的监控信息。所提出的具有多路径训练方法的复杂网络比同等深度的网络（ResNet）要好。例如，在几个基准数据集（即CIFAR-10，CIFAR-100和SVHN）上，具有44层的AuxNet性能比具有110层的ResNet性能要好。

##### URL
[https://arxiv.org/abs/1611.01773](https://arxiv.org/abs/1611.01773)

##### PDF
[https://arxiv.org/pdf/1611.01773](https://arxiv.org/pdf/1611.01773)

