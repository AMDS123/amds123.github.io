---
layout: post
title: "Effective Neural Solution for Multi-Criteria Word Segmentation"
date: 2017-12-07 20:48:15
categories: arXiv_CL
tags: arXiv_CL Knowledge Segmentation GAN RNN
author: He Han, Wu Lei, Yan Hua, Gao Zhimin, Feng Yi, Townsend George
mathjax: true
---

* content
{:toc}

##### Abstract
We present a simple yet elegant solution to train a single joint model on multi-criteria corpora for Chinese Word Segmentation (CWS). Our novel design requires no private layers in model architecture, instead, introduces two artificial tokens at the beginning and ending of input sentence to specify the required target criteria. The rest of the model including Long Short-Term Memory (LSTM) layer and Conditional Random Fields (CRFs) layer remains unchanged and is shared across all datasets, keeping the size of parameter collection minimal and constant. On Bakeoff 2005 and Bakeoff 2008 datasets, our innovative design has surpassed both single-criterion and multi-criteria state-of-the-art learning results. To the best knowledge, our design is the first one that has achieved the latest high performance on such large scale datasets. Source codes and corpora of this paper are available on GitHub.

##### Abstract (translated by Google)
我们提出了一个简单而优雅的解决方案来训练一个关于中文分词（CWS）的多标准语料库的单个联合模型。我们的新颖设计在模型架构中不需要私有层，而是在输入语句的开始和结尾处引入两个人工标记来指定所需的目标标准。包括长期短期记忆（LSTM）层和条件随机场（CRF）层的其余部分保持不变，并在所有数据集中共享，保持参数集合的大小最小且恒定。在Bakeoff 2005和Bakeoff 2008数据集上，我们的创新设计已经超越了单一标准和多标准最新的学习成果。据了解，我们的设计是第一个在大规模数据集上取得最高性能的设计。本文的源代码和语料库可在GitHub上获得。

##### URL
[https://arxiv.org/abs/1712.02856](https://arxiv.org/abs/1712.02856)

##### PDF
[https://arxiv.org/pdf/1712.02856](https://arxiv.org/pdf/1712.02856)

