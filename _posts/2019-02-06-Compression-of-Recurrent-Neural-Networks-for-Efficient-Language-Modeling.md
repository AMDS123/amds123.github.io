---
layout: post
title: "Compression of Recurrent Neural Networks for Efficient Language Modeling"
date: 2019-02-06 19:49:22
categories: arXiv_CL
tags: arXiv_CL Attention Inference RNN Language_Model
author: Artem M. Grachev, Dmitry I. Ignatov, Andrey V. Savchenko
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural networks have proved to be an effective method for statistical language modeling. However, in practice their memory and run-time complexity are usually too large to be implemented in real-time offline mobile applications. In this paper we consider several compression techniques for recurrent neural networks including Long-Short Term Memory models. We make particular attention to the high-dimensional output problem caused by the very large vocabulary size. We focus on effective compression methods in the context of their exploitation on devices: pruning, quantization, and matrix decomposition approaches (low-rank factorization and tensor train decomposition, in particular). For each model we investigate the trade-off between its size, suitability for fast inference and perplexity. We propose a general pipeline for applying the most suitable methods to compress recurrent neural networks for language modeling. It has been shown in the experimental study with the Penn Treebank (PTB) dataset that the most efficient results in terms of speed and compression-perplexity balance are obtained by matrix decomposition techniques.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.02380](http://arxiv.org/abs/1902.02380)

##### PDF
[http://arxiv.org/pdf/1902.02380](http://arxiv.org/pdf/1902.02380)

