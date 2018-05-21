---
layout: post
title: "Adaptive Recurrent Neural Network via Persistent Memory"
date: 2018-05-18 09:45:30
categories: arXiv_AI
tags: arXiv_AI Knowledge RNN Gradient_Descent
author: Kui Zhao, Yuechuan Li, Chi Zhang, Cheng Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Although Recurrent Neural Network (RNN) has been a powerful tool for modeling sequential data, its performance is inadequate when processing sequences with multiple patterns. In this paper, we address this challenge by introducing a persistent memory and constructing an adaptive RNN. The persistent memory augmented RNN (termed as PRNN) captures the principle patterns in training sequences and stores them in an external memory. By leveraging the persistent memory, the proposed method can adaptively update states according to the similarities between encoded inputs and memory slots, leading to a stronger capacity in assimilating sequences with multiple patterns. Content-based addressing is suggested in memory accessing, and gradient descent is utilized for implicitly updating the memory. Our approach can be further extended by combining the prior knowledge of data. Experiments on several datasets demonstrate the effectiveness of our method.

##### Abstract (translated by Google)
虽然递归神经网络（RNN）一直是模拟连续数据的强大工具，但在处理具有多种模式的序列时，其性能不足。在本文中，我们通过引入持久性内存并构建自适应RNN来解决这一挑战。持久记忆增强型RNN（称为PRNN）捕获训练序列中的原理模式并将它们存储在外部存储器中。通过利用持久性存储器，所提出的方法可以根据编码输入和存储器插槽之间的相似性来自适应地更新状态，从而导致具有多种模式的同化序列的更强的容量。内存访问中建议使用基于内容的寻址，并利用梯度下降来隐式更新内存。我们的方法可以通过结合数据的先验知识进一步扩展。对几个数据集的实验证明了我们方法的有效性。

##### URL
[http://arxiv.org/abs/1801.08094](http://arxiv.org/abs/1801.08094)

##### PDF
[http://arxiv.org/pdf/1801.08094](http://arxiv.org/pdf/1801.08094)

