---
layout: post
title: "Adaptive Parallel Iterative Deepening Search"
date: 2011-05-27 01:47:18
categories: arXiv_CV
tags: arXiv_CV
author: D. J. Cook, R. C. Varnell
mathjax: true
---

* content
{:toc}

##### Abstract
Many of the artificial intelligence techniques developed to date rely on heuristic search through large spaces. Unfortunately, the size of these spaces and the corresponding computational effort reduce the applicability of otherwise novel and effective algorithms. A number of parallel and distributed approaches to search have considerably improved the performance of the search process. Our goal is to develop an architecture that automatically selects parallel search strategies for optimal performance on a variety of search problems. In this paper we describe one such architecture realized in the Eureka system, which combines the benefits of many different approaches to parallel heuristic search. Through empirical and theoretical analyses we observe that features of the problem space directly affect the choice of optimal parallel search strategy. We then employ machine learning techniques to select the optimal parallel search strategy for a given problem space. When a new search task is input to the system, Eureka uses features describing the search space and the chosen architecture to automatically select the appropriate search strategy. Eureka has been tested on a MIMD parallel processor, a distributed network of workstations, and a single workstation using multithreading. Results generated from fifteen puzzle problems, robot arm motion problems, artificial search spaces, and planning problems indicate that Eureka outperforms any of the tested strategies used exclusively for all problem instances and is able to greatly reduce the search time for these applications.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1105.5447](https://arxiv.org/abs/1105.5447)

##### PDF
[https://arxiv.org/pdf/1105.5447](https://arxiv.org/pdf/1105.5447)

