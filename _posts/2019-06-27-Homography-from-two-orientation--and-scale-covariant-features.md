---
layout: post
title: "Homography from two orientation- and scale-covariant features"
date: 2019-06-27 19:34:08
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Daniel Barath, Zuzana Kukelova
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a geometric interpretation of the angles and scales which the orientation- and scale-covariant feature detectors, e.g. SIFT, provide. Two new general constraints are derived on the scales and rotations which can be used in any geometric model estimation tasks. Using these formulas, two new constraints on homography estimation are introduced. Exploiting the derived equations, a solver for estimating the homography from the minimal number of two correspondences is proposed. Also, it is shown how the normalization of the point correspondences affects the rotation and scale parameters, thus achieving numerically stable results. Due to requiring merely two feature pairs, robust estimators, e.g. RANSAC, do significantly fewer iterations than by using the four-point algorithm. When using covariant features, e.g. SIFT, the information about the scale and orientation is given at no cost. The proposed homography estimation method is tested in a synthetic environment and on publicly available real-world datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.11927](http://arxiv.org/abs/1906.11927)

##### PDF
[http://arxiv.org/pdf/1906.11927](http://arxiv.org/pdf/1906.11927)

