---
layout: post
title: "End-to-end Language Identification using NetFV and NetVLAD"
date: 2018-09-09 01:07:11
categories: arXiv_AI
tags: arXiv_AI CNN
author: Jinkun Chen, Weicheng Cai, Danwei Cai, Zexin Cai, Haibin Zhong, Ming Li
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we apply the NetFV and NetVLAD layers for the end-to-end language identification task. NetFV and NetVLAD layers are the differentiable implementations of the standard Fisher Vector and Vector of Locally Aggregated Descriptors (VLAD) methods, respectively. Both of them can encode a sequence of feature vectors into a fixed dimensional vector which is very important to process those variable-length utterances. We first present the relevances and differences between the classical i-vector and the aforementioned encoding schemes. Then, we construct a flexible end-to-end framework including a convolutional neural network (CNN) architecture and an encoding layer (NetFV or NetVLAD) for the language identification task. Experimental results on the NIST LRE 2007 close-set task show that the proposed system achieves significant EER reductions against the conventional i-vector baseline and the CNN temporal average pooling system, respectively.

##### Abstract (translated by Google)
在本文中，我们将NetFV和NetV​​LAD层应用于端到端语言识别任务。 NetFV和NetV​​LAD层分别是标准Fisher矢量和局部聚合描述符矢量（VLAD）方法的可微分实现。它们都可以将特征向量序列编码成固定的维度向量，这对于处理那些可变长度的话语非常重要。我们首先介绍经典i向量和上述编码方案之间的相关性和差异。然后，我们构建了一个灵活的端到端框架，包括卷积神经网络（CNN）架构和用于语言识别任务的编码层（NetFV或NetVLAD）。 NIST LRE 2007近期任务的实验结果表明，所提出的系统分别对传统的i-vector基线和CNN时间平均汇集系统实现了显着的EER降低。

##### URL
[http://arxiv.org/abs/1809.02906](http://arxiv.org/abs/1809.02906)

##### PDF
[http://arxiv.org/pdf/1809.02906](http://arxiv.org/pdf/1809.02906)

