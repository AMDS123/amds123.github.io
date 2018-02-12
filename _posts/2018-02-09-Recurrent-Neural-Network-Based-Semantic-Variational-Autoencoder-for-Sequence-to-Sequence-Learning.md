---
layout: post
title: "Recurrent Neural Network-Based Semantic Variational Autoencoder for Sequence-to-Sequence Learning"
date: 2018-02-09 12:58:29
categories: arXiv_CL
tags: arXiv_CL Attention Summarization Speech_Recognition RNN Language_Model Recognition
author: Myeongjun Jang, Seungwan Seo, Pilsung Kang
mathjax: true
---

* content
{:toc}

##### Abstract
Sequence-to-sequence (Seq2seq) models have played an import role in the recent success of various natural language processing methods, such as machine translation, text summarization, and speech recognition. However, current Seq2seq models have trouble preserving global latent information from a long sequence of words. Variational autoencoder (VAE) alleviates this problem by learning a continuous semantic space of the input sentence. However, it does not solve the problem completely. In this paper, we propose a new recurrent neural network (RNN)-based Seq2seq model, RNN semantic variational autoencoder (RNN--SVAE), to better capture the global latent information of a sequence of words. To consider the words in a sentence equally, without regard to its position within the sentence, we construct a document information vector using the attention information between the final state of the encoder and every prior hidden state. Then, we combine this document information vector with the final hidden state of the bi-directional RNN encoder to construct the global latent vector, which becomes the output of the encoder part. Then, the mean and standard deviation of the continuous semantic space are learned to take advantage of the variational method. Experimental results of three natural language tasks (i.e., language modeling, missing word imputation, paraphrase identification) confirm that the proposed RNN--SVAE yields higher performance than two benchmark models.

##### Abstract (translated by Google)
序列到序列（Seq2seq）模型在各种自然语言处理方法（例如机器翻译，文本总结和语音识别）的最近成功中发挥了重要作用。然而，目前的Seq2seq模型难以保留全球潜在的信息。变分自动编码器（VAE）通过学习输入句子的连续语义空间来缓解这个问题。但是，这并不能完全解决问题。在本文中，我们提出了一种新的基于递归神经网络（RNN）的Seq2seq模型，即RNN语义变分自动编码器（RNN  -  SVAE），以更好地捕获一系列单词的全局潜在信息。为了平等地考虑句子中的单词，不考虑它在句子中的位置，我们使用编码器的最终状态和每个在先隐藏状态之间的关注信息来构造文档信息向量。然后，将该文档信息向量与双向RNN编码器的最终隐藏状态相结合，构成全局潜在向量，成为编码器部分的输出。然后，学习连续语义空间的均值和标准差以利用变分法。三种自然语言任务的实验结果（即语言建模，缺失词汇插入，释义识别）证实了所提出的RNN  -  SVAE比两个基准模型具有更高的性能。

##### URL
[http://arxiv.org/abs/1802.03238](http://arxiv.org/abs/1802.03238)

##### PDF
[http://arxiv.org/pdf/1802.03238](http://arxiv.org/pdf/1802.03238)

