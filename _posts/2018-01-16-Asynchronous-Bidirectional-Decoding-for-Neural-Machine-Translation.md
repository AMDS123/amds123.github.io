---
layout: post
title: "Asynchronous Bidirectional Decoding for Neural Machine Translation"
date: 2018-01-16 05:21:43
categories: arXiv_CL
tags: arXiv_CL Attention NMT RNN Prediction
author: Xiangwen Zhang, Jinsong Su, Yue Qin, Yang Liu, Rongrong Ji, Hongji Wang
mathjax: true
---

* content
{:toc}

##### Abstract
The dominant neural machine translation (NMT) models apply unified attentional encoder-decoder neural networks for translation. Traditionally, the NMT decoders adopt recurrent neural networks (RNNs) to perform translation in a left-toright manner, leaving the target-side contexts generated from right to left unexploited during translation. In this paper, we equip the conventional attentional encoder-decoder NMT framework with a backward decoder, in order to explore bidirectional decoding for NMT. Attending to the hidden state sequence produced by the encoder, our backward decoder first learns to generate the target-side hidden state sequence from right to left. Then, the forward decoder performs translation in the forward direction, while in each translation prediction timestep, it simultaneously applies two attention models to consider the source-side and reverse target-side hidden states, respectively. With this new architecture, our model is able to fully exploit source- and target-side contexts to improve translation quality altogether. Experimental results on NIST Chinese-English and WMT English-German translation tasks demonstrate that our model achieves substantial improvements over the conventional NMT by 3.14 and 1.38 BLEU points, respectively. The source code of this work can be obtained from https://github.com/DeepLearnXMU/ABDNMT.

##### Abstract (translated by Google)
主导的神经机器翻译（NMT）模型使用统一的注意编码器 - 解码器神经网络进行翻译。传统上，NMT解码器采用递归神经网络（RNN）以左旋方式执行翻译，使从右向左生成的目标侧上下文在翻译期间未被利用。在本文中，我们将传统的注意编码器 - 解码器NMT框架配备反向解码器，以探索NMT的双向解码。参照编码器产生的隐藏状态序列，我们的反向解码器首先学习从右向左产生目标侧隐藏状态序列。然后，正向解码器正向执行翻译，而在每个翻译预测时间步骤中，其同时应用两个关注模型以分别考虑源侧和反向目标侧隐藏状态。借助这种新的架构，我们的模型能够充分利用源语言和目标语境来提高翻译质量。 NIST中英文和WMT英德翻译任务的实验结果表明，我们的模型分别比传统的NMT提高了3.14和1.38 BLEU点。这个工作的源代码可以从https://github.com/DeepLearnXMU/ABDNMT获得。

##### URL
[http://arxiv.org/abs/1801.05122](http://arxiv.org/abs/1801.05122)

##### PDF
[http://arxiv.org/pdf/1801.05122](http://arxiv.org/pdf/1801.05122)

