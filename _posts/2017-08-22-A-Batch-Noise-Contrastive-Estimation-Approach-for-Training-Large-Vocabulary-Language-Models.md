---
layout: post
title: "A Batch Noise Contrastive Estimation Approach for Training Large Vocabulary Language Models"
date: 2017-08-22 09:15:38
categories: arXiv_CL
tags: arXiv_CL Language_Model
author: Youssef Oualil, Dietrich Klakow
mathjax: true
---

* content
{:toc}

##### Abstract
Training large vocabulary Neural Network Language Models (NNLMs) is a difficult task due to the explicit requirement of the output layer normalization, which typically involves the evaluation of the full softmax function over the complete vocabulary. This paper proposes a Batch Noise Contrastive Estimation (B-NCE) approach to alleviate this problem. This is achieved by reducing the vocabulary, at each time step, to the target words in the batch and then replacing the softmax by the noise contrastive estimation approach, where these words play the role of targets and noise samples at the same time. In doing so, the proposed approach can be fully formulated and implemented using optimal dense matrix operations. Applying B-NCE to train different NNLMs on the Large Text Compression Benchmark (LTCB) and the One Billion Word Benchmark (OBWB) shows a significant reduction of the training time with no noticeable degradation of the models performance. This paper also presents a new baseline comparative study of different standard NNLMs on the large OBWB on a single Titan-X GPU.

##### Abstract (translated by Google)
训练大量词汇表由于输出层规范化的明确要求，神经网络语言模型（NNLMs）是一项艰巨的任务，它通常涉及整个词汇表上完整的softmax函数的评估。本文提出批量噪声对比估计（B-NCE）方法来缓解这个问题。这是通过在每个时间步骤将词汇量减少到批量中的目标词语，然后用噪声对比估计方法代替softmax来实现的，其中这些词语同时扮演目标和噪声样本的角色。这样做，提出的方法可以充分制定和实施使用最佳的密集矩阵操作。在大文本压缩基准（LTCB）和十亿字基准（OBWB）上应用B-NCE来训练不同的NNLM，显示训练时间显着减少，模型性能没有显着降低。本文还介绍了在单个Titan-X GPU上的大型OBWB上的不同标准NNLM的基准比较研究。

##### URL
[https://arxiv.org/abs/1708.05997](https://arxiv.org/abs/1708.05997)

##### PDF
[https://arxiv.org/pdf/1708.05997](https://arxiv.org/pdf/1708.05997)

