---
layout: post
title: "Improving Long Distance Slot Carryover in Spoken Dialogue Systems"
date: 2019-06-04 01:13:20
categories: arXiv_CL
tags: arXiv_CL Attention Tracking
author: Tongfei Chen, Chetan Naik, Hua He, Pushpendre Rastogi, Lambert Mathias
mathjax: true
---

* content
{:toc}

##### Abstract
Tracking the state of the conversation is a central component in task-oriented spoken dialogue systems. One such approach for tracking the dialogue state is slot carryover, where a model makes a binary decision if a slot from the context is relevant to the current turn. Previous work on the slot carryover task used models that made independent decisions for each slot. A close analysis of the results show that this approach results in poor performance over longer context dialogues. In this paper, we propose to jointly model the slots. We propose two neural network architectures, one based on pointer networks that incorporate slot ordering information, and the other based on transformer networks that uses self attention mechanism to model the slot interdependencies. Our experiments on an internal dialogue benchmark dataset and on the public DSTC2 dataset demonstrate that our proposed models are able to resolve longer distance slot references and are able to achieve competitive performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.01149](http://arxiv.org/abs/1906.01149)

##### PDF
[http://arxiv.org/pdf/1906.01149](http://arxiv.org/pdf/1906.01149)

