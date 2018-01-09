---
layout: post
title: "Gated Recurrent Networks for Seizure Detection"
date: 2018-01-03 00:54:05
categories: arXiv_AI
tags: arXiv_AI Regularization CNN RNN Detection
author: Meysam Golmohammadi, Saeedeh Ziyabari, Vinit Shah, Eva Von Weltin, Christopher Campbell, Iyad Obeid, Joseph Picone
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent Neural Networks (RNNs) with sophisticated units that implement a gating mechanism have emerged as powerful technique for modeling sequential signals such as speech or electroencephalography (EEG). The latter is the focus on this paper. A significant big data resource, known as the TUH EEG Corpus (TUEEG), has recently become available for EEG research, creating a unique opportunity to evaluate these recurrent units on the task of seizure detection. In this study, we compare two types of recurrent units: long short-term memory units (LSTM) and gated recurrent units (GRU). These are evaluated using a state of the art hybrid architecture that integrates Convolutional Neural Networks (CNNs) with RNNs. We also investigate a variety of initialization methods and show that initialization is crucial since poorly initialized networks cannot be trained. Furthermore, we explore regularization of these convolutional gated recurrent networks to address the problem of overfitting. Our experiments revealed that convolutional LSTM networks can achieve significantly better performance than convolutional GRU networks. The convolutional LSTM architecture with proper initialization and regularization delivers 30% sensitivity at 6 false alarms per 24 hours.

##### Abstract (translated by Google)
具有实现门控机制的复杂单元的递归神经网络（RNN）已经成为模拟诸如语音或脑电图（EEG）的顺序信号的强大技术。后者是本文的重点。被称为TUH EEG语料库（TUEEG）的重要大数据资源最近已经可用于脑电图研究，为评估这些经常出现的癫痫发作单元创造了独特的机会。在这项研究中，我们比较两种类型的经常性单位：长期短期记忆单位（LSTM）和门控循环单位（GRU）。这些评估采用最先进的混合架构，将卷积神经网络（CNN）与RNN集成在一起。我们还研究了各种初始化方法，并表明初始化是至关重要的，因为初始化不良的网络不能被训练。此外，我们探索这些卷积门控循环网络的正则化来解决过度拟合的问题。我们的实验表明，卷积LSTM网络可以比卷积GRU网络获得更好的性能。具有正确初始化和正则化的卷积LSTM架构在每24小时6次虚警中提供30％的灵敏度。

##### URL
[http://arxiv.org/abs/1801.02471](http://arxiv.org/abs/1801.02471)

##### PDF
[http://arxiv.org/pdf/1801.02471](http://arxiv.org/pdf/1801.02471)

