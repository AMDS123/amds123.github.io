---
layout: post
title: "A Theoretically Sound Upper Bound on the Triplet Loss for Improving the Efficiency of Deep Distance Metric Learning"
date: 2019-04-18 12:14:50
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Thanh-Toan Do, Toan Tran, Ian Reid, Vijay Kumar, Tuan Hoang, Gustavo Carneiro
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a method that substantially improves the efficiency of deep distance metric learning based on the optimization of the triplet loss function. One epoch of such training process based on a naive optimization of the triplet loss function has a run-time complexity O(N^3), where N is the number of training samples. Such optimization scales poorly, and the most common approach proposed to address this high complexity issue is based on sub-sampling the set of triplets needed for the training process. Another approach explored in the field relies on an ad-hoc linearization (in terms of N) of the triplet loss that introduces class centroids, which must be optimized using the whole training set for each mini-batch - this means that a naive implementation of this approach has run-time complexity O(N^2). This complexity issue is usually mitigated with poor, but computationally cheap, approximate centroid optimization methods. In this paper, we first propose a solid theory on the linearization of the triplet loss with the use of class centroids, where the main conclusion is that our new linear loss represents a tight upper-bound to the triplet loss. Furthermore, based on the theory above, we propose a training algorithm that no longer requires the centroid optimization step, which means that our approach is the first in the field with a guaranteed linear run-time complexity. We show that the training of deep distance metric learning methods using the proposed upper-bound is substantially faster than triplet-based methods, while producing competitive retrieval accuracy results on benchmark datasets (CUB-200-2011 and CAR196).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08720](http://arxiv.org/abs/1904.08720)

##### PDF
[http://arxiv.org/pdf/1904.08720](http://arxiv.org/pdf/1904.08720)

