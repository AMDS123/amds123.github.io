---
layout: post
title: "Exponential-Binary State-Space Search"
date: 2019-06-07 06:11:06
categories: arXiv_AI
tags: arXiv_AI
author: Nathan Sturtevant, Malte Helmert
mathjax: true
---

* content
{:toc}

##### Abstract
Iterative deepening search is used in applications where the best cost bound for state-space search is unknown. The iterative deepening process is used to avoid overshooting the appropriate cost bound and doing too much work as a result. However, iterative deepening search also does too much work if the cost bound grows too slowly. This paper proposes a new framework for iterative deepening search called exponential-binary state-space search. The approach interleaves exponential and binary searches to find the desired cost bound, reducing the worst-case overhead from polynomial to logarithmic. Exponential-binary search can be used with bounded depth-first search to improve the worst-case performance of IDA* and with breadth-first heuristic search to improve the worst-case performance of search with inconsistent heuristics.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.02912](http://arxiv.org/abs/1906.02912)

##### PDF
[http://arxiv.org/pdf/1906.02912](http://arxiv.org/pdf/1906.02912)

