---
layout: post
title: "Sequential Recurrent Neural Networks for Language Modeling"
date: 2017-03-23 13:48:45
categories: arXiv_SD
tags: arXiv_SD RNN Language_Model
author: Youssef Oualil, Clayton Greenberg, Mittul Singh, Dietrich Klakow
mathjax: true
---

* content
{:toc}

##### Abstract
Feedforward Neural Network (FNN)-based language models estimate the probability of the next word based on the history of the last N words, whereas Recurrent Neural Networks (RNN) perform the same task based only on the last word and some context information that cycles in the network. This paper presents a novel approach, which bridges the gap between these two categories of networks. In particular, we propose an architecture which takes advantage of the explicit, sequential enumeration of the word history in FNN structure while enhancing each word representation at the projection layer through recurrent context information that evolves in the network. The context integration is performed using an additional word-dependent weight matrix that is also learned during the training. Extensive experiments conducted on the Penn Treebank (PTB) and the Large Text Compression Benchmark (LTCB) corpus showed a significant reduction of the perplexity when compared to state-of-the-art feedforward as well as recurrent neural network architectures.

##### Abstract (translated by Google)
基于前馈神经网络（FNN）的语言模型基于最后N个词的历史来估计下一个词的概率，而递归神经网络（RNN）仅基于最后一个词和一些周期性信息来执行相同的任务在网络中。本文提出了一种新颖的方法，弥合这两类网络之间的差距。具体而言，我们提出了一种架构，其利用FNN结构中的历史的字面显式，顺序列举，同时通过在网络中演变的循环上下文信息来增强投影层处的每个词表示。上下文整合使用在训练期间也学习到的附加的依赖于单词的权重矩阵来执行。在Penn Treebank（PTB）和大文本压缩基准（LTCB）语料库上进行的大量实验显示，与最先进的前馈以及递归神经网络结构相比，困惑性显着减少。

##### URL
[https://arxiv.org/abs/1703.08068](https://arxiv.org/abs/1703.08068)

##### PDF
[https://arxiv.org/pdf/1703.08068](https://arxiv.org/pdf/1703.08068)

