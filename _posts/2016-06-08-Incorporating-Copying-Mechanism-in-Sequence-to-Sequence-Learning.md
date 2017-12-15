---
layout: post
title: "Incorporating Copying Mechanism in Sequence-to-Sequence Learning"
date: 2016-06-08 13:53:21
categories: arXiv_SD
tags: arXiv_SD Summarization RNN
author: Jiatao Gu, Zhengdong Lu, Hang Li, Victor O.K. Li
mathjax: true
---

* content
{:toc}

##### Abstract
We address an important problem in sequence-to-sequence (Seq2Seq) learning referred to as copying, in which certain segments in the input sequence are selectively replicated in the output sequence. A similar phenomenon is observable in human language communication. For example, humans tend to repeat entity names or even long phrases in conversation. The challenge with regard to copying in Seq2Seq is that new machinery is needed to decide when to perform the operation. In this paper, we incorporate copying into neural network-based Seq2Seq learning and propose a new model called CopyNet with encoder-decoder structure. CopyNet can nicely integrate the regular way of word generation in the decoder with the new copying mechanism which can choose sub-sequences in the input sequence and put them at proper places in the output sequence. Our empirical study on both synthetic data sets and real world data sets demonstrates the efficacy of CopyNet. For example, CopyNet can outperform regular RNN-based model with remarkable margins on text summarization tasks.

##### Abstract (translated by Google)
我们解决了序列到序列（Seq2Seq）学习中被称为复制的一个重要问题，其中输入序列中的某些片段被有选择地复制到输出序列中。人类语言交际中也可以观察到类似现象。例如，人们倾向于在对话中重复实体名称或甚至长的短语。在Seq2Seq中复制的挑战是需要新的机器来决定何时执行操作。在本文中，我们将复制结合到基于神经网络的Seq2Seq学习中，并提出了一个带有编码器 - 解码器结构的称为CopyNet的新模型。 CopyNet可以很好地将解码器中常规的单词生成方式与新的复制机制相结合，可以在输入序列中选择子序列，并将它们放在输出序列的适当位置。我们对合成数据集和现实世界数据集的实证研究证明了CopyNet的有效性。例如，CopyNet可以超越常规的基于RNN的模型，在文本摘要任务上有显着的利润空间。

##### URL
[https://arxiv.org/abs/1603.06393](https://arxiv.org/abs/1603.06393)

##### PDF
[https://arxiv.org/pdf/1603.06393](https://arxiv.org/pdf/1603.06393)

