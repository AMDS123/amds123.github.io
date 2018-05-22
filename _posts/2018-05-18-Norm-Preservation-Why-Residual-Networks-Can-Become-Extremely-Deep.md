---
layout: post
title: "Norm-Preservation: Why Residual Networks Can Become Extremely Deep?"
date: 2018-05-18 23:37:17
categories: arXiv_CV
tags: arXiv_CV OCR Optimization
author: Alireza Zaeemzadeh, Nazanin Rahnavard, Mubarak Shah
mathjax: true
---

* content
{:toc}

##### Abstract
Augmenting deep neural networks with skip connections, as introduced in the so called ResNet architecture, surprised the community by enabling the training of networks of more than 1000 layers with significant performance gains. It has been shown that identity skip connections eliminate singularities and improve the optimization landscape of the network. This paper deciphers ResNet by analyzing the of effect of skip connections in the backward path and sets forth new theoretical results on the advantages of identity skip connections in deep neural networks. We prove that the skip connections in the residual blocks facilitate preserving the norm of the gradient and lead to well-behaved and stable back-propagation, which is a desirable feature from optimization perspective. We also show that, perhaps surprisingly, as more residual blocks are stacked, the network becomes more norm-preserving. Traditionally, norm-preservation is enforced on the network only at beginning of the training, by using initialization techniques. However, we show that identity skip connection retain norm-preservation during the training procedure. Our theoretical arguments are supported by extensive empirical evidence. Can we push for more norm-preservation? We answer this question by proposing zero-phase whitening of the fully-connected layer and adding norm-preserving transition layers. Our numerical investigations demonstrate that the learning dynamics and the performance of ResNets can be improved by making it even more norm preserving through changing only a few blocks in very deep residual networks. Our results and the introduced modification for ResNet, referred to as Procrustes ResNets, can be used as a guide for studying more complex architectures such as DenseNet, training deeper networks, and inspiring new architectures.

##### Abstract (translated by Google)
正如ResNet架构中介绍的那样，通过跳过连接来增强深度神经网络，让社区感到惊讶，因为它可以训练1000多层网络，并显着提高性能。已经证明，身份跳过连接消除了奇点并改善了网络的优化格局。本文通过分析后向路径中跳过连接的影响，对ResNet进行解译，并对深度神经网络中身份跳过连接的优点提出了新的理论结果。我们证明了残差块中的跳跃连接有助于保持梯度的规范并导致良好的稳定的反向传播，这是从优化角度来看的一个理想特征。我们还表明，也许令人惊讶的是，随着更多的残留块被堆叠，网络变得更加规范保存。传统上，通过使用初始化技术，仅在培训开始时才在网络上实施保护标准。但是，我们显示身份跳过连接在训练过程中保留规范保存。我们的理论论证得到广泛的经验证据的支持。我们能否推动更多的规范保护？我们通过提出完全连接层的零相位白化和添加保护范数的转换层来回答这个问题。我们的数值研究表明，ResNets的学习动态和性能可以通过在非常深的剩余网络中仅改变几个块来进行更加规范的保存而得到改进。我们的研究成果和ResNet的改进版，被称为Procrustes ResNets，可以用作学习更复杂的体系结构（如DenseNet），培训更深层次的网络以及激发新体系结构的指南。

##### URL
[https://arxiv.org/abs/1805.07477](https://arxiv.org/abs/1805.07477)

##### PDF
[https://arxiv.org/pdf/1805.07477](https://arxiv.org/pdf/1805.07477)

