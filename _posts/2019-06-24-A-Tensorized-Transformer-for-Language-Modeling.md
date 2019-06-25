---
layout: post
title: "A Tensorized Transformer for Language Modeling"
date: 2019-06-24 08:28:37
categories: arXiv_CL
tags: arXiv_CL Attention Language_Model
author: Xindian Ma, Peng Zhang, Shuai Zhang, Nan Duan, Yuexian Hou, Dawei Song, Ming Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
Latest development of neural models has connected the encoder and decoder through a self-attention mechanism. In particular, Transformer, which is solely based on self-attention, has led to breakthroughs in Natural Language Processing (NLP) tasks. However, the multi-head attention mechanism, as a key component of Transformer, limits the effective deployment of the model to a limited resource setting. In this paper, based on the ideas of tensor decomposition and parameters sharing, we propose a novel self-attention model (namely Multi-linear attention) with Block-Term Tensor Decomposition (BTD). We test and verify the proposed attention method on three language modeling tasks (i.e., PTB, WikiText-103 and One-billion) and a neural machine translation task (i.e., WMT-2016 English-German). Multi-linear attention can not only largely compress the model parameters but also obtain performance improvements, compared with a number of language modeling approaches, such as Transformer, Transformer-XL, and Transformer with tensor train decomposition.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.09777](http://arxiv.org/abs/1906.09777)

##### PDF
[http://arxiv.org/pdf/1906.09777](http://arxiv.org/pdf/1906.09777)

