---
layout: post
title: "Strongly polynomial efficient approximation scheme for segmentation"
date: 2019-02-05 15:30:31
categories: arXiv_AI
tags: arXiv_AI Segmentation Optimization
author: Nikolaj Tatti
mathjax: true
---

* content
{:toc}

##### Abstract
Partitioning a sequence of length $n$ into $k$ coherent segments (Seg) is one of the classic optimization problems. As long as the optimization criterion is additive, Seg can be solved exactly in $O(n^2k)$ time using a classic dynamic program. Due to the quadratic term, computing the exact segmentation may be too expensive for long sequences, which has led to development of approximate solutions. We consider an existing estimation scheme that computes $(1 + \epsilon)$ approximation in polylogarithmic time. We augment this algorithm, making it strongly polynomial. We do this by first solving a slightly different segmentation problem (MaxSeg), where the quality of the segmentation is the maximum penalty of an individual segment. By using this solution to initialize the estimation scheme, we are able to obtain a strongly polynomial algorithm. In addition, we consider a cumulative version of Seg, where we are asked to discover the optimal segmentation for each prefix of the input sequence. We propose a strongly polynomial algorithm that yields $(1 + \epsilon)$ approximation in $O(nk^2 / \epsilon)$ time. Finally, we consider a cumulative version of MaxSeg, and show that we can solve the problem in $O(nk \log k)$ time.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.11170](http://arxiv.org/abs/1805.11170)

##### PDF
[http://arxiv.org/pdf/1805.11170](http://arxiv.org/pdf/1805.11170)

