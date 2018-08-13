---
layout: post
title: "Speaker Verification using Convolutional Neural Networks"
date: 2018-08-10 17:45:24
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
在本文中，已经开发了一种新颖的卷积神经网络架构用于说话者验证，以便分别同时捕获和丢弃说话者和非说话者信息。在训练阶段，训练网络以区分用于创建背景模型的不同说话者身份。其中一个关键部分是创建扬声器模型。大多数先前的方法基于对背景模型提供的说话者表示进行平均来创建说话者模型。我们通过使用Siamese框架进一步微调训练的模型来推翻这个问题，以生成区别特征空间，以区分相同和不同的发言者，无论他们的身份如何。这提供了一种机制，其同时捕获与说话者相关的信息并创建对于说话者内变体的鲁棒性。证明了所提出的方法优于直接从背景模型创建说话者模型的传统验证方法。

##### URL
[http://arxiv.org/abs/1803.05427](http://arxiv.org/abs/1803.05427)

##### PDF
[http://arxiv.org/pdf/1803.05427](http://arxiv.org/pdf/1803.05427)

