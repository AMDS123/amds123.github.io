---
layout: post
title: "Attention-based Memory Selection Recurrent Network for Language Modeling"
date: 2016-11-26 04:25:00
categories: arXiv_CV
tags: arXiv_CV Review Attention RNN Language_Model
author: Da-Rong Liu, Shun-Po Chuang, Hung-yi Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural networks (RNNs) have achieved great success in language modeling. However, since the RNNs have fixed size of memory, their memory cannot store all the information about the words it have seen before in the sentence, and thus the useful long-term information may be ignored when predicting the next words. In this paper, we propose Attention-based Memory Selection Recurrent Network (AMSRN), in which the model can review the information stored in the memory at each previous time step and select the relevant information to help generate the outputs. In AMSRN, the attention mechanism finds the time steps storing the relevant information in the memory, and memory selection determines which dimensions of the memory are involved in computing the attention weights and from which the information is extracted.In the experiments, AMSRN outperformed long short-term memory (LSTM) based language models on both English and Chinese corpora. Moreover, we investigate using entropy as a regularizer for attention weights and visualize how the attention mechanism helps language modeling.

##### Abstract (translated by Google)
递归神经网络（RNN）在语言建模方面取得了巨大的成功。然而，由于RNN具有固定的存储器大小，其存储器不能存储关于在句子中所看到的单词的所有信息，因此在预测下一个单词时可以忽略有用的长期信息。在本文中，我们提出了基于注意力的记忆选择递归网络（AMSRN），其中模型可以在前一时间步骤中查看存储在存储器中的信息，并选择相关信息来帮助生成输出。在AMSRN中，注意机制在存储器中查找存储相关信息的时间步长，存储器的选择决定了计算注意权重时所涉及的存储器的哪个维度，并从中提取信息。实验中，AMSRN优于长短（LSTM）的语言模型。此外，我们调查使用熵作为一个正规化的注意力权重和形象化的注意机制如何帮助语言建模。

##### URL
[https://arxiv.org/abs/1611.08656](https://arxiv.org/abs/1611.08656)

##### PDF
[https://arxiv.org/pdf/1611.08656](https://arxiv.org/pdf/1611.08656)

