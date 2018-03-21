---
layout: post
title: "Speaker Verification using Convolutional Neural Networks"
date: 2018-03-14 20:12:32
categories: arXiv_SD
tags: arXiv_SD CNN
author: Hossein Salehghaffari
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, a novel Convolutional Neural Network architecture has been developed for speaker verification in order to simultaneously capture and discard speaker and non-speaker information, respectively. In training phase, the network is trained to distinguish between different speaker identities for creating the background model. One of the crucial parts is to create the speaker models. Most of the previous approaches create speaker models based on averaging the speaker representations provided by the background model. We overturn this problem by further fine-tuning the trained model using the Siamese framework for generating a discriminative feature space to distinguish between same and different speakers regardless of their identity. This provides a mechanism which simultaneously captures the speaker-related information and create robustness to within-speaker variations. It is demonstrated that the proposed method outperforms the traditional verification methods which create speaker models directly from the background model.

##### Abstract (translated by Google)
在本文中，为了同时捕获和丢弃扬声器和非扬声器信息，已经开发了用于说话者验证的新型卷积神经网络架构。在训练阶段，训练网络以区分用于创建背景模型的不同扬声器身份。其中一个关键部分是创建扬声器模型。大多数先前的方法基于平均由背景模型提供的说话者表示来创建说话者模型。我们通过使用连体框架对经过训练的模型进行进一步微调来推翻这个问题，以产生区分性特征空间来区分相同和不同的说话人，而不管他们的身份如何。这提供了一种机制，可以同时捕获与讲话人相关的信息并为讲话人内变体创建稳健性。结果表明，所提出的方法优于直接从背景模型创建说话人模型的传统验证方法。

##### URL
[https://arxiv.org/abs/1803.05427](https://arxiv.org/abs/1803.05427)

##### PDF
[https://arxiv.org/pdf/1803.05427](https://arxiv.org/pdf/1803.05427)

