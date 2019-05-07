---
layout: post
title: "External Memory based Distributed Generation of Massive Scale Social Networks on Small Clusters"
date: 2012-09-30 11:14:21
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Sandeep Gupta
mathjax: true
---

* content
{:toc}

##### Abstract
Small distributed systems are limited by their main memory to generate massively large graphs. Trivial extension to current graph generators to utilize external memory leads to large amount of random I/O hence do not scale with size. In this work we offer a technique to generate massive scale graphs on small cluster of compute nodes with limited main memory. We develop several distributed and external memory algorithms, primarily, shuffle, relabel, redistribute, and, compressed-sparse-row (csr) convert. The algorithms are implemented in MPI/pthread model to help parallelize the operations across multicores within each core. Using our scheme it is feasible to generate a graph of size $2^{38}$ nodes (scale 38) using only 64 compute nodes. This can be compared with the current scheme would require at least 8192 compute node, assuming 64GB of main memory. Our work has broader implications for external memory graph libraries such as STXXL and graph processing on SSD-based supercomputers such as Dash and Gordon [1][2].

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1210.0187](https://arxiv.org/abs/1210.0187)

##### PDF
[https://arxiv.org/pdf/1210.0187](https://arxiv.org/pdf/1210.0187)

