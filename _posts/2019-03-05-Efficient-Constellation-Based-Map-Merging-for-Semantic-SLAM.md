---
layout: post
title: "Efficient Constellation-Based Map-Merging for Semantic SLAM"
date: 2019-03-05 20:41:27
categories: arXiv_RO
tags: arXiv_RO SLAM
author: Kristoffer M. Frey, Ted J. Steiner, Jonathan P. How
mathjax: true
---

* content
{:toc}

##### Abstract
Data association in SLAM is fundamentally challenging, and handling ambiguity well is crucial to achieve robust operation in real-world environments. When ambiguous measurements arise, conservatism often mandates that the measurement is discarded or a new landmark is initialized rather than risking an incorrect association. To address the inevitable `duplicate' landmarks that arise, we present an efficient map-merging framework to detect duplicate constellations of landmarks, providing a high-confidence loop-closure mechanism well-suited for object-level SLAM. This approach uses an incrementally-computable approximation of landmark uncertainty that only depends on local information in the SLAM graph, avoiding expensive recovery of the full system covariance matrix. This enables a search based on geometric consistency (GC) (rather than full joint compatibility (JC)) that inexpensively reduces the search space to a handful of `best' hypotheses. Furthermore, we reformulate the commonly-used interpretation tree to allow for more efficient integration of clique-based pairwise compatibility, accelerating the branch-and-bound max-cardinality search. Our method is demonstrated to match the performance of full JC methods at significantly-reduced computational cost, facilitating robust object-based loop-closure over large SLAM problems.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.09646](http://arxiv.org/abs/1809.09646)

##### PDF
[http://arxiv.org/pdf/1809.09646](http://arxiv.org/pdf/1809.09646)

