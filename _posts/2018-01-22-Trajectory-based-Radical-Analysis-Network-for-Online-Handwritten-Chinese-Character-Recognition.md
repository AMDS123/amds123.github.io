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
最近，由于深度学习技术的出现，在线手写汉字识别已经取得了很大进展。然而，先前的研究大多将每个汉字视为一个类而没有明确考虑其固有结构，即具有复杂几何形状的激进分量。在这项研究中，我们提出了一种新的基于轨迹的激进分析网络（TRAN），首先识别自由基并同时分析基团之间的二维结构，然后通过基于内部自由基的分析生成字符来识别汉字。所提出的TRAN使用递归神经网络（RNN）作为编码器和解码器。 RNN编码器通过直接将手写轨迹转换为高级特征来充分利用在线信息。 RNN解码器旨在通过注意模型检测自由基和空间结构来生成字幕。将汉字作为激进的二维组合处理的方式可以减少词汇的大小，并且只有在看到相应的部首时，才能使TRAN具有识别看不见的汉字类的能力。在CASIA-OLHWDB数据库上进行评估，所提出的方法明显优于最先进的全字符建模方法，相对字符错误率（CER）降低10％。同时，对于识别500个看不见的汉字的情况，TRAN可以达到约60％的字符精度，而传统的整体字符方法无法处理它们。

##### URL
[https://arxiv.org/abs/1801.10109](https://arxiv.org/abs/1801.10109)

##### PDF
[https://arxiv.org/pdf/1801.10109](https://arxiv.org/pdf/1801.10109)

