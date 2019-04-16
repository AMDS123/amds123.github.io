---
layout: post
title: "Enhanced Neural Machine Translation by Learning from Draft"
date: 2017-10-04 20:13:43
categories: arXiv_CL
tags: arXiv_CL Attention NMT
author: Aodong Li, Shiyue Zhang, Dong Wang, Thomas Fang Zheng
mathjax: true
---

* content
{:toc}

##### Abstract
Neural machine translation (NMT) has recently achieved impressive results. A potential problem of the existing NMT algorithm, however, is that the decoding is conducted from left to right, without considering the right context. This paper proposes an two-stage approach to solve the problem. In the first stage, a conventional attention-based NMT system is used to produce a draft translation, and in the second stage, a novel double-attention NMT system is used to refine the translation, by looking at the original input as well as the draft translation. This drafting-and-refinement can obtain the right-context information from the draft, hence producing more consistent translations. We evaluated this approach using two Chinese-English translation tasks, one with 44k pairs and 1M pairs respectively. The experiments showed that our approach achieved positive improvements over the conventional NMT system: the improvements are 2.4 and 0.9 BLEU points on the small-scale and large-scale tasks, respectively.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1710.01789](https://arxiv.org/abs/1710.01789)

##### PDF
[https://arxiv.org/pdf/1710.01789](https://arxiv.org/pdf/1710.01789)

