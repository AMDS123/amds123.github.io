---
layout: post
title: "Learning Efficient Algorithms with Hierarchical Attentive Memory"
date: 2016-02-23 10:22:25
categories: arXiv_CV
tags: arXiv_CV Attention RNN
author: Marcin Andrychowicz, Karol Kurach
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose and investigate a novel memory architecture for neural networks called Hierarchical Attentive Memory (HAM). It is based on a binary tree with leaves corresponding to memory cells. This allows HAM to perform memory access in O(log n) complexity, which is a significant improvement over the standard attention mechanism that requires O(n) operations, where n is the size of the memory. We show that an LSTM network augmented with HAM can learn algorithms for problems like merging, sorting or binary searching from pure input-output examples. In particular, it learns to sort n numbers in time O(n log n) and generalizes well to input sequences much longer than the ones seen during the training. We also show that HAM can be trained to act like classic data structures: a stack, a FIFO queue and a priority queue.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1602.03218](https://arxiv.org/abs/1602.03218)

##### PDF
[https://arxiv.org/pdf/1602.03218](https://arxiv.org/pdf/1602.03218)

