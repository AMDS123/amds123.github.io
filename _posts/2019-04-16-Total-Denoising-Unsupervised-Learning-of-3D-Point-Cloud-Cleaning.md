---
layout: post
title: "Total Denoising: Unsupervised Learning of 3D Point Cloud Cleaning"
date: 2019-04-16 12:11:26
categories: arXiv_CV
tags: arXiv_CV
author: Pedro Hermosilla, Tobias Ritschel, Timo Ropinski
mathjax: true
---

* content
{:toc}

##### Abstract
We show that denoising of 3D point clouds can be learned unsupervised, directly from noisy 3D point cloud data only. This is achieved by extending recent ideas from learning of unsupervised image denoisers to unstructured 3D point clouds. Unsupervised image denoisers operate under the assumption that a noisy pixel observation is a random realization of a distribution around a clean pixel value, which allows appropriate learning on this distribution to eventually converge to the correct value. Regrettably, this assumption is not valid for unstructured points: 3D point clouds are subject to total noise, i. e., deviations in all coordinates, with no reliable pixel grid. Thus, an observation can be the realization of an entire manifold of clean 3D points, which makes a na\"ive extension of unsupervised image denoisers to 3D point clouds impractical. Overcoming this, we introduce a spatial prior term, that steers converges to the unique closest out of the many possible modes on a manifold. Our results demonstrate unsupervised denoising performance similar to that of supervised learning with clean data when given enough training examples - whereby we do not need any pairs of noisy and clean training data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.07615](http://arxiv.org/abs/1904.07615)

##### PDF
[http://arxiv.org/pdf/1904.07615](http://arxiv.org/pdf/1904.07615)

