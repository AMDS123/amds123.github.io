---
layout: post
title: "Graph Convolutional Encoders for Syntax-aware Neural Machine Translation"
date: 2017-07-28 18:18:52
categories: arXiv_CL
tags: arXiv_CL Attention CNN RNN
author: Joost Bastings, Ivan Titov, Wilker Aziz, Diego Marcheggiani, Khalil Sima'an
mathjax: true
---

* content
{:toc}

##### Abstract
We present a simple and effective approach to incorporating syntactic structure into neural attention-based encoder-decoder models for machine translation. We rely on graph-convolutional networks (GCNs), a recent class of neural networks developed for modeling graph-structured data. Our GCNs use predicted syntactic dependency trees of source sentences to produce representations of words (i.e. hidden states of the encoder) that are sensitive to their syntactic neighborhoods. GCNs take word representations as input and produce word representations as output, so they can easily be incorporated as layers into standard encoders (e.g., on top of bidirectional RNNs or convolutional neural networks). We evaluate their effectiveness with English-German and English-Czech translation experiments for different types of encoders and observe substantial improvements over their syntax-agnostic versions in all the considered setups.

##### Abstract (translated by Google)
我们提出了一种简单而有效的方法来将语法结构纳入机器翻译的基于神经关注的编码器 - 解码器模型中。我们依赖图形卷积网络（GCNs），这是一种最新的用于建模图形结构数据的神经网络。我们的GCN使用源句子的预测的句法依赖树来产生对其句法邻域敏感的单词表示（即编码器的隐藏状态）。 GCN以词表示作为输入并产生词表示作为输出，因此它们可以容易地作为分层并入标准编码器（例如，在双向RNN或卷积神经网络之上）。我们通过英德和英捷翻译实验针对不同类型的编码器评估其有效性，并在所有考虑的设置中观察其语法不可知的版本的实质性改进。

##### URL
[https://arxiv.org/abs/1704.04675](https://arxiv.org/abs/1704.04675)

##### PDF
[https://arxiv.org/pdf/1704.04675](https://arxiv.org/pdf/1704.04675)

