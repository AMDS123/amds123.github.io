---
layout: post
title: "Simpler and Faster Learning of Adaptive Policies for Simultaneous Translation"
date: 2019-09-04 05:37:36
categories: arXiv_CL
tags: arXiv_CL NMT
author: Baigong Zheng, Renjie Zheng, Mingbo Ma, Liang Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Simultaneous translation is widely useful but remains challenging. Previous work falls into two main categories: (a) fixed-latency policies such as Ma et al. (2019) and (b) adaptive policies such as Gu et al. (2017). The former are simple and effective, but have to aggressively predict future content due to diverging source-target word order; the latter do not anticipate, but suffer from unstable and inefficient training. To combine the merits of both approaches, we propose a simple supervised-learning framework to learn an adaptive policy from oracle READ/WRITE sequences generated from parallel text. At each step, such an oracle sequence chooses to WRITE the next target word if the available source sentence context provides enough information to do so, otherwise READ the next source word. Experiments on German&lt;-&gt;English show that our method, without retraining the underlying NMT model, can learn flexible policies with better BLEU scores and similar latencies compared to previous work.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.01559](http://arxiv.org/abs/1909.01559)

##### PDF
[http://arxiv.org/pdf/1909.01559](http://arxiv.org/pdf/1909.01559)

