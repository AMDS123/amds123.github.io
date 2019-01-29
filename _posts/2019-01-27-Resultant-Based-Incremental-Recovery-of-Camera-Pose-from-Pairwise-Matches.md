---
layout: post
title: "Resultant Based Incremental Recovery of Camera Pose from Pairwise Matches"
date: 2019-01-27 12:13:51
categories: arXiv_CV
tags: arXiv_CV Tracking
author: Yoni Kasten, Meirav Galun, Ronen Basri
mathjax: true
---

* content
{:toc}

##### Abstract
Incremental (online) structure from motion pipelines seek to recover the camera matrix associated with an image $I_n$ given $n-1$ images, $I_1,...,I_{n-1}$, whose camera matrices have already been recovered. In this paper, we introduce a novel solution to the six-point online algorithm to recover the exterior parameters associated with $I_n$. Our algorithm uses just six corresponding pairs of 2D points, extracted each from $I_n$ and from \textit{any} of the preceding $n-1$ images, allowing the recovery of the full six degrees of freedom of the $n$'th camera, and unlike common methods, does not require tracking feature points in three or more images. Our novel solution is based on constructing a Dixon resultant, yielding a solution method that is both efficient and accurate compared to existing solutions. We further use Bernstein's theorem to prove a tight bound on the number of complex solutions. Our experiments demonstrate the utility of our approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.09364](http://arxiv.org/abs/1901.09364)

##### PDF
[http://arxiv.org/pdf/1901.09364](http://arxiv.org/pdf/1901.09364)

