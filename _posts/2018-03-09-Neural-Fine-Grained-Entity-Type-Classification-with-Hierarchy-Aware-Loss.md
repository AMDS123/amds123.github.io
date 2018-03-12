---
layout: post
title: "Neural Fine-Grained Entity Type Classification with Hierarchy-Aware Loss"
date: 2018-03-09 04:15:22
categories: arXiv_CL
tags: arXiv_CL Classification
author: Peng Xu, Denilson Barbosa
mathjax: true
---

* content
{:toc}

##### Abstract
The task of Fine-grained Entity Type Classification (FETC) consists of assigning types from a hierarchy to entity mentions in text. The state-of-the-art relies on distant supervision and is susceptible to noisy labels that can be out-of-context or overly-specific relative to the training example. Previous methods that attempt to address this issue do so with hand- crafted features. Also, previous work solve FETC a multi-label classification followed by post-processing. Instead, we propose an end-to-end solution with a neural network model that uses a variant of cross-entropy loss function to handle out-of-context labels, and hierarchical loss normalization to cope with overly-specific ones. We show experimentally that our approach is robust against noise and consistently outperforms the state-of-the-art on established benchmarks for the task.

##### Abstract (translated by Google)
细粒度实体类型分类（FETC）的任务包括从文本中将层次结构分配给实体提及。最先进的技术依赖于远程监控，并且容易受到相对于训练示例而言可能超出上下文或过于具体的嘈杂标签的影响。试图解决这个问题的以前的方法通过手工特征来实现。此外，以前的工作解决了FETC多标签分类和后处理。相反，我们提出了一个端到端的解决方案，其中使用了一个神经网络模型，该模型使用了一个交叉熵损失函数的变体来处理超出上下文的标签，并通过分层损失归一化来处理过于具体的标签。我们通过实验证明，我们的方法对噪声强健，并且始终优于已建立的任务基准的最新技术。

##### URL
[http://arxiv.org/abs/1803.03378](http://arxiv.org/abs/1803.03378)

##### PDF
[http://arxiv.org/pdf/1803.03378](http://arxiv.org/pdf/1803.03378)

