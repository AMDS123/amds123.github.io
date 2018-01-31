---
layout: post
title: "Trajectory-based Radical Analysis Network for Online Handwritten Chinese Character Recognition"
date: 2018-01-22 02:42:32
categories: arXiv_CV
tags: arXiv_CV Attention Caption RNN Deep_Learning Recognition
author: Jianshu Zhang, Yixing Zhu, Jun Du, Lirong Dai
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, great progress has been made for online handwritten Chinese character recognition due to the emergence of deep learning techniques. However, previous research mostly treated each Chinese character as one class without explicitly considering its inherent structure, namely the radical components with complicated geometry. In this study, we propose a novel trajectory-based radical analysis network (TRAN) to firstly identify radicals and analyze two-dimensional structures among radicals simultaneously, then recognize Chinese characters by generating captions of them based on the analysis of their internal radicals. The proposed TRAN employs recurrent neural networks (RNNs) as both an encoder and a decoder. The RNN encoder makes full use of online information by directly transforming handwriting trajectory into high-level features. The RNN decoder aims at generating the caption by detecting radicals and spatial structures through an attention model. The manner of treating a Chinese character as a two-dimensional composition of radicals can reduce the size of vocabulary and enable TRAN to possess the capability of recognizing unseen Chinese character classes, only if the corresponding radicals have been seen. Evaluated on CASIA-OLHWDB database, the proposed approach significantly outperforms the state-of-the-art whole-character modeling approach with a relative character error rate (CER) reduction of 10%. Meanwhile, for the case of recognition of 500 unseen Chinese characters, TRAN can achieve a character accuracy of about 60% while the traditional whole-character method has no capability to handle them.

##### Abstract (translated by Google)
近年来，由于深度学习技术的出现，在线手写汉字识别技术取得了长足的进步。然而，以往的研究大都把每个汉字作为一个类别，而没有明确地考虑它的内在结构，即几何形状复杂的根本成分。在这项研究中，我们提出了一个新的基于轨迹的自由基分析网络（TRAN）首先识别自由基，同时分析自由基之间的二维结构，然后根据内部自由基的分析生成字幕来识别汉字。所提出的TRAN采用递归神经网络（RNN）作为编码器和解码器。 RNN编码器通过将手写轨迹直接转换为高级特征来充分利用在线信息。 RNN解码器旨在通过通过关注模型检测自由基和空间结构来生成字幕。将汉字视为二维组成部分的方式可以减少词汇的大小，使TRAN能够识别看不见的汉字类别，只要看到相应的词根。在CASIA-OLHWDB数据库上评估，所提出的方法明显优于最先进的全角建模方法，相对字符错误率（CER）降低了10％。同时，在识别500个不可见汉字的情况下，TRAN可以达到约60％的字符精度，而传统的全字符方法则无法处理。

##### URL
[http://arxiv.org/abs/1801.10109](http://arxiv.org/abs/1801.10109)

##### PDF
[http://arxiv.org/pdf/1801.10109](http://arxiv.org/pdf/1801.10109)

