---
layout: post
title: "Subword Encoding in Lattice LSTM for Chinese Word Segmentation"
date: 2018-10-30 09:14:37
categories: arXiv_CL
tags: arXiv_CL Segmentation Embedding RNN
author: Jie Yang, Yue Zhang, Shuailong Liang
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate a lattice LSTM network for Chinese word segmentation (CWS) to utilize words or subwords. It integrates the character sequence features with all subsequences information matched from a lexicon. The matched subsequences serve as information shortcut tunnels which link their start and end characters directly. Gated units are used to control the contribution of multiple input links. Through formula derivation and comparison, we show that the lattice LSTM is an extension of the standard LSTM with the ability to take multiple inputs. Previous lattice LSTM model takes word embeddings as the lexicon input, we prove that subword encoding can give the comparable performance and has the benefit of not relying on any external segmentor. The contribution of lattice LSTM comes from both lexicon and pretrained embeddings information, we find that the lexicon information contributes more than the pretrained embeddings information through controlled experiments. Our experiments show that the lattice structure with subword encoding gives competitive or better results with previous state-of-the-art methods on four segmentation benchmarks. Detailed analyses are conducted to compare the performance of word encoding and subword encoding in lattice LSTM. We also investigate the performance of lattice LSTM structure under different circumstances and when this model works or fails.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.12594](http://arxiv.org/abs/1810.12594)

##### PDF
[http://arxiv.org/pdf/1810.12594](http://arxiv.org/pdf/1810.12594)

