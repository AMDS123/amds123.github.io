---
layout: post
title: "Leveraging Sentence-level Information with Encoder LSTM for Semantic Slot Filling"
date: 2016-08-31 00:30:10
categories: arXiv_SD
tags: arXiv_SD RNN
author: Gakuto Kurata, Bing Xiang, Bowen Zhou, Mo Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent Neural Network (RNN) and one of its specific architectures, Long Short-Term Memory (LSTM), have been widely used for sequence labeling. In this paper, we first enhance LSTM-based sequence labeling to explicitly model label dependencies. Then we propose another enhancement to incorporate the global information spanning over the whole input sequence. The latter proposed method, encoder-labeler LSTM, first encodes the whole input sequence into a fixed length vector with the encoder LSTM, and then uses this encoded vector as the initial state of another LSTM for sequence labeling. Combining these methods, we can predict the label sequence with considering label dependencies and information of whole input sequence. In the experiments of a slot filling task, which is an essential component of natural language understanding, with using the standard ATIS corpus, we achieved the state-of-the-art F1-score of 95.66%.

##### Abstract (translated by Google)
递归神经网络（RNN）及其特定体系结构之一长时间短期记忆（LSTM）已被广泛用于序列标记。在本文中，我们首先增强基于LSTM的序列标签来明确地建模标签依赖性。然后，我们提出另一个增强，将整个输入序列中的全局信息合并起来。后者提出的方法，即编码器LSTM首先将整个输入序列编码成一个固定长度的向量与编码器LSTM，然后用这个编码向量作为另一个LSTM的初始状态进行序列标记。结合这些方法，我们可以预测标签序列，考虑标签依赖性和整个输入序列的信息。在作为自然语言理解的重要组成部分的时隙填充任务的实验中，使用标准的ATIS语料库，我们获得了95.66％的最新F1分数。

##### URL
[https://arxiv.org/abs/1601.01530](https://arxiv.org/abs/1601.01530)

##### PDF
[https://arxiv.org/pdf/1601.01530](https://arxiv.org/pdf/1601.01530)

