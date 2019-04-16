---
layout: post
title: "Sparse Persistent RNNs: Squeezing Large Recurrent Networks On-Chip"
date: 2018-04-26 18:18:57
categories: arXiv_CL
tags: arXiv_CL Sparse Speech_Recognition Optimization NMT RNN Recognition
author: Feiwen Zhu, Jeff Pool, Michael Andersch, Jeremy Appleyard, Fung Xie
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent Neural Networks (RNNs) are powerful tools for solving sequence-based problems, but their efficacy and execution time are dependent on the size of the network. Following recent work in simplifying these networks with model pruning and a novel mapping of work onto GPUs, we design an efficient implementation for sparse RNNs. We investigate several optimizations and tradeoffs: Lamport timestamps, wide memory loads, and a bank-aware weight layout. With these optimizations, we achieve speedups of over 6x over the next best algorithm for a hidden layer of size 2304, batch size of 4, and a density of 30%. Further, our technique allows for models of over 5x the size to fit on a GPU for a speedup of 2x, enabling larger networks to help advance the state-of-the-art. We perform case studies on NMT and speech recognition tasks in the appendix, accelerating their recurrent layers by up to 3x.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1804.10223](https://arxiv.org/abs/1804.10223)

##### PDF
[https://arxiv.org/pdf/1804.10223](https://arxiv.org/pdf/1804.10223)

