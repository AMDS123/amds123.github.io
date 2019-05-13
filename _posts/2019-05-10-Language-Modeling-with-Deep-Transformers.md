---
layout: post
title: "Language Modeling with Deep Transformers"
date: 2019-05-10 15:50:00
categories: arXiv_CL
tags: arXiv_CL Attention Speech_Recognition RNN Language_Model Recognition
author: Kazuki Irie, Albert Zeyer, Ralf Schl&#xfc;ter, Hermann Ney
mathjax: true
---

* content
{:toc}

##### Abstract
We explore multi-layer autoregressive Transformer models in language modeling for speech recognition. We focus on two aspects. First, we revisit Transformer model configurations specifically for language modeling. We show that well configured Transformer models outperform our baseline models based on the shallow stack of LSTM recurrent neural network layers. We carry out experiments on the open-source LibriSpeech 960hr task, for both 200K vocabulary word-level and 10K byte-pair encoding subword-level language modeling. We apply our word-level models to conventional hybrid speech recognition by lattice rescoring, and the subword-level models to attention based encoder-decoder models by shallow fusion. Second, we show that deep Transformer language models do not require positional encoding. The positional encoding is an essential augmentation for the self-attention mechanism which is invariant to sequence ordering. However, in autoregressive setup, as is the case for language modeling, the amount of information increases along the position dimension, which is a positional signal by its own. The analysis of attention weights shows that deep autoregressive self-attention models can automatically make use of such positional information. We find that removing the positional encoding even slightly improves the performance of these models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.04226](http://arxiv.org/abs/1905.04226)

##### PDF
[http://arxiv.org/pdf/1905.04226](http://arxiv.org/pdf/1905.04226)

