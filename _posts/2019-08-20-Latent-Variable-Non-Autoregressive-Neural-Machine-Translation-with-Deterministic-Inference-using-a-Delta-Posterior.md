---
layout: post
title: "Latent-Variable Non-Autoregressive Neural Machine Translation with Deterministic Inference using a Delta Posterior"
date: 2019-08-20 06:14:18
categories: arXiv_CL
tags: arXiv_CL Inference
author: Raphael Shu, Jason Lee, Hideki Nakayama, Kyunghyun Cho
mathjax: true
---

* content
{:toc}

##### Abstract
Although neural machine translation models reached high translation quality, the autoregressive nature makes inference difficult to parallelize and leads to high translation latency. Inspired by recent refinement-based approaches, we propose a latent-variable non-autoregressive model with continuous latent variables and deterministic inference procedure. In contrast to existing approaches, we use a deterministic iterative inference algorithm to find a target sequence that maximizes the lowerbound to the log-probability. During inference, the length of translation automatically adapts itself. Our experiments show that the lowerbound can be greatly increased by running the inference algorithm for only one step, resulting in significantly improved translation quality. Our proposed model closes the gap between non-autoregressive and autoregressive approaches on ASPEC Ja-En dataset with 7.8x faster decoding. On WMT'14 En-De dataset, our model narrows the performance gap with autoregressive baseline down to 2.0 BLEU points with 12.5x speedup.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.07181](http://arxiv.org/abs/1908.07181)

##### PDF
[http://arxiv.org/pdf/1908.07181](http://arxiv.org/pdf/1908.07181)

