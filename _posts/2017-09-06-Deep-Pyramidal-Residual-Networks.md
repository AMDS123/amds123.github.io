---
layout: post
title: "Deep Pyramidal Residual Networks"
date: 2017-09-06 10:18:53
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification
author: Dongyoon Han, Jiwhan Kim, Junmo Kim
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural networks (DCNNs) have shown remarkable performance in image classification tasks in recent years. Generally, deep neural network architectures are stacks consisting of a large number of convolutional layers, and they perform downsampling along the spatial dimension via pooling to reduce memory usage. Concurrently, the feature map dimension (i.e., the number of channels) is sharply increased at downsampling locations, which is essential to ensure effective performance because it increases the diversity of high-level attributes. This also applies to residual networks and is very closely related to their performance. In this research, instead of sharply increasing the feature map dimension at units that perform downsampling, we gradually increase the feature map dimension at all units to involve as many locations as possible. This design, which is discussed in depth together with our new insights, has proven to be an effective means of improving generalization ability. Furthermore, we propose a novel residual unit capable of further improving the classification accuracy with our new network architecture. Experiments on benchmark CIFAR-10, CIFAR-100, and ImageNet datasets have shown that our network architecture has superior generalization ability compared to the original residual networks. Code is available at this https URL}

##### Abstract (translated by Google)
深卷积神经网络（DCNNs）在近年来的图像分类任务中表现出了显着的性能。通常，深度神经网络体系结构是由大量卷积层组成的堆栈，并且它们通过汇集执行沿着空间维度的下采样以减少存储器使用。同时，下采样位置处的特征映射维度（即信道数目）急剧增加，这对于确保有效性能是必不可少的，因为它增加了高级属性的多样性。这也适用于残余网络，并且与其性能密切相关。在这项研究中，我们逐渐增加所有单元的特征映射维度，以尽可能多地包含特征映射维度，而不是急剧增加特征映射维度。这个设计，与我们的新见解一起深入讨论，已被证明是提高泛化能力的有效手段。此外，我们提出了一种新的残留单元，能够进一步提高我们新的网络架构的分类精度。在基准CIFAR-10，CIFAR-100和ImageNet数据集上的实验表明，我们的网络体系结构比原有的剩余网络具有更好的泛化能力。代码可在此https URL获得}

##### URL
[https://arxiv.org/abs/1610.02915](https://arxiv.org/abs/1610.02915)

##### PDF
[https://arxiv.org/pdf/1610.02915](https://arxiv.org/pdf/1610.02915)

