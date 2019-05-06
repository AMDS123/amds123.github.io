---
layout: post
title: "Accelerating Direction-Optimized Breadth First Search on Hybrid Architectures"
date: 2015-10-02 07:16:32
categories: arXiv_CV
tags: arXiv_CV
author: Scott Sallinen, Abdullah Gharaibeh, Matei Ripeanu
mathjax: true
---

* content
{:toc}

##### Abstract
Large scale-free graphs are famously difficult to process efficiently: the skewed vertex degree distribution makes it difficult to obtain balanced partitioning. Our research instead aims to turn this into an advantage by partitioning the workload to match the strength of the individual computing elements in a Hybrid, GPU-accelerated architecture. As a proof of concept we focus on the direction-optimized breadth first search algorithm. We present the key graph partitioning, workload allocation, and communication strategies required for massive concurrency and good overall performance. We show that exploiting specialization enables gains as high as 2.4x in terms of time-to-solution and 2.0x in terms of energy efficiency by adding 2 GPUs to a 2 CPU-only baseline, for synthetic graphs with up to 16 Billion undirected edges as well as for large real-world graphs. We also show that, for a capped energy envelope, it is more efficient to add a GPU than an additional CPU. Finally, our performance would place us at the top of today's [Green]Graph500 challenges for Scale29 graphs.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1503.04359](https://arxiv.org/abs/1503.04359)

##### PDF
[https://arxiv.org/pdf/1503.04359](https://arxiv.org/pdf/1503.04359)

