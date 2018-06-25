---
layout: post
title: "Persistent Hidden States and Nonlinear Transformation for Long Short-Term Memory"
date: 2018-06-22 16:19:46
categories: arXiv_CL
tags: arXiv_CL Attention Speech_Recognition RNN Deep_Learning Recognition
author: Heeyoul Choi
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural networks (RNNs) have been drawing much attention with great success in many applications like speech recognition and neural machine translation. Long short-term memory (LSTM) is one of the most popular RNN units in deep learning applications. LSTM transforms the input and the previous hidden states to the next states with the affine transformation, multiplication operations and a nonlinear activation function, which makes a good data representation for a given task. The affine transformation includes rotation and reflection, which change the semantic or syntactic information of dimensions in the hidden states. However, considering that a model interprets the output sequence of LSTM over the whole input sequence, the dimensions of the states need to keep the same type of semantic or syntactic information regardless of the location in the sequence. In this paper, we propose a simple variant of the LSTM unit, persistent recurrent unit (PRU), where each dimension of hidden states keeps persistent information across time, so that the space keeps the same meaning over the whole sequence. In addition, to improve the nonlinear transformation power, we add a feedforward layer in the PRU structure. In the experiment, we evaluate our proposed methods with three different tasks, and the results confirm that our methods have better performance than the conventional LSTM.

##### Abstract (translated by Google)
递归神经网络（RNN）在语音识别和神经机器翻译等许多应用中取得了巨大的成功。长期短期记忆（LSTM）是深度学习应用中最受欢迎的RNN单位之一。 LSTM利用仿射变换，乘法运算和非线性激活函数将输入和以前的隐藏状态转换为下一个状态，这为给定任务提供了良好的数据表示。仿射变换包括旋转和反射，它们改变隐藏状态下维度的语义或语法信息。然而，考虑到模型在整个输入序列上解释LSTM的输出序列，状态的维度需要保持相同类型的语义或句法信息，而不管序列中的位置如何。在本文中，我们提出了LSTM单元的一个简单变体，即持久性重现单元（PRU），其中隐藏状态的每个维度在时间上保持持久信息，以便该空间在整个序列中保持相同的含义。另外，为了改善非线性变换能力，我们在PRU结构中增加了一个前馈层。在实验中，我们评估了我们提出的三种不同任务的方法，结果证实我们的方法比传统的LSTM具有更好的性能。

##### URL
[http://arxiv.org/abs/1806.08748](http://arxiv.org/abs/1806.08748)

##### PDF
[http://arxiv.org/pdf/1806.08748](http://arxiv.org/pdf/1806.08748)

