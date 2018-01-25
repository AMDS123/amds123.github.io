---
layout: post
title: "PRNN: Recurrent Neural Network with Persistent Memory"
date: 2018-01-24 17:38:48
categories: arXiv_AI
tags: arXiv_AI RNN Gradient_Descent
author: Kui Zhao, Yuechuan Li, Chi Zhang, Cheng Yang, Shenghuo Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
Although Recurrent Neural Network (RNN) has been a powerful tool for modeling sequential data, its performance is inadequate when processing sequences with multiple patterns. In this paper, we address this challenge by introducing an external memory and constructing a novel persistent memory augmented RNN (term as PRNN) model. The PRNN model captures the principle patterns in training sequences and stores them in the explicit memory. By leveraging the persistent memory, the proposed method can adaptively update states according to the similarities between encoded inputs and memory slots, leading to a stronger capacity in assimilating sequences with multiple patterns. Content-based addressing is suggested in memory accessing, and gradient descent is utilized for implicitly updating the memory. Experiments on several datasets demonstrate the effectiveness of the proposed method.

##### Abstract (translated by Google)
尽管递归神经网络（RNN）一直是模拟连续数据的强大工具，但在处理具有多种模式的序列时，其性能不足。在本文中，我们通过引入外部存储器并构造一种新颖的持久性存储器增强型RNN（term as PRNN）模型来解决这个挑战。 PRNN模型捕获训练序列中的原理模式并将它们存储在显式存储器中。通过利用持久性存储器，所提出的方法能够根据编码输入和存储器时隙之间的相似性来自适应地更新状态，从而导致具有多种模式的同化序列的更强的容量。在内存访问中建议使用基于内容的寻址，并利用梯度下降来隐式更新内存。在几个数据集上的实验证明了所提出方法的有效性。

##### URL
[http://arxiv.org/abs/1801.08094](http://arxiv.org/abs/1801.08094)

##### PDF
[http://arxiv.org/pdf/1801.08094](http://arxiv.org/pdf/1801.08094)

