---
layout: post
title: "Differentiable Pooling for Unsupervised Acoustic Model Adaptation"
date: 2016-07-13 18:12:49
categories: arXiv_SD
tags: arXiv_SD Speech_Recognition Recognition
author: Pawel Swietojanski, Steve Renals
mathjax: true
---

* content
{:toc}

##### Abstract
We present a deep neural network (DNN) acoustic model that includes parametrised and differentiable pooling operators. Unsupervised acoustic model adaptation is cast as the problem of updating the decision boundaries implemented by each pooling operator. In particular, we experiment with two types of pooling parametrisations: learned $L_p$-norm pooling and weighted Gaussian pooling, in which the weights of both operators are treated as speaker-dependent. We perform investigations using three different large vocabulary speech recognition corpora: AMI meetings, TED talks and Switchboard conversational telephone speech. We demonstrate that differentiable pooling operators provide a robust and relatively low-dimensional way to adapt acoustic models, with relative word error rates reductions ranging from 5--20% with respect to unadapted systems, which themselves are better than the baseline fully-connected DNN-based acoustic models. We also investigate how the proposed techniques work under various adaptation conditions including the quality of adaptation data and complementarity to other feature- and model-space adaptation methods, as well as providing an analysis of the characteristics of each of the proposed approaches.

##### Abstract (translated by Google)
我们提出了一个深层神经网络（DNN）声学模型，其中包括参数化和可微池化算子。无监督的声学模型适应是由每个汇集运营商实施的更新决策边界的问题。具体来说，我们试验了两种类型的池化参数：学习$ L_p $ -norm池和加权高斯池，其中两个运算符的权重被视为与讲话者相关。我们使用三种不同的大词汇量语音识别语料库进行调查：AMI会议，TED会谈和交换机对话电话。我们证明了可微分池操作提供了一个稳健的和相对低维的方法来适应声学模型，相对于无适应系统的相对字误差率降低5-20％，其本身比基线完全连接的DNN基于声学模型。我们还研究了所提出的技术在各种适应条件下是如何工作的，包括适应数据的质量和与其他特征和模型空间适应方法的互补性，以及分析每个提出的方法的特性。

##### URL
[https://arxiv.org/abs/1603.09630](https://arxiv.org/abs/1603.09630)

##### PDF
[https://arxiv.org/pdf/1603.09630](https://arxiv.org/pdf/1603.09630)

