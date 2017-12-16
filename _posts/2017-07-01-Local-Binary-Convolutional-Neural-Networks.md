---
layout: post
title: "Local Binary Convolutional Neural Networks"
date: 2017-07-01 17:02:44
categories: arXiv_CV
tags: arXiv_CV Sparse CNN
author: Felix Juefei-Xu, Vishnu Naresh Boddeti, Marios Savvides
mathjax: true
---

* content
{:toc}

##### Abstract
We propose local binary convolution (LBC), an efficient alternative to convolutional layers in standard convolutional neural networks (CNN). The design principles of LBC are motivated by local binary patterns (LBP). The LBC layer comprises of a set of fixed sparse pre-defined binary convolutional filters that are not updated during the training process, a non-linear activation function and a set of learnable linear weights. The linear weights combine the activated filter responses to approximate the corresponding activated filter responses of a standard convolutional layer. The LBC layer affords significant parameter savings, 9x to 169x in the number of learnable parameters compared to a standard convolutional layer. Furthermore, the sparse and binary nature of the weights also results in up to 9x to 169x savings in model size compared to a standard convolutional layer. We demonstrate both theoretically and experimentally that our local binary convolution layer is a good approximation of a standard convolutional layer. Empirically, CNNs with LBC layers, called local binary convolutional neural networks (LBCNN), achieves performance parity with regular CNNs on a range of visual datasets (MNIST, SVHN, CIFAR-10, and ImageNet) while enjoying significant computational savings.

##### Abstract (translated by Google)
我们提出了局部二进制卷积（LBC），它是标准卷积神经网络（CNN）中卷积层的有效替代。 LBC的设计原则是由局部二元模式（LBP）驱动的。 LBC层包括一组固定的稀疏预定义的二进制卷积滤波器，它们在训练过程中不被更新，非线性激活函数和一组可学习的线性权重。线性权重组合激活的滤波器响应以近似于标准卷积层的相应激活的滤波器响应。与标准卷积层相比，LBC层提供了显着的参数节省，可学习参数的数量是9x至169x。此外，与标准卷积层相比，权重的稀疏性和二元性也使得模型尺寸节省高达9倍至169倍。我们从理论上和实验上证明了我们的局部二进制卷积层是一个标准卷积层的很好的近似。经验上，具有LBC层的CNN称为局部二进制卷积神经网络（LBCNN），在一系列视觉数据集（MNIST，SVHN，CIFAR-10和ImageNet）上实现与常规CNN的性能平衡，同时节省显着的计算量。

##### URL
[https://arxiv.org/abs/1608.06049](https://arxiv.org/abs/1608.06049)

##### PDF
[https://arxiv.org/pdf/1608.06049](https://arxiv.org/pdf/1608.06049)

