---
layout: post
title: "Feedforward Sequential Memory Networks: A New Structure to Learn Long-term Dependency"
date: 2016-01-05 02:40:41
categories: arXiv_CV
tags: arXiv_CV Speech_Recognition RNN Language_Model Memory_Networks Recognition
author: Shiliang Zhang, Cong Liu, Hui Jiang, Si Wei, Lirong Dai, Yu Hu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel neural network structure, namely \emph{feedforward sequential memory networks (FSMN)}, to model long-term dependency in time series without using recurrent feedback. The proposed FSMN is a standard fully-connected feedforward neural network equipped with some learnable memory blocks in its hidden layers. The memory blocks use a tapped-delay line structure to encode the long context information into a fixed-size representation as short-term memory mechanism. We have evaluated the proposed FSMNs in several standard benchmark tasks, including speech recognition and language modelling. Experimental results have shown FSMNs significantly outperform the conventional recurrent neural networks (RNN), including LSTMs, in modeling sequential signals like speech or language. Moreover, FSMNs can be learned much more reliably and faster than RNNs or LSTMs due to the inherent non-recurrent model structure.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的神经网络结构，即前馈顺序记忆网络（FSMN），用于在不使用递归反馈的情况下对时间序列的长期依赖性进行建模。提出的FSMN是一个标准的全连接的前馈神经网络，在其隐藏层中配备了一些可学习的存储块。存储器块使用抽头延迟线结构将长的上下文信息编码为固定大小的表示作为短期存储器机制。我们已经在几个标准的基准任务中评估了提议的FSMN，包括语音识别和语言建模。实验结果表明FSMNs在语音或语言等连续信号建模中显着优于传统的递归神经网络（RNN），包括LSTMs。此外，由于固有的非经常性模型结构，FSMN可以比RNN或LSTM更加可靠和快速地学习。

##### URL
[https://arxiv.org/abs/1512.08301](https://arxiv.org/abs/1512.08301)

##### PDF
[https://arxiv.org/pdf/1512.08301](https://arxiv.org/pdf/1512.08301)

