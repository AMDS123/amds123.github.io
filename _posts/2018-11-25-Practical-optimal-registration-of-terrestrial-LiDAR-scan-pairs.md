---
layout: post
title: "Practical optimal registration of terrestrial LiDAR scan pairs"
date: 2018-11-25 06:36:28
categories: arXiv_CV
tags: arXiv_CV Survey
author: Zhipeng Cai, Tat-Jun Chin, Alvaro Parra Bustos, Konrad Schindler
mathjax: true
---

* content
{:toc}

##### Abstract
Point cloud registration is a fundamental problem in 3D scanning. In this paper, we address the frequent special case of registering terrestrial LiDAR scans (or, more generally, levelled point clouds). Many current solutions still rely on the Iterative Closest Point (ICP) method or other heuristic procedures, which require good initializations to succeed and/or provide no guarantees of success. On the other hand, exact or optimal registration algorithms can compute the best possible solution without requiring initializations; however, they are currently too slow to be practical in realistic applications. Existing optimal approaches ignore the fact that in routine use the relative rotations between scans are constrained to the azimuth, via the built-in level compensation in LiDAR scanners. We propose a novel, optimal and computationally efficient registration method for this 4DOF scenario. Our approach operates on candidate 3D keypoint correspondences, and contains two main steps: (1) a deterministic selection scheme that significantly reduces the candidate correspondence set in a way that is guaranteed to preserve the optimal solution; and (2) a fast branch-and-bound (BnB) algorithm with a novel polynomial-time subroutine for 1D rotation search, that quickly finds the optimal alignment for the reduced set. We demonstrate the practicality of our method on realistic point clouds from multiple LiDAR surveys.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.09962](https://arxiv.org/abs/1811.09962)

##### PDF
[https://arxiv.org/pdf/1811.09962](https://arxiv.org/pdf/1811.09962)

