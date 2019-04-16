---
layout: post
title: "Deep Neural Machine Translation with Weakly-Recurrent Units"
date: 2018-05-10 21:55:32
categories: arXiv_CL
tags: arXiv_CL Attention NMT Inference RNN
author: Mattia Antonino Di Gangi, Marcello Federico
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural networks (RNNs) have represented for years the state of the art in neural machine translation. Recently, new architectures have been proposed, which can leverage parallel computation on GPUs better than classical RNNs. Faster training and inference combined with different sequence-to-sequence modeling also lead to performance improvements. While the new models completely depart from the original recurrent architecture, we decided to investigate how to make RNNs more efficient. In this work, we propose a new recurrent NMT architecture, called Simple Recurrent NMT, built on a class of fast and weakly-recurrent units that use layer normalization and multiple attentions. Our experiments on the WMT14 English-to-German and WMT16 English-Romanian benchmarks show that our model represents a valid alternative to LSTMs, as it can achieve better results at a significantly lower computational cost.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1805.04185](https://arxiv.org/abs/1805.04185)

##### PDF
[https://arxiv.org/pdf/1805.04185](https://arxiv.org/pdf/1805.04185)

