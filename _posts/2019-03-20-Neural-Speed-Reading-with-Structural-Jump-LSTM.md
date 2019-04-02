---
layout: post
title: "Neural Speed Reading with Structural-Jump-LSTM"
date: 2019-03-20 12:01:46
categories: arXiv_CL
tags: arXiv_CL Inference RNN
author: Christian Hansen, Casper Hansen, Stephen Alstrup, Jakob Grue Simonsen, Christina Lioma
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural networks (RNNs) can model natural language by sequentially 'reading' input tokens and outputting a distributed representation of each token. Due to the sequential nature of RNNs, inference time is linearly dependent on the input length, and all inputs are read regardless of their importance. Efforts to speed up this inference, known as 'neural speed reading', either ignore or skim over part of the input. We present Structural-Jump-LSTM: the first neural speed reading model to both skip and jump text during inference. The model consists of a standard LSTM and two agents: one capable of skipping single words when reading, and one capable of exploiting punctuation structure (sub-sentence separators (,:), sentence end symbols (.!?), or end of text markers) to jump ahead after reading a word. A comprehensive experimental evaluation of our model against all five state-of-the-art neural reading models shows that Structural-Jump-LSTM achieves the best overall floating point operations (FLOP) reduction (hence is faster), while keeping the same accuracy or even improving it compared to a vanilla LSTM that reads the whole text.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.00761](http://arxiv.org/abs/1904.00761)

##### PDF
[http://arxiv.org/pdf/1904.00761](http://arxiv.org/pdf/1904.00761)

