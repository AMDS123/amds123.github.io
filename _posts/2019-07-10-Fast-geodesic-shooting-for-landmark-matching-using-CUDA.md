---
layout: post
title: "Fast geodesic shooting for landmark matching using CUDA"
date: 2019-07-10 17:36:57
categories: arXiv_CV
tags: arXiv_CV
author: Jiancong Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Landmark matching via geodesic shooting is a prerequisite task for numerous registration based applications in biomedicine. Geodesic shooting has been developed as one solution approach and formulates the diffeomorphic registration as an optimal control problem under the Hamiltonian framework. In this framework, with landmark positions q0 fixed, the problem solely depends on the initial momentum p0 and evolves through time steps according to a set of constraint equations. Given an initial p0, the algorithm flows q and p forward through time steps, calculates a loss based on point-set mismatch and kinetic energy, back-propagate through time to calculate gradient on p0 and update it. In the forward and backward pass, a pair-wise kernel on landmark points K and additional intermediate terms have to be calculated and marginalized, leading to O(N2) computational complexity, N being the number of points to be registered. For medical image applications, N maybe in the range of thousands, rendering this operation computationally expensive. In this work we ropose a CUDA implementation based on shared memory reduction. Our implementation achieves nearly 2 orders magnitude speed up compared to a naive CPU-based implementation, in addition to improved numerical accuracy as well as better registration results.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.04839](http://arxiv.org/abs/1907.04839)

##### PDF
[http://arxiv.org/pdf/1907.04839](http://arxiv.org/pdf/1907.04839)

