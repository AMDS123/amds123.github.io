---
layout: post
title: "Efficient and Effective Tail Latency Minimization in Multi-Stage Retrieval Systems"
date: 2017-04-20 23:34:13
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Joel Mackenzie, J. Shane Culpepper, Roi Blanco, Matt Crane, Charles L. A. Clarke, Jimmy Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Scalable web search systems typically employ multi-stage retrieval architectures, where an initial stage generates a set of candidate documents that are then pruned and re-ranked. Since subsequent stages typically exploit a multitude of features of varying costs using machine-learned models, reducing the number of documents that are considered at each stage improves latency. In this work, we propose and validate a unified framework that can be used to predict a wide range of performance-sensitive parameters which minimize effectiveness loss, while simultaneously minimizing query latency, across all stages of a multi-stage search architecture. Furthermore, our framework can be easily applied in large-scale IR systems, can be trained without explicitly requiring relevance judgments, and can target a variety of different efficiency-effectiveness trade-offs, making it well suited to a wide range of search scenarios. Our results show that we can reliably predict a number of different parameters on a per-query basis, while simultaneously detecting and minimizing the likelihood of tail-latency queries that exceed a pre-specified performance budget. As a proof of concept, we use the prediction framework to help alleviate the problem of tail-latency queries in early stage retrieval. On the standard ClueWeb09B collection and 31k queries, we show that our new hybrid system can reliably achieve a maximum query time of 200 ms with a 99.99% response time guarantee without a significant loss in overall effectiveness. The solutions presented are practical, and can easily be used in large-scale distributed search engine deployments with a small amount of additional overhead.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1704.03970](https://arxiv.org/abs/1704.03970)

##### PDF
[https://arxiv.org/pdf/1704.03970](https://arxiv.org/pdf/1704.03970)

