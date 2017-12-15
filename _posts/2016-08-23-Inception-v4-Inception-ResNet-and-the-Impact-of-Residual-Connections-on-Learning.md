---
layout: post
title: "Inception-v4, Inception-ResNet and the Impact of Residual Connections on Learning"
date: 2016-08-23 16:42:29
categories: arXiv_CV
tags: arXiv_CV CNN Classification Recognition
author: Christian Szegedy, Sergey Ioffe, Vincent Vanhoucke, Alex Alemi
mathjax: true
---

* content
{:toc}

##### Abstract
Very deep convolutional networks have been central to the largest advances in image recognition performance in recent years. One example is the Inception architecture that has been shown to achieve very good performance at relatively low computational cost. Recently, the introduction of residual connections in conjunction with a more traditional architecture has yielded state-of-the-art performance in the 2015 ILSVRC challenge; its performance was similar to the latest generation Inception-v3 network. This raises the question of whether there are any benefit in combining the Inception architecture with residual connections. Here we give clear empirical evidence that training with residual connections accelerates the training of Inception networks significantly. There is also some evidence of residual Inception networks outperforming similarly expensive Inception networks without residual connections by a thin margin. We also present several new streamlined architectures for both residual and non-residual Inception networks. These variations improve the single-frame recognition performance on the ILSVRC 2012 classification task significantly. We further demonstrate how proper activation scaling stabilizes the training of very wide residual Inception networks. With an ensemble of three residual and one Inception-v4, we achieve 3.08 percent top-5 error on the test set of the ImageNet classification (CLS) challenge

##### Abstract (translated by Google)
近年来，非常深的卷积网络已经成为图像识别性能方面最大进步的核心。一个例子是已经显示在相对较低的计算成本下实现非常好的性能的初始架构。最近，在更加传统的体系结构中引入剩余连接在2015 ILSVRC挑战中取得了最先进的性能。其性能类似于最新一代的Inception-v3网络。这提出了将初始结构与剩余连接结合起来是否有任何好处的问题。在这里，我们给出明确的经验证据表明，残留连接训练显着加速了初始网络的训练。还有一些证据表明，残留的先启网络性能优于同样昂贵的先启网络，而且不存在剩余连接。我们还为残留和非残留先入先出网络提出了几个新的简化架构。这些变体显着提高了ILSVRC 2012分类任务的单帧识别性能。我们进一步证明适当的激活规模如何稳定非常广泛的残留先验网络的训练。通过三个剩余和一个Inception-v4的集合，我们在ImageNet分类（CLS）挑战的测试集上实现了3.08％的前5个错误

##### URL
[https://arxiv.org/abs/1602.07261](https://arxiv.org/abs/1602.07261)

##### PDF
[https://arxiv.org/pdf/1602.07261](https://arxiv.org/pdf/1602.07261)

