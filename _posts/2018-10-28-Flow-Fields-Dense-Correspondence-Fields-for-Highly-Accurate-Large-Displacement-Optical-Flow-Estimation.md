---
layout: post
title: "Flow Fields: Dense Correspondence Fields for Highly Accurate Large Displacement Optical Flow Estimation"
date: 2018-10-28 08:00:11
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse
author: Christian Bailer, Bertram Taetz, Didier Stricker
mathjax: true
---

* content
{:toc}

##### Abstract
Modern large displacement optical flow algorithms usually use an initialization by either sparse descriptor matching techniques or dense approximate nearest neighbor fields. While the latter have the advantage of being dense, they have the major disadvantage of being very outlier-prone as they are not designed to find the optical flow, but the visually most similar correspondence. In this article we present a dense correspondence field approach that is much less outlier-prone and thus much better suited for optical flow estimation than approximate nearest neighbor fields. Our approach does not require explicit regularization, smoothing (like median filtering) or a new data term. Instead we solely rely on patch matching techniques and a novel multi-scale matching strategy. We also present enhancements for outlier filtering. We show that our approach is better suited for large displacement optical flow estimation than modern descriptor matching techniques. We do so by initializing EpicFlow with our approach instead of their originally used state-of-the-art descriptor matching technique. We significantly outperform the original EpicFlow on MPI-Sintel, KITTI 2012, KITTI 2015 and Middlebury. In this extended article of our former conference publication we further improve our approach in matching accuracy as well as runtime and present more experiments and insights.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1703.02563](http://arxiv.org/abs/1703.02563)

##### PDF
[http://arxiv.org/pdf/1703.02563](http://arxiv.org/pdf/1703.02563)

