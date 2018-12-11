---
layout: post
title: "EcoRNN: Efficient Computing of LSTM RNN Training on GPUs"
date: 2018-12-09 06:11:50
categories: arXiv_AI
tags: arXiv_AI Attention Optimization NMT RNN
author: Bojian Zheng, Abhishek Tiwari, Nandita Vijaykumar, Gennady Pekhimenko
mathjax: true
---

* content
{:toc}

##### Abstract
The Long-Short-Term-Memory Recurrent Neural Network (LSTM RNN) is a state-of-the-art machine learning model for analyzing sequential data. It, however, has low training throughput and is limited by memory capacity when running on GPUs. Our results from profiling the LSTM RNN-based Neural Machine Translation (NMT) model reveal that the feature maps of the attention layers form the major memory bottleneck and the fully-connected layers form the runtime bottleneck when training on a modern GPU. We identify the key reason why the attention layers disproportionately consume so much GPU memory: their computation exhibits an O-shape (i.e. small input and output size, but large amounts of intermediate values). We observe that the repetitive nature of LSTM RNNs can be exploited to improve performance of the fully-connected layers by better utilizing the GPU memory hierarchy. Based on these observations, we propose EcoRNN that incorporates two optimizations that significantly reduce the memory footprint and runtime. (1) Partial forward propagation reduces the memory footprint by stashing the small input values of the attention layers and then recomputing the feature maps during the backward passes, instead of saving them in memory. (2) Data layout optimization boosts runtime performance of fully-connected layers by transposing the data between row-major and column-major layout. It is transparent to programmers since EcoRNN automatically selects the best implementation using model hyperparameters.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.08899](http://arxiv.org/abs/1805.08899)

##### PDF
[http://arxiv.org/pdf/1805.08899](http://arxiv.org/pdf/1805.08899)

