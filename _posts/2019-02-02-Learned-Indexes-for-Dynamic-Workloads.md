---
layout: post
title: "Learned Indexes for Dynamic Workloads"
date: 2019-02-02 07:03:00
categories: arXiv_AI
tags: arXiv_AI
author: Chuzhe Tang, Zhiyuan Dong, Minjie Wang, Zhaoguo Wang, Haibo Chen
mathjax: true
---

* content
{:toc}

##### Abstract
The recent proposal of learned index structures opens up a new perspective on how traditional range indexes can be optimized. However, the current learned indexes assume the data distribution is relatively static and the access pattern is uniform, while real-world scenarios consist of skew query distribution and evolving data. In this paper, we demonstrate that the missing consideration of access patterns and dynamic data distribution notably hinders the applicability of learned indexes. To this end, we propose solutions for learned indexes for dynamic workloads (called Doraemon). To improve the latency for skew queries, Doraemon augments the training data with access frequencies. To address the slow model re-training when data distribution shifts, Doraemon caches the previously-trained models and incrementally fine-tunes them for similar access patterns and data distribution. Our preliminary result shows that, Doraemon improves the query latency by 45.1% and reduces the model re-training time to 1/20.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.00655](http://arxiv.org/abs/1902.00655)

##### PDF
[http://arxiv.org/pdf/1902.00655](http://arxiv.org/pdf/1902.00655)

