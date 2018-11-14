---
layout: post
title: "Attentive Convolution: Equipping CNNs with RNN-style Attention Mechanisms"
date: 2018-11-13 16:12:16
categories: arXiv_CL
tags: arXiv_CL Sentiment Attention CNN Represenation_Learning RNN
author: Wenpeng Yin, Hinrich Sch&#xfc;tze
mathjax: true
---

* content
{:toc}

##### Abstract
In NLP, convolutional neural networks (CNNs) have benefited less than recurrent neural networks (RNNs) from attention mechanisms. We hypothesize that this is because the attention in CNNs has been mainly implemented as attentive pooling (i.e., it is applied to pooling) rather than as attentive convolution (i.e., it is integrated into convolution). Convolution is the differentiator of CNNs in that it can powerfully model the higher-level representation of a word by taking into account its local fixed-size context in the input text t^x. In this work, we propose an attentive convolution network, ATTCONV. It extends the context scope of the convolution operation, deriving higher-level features for a word not only from local context, but also information extracted from nonlocal context by the attention mechanism commonly used in RNNs. This nonlocal context can come (i) from parts of the input text t^x that are distant or (ii) from extra (i.e., external) contexts t^y. Experiments on sentence modeling with zero-context (sentiment analysis), single-context (textual entailment) and multiple-context (claim verification) demonstrate the effectiveness of ATTCONV in sentence representation learning with the incorporation of context. In particular, attentive convolution outperforms attentive pooling and is a strong competitor to popular attentive RNNs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1710.00519](http://arxiv.org/abs/1710.00519)

##### PDF
[http://arxiv.org/pdf/1710.00519](http://arxiv.org/pdf/1710.00519)

