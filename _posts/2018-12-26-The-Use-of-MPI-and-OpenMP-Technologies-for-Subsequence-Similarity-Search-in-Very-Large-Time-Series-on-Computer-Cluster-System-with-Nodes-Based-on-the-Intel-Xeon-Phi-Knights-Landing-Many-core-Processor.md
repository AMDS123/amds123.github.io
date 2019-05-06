---
layout: post
title: "The Use of MPI and OpenMP Technologies for Subsequence Similarity Search in Very Large Time Series on Computer Cluster System with Nodes Based on the Intel Xeon Phi Knights Landing Many-core Processor"
date: 2018-12-26 13:12:19
categories: arXiv_CV
tags: arXiv_CV
author: Yana Kraeva, Mikhail Zymbler
mathjax: true
---

* content
{:toc}

##### Abstract
Nowadays, subsequence similarity search is required in a wide range of time series mining applications: climate modeling, financial forecasts, medical research, etc. In most of these applications, the Dynamic TimeWarping (DTW) similarity measure is used since DTW is empirically confirmed as one of the best similarity measure for most subject domains. Since the DTW measure has a quadratic computational complexity w.r.t. the length of query subsequence, a number of parallel algorithms for various many-core architectures have been developed, namely FPGA, GPU, and Intel MIC. In this article, we propose a new parallel algorithm for subsequence similarity search in very large time series on computer cluster systems with nodes based on Intel Xeon Phi Knights Landing (KNL) many-core processors. Computations are parallelized on two levels as follows: through MPI at the level of all cluster nodes, and through OpenMP within one cluster node. The algorithm involves additional data structures and redundant computations, which make it possible to effectively use the capabilities of vector computations on Phi KNL. Experimental evaluation of the algorithm on real-world and synthetic datasets shows that it is highly scalable.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1812.10302](https://arxiv.org/abs/1812.10302)

##### PDF
[https://arxiv.org/pdf/1812.10302](https://arxiv.org/pdf/1812.10302)

