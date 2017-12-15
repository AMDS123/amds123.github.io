---
layout: post
title: "Neural Machine Transliteration: Preliminary Results"
date: 2016-09-14 13:12:12
categories: arXiv_CL
tags: arXiv_CL Attention RNN
author: Amir H. Jadidinejad
mathjax: true
---

* content
{:toc}

##### Abstract
Machine transliteration is the process of automatically transforming the script of a word from a source language to a target language, while preserving pronunciation. Sequence to sequence learning has recently emerged as a new paradigm in supervised learning. In this paper a character-based encoder-decoder model has been proposed that consists of two Recurrent Neural Networks. The encoder is a Bidirectional recurrent neural network that encodes a sequence of symbols into a fixed-length vector representation, and the decoder generates the target sequence using an attention-based recurrent neural network. The encoder, the decoder and the attention mechanism are jointly trained to maximize the conditional probability of a target sequence given a source sequence. Our experiments on different datasets show that the proposed encoder-decoder model is able to achieve significantly higher transliteration quality over traditional statistical models.

##### Abstract (translated by Google)
机器音译是将一个单词的脚本从源语言自动转换为目标语言的过程，同时保留发音。序列学习的序列最近已经成为监督学习的新范式。本文提出了一种基于字符的编码器 - 解码器模型，由两个递归神经网络组成。编码器是双向递归神经网络，将一系列符号编码成固定长度的向量表示，解码器使用基于注意力的递归神经网络产生目标序列。编码器，解码器和关注机制被联合训练，以最大化给定源序列的目标序列的条件概率。我们在不同数据集上的实验表明，所提出的编码器 - 解码器模型能够比传统统计模型显着提高音译质量。

##### URL
[https://arxiv.org/abs/1609.04253](https://arxiv.org/abs/1609.04253)

##### PDF
[https://arxiv.org/pdf/1609.04253](https://arxiv.org/pdf/1609.04253)

