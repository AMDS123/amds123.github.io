---
layout: post
title: "Privacy-Preserving Hierarchical Clustering: Formal Security and Efficient Approximation"
date: 2019-04-09 05:58:28
categories: arXiv_AI
tags: arXiv_AI
author: Xianrui Meng, Dimitrios Papadopoulos, Alina Oprea, Nikos Triandopoulos
mathjax: true
---

* content
{:toc}

##### Abstract
Machine Learning (ML) is widely used for predictive tasks in a number of critical applications. Recently, collaborative or federated learning is a new paradigm that enables multiple parties to jointly learn ML models on their combined datasets. Yet, in most application domains, such as healthcare and security analytics, privacy risks limit entities to individually learning local models over the sensitive datasets they own. In this work, we present the first formal study for privacy-preserving collaborative hierarchical clustering, overall featuring scalable cryptographic protocols that allow two parties to privately compute joint clusters on their combined sensitive datasets. First, we provide a formal definition that balances accuracy and privacy, and we present a provably secure protocol along with an optimized version for single linkage clustering. Second, we explore the integration of our protocol with existing approximation algorithms for hierarchical clustering, resulting in a protocol that can efficiently scale to very large datasets. Finally, we provide a prototype implementation and experimentally evaluate the feasibility and efficiency of our approach on synthetic and real datasets, with encouraging results. For example, for a dataset of one million records and 10 dimensions, our optimized privacy-preserving approximation protocol requires 35 seconds for end-to-end execution, just 896KB of communication, and achieves 97.09% accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04475](http://arxiv.org/abs/1904.04475)

##### PDF
[http://arxiv.org/pdf/1904.04475](http://arxiv.org/pdf/1904.04475)

