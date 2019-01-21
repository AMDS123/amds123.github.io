---
layout: post
title: "Linearized ADMM and Fast Nonlocal Denoising for Efficient Plug-and-Play Restoration"
date: 2019-01-18 07:20:32
categories: arXiv_CV
tags: arXiv_CV Regularization Super_Resolution Optimization
author: Unni V. S., Sanjay Ghosh, Kunal N. Chaudhury
mathjax: true
---

* content
{:toc}

##### Abstract
In plug-and-play image restoration, the regularization is performed using powerful denoisers such as nonlocal means (NLM) or BM3D. This is done within the framework of alternating direction method of multipliers (ADMM), where the regularization step is formally replaced by an off-the-shelf denoiser. Each plug-and-play iteration involves the inversion of the forward model followed by a denoising step. In this paper, we present a couple of ideas for improving the efficiency of the inversion and denoising steps. First, we propose to use linearized ADMM, which generally allows us to perform the inversion at a lower cost than standard ADMM. Moreover, we can easily incorporate hard constraints into the optimization framework as a result. Second, we develop a fast algorithm for doubly stochastic NLM, originally proposed by Sreehari et al. (IEEE TCI, 2016), which is about 80x faster than brute-force computation. This particular denoiser can be expressed as the proximal map of a convex regularizer and, as a consequence, we can guarantee convergence for linearized plug-and-play ADMM. We demonstrate the effectiveness of our proposals for super-resolution and single-photon imaging.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.06110](http://arxiv.org/abs/1901.06110)

##### PDF
[http://arxiv.org/pdf/1901.06110](http://arxiv.org/pdf/1901.06110)

