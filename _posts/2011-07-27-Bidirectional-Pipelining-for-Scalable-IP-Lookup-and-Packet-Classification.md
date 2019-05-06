---
layout: post
title: "Bidirectional Pipelining for Scalable IP Lookup and Packet Classification"
date: 2011-07-27 03:01:36
categories: arXiv_CV
tags: arXiv_CV Classification
author: Weirong Jiang, Hoang Le, Viktor K. Prasanna
mathjax: true
---

* content
{:toc}

##### Abstract
Both IP lookup and packet classification in IP routers can be implemented by some form of tree traversal. SRAM-based Pipelining can improve the throughput dramatically. However, previous pipelining schemes result in unbalanced memory allocation over the pipeline stages. This has been identified as a major challenge for scalable pipelined solutions. This paper proposes a flexible bidirectional linear pipeline architecture based on widely-used dual-port SRAMs. A search tree is partitioned, and then mapped onto pipeline stages by a bidirectional fine-grained mapping scheme. We introduce the notion of inversion factor and several heuristics to invert subtrees for memory balancing. Due to its linear structure, the architecture maintains packet input order, and supports non-blocking route updates. Our experiments show that, the architecture can achieve a perfectly balanced memory distribution over the pipeline stages, for both trie-based IP lookup and tree-based multi-dimensional packet classification. For IP lookup, it can store a full backbone routing table with 154419 entries using 2MB of memory, and sustain a high throughput of 1.87 billion packets per second (GPPS), i.e. 0.6 Tbps for the minimum size (40 bytes) packets. The throughput can be improved further to be 2.4 Tbps, by employing caching to exploit the Internet traffic locality.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1107.5372](https://arxiv.org/abs/1107.5372)

##### PDF
[https://arxiv.org/pdf/1107.5372](https://arxiv.org/pdf/1107.5372)

