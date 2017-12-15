---
layout: post
title: "Recurrent Highway Networks"
date: 2017-07-04 19:29:23
categories: arXiv_CL
tags: arXiv_CL Optimization RNN Language_Model Prediction
author: Julian Georg Zilly, Rupesh Kumar Srivastava, Jan Koutník, Jürgen Schmidhuber
mathjax: true
---

* content
{:toc}

##### Abstract
Many sequential processing tasks require complex nonlinear transition functions from one step to the next. However, recurrent neural networks with 'deep' transition functions remain difficult to train, even when using Long Short-Term Memory (LSTM) networks. We introduce a novel theoretical analysis of recurrent networks based on Gersgorin's circle theorem that illuminates several modeling and optimization issues and improves our understanding of the LSTM cell. Based on this analysis we propose Recurrent Highway Networks, which extend the LSTM architecture to allow step-to-step transition depths larger than one. Several language modeling experiments demonstrate that the proposed architecture results in powerful and efficient models. On the Penn Treebank corpus, solely increasing the transition depth from 1 to 10 improves word-level perplexity from 90.6 to 65.4 using the same number of parameters. On the larger Wikipedia datasets for character prediction (text8 and enwik8), RHNs outperform all previous results and achieve an entropy of 1.27 bits per character.

##### Abstract (translated by Google)
许多顺序处理任务需要从一步到下一步的复杂的非线性转换功能。然而，即使使用长期短期记忆（LSTM）网络，具有“深度”转换功能的递归神经网络仍难以训练。本文介绍了一种基于格尔森圆定理的循环网络的新型理论分析，阐明了几个建模和优化问题，提高了我们对LSTM单元的理解。基于这个分析，我们提出了复发高速公路网络，它扩展了LSTM架构以允许一步到一步的转换深度大于1。几种语言建模实验表明，所提出的体系结构导致强大而有效的模型。在Penn Treebank语料库上，单独将转换深度从1增加到10，使用相同数量的参数将词级困惑从90.6提高到65.4。在用于字符预测的更大维基百科数据集（text8和enwik8）上，RHN胜过所有先前的结果，并且实现每个字符1.27位的熵。

##### URL
[https://arxiv.org/abs/1607.03474](https://arxiv.org/abs/1607.03474)

##### PDF
[https://arxiv.org/pdf/1607.03474](https://arxiv.org/pdf/1607.03474)

