---
layout: post
title: "Revisiting Activation Regularization for Language RNNs"
date: 2017-08-03 05:53:53
categories: arXiv_CL
tags: arXiv_CL Regularization RNN Language_Model
author: Stephen Merity, Bryan McCann, Richard Socher
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural networks (RNNs) serve as a fundamental building block for many sequence tasks across natural language processing. Recent research has focused on recurrent dropout techniques or custom RNN cells in order to improve performance. Both of these can require substantial modifications to the machine learning model or to the underlying RNN configurations. We revisit traditional regularization techniques, specifically L2 regularization on RNN activations and slowness regularization over successive hidden states, to improve the performance of RNNs on the task of language modeling. Both of these techniques require minimal modification to existing RNN architectures and result in performance improvements comparable or superior to more complicated regularization techniques or custom cell architectures. These regularization techniques can be used without any modification on optimized LSTM implementations such as the NVIDIA cuDNN LSTM.

##### Abstract (translated by Google)
递归神经网络（RNN）作为自然语言处理中许多序列任务的基本构建块。最近的研究集中在复发性丢失技术或定制的RNN细胞以提高性能。这两者都可能需要对机器学习模型或底层RNN配置进行重大修改。我们重新审视传统的正则化技术，特别是二次RNN激活的正则化和连续隐藏状态下的慢度正则化，以提高RNN在语言建模任务上的性能。这两种技术都需要对现有RNN体系结构进行最小限度的修改，并导致与更复杂的正则化技术或定制单元体系结构相比甚至更好的性能改进。这些正则化技术可以在不对优化的LSTM实现（如NVIDIA cuDNN LSTM）进行任何修改的情况下使用。

##### URL
[https://arxiv.org/abs/1708.01009](https://arxiv.org/abs/1708.01009)

##### PDF
[https://arxiv.org/pdf/1708.01009](https://arxiv.org/pdf/1708.01009)

