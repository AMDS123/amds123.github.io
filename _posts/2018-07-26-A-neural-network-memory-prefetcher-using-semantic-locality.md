---
layout: post
title: "A neural network memory prefetcher using semantic locality"
date: 2018-07-26 15:14:09
categories: arXiv_CV
tags: arXiv_CV Optimization Prediction Relation
author: Leeor Peled, Uri Weiser, Yoav Etsion
mathjax: true
---

* content
{:toc}

##### Abstract
Accurate memory prefetching is paramount for processor performance, and modern processors employ various techniques to identify and prefetch different memory access patterns. While most modern prefetchers target spatio-temporal patterns by matching memory addresses that are accessed in close proximity (either in space or time), the recently proposed concept of semantic locality views locality as an artifact of the algorithmic level and searches for correlations between memory accesses and program state. While this approach was shown to be effective, capturing semantic locality requires significant associative learning capabilities. In this paper we utilize neural networks for this task. We leverage recent advances in machine learning to propose a neural network prefetcher. We show that by observing program context, this prefetcher can learn distinct memory access patterns that cannot be covered by other state-of-the-art prefetchers. We evaluate the neural network prefetcher over SPEC2006, Graph500, and several microbenchmarks. We show that the prefetcher can deliver an average speedup of 30% for SPEC2006 (up to 2.7x) and up to 4.6x over kernels. We also present a high-level design of our prefetcher, explore the power, energy and area limitations, and propose several optimizations for feasibility. We believe that this line of research can further improve the efficiency of such neural networks and allow harnessing them for additional micro-architectural predictions.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1804.00478](https://arxiv.org/abs/1804.00478)

##### PDF
[https://arxiv.org/pdf/1804.00478](https://arxiv.org/pdf/1804.00478)

