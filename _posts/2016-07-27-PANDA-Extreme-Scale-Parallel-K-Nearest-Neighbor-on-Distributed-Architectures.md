---
layout: post
title: "PANDA: Extreme Scale Parallel K-Nearest Neighbor on Distributed Architectures"
date: 2016-07-27 19:13:07
categories: arXiv_CV
tags: arXiv_CV
author: Md. Mostofa Ali Patwary, Nadathur Rajagopalan Satish, Narayanan Sundaram, Jialin Liu, Peter Sadowski, Evan Racah, Suren Byna, Craig Tull, Wahid Bhimji, Prabhat, Pradeep Dubey
mathjax: true
---

* content
{:toc}

##### Abstract
Computing $k$-Nearest Neighbors (KNN) is one of the core kernels used in many machine learning, data mining and scientific computing applications. Although kd-tree based $O(\log n)$ algorithms have been proposed for computing KNN, due to its inherent sequentiality, linear algorithms are being used in practice. This limits the applicability of such methods to millions of data points, with limited scalability for Big Data analytics challenges in the scientific domain. In this paper, we present parallel and highly optimized kd-tree based KNN algorithms (both construction and querying) suitable for distributed architectures. Our algorithm includes novel approaches for pruning search space and improving load balancing and partitioning among nodes and threads. Using TB-sized datasets from three science applications: astrophysics, plasma physics, and particle physics, we show that our implementation can construct kd-tree of 189 billion particles in 48 seconds on utilizing $\sim$50,000 cores. We also demonstrate computation of KNN of 19 billion queries in 12 seconds. We demonstrate almost linear speedup both for shared and distributed memory computers. Our algorithms outperforms earlier implementations by more than order of magnitude; thereby radically improving the applicability of our implementation to state-of-the-art Big Data analytics problems. In addition, we showcase performance and scalability on the recently released Intel Xeon Phi processor showing that our algorithm scales well even on massively parallel architectures.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1607.08220](https://arxiv.org/abs/1607.08220)

##### PDF
[https://arxiv.org/pdf/1607.08220](https://arxiv.org/pdf/1607.08220)

