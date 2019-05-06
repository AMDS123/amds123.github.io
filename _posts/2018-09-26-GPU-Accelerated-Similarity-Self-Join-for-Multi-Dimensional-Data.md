---
layout: post
title: "GPU Accelerated Similarity Self-Join for Multi-Dimensional Data"
date: 2018-09-26 12:04:51
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Michael Gowanlock, Ben Karsin
mathjax: true
---

* content
{:toc}

##### Abstract
The self-join finds all objects in a dataset that are within a search distance, epsilon, of each other; therefore, the self-join is a building block of many algorithms. We advance a GPU-accelerated self-join algorithm targeted towards high dimensional data. The massive parallelism afforded by the GPU and high aggregate memory bandwidth makes the architecture well-suited for data-intensive workloads. We leverage a grid-based, GPU-tailored index to perform range queries. We propose the following optimizations: (i) a trade-off between candidate set filtering and index search overhead by exploiting properties of the index; (ii) reordering the data based on variance in each dimension to improve the filtering power of the index; and (iii) a pruning method for reducing the number of expensive distance calculations. Across most scenarios on real-world and synthetic datasets, our algorithm outperforms the parallel state-of-the-art approach. Exascale systems are converging on heterogeneous distributed-memory architectures. We show that an entity partitioning method can be utilized to achieve a balanced workload, and thus good scalability for multi-GPU or distributed-memory self-joins.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1809.09930](https://arxiv.org/abs/1809.09930)

##### PDF
[https://arxiv.org/pdf/1809.09930](https://arxiv.org/pdf/1809.09930)

