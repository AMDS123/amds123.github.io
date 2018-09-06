---
layout: post
title: "A Hierarchical Recurrent Neural Network for Symbolic Melody Generation"
date: 2018-09-05 03:25:40
categories: arXiv_SD
tags: arXiv_SD RNN
author: Jian Wu, Changran Hu, Yulong Wang, Xiaolin Hu, Jun Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, neural networks have been used to generate symbolic melodies. However, the long-term structure in the melody has posed great difficulty for designing a good model. In this paper, we present a hierarchical recurrent neural network for melody generation, which consists of three Long-Short-Term-Memory (LSTM) subnetworks working in a coarse-to-fine manner along time. Specifically, the three subnetworks generate bar profiles, beat profiles and notes in turn, and the output of the high-level subnetworks are fed into the low-level subnetworks, serving as guidance for generating the finer time-scale melody components in low-level subnetworks. Two human behavior experiments demonstrate the advantage of this structure over the single-layer LSTM which attempts to learn all hidden structures in melodies. Compared with the state-of-the-art models MidiNet and MusicVAE, the hierarchical recurrent neural network produces better melodies evaluated by humans.

##### Abstract (translated by Google)
近年来，神经网络已被用于产生符号旋律。然而，旋律中的长期结构给设计好的模型带来了很大的困难。在本文中，我们提出了一种用于旋律生成的分层递归神经网络，它由三个长 - 短期 - 内存（LSTM）子网络组成，这些子网络随着时间的推移以粗到细的方式工作。具体来说，三个子网络依次生成条形图，节拍轮廓和音符，高级子网的输出被送入低级子网，作为生成低级精细时间尺度旋律组件的指导。子网。两个人类行为实验证明了这种结构优于单层LSTM的优势，LSTM试图学习旋律中所有隐藏的结构。与最先进的MidiNet和MusicVAE模型相比，分层递归神经网络可以产生更好的人体评估旋律。

##### URL
[http://arxiv.org/abs/1712.05274](http://arxiv.org/abs/1712.05274)

##### PDF
[http://arxiv.org/pdf/1712.05274](http://arxiv.org/pdf/1712.05274)

