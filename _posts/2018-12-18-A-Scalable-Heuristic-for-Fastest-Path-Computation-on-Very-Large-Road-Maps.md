---
layout: post
title: "A Scalable Heuristic for Fastest-Path Computation on Very Large Road Maps"
date: 2018-12-18 15:46:17
categories: arXiv_AI
tags: arXiv_AI
author: Renjie Chen, Craig Gotsman
mathjax: true
---

* content
{:toc}

##### Abstract
Fastest-path queries between two points in a very large road map is an increasingly important primitive in modern transportation and navigation systems, thus very efficient computation of these paths is critical for system performance and throughput. We present a method to compute an effective heuristic for the fastest path travel time between two points on a road map, which can be used to significantly accelerate the classical A* algorithm when computing fastest paths. Our method is based on two hierarchical sets of separators of the map represented by two binary trees. A preprocessing step computes a short vector of values per road junction based on the separator trees, which is then stored with the map and used to efficiently compute the heuristic at the online query stage. We demonstrate experimentally that this method scales well to any map size, providing a better quality heuristic, thus more efficient A* search, for fastest path queries between points at all distances - especially small and medium range - relative to other known heuristics.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.07441](http://arxiv.org/abs/1812.07441)

##### PDF
[http://arxiv.org/pdf/1812.07441](http://arxiv.org/pdf/1812.07441)

