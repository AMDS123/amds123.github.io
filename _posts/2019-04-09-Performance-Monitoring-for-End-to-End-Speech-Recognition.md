---
layout: post
title: "Performance Monitoring for End-to-End Speech Recognition"
date: 2019-04-09 20:35:25
categories: arXiv_CL
tags: arXiv_CL Attention Speech_Recognition RNN Prediction Recognition
author: Ruizhi Li, Gregory Sell, Hynek Hermansky
mathjax: true
---

* content
{:toc}

##### Abstract
Measuring performance of an automatic speech recognition (ASR) system without ground-truth could be beneficial in many scenarios, especially with data from unseen domains, where performance can be highly inconsistent. In conventional ASR systems, several performance monitoring (PM) techniques have been well-developed to monitor performance by looking at tri-phone posteriors or pre-softmax activations from neural network acoustic modeling. However, strategies for monitoring more recently developed end-to-end ASR systems have not yet been explored, and so that is the focus of this paper. We adapt previous PM measures (Entropy, M-measure and Auto-encoder) and apply our proposed RNN predictor in the end-to-end setting. These measures utilize the decoder output layer and attention probability vectors, and their predictive power is measured with simple linear models. Our findings suggest that decoder-level features are more feasible and informative than attention-level probabilities for PM measures, and that M-measure on the decoder posteriors achieves the best overall predictive performance with an average prediction error 8.8%. Entropy measures and RNN-based prediction also show competitive predictability, especially for unseen conditions.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04896](http://arxiv.org/abs/1904.04896)

##### PDF
[http://arxiv.org/pdf/1904.04896](http://arxiv.org/pdf/1904.04896)

