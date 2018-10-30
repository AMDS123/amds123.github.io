---
layout: post
title: "Objects Localisation from Motion with Constraints"
date: 2018-10-28 11:24:42
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Paul Gay, Alessio Del Bue
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a method to estimate the 3D object position and occupancy given a set of object detections in multiple images and calibrated cameras. This problem is modelled as the estimation of a set of quadrics given 2D conics fit to the object bounding boxes. Although a closed form solution has been recently proposed, the resulting quadrics can be inaccurate or even be non valid ellipsoids in presence of noisy and inaccurate detections. This effect is especially important in case of small baselines, resulting in dramatic failures. To cope with this problem, we propose a set of linear constraints by matching the centres of the reprojected quadrics with the centres of the observed conics. These constraints can be solved with a linear system thus providing a more computationally efficient solution with respect to a non-linear alternative. Experiments on real data show that the proposed approach improves significantly the accuracy and the validity of the ellipsoids.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1803.10474](http://arxiv.org/abs/1803.10474)

##### PDF
[http://arxiv.org/ps/1803.10474](http://arxiv.org/ps/1803.10474)

