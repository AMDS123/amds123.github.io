---
layout: post
title: "Cooperative Training of Descriptor and Generator Networks"
date: 2017-02-08 17:32:46
categories: arXiv_CV
tags: arXiv_CV CNN
author: Jianwen Xie, Yang Lu, Ruiqi Gao, Song-Chun Zhu, Ying Nian Wu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper studies the cooperative training of two probabilistic models of signals such as images. Both models are parametrized by convolutional neural networks (ConvNets). The first network is a descriptor network, which is an exponential family model or an energy-based model, whose feature statistics or energy function are defined by a bottom-up ConvNet, which maps the observed signal to the feature statistics. The second network is a generator network, which is a non-linear version of factor analysis. It is defined by a top-down ConvNet, which maps the latent factors to the observed signal. The maximum likelihood training algorithms of both the descriptor net and the generator net are in the form of alternating back-propagation, and both algorithms involve Langevin sampling. We observe that the two training algorithms can cooperate with each other by jumpstarting each other's Langevin sampling, and they can be naturally and seamlessly interwoven into a CoopNets algorithm that can train both nets simultaneously.

##### Abstract (translated by Google)
本文研究了两种信号概率模型如图像的协同训练。这两个模型都通过卷积神经网络（ConvNets）进行参数化。第一个网络是一个描述符网络，它是一个指数族模型或基于能量的模型，其特征统计量或能量函数由自底向上的ConvNet定义，将观测信号映射到特征统计量。第二个网络是一个发电机网络，它是一个因子分析的非线性版本。它由自顶向下的ConvNet定义，它将潜在因素映射到观测信号。描述符网络和发生器网络的最大似然训练算法是交替反向传播的形式，两种算法都涉及Langevin抽样。我们观察到，两种训练算法可以通过相互启动对方的Langevin抽样来相互配合，并且可以自然而无缝地交织成可以同时训练两个网络的CoopNets算法。

##### URL
[https://arxiv.org/abs/1609.09408](https://arxiv.org/abs/1609.09408)

##### PDF
[https://arxiv.org/pdf/1609.09408](https://arxiv.org/pdf/1609.09408)

