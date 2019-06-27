---
layout: post
title: "Sharing Attention Weights for Fast Transformer"
date: 2019-06-26 12:27:05
categories: arXiv_CL
tags: arXiv_CL Attention NMT Inference
author: Tong Xiao, Yinqiao Li, Jingbo Zhu, Zhengtao Yu, Tongran Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, the Transformer machine translation system has shown strong results by stacking attention layers on both the source and target-language sides. But the inference of this model is slow due to the heavy use of dot-product attention in auto-regressive decoding. In this paper we speed up Transformer via a fast and lightweight attention model. More specifically, we share attention weights in adjacent layers and enable the efficient re-use of hidden states in a vertical manner. Moreover, the sharing policy can be jointly learned with the MT model. We test our approach on ten WMT and NIST OpenMT tasks. Experimental results show that it yields an average of 1.3X speed-up (with almost no decrease in BLEU) on top of a state-of-the-art implementation that has already adopted a cache for fast inference. Also, our approach obtains a 1.8X speed-up when it works with the \textsc{Aan} model. This is even 16 times faster than the baseline with no use of the attention cache.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.11024](http://arxiv.org/abs/1906.11024)

##### PDF
[http://arxiv.org/pdf/1906.11024](http://arxiv.org/pdf/1906.11024)

