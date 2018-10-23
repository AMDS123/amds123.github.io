---
layout: post
title: "Real-time Neural-based Input Method"
date: 2018-10-19 12:57:37
categories: arXiv_CL
tags: arXiv_CL RNN Language_Model Prediction
author: Jiali Yao, Raphael Shu, Xinjian Li, Katsutoshi Ohtsuki, Hideki Nakayama
mathjax: true
---

* content
{:toc}

##### Abstract
The input method is an essential service on every mobile and desktop devices that provides text suggestions. It converts sequential keyboard inputs to the characters in its target language, which is indispensable for Japanese and Chinese users. Due to critical resource constraints and limited network bandwidth of the target devices, applying neural models to input method is not well explored. In this work, we apply a LSTM-based language model to input method and evaluate its performance for both prediction and conversion tasks with Japanese BCCWJ corpus. We articulate the bottleneck to be the slow softmax computation during conversion. To solve the issue, we propose incremental softmax approximation approach, which computes softmax with a selected subset vocabulary and fix the stale probabilities when the vocabulary is updated in future steps. We refer to this method as incremental selective softmax. The results show a two order speedup for the softmax computation when converting Japanese input sequences with a large vocabulary, reaching real-time speed on commodity CPU. We also exploit the model compressing potential to achieve a 92% model size reduction without losing accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.09309](http://arxiv.org/abs/1810.09309)

##### PDF
[http://arxiv.org/pdf/1810.09309](http://arxiv.org/pdf/1810.09309)

