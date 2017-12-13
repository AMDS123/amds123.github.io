---
layout: post
title: "A Massively Parallel Associative Memory Based on Sparse Neural Networks"
date: 2013-07-21 14:29:21
categories: arXiv_CV
tags: arXiv_CV Sparse Face Detection Recognition Face_Recognition
author: Zhe Yao, Vincent Gripon, Michael G. Rabbat
mathjax: true
---

* content
{:toc}

##### Abstract
Associative memories store content in such a way that the content can be later retrieved by presenting the memory with a small portion of the content, rather than presenting the memory with an address as in more traditional memories. Associative memories are used as building blocks for algorithms within database engines, anomaly detection systems, compression algorithms, and face recognition systems. A classical example of an associative memory is the Hopfield neural network. Recently, Gripon and Berrou have introduced an alternative construction which builds on ideas from the theory of error correcting codes and which greatly outperforms the Hopfield network in capacity, diversity, and efficiency. In this paper we implement a variation of the Gripon-Berrou associative memory on a general purpose graphical processing unit (GPU). The work of Gripon and Berrou proposes two retrieval rules, sum-of-sum and sum-of-max. The sum-of-sum rule uses only matrix-vector multiplication and is easily implemented on the GPU. The sum-of-max rule is much less straightforward to implement because it involves non-linear operations. However, the sum-of-max rule gives significantly better retrieval error rates. We propose a hybrid rule tailored for implementation on a GPU which achieves a 880-fold speedup without sacrificing any accuracy.

##### Abstract (translated by Google)
联想存储器以这样的方式存储内容，即通过将内容的一小部分呈现给存储器而稍后检索内容，而不是像在更传统的存储器中那样向存储器呈现地址。联想存储器用作数据库引擎，异常检测系统，压缩算法和人脸识别系统中算法的构建块。联想记忆的典型例子是Hopfield神经网络。最近，Gripon和Berrou引入了一个替代的构造，它建立在纠错码理论的基础上，并且在容量，多样性和效率方面远远优于Hopfield网络。在本文中，我们实现了通用图形处理单元（GPU）上的Gripon-Berrou联想记忆的变体。 Gripon和Berrou的工作提出了两个检索规则，即sum-of-sum和max-max。总和和规则仅使用矩阵向量乘法，并且在GPU上容易实现。 max-sum规则的实现要简单得多，因为它涉及非线性操作。然而，max-sum规则提供了显着更好的检索错误率。我们提出了一个专门针对GPU实现的混合规则，在不牺牲任何准确性的情况下实现了880倍的加速。

##### URL
[https://arxiv.org/abs/1303.7032](https://arxiv.org/abs/1303.7032)

##### PDF
[https://arxiv.org/pdf/1303.7032](https://arxiv.org/pdf/1303.7032)

