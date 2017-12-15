---
layout: post
title: "Highway Long Short-Term Memory RNNs for Distant Speech Recognition"
date: 2016-01-11 09:48:01
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition RNN Recognition
author: Yu Zhang, Guoguo Chen, Dong Yu, Kaisheng Yao, Sanjeev Khudanpur, James Glass
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we extend the deep long short-term memory (DLSTM) recurrent neural networks by introducing gated direct connections between memory cells in adjacent layers. These direct links, called highway connections, enable unimpeded information flow across different layers and thus alleviate the gradient vanishing problem when building deeper LSTMs. We further introduce the latency-controlled bidirectional LSTMs (BLSTMs) which can exploit the whole history while keeping the latency under control. Efficient algorithms are proposed to train these novel networks using both frame and sequence discriminative criteria. Experiments on the AMI distant speech recognition (DSR) task indicate that we can train deeper LSTMs and achieve better improvement from sequence training with highway LSTMs (HLSTMs). Our novel model obtains $43.9/47.7\%$ WER on AMI (SDM) dev and eval sets, outperforming all previous works. It beats the strong DNN and DLSTM baselines with $15.7\%$ and $5.3\%$ relative improvement respectively.

##### Abstract (translated by Google)
在本文中，我们通过在相邻层中的存储器单元之间引入门控直接连接来扩展深长期短期记忆（DLSTM）递归神经网络。这些直接连接称为高速公路连接，可以使不同层次的信息畅通无阻，从而减轻建设更深层次LSTM时的梯度消失问题。我们进一步介绍了延迟控制的双向LSTM（BLSTM），它可以利用整个历史，同时保持延迟的控制。提出有效的算法来训练这些使用帧和序列判别准则的新颖网络。 AMI远距离语音识别（DSR）任务的实验表明，我们可以训练更深层次的LSTM，并通过高速公路LSTM（HLSTM）进行序列训练来获得更好的改进。我们的新模型在AMI（SDM）开发和评估套件上获得$ 43.9 / 47.7 \％$ WER，超越了以前的所有工作。它击败强劲的DNN和DLSTM基线分别为$ 15.7 \％$和$ 5.3 \％$相对改善。

##### URL
[https://arxiv.org/abs/1510.08983](https://arxiv.org/abs/1510.08983)

##### PDF
[https://arxiv.org/pdf/1510.08983](https://arxiv.org/pdf/1510.08983)

