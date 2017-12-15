---
layout: post
title: "A Regularized Framework for Sparse and Structured Neural Attention"
date: 2017-11-03 23:58:20
categories: arXiv_CL
tags: arXiv_CL Sparse Attention Summarization
author: Vlad Niculae, Mathieu Blondel
mathjax: true
---

* content
{:toc}

##### Abstract
Modern neural networks are often augmented with an attention mechanism, which tells the network where to focus within the input. We propose in this paper a new framework for sparse and structured attention, building upon a smoothed max operator. We show that the gradient of this operator defines a mapping from real values to probabilities, suitable as an attention mechanism. Our framework includes softmax and a slight generalization of the recently-proposed sparsemax as special cases. However, we also show how our framework can incorporate modern structured penalties, resulting in more interpretable attention mechanisms, that focus on entire segments or groups of an input. We derive efficient algorithms to compute the forward and backward passes of our attention mechanisms, enabling their use in a neural network trained with backpropagation. To showcase their potential as a drop-in replacement for existing ones, we evaluate our attention mechanisms on three large-scale tasks: textual entailment, machine translation, and sentence summarization. Our attention mechanisms improve interpretability without sacrificing performance; notably, on textual entailment and summarization, we outperform the standard attention mechanisms based on softmax and sparsemax.

##### Abstract (translated by Google)
现代神经网络往往增加了一个注意机制，它告诉网络在输入内聚焦的地方。我们在本文中提出了一个新的框架稀疏和结构化的关注，建立在一个平滑的最大运算符。我们显示这个算子的梯度定义了一个从真实值到概率的映射，适合作为注意机制。我们的框架包括softmax和作为特例的最近提出的sparsemax的略微概括。然而，我们也展示了我们的框架如何纳入现代的结构性惩罚，从而产生更多的可解释的关注机制，关注整个部分或输入组。我们推导出高效的算法来计算我们关注机制的前进和后退过程，使它们能够在反向传播训练的神经网络中使用。为了展示他们潜在的替代现有的潜力，我们评估了我们的注意机制对三个大规模的任务：文本蕴涵，机器翻译和句子总结。我们的注意机制在不牺牲绩效的前提下提高了解释性特别是在文本的包含和总结上，我们超越了基于softmax和sparsemax的标准关注机制。

##### URL
[https://arxiv.org/abs/1705.07704](https://arxiv.org/abs/1705.07704)

##### PDF
[https://arxiv.org/pdf/1705.07704](https://arxiv.org/pdf/1705.07704)

