---
layout: post
title: "Application-Driven Near-Data Processing for Similarity Search"
date: 2017-07-10 16:56:51
categories: arXiv_CV
tags: arXiv_CV Recommendation
author: Vincent T. Lee, Amrita Mazumdar, Carlo C. del Mundo, Armin Alaghi, Luis Ceze, Mark Oskin
mathjax: true
---

* content
{:toc}

##### Abstract
Similarity search is a key to a variety of applications including content-based search for images and video, recommendation systems, data deduplication, natural language processing, computer vision, databases, computational biology, and computer graphics. At its core, similarity search manifests as k-nearest neighbors (kNN), a computationally simple primitive consisting of highly parallel distance calculations and a global top-k sort. However, kNN is poorly supported by today's architectures because of its high memory bandwidth requirements. This paper proposes an application-driven near-data processing accelerator for similarity search: the Similarity Search Associative Memory (SSAM). By instantiating compute units close to memory, SSAM benefits from the higher memory bandwidth and density exposed by emerging memory technologies. We evaluate the SSAM design down to layout on top of the Micron hybrid memory cube (HMC), and show that SSAM can achieve up to two orders of magnitude area-normalized throughput and energy efficiency improvement over multicore CPUs; we also show SSAM is faster and more energy efficient than competing GPUs and FPGAs. Finally, we show that SSAM is also useful for other data intensive tasks like kNN index construction, and can be generalized to semantically function as a high capacity content addressable memory.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1606.03742](https://arxiv.org/abs/1606.03742)

##### PDF
[https://arxiv.org/pdf/1606.03742](https://arxiv.org/pdf/1606.03742)

