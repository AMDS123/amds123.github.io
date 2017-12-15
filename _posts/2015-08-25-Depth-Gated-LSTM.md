---
layout: post
title: "Depth-Gated LSTM"
date: 2015-08-25 04:24:20
categories: arXiv_CL
tags: arXiv_CL RNN Language_Model
author: Kaisheng Yao, Trevor Cohn, Katerina Vylomova, Kevin Duh, Chris Dyer
mathjax: true
---

* content
{:toc}

##### Abstract
In this short note, we present an extension of long short-term memory (LSTM) neural networks to using a depth gate to connect memory cells of adjacent layers. Doing so introduces a linear dependence between lower and upper layer recurrent units. Importantly, the linear dependence is gated through a gating function, which we call depth gate. This gate is a function of the lower layer memory cell, the input to and the past memory cell of this layer. We conducted experiments and verified that this new architecture of LSTMs was able to improve machine translation and language modeling performances.

##### Abstract (translated by Google)
在这个简短的说明中，我们提出了一个长期短期记忆（LSTM）神经网络的延伸，以使用深度门来连接相邻层的存储单元。这样做会引起下层和上层循环单元之间的线性相关性。重要的是，线性依赖通过一个门控函数门控，我们称之为深度门。该门是该层的下层存储单元，输入和过去的存储单元的功能。我们进行了实验，并验证了这种新的LSTM架构能够提高机器翻译和语言建模性能。

##### URL
[https://arxiv.org/abs/1508.03790](https://arxiv.org/abs/1508.03790)

##### PDF
[https://arxiv.org/pdf/1508.03790](https://arxiv.org/pdf/1508.03790)

