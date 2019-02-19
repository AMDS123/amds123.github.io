---
layout: post
title: "Self-Attention Aligner: A Latency-Control End-to-End Model for ASR Using Self-Attention Network and Chunk-Hopping"
date: 2019-02-18 08:17:24
categories: arXiv_CL
tags: arXiv_CL Attention Speech_Recognition RNN Language_Model Recognition
author: Linhao Dong, Feng Wang, Bo Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Self-attention network, an attention-based feedforward neural network, has recently shown the potential to replace recurrent neural networks (RNNs) in a variety of NLP tasks. However, it is not clear if the self-attention network could be a good alternative of RNNs in automatic speech recognition (ASR), which processes the longer speech sequences and may have online recognition requirements. In this paper, we present a RNN-free end-to-end model: self-attention aligner (SAA), which applies the self-attention networks to a simplified recurrent neural aligner (RNA) framework. We also propose a chunk-hopping mechanism, which enables the SAA model to encode on segmented frame chunks one after another to support online recognition. Experiments on two Mandarin ASR datasets show the replacement of RNNs by the self-attention networks yields a 8.4%-10.2% relative character error rate (CER) reduction. In addition, the chunk-hopping mechanism allows the SAA to have only a 2.5% relative CER degradation with a 320ms latency. After jointly training with a self-attention network language model, our SAA model obtains further error rate reduction on multiple datasets. Especially, it achieves 24.12% CER on the Mandarin ASR benchmark (HKUST), exceeding the best end-to-end model by over 2% absolute CER.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.06450](http://arxiv.org/abs/1902.06450)

##### PDF
[http://arxiv.org/pdf/1902.06450](http://arxiv.org/pdf/1902.06450)

