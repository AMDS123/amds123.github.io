---
layout: post
title: "A Convolutional Attention Network for Extreme Summarization of Source Code"
date: 2016-05-25 12:18:28
categories: arXiv_SD
tags: arXiv_SD Attention Summarization CNN
author: Miltiadis Allamanis, Hao Peng, Charles Sutton
mathjax: true
---

* content
{:toc}

##### Abstract
Attention mechanisms in neural networks have proved useful for problems in which the input and output do not have fixed dimension. Often there exist features that are locally translation invariant and would be valuable for directing the model's attention, but previous attentional architectures are not constructed to learn such features specifically. We introduce an attentional neural network that employs convolution on the input tokens to detect local time-invariant and long-range topical attention features in a context-dependent way. We apply this architecture to the problem of extreme summarization of source code snippets into short, descriptive function name-like summaries. Using those features, the model sequentially generates a summary by marginalizing over two attention mechanisms: one that predicts the next summary token based on the attention weights of the input tokens and another that is able to copy a code token as-is directly into the summary. We demonstrate our convolutional attention neural network's performance on 10 popular Java projects showing that it achieves better performance compared to previous attentional mechanisms.

##### Abstract (translated by Google)
神经网络中的注意机制对于输入和输出没有固定维数的问题证明是有用的。常常存在局部平移不变的特征，对于引导模型的注意力而言是有价值的，但是之前的注意力架构不是专门学习这些特征的。我们引入一个注意神经网络，对输入令牌进行卷积，以依赖于上下文的方式检测局部时间不变和长时间的主题注意特征。我们将这种体系结构应用于源代码片段的极度概括成简短的，描述性的函数名称摘要的问题。通过使用这些特征，模型通过边缘化两个注意机制来顺序生成概要：一个基于输入令牌的注意权重来预测下一个摘要令牌，另一个能够将代码令牌直接复制到摘要中。我们展示了卷积关注神经网络在10个流行的Java项目上的表现，表明它比以前的注意机制实现了更好的性能。

##### URL
[https://arxiv.org/abs/1602.03001](https://arxiv.org/abs/1602.03001)

##### PDF
[https://arxiv.org/pdf/1602.03001](https://arxiv.org/pdf/1602.03001)

