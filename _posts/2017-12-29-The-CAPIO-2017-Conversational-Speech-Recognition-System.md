---
layout: post
title: "The CAPIO 2017 Conversational Speech Recognition System"
date: 2017-12-29 23:31:05
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition CNN Image_Classification RNN Classification Recognition
author: Kyu J. Han, Akshay Chandrashekaran, Jungsuk Kim, Ian Lane
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we show how we have achieved the state-of-the-art performance on the industry-standard NIST 2000 Hub5 English evaluation set. We explore densely connected LSTMs, inspired by the densely connected convolutional networks recently introduced for image classification tasks. We also propose an acoustic model adaptation scheme that simply averages the parameters of a seed neural network acoustic model and its adapted version. This method was applied with the CallHome training corpus and improved individual system performances by on average 6.1% (relative) against the CallHome portion of the evaluation set with no performance loss on the Switchboard portion. With RNN-LM rescoring and lattice combination on the 5 systems trained across three different phone sets, our 2017 speech recognition system has obtained 5.0% and 9.1% on Switchboard and CallHome, respectively, both of which are the best word error rates reported thus far. According to IBM in their latest work to compare human and machine transcriptions, our reported Switchboard word error rate can be considered to surpass the human parity (5.1%) of transcribing conversational telephone speech.

##### Abstract (translated by Google)
在本文中，我们将展示如何在行业标准的NIST 2000 Hub5英文评估集上取得最先进的性能。我们探索密集连接的LSTM，灵感来自最近为图像分类任务而引入的密集连接的卷积网络。我们还提出了一个声学模型自适应方案，简单地平均了种子神经网络声学模型及其适应版本的参数。这种方法适用于CallHome训练语料库，相对于评估集的CallHome部分，平均提高了6.1％（相对），在交换机部分没有性能损失。通过三个不同电话机上训练的5个系统的RNN-LM重新编码和格点组合，我们的2017语音识别系统在交换机和CallHome上分别获得了5.0％和9.1％，这两者都是目前为止报道的最好的字错误率。根据IBM最近的一项比较人机交互的工作，我们所报告的交换机字错误率可以被认为超过了转录会话电话语音的人平等（5.1％）。

##### URL
[http://arxiv.org/abs/1801.00059](http://arxiv.org/abs/1801.00059)

##### PDF
[http://arxiv.org/pdf/1801.00059](http://arxiv.org/pdf/1801.00059)

