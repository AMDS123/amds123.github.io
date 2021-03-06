---
layout: post
title: "On the Exact Recovery Conditions of 3D Human Motion from 2D Landmark Motion with Sparse Articulated Motion"
date: 2019-07-09 03:34:20
categories: arXiv_CV
tags: arXiv_CV Sparse Tracking
author: Abed Malti
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we address the problem of exact recovery condition in retrieving 3D human motion from 2D landmark motion. We use a skeletal kinematic model to represent the 3D human motion as a vector of angular articulation motion. We address this problem based on the observation that at high tracking rate, regardless of the global rigid motion, only few angular articulations have non-zero motion. We propose a first ideal formulation with $\ell_0$-norm to minimize the cardinal of non-zero angular articulation motion given an equality constraint on the time-differentiation of the reprojection error. The second relaxed formulation relies on an $\ell_1$-norm to minimize the sum of absolute values of the angular articulation motion. This formulation has the advantage of being able to provide 3D motion even in the under-determined case when twice the number of 2D landmarks is smaller than the number of angular articulations. We define a specific property which is the Projective Kinematic Space Property (PKSP) that takes into account the reprojection constraint and the kinematic model. We prove that for the relaxed formulation we are able to recover the exact 3D human motion from 2D landmarks if and only if the PKSP property is verified. We further demonstrate that solving the relaxed formulation provides the same ground-truth solution as the ideal formulation if and only if the PKSP condition is filled. Results with simulated sparse skeletal angular motion show the ability of the proposed method to recover exact location of angular motion. We provide results on publicly available real data (HUMAN3.6M, PANOPTIC and MPI-I3DHP).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.03967](http://arxiv.org/abs/1907.03967)

##### PDF
[http://arxiv.org/pdf/1907.03967](http://arxiv.org/pdf/1907.03967)

