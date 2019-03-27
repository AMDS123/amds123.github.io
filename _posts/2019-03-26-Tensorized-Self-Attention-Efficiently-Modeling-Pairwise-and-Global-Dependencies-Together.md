---
layout: post
title: "Tensorized Self-Attention: Efficiently Modeling Pairwise and Global Dependencies Together"
date: 2019-03-26 09:07:00
categories: arXiv_CL
tags: arXiv_CL Attention RNN
author: Tao Shen, Tianyi Zhou, Guodong Long, Jing Jiang, Chengqi Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Neural networks equipped with self-attention have parallelizable computation, light-weight structure, and the ability to capture both long-range and local dependencies. Further, their expressive power and performance can be boosted by using a vector to measure pairwise dependency, but this requires to expand the alignment matrix to a tensor, which results in memory and computation bottlenecks. In this paper, we propose a novel attention mechanism called "Multi-mask Tensorized Self-Attention" (MTSA), which is as fast and as memory-efficient as a CNN, but significantly outperforms previous CNN-/RNN-/attention-based models. MTSA 1) captures both pairwise (token2token) and global (source2token) dependencies by a novel compatibility function composed of dot-product and additive attentions, 2) uses a tensor to represent the feature-wise alignment scores for better expressive power but only requires parallelizable matrix multiplications, and 3) combines multi-head with multi-dimensional attentions, and applies a distinct positional mask to each head (subspace), so the memory and computation can be distributed to multiple heads, each with sequential information encoded independently. The experiments show that a CNN/RNN-free model based on MTSA achieves state-of-the-art or competitive performance on nine NLP benchmarks with compelling memory- and time-efficiency.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.00912](http://arxiv.org/abs/1805.00912)

##### PDF
[http://arxiv.org/pdf/1805.00912](http://arxiv.org/pdf/1805.00912)

