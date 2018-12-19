---
layout: post
title: "EventNet: Asynchronous recursive event processing"
date: 2018-12-07 09:47:35
categories: arXiv_CV
tags: arXiv_CV Sparse Knowledge Inference
author: Yusuke Sekikawa, Kosuke Hara, Hideo Saito
mathjax: true
---

* content
{:toc}

##### Abstract
Event cameras are bio-inspired vision sensors which mimic retinas to asynchronously report per-pixel intensity change rather than outputting an actual intensity image at regular interval. This new paradigm of image sensor offers significant potential advantages: namely sparse and non-redundant data representation. Unfortunately, however, most of the existing artificial neural network architecture, such as CNN, requires dense synchronous input data, thereby cannot make use of the sparseness of the data. Here, we propose EventNet, to the best of our knowledge, the first trainable neural network architecture, which can directly process asynchronous sparse event signals recursively in an event-wise manner. EventNet models dependence of the output on tens of thousands of causal event recursively by the novel temporal coding scheme. As a result, at inference time, our network operates in the event-wise manner which is realized by very few sum-of-the-product operations---table look-up and temporal feature aggregation---which enabled processing of $1$ mega or more event per second on standard CPU. In experiments using real data, we demonstrate the real-time performance and robustness of our framework.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.07045](http://arxiv.org/abs/1812.07045)

##### PDF
[http://arxiv.org/pdf/1812.07045](http://arxiv.org/pdf/1812.07045)

