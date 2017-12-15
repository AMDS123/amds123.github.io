---
layout: post
title: "Learning to Compose Task-Specific Tree Structures"
date: 2017-11-21 12:00:19
categories: arXiv_CL
tags: arXiv_CL Sentiment Inference RNN
author: Jihun Choi, Kang Min Yoo, Sang-goo Lee
mathjax: true
---

* content
{:toc}

##### Abstract
For years, recursive neural networks (RvNNs) have been shown to be suitable for representing text into fixed-length vectors and achieved good performance on several natural language processing tasks. However, the main drawback of RvNNs is that they require structured input, which makes data preparation and model implementation hard. In this paper, we propose Gumbel Tree-LSTM, a novel tree-structured long short-term memory architecture that learns how to compose task-specific tree structures only from plain text data efficiently. Our model uses Straight-Through Gumbel-Softmax estimator to decide the parent node among candidates dynamically and to calculate gradients of the discrete decision. We evaluate the proposed model on natural language inference and sentiment analysis, and show that our model outperforms or is at least comparable to previous models. We also find that our model converges significantly faster than other models.

##### Abstract (translated by Google)
多年来，递归神经网络（RvNN）已被证明适合于将文本表示成固定长度的向量，并且在几种自然语言处理任务中取得了良好的性能。然而，RvNNs的主要缺点是需要结构化的输入，这使得数据准备和模型实现变得困难。在本文中，我们提出了Gumbel Tree-LSTM，这是一种新颖的树状结构的长期短期记忆体系结构，可以有效地从纯文本数据中学习如何构建任务特定的树状结构。我们的模型使用直通Gumbel-Softmax估计器来动态地决定候选者之间的父节点，并计算离散决策的梯度。我们评估提出的自然语言推理和情感分析模型，并表明我们的模型性能优于或至少可以与以前的模型相媲美。我们还发现，我们的模型收敛速度比其他模型快得多。

##### URL
[https://arxiv.org/abs/1707.02786](https://arxiv.org/abs/1707.02786)

##### PDF
[https://arxiv.org/pdf/1707.02786](https://arxiv.org/pdf/1707.02786)

