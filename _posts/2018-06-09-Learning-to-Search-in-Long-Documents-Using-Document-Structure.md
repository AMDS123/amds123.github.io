---
layout: post
title: "Learning to Search in Long Documents Using Document Structure"
date: 2018-06-09 18:55:00
categories: arXiv_CL
tags: arXiv_CL RNN
author: Mor Geva, Jonathan Berant
mathjax: true
---

* content
{:toc}

##### Abstract
Reading comprehension models are based on recurrent neural networks that sequentially process the document tokens. As interest turns to answering more complex questions over longer documents, sequential reading of large portions of text becomes a substantial bottleneck. Inspired by how humans use document structure, we propose a novel framework for reading comprehension. We represent documents as trees, and model an agent that learns to interleave quick navigation through the document tree with more expensive answer extraction. To encourage exploration of the document tree, we propose a new algorithm, based on Deep Q-Network (DQN), which strategically samples tree nodes at training time. Empirically we find our algorithm improves question answering performance compared to DQN and a strong information-retrieval (IR) baseline, and that ensembling our model with the IR baseline results in further gains in performance.

##### Abstract (translated by Google)
阅读理解模型基于顺序处理文档令牌的递归神经网络。随着对长篇文档的回答越来越复杂，连续阅读大部分文本成为一个严重的瓶颈。受人类如何使用文档结构的启发，我们提出了一种新颖的阅读理解框架。我们将文档表示为树，并对一个代理进行建模，该代理学习通过文档树交叉快速导航，并使用更昂贵的答案提取。为了鼓励对文档树的探索，我们提出了一种基于深度Q网络（DQN）的新算法，该算法在训练时间对树节点进行策略性采样。经验上我们发现，与DQN和强大的信息检索（IR）基线相比，我们的算法改善了问题回答性能，并且将我们的模型与IR基准相结合可以进一步提高性能。

##### URL
[http://arxiv.org/abs/1806.03529](http://arxiv.org/abs/1806.03529)

##### PDF
[http://arxiv.org/pdf/1806.03529](http://arxiv.org/pdf/1806.03529)

