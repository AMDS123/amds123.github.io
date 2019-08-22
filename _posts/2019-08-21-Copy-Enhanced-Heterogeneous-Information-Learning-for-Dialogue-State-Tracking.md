---
layout: post
title: "Copy-Enhanced Heterogeneous Information Learning for Dialogue State Tracking"
date: 2019-08-21 04:05:54
categories: arXiv_CL
tags: arXiv_CL Ontology Tracking
author: Qingbin Liu, Shizhu He, Kang Liu, Shengping Liu, Jun Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Dialogue state tracking (DST) is an essential component in task-oriented dialogue systems, which estimates user goals at every dialogue turn. However, most previous approaches usually suffer from the following problems. Many discriminative models, especially end-to-end (E2E) models, are difficult to extract unknown values that are not in the candidate ontology; previous generative models, which can extract unknown values from utterances, degrade the performance due to ignoring the semantic information of pre-defined ontology. Besides, previous generative models usually need a hand-crafted list to normalize the generated values. How to integrate the semantic information of pre-defined ontology and dialogue text (heterogeneous texts) to generate unknown values and improve performance becomes a severe challenge. In this paper, we propose a Copy-Enhanced Heterogeneous Information Learning model with multiple encoder-decoder for DST (CEDST), which can effectively generate all possible values including unknown values by copying values from heterogeneous texts. Meanwhile, CEDST can effectively decompose the large state space into several small state spaces through multi-encoder, and employ multi-decoder to make full use of the reduced spaces to generate values. Multi-encoder-decoder architecture can significantly improve performance. Experiments show that CEDST can achieve state-of-the-art results on two datasets and our constructed datasets with many unknown values.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.07705](http://arxiv.org/abs/1908.07705)

##### PDF
[http://arxiv.org/pdf/1908.07705](http://arxiv.org/pdf/1908.07705)

