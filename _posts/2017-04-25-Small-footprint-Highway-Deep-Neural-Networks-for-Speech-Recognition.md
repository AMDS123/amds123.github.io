---
layout: post
title: "Small-footprint Highway Deep Neural Networks for Speech Recognition"
date: 2017-04-25 19:48:41
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Recognition
author: Liang Lu, Steve Renals
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art speech recognition systems typically employ neural network acoustic models. However, compared to Gaussian mixture models, deep neural network (DNN) based acoustic models often have many more model parameters, making it challenging for them to be deployed on resource-constrained platforms, such as mobile devices. In this paper, we study the application of the recently proposed highway deep neural network (HDNN) for training small-footprint acoustic models. HDNNs are a depth-gated feedforward neural network, which include two types of gate functions to facilitate the information flow through different layers. Our study demonstrates that HDNNs are more compact than regular DNNs for acoustic modeling, i.e., they can achieve comparable recognition accuracy with many fewer model parameters. Furthermore, HDNNs are more controllable than DNNs: the gate functions of an HDNN can control the behavior of the whole network using a very small number of model parameters. Finally, we show that HDNNs are more adaptable than DNNs. For example, simply updating the gate functions using adaptation data can result in considerable gains in accuracy. We demonstrate these aspects by experiments using the publicly available AMI corpus, which has around 80 hours of training data.

##### Abstract (translated by Google)
最先进的语音识别系统通常使用神经网络声学模型。然而，与高斯混合模型相比，基于深度神经网络（DNN）的声学模型通常具有更多的模型参数，使得它们难以部署在资源受限的平台（例如移动设备）上。在本文中，我们研究了最近提出的公路深度神经网络（HDNN）在小尺寸声学模型训练中的应用。 HDNN是一个深度门控的前馈神经网络，它包括两种门功能，以促进不同层次的信息流。我们的研究表明HDNN比常规DNN在声学建模方面更加紧凑，即它们可以通过少得多的模型参数来实现可比较的识别精度。此外，HDNN比DNN具有更好的可控性：HDNN的门功能可以使用非常少的模型参数来控制整个网络的行为。最后，我们显示HDNN比DNN更具适应性。例如，简单地使用自适应数据更新门功能可以导致相当高的准确性。我们通过使用公开可用的AMI语料库的实验来证明这些方面，其具有大约80个小时的训练数据。

##### URL
[https://arxiv.org/abs/1610.05812](https://arxiv.org/abs/1610.05812)

##### PDF
[https://arxiv.org/pdf/1610.05812](https://arxiv.org/pdf/1610.05812)

