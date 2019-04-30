---
layout: post
title: "The Mutex Watershed and its Objective: Efficient, Parameter-Free Image Partitioning"
date: 2019-04-25 17:29:45
categories: arXiv_CV
tags: arXiv_CV Segmentation Relation
author: Steffen Wolf, Alberto Bailoni, Constantin Pape, Nasim Rahaman, Anna Kreshuk, Ullrich K&#xf6;the, Fred A. Hamprecht
mathjax: true
---

* content
{:toc}

##### Abstract
Image partitioning, or segmentation without semantics, is the task of decomposing an image into distinct segments, or equivalently to detect closed contours. Most prior work either requires seeds, one per segment; or a threshold; or formulates the task as multicut / correlation clustering, an NP-hard problem. Here, we propose a greedy algorithm for signed graph partitioning, the "Mutex Watershed". Unlike seeded watershed, the algorithm can accommodate not only attractive but also repulsive cues, allowing it to find a previously unspecified number of segments without the need for explicit seeds or a tunable threshold. We also prove that this simple algorithm solves to global optimality an objective function that is intimately related to the multicut / correlation clustering integer linear programming formulation. The algorithm is deterministic, very simple to implement, and has empirically linearithmic complexity. When presented with short-range attractive and long-range repulsive cues from a deep neural network, the Mutex Watershed gives the best results currently known for the competitive ISBI 2012 EM segmentation benchmark.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.12654](http://arxiv.org/abs/1904.12654)

##### PDF
[http://arxiv.org/pdf/1904.12654](http://arxiv.org/pdf/1904.12654)

