---
layout: post
title: "Monotonic Infinite Lookback Attention for Simultaneous Machine Translation"
date: 2019-06-12 15:49:31
categories: arXiv_CL
tags: arXiv_CL Attention NMT
author: Naveen Arivazhagan, Colin Cherry, Wolfgang Macherey, Chung-Cheng Chiu, Semih Yavuz, Ruoming Pang, Wei Li, Colin Raffel
mathjax: true
---

* content
{:toc}

##### Abstract
Simultaneous machine translation begins to translate each source sentence before the source speaker is finished speaking, with applications to live and streaming scenarios. Simultaneous systems must carefully schedule their reading of the source sentence to balance quality against latency. We present the first simultaneous translation system to learn an adaptive schedule jointly with a neural machine translation (NMT) model that attends over all source tokens read thus far. We do so by introducing Monotonic Infinite Lookback (MILk) attention, which maintains both a hard, monotonic attention head to schedule the reading of the source sentence, and a soft attention head that extends from the monotonic head back to the beginning of the source. We show that MILk's adaptive schedule allows it to arrive at latency-quality trade-offs that are favorable to those of a recently proposed wait-k strategy for many latency values.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.05218](http://arxiv.org/abs/1906.05218)

##### PDF
[http://arxiv.org/pdf/1906.05218](http://arxiv.org/pdf/1906.05218)

