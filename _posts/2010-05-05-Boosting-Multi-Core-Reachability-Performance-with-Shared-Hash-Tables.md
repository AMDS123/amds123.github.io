---
layout: post
title: "Boosting Multi-Core Reachability Performance with Shared Hash Tables"
date: 2010-05-05 00:48:29
categories: arXiv_CV
tags: arXiv_CV
author: Alfons Laarman, Jaco van de Pol, Michael Weber
mathjax: true
---

* content
{:toc}

##### Abstract
This paper focuses on data structures for multi-core reachability, which is a key component in model checking algorithms and other verification methods. A cornerstone of an efficient solution is the storage of visited states. In related work, static partitioning of the state space was combined with thread-local storage and resulted in reasonable speedups, but left open whether improvements are possible. In this paper, we present a scaling solution for shared state storage which is based on a lockless hash table implementation. The solution is specifically designed for the cache architecture of modern CPUs. Because model checking algorithms impose loose requirements on the hash table operations, their design can be streamlined substantially compared to related work on lockless hash tables. Still, an implementation of the hash table presented here has dozens of sensitive performance parameters (bucket size, cache line size, data layout, probing sequence, etc.). We analyzed their impact and compared the resulting speedups with related tools. Our implementation outperforms two state-of-the-art multi-core model checkers (SPIN and DiVinE) by a substantial margin, while placing fewer constraints on the load balancing and search algorithms.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1004.2772](https://arxiv.org/abs/1004.2772)

##### PDF
[https://arxiv.org/pdf/1004.2772](https://arxiv.org/pdf/1004.2772)

