---
layout: post
title: "Globally Optimal Registration based on Fast Branch and Bound"
date: 2019-01-28 13:43:24
categories: arXiv_RO
tags: arXiv_RO
author: Luca Consolini, Mattia Laurini, Marco Locatelli, Dario Lodi Rizzini
mathjax: true
---

* content
{:toc}

##### Abstract
The problem of planar registration consists in finding the transformation that better aligns two point sets. In our setting, the search domain is the set of planar rigid transformations and the objective function is the sum of the distances between each point of the transformed source set and the destination set. We propose a novel Branch and Bound (BnB) method for finding the globally optimal solution. The algorithm recursively splits the search domain into boxes and computes an upper and a lower bound for the minimum value of the restricted problem. We present two main contributions. First, we define two lower bounds. The cheap bound consists of the sum of the minimum distances between each point of source point set, transformed according to current box, and all the candidate points in the destination point set. The relaxation bound corresponds to the solution of a concave relaxation of the objective function based on the linearization of the distance. In large boxes, the cheap bound is a better approximation of the function minimum, while, in small boxes, the relaxation bound is much more accurate. Second, we present a queue-based algorithm that considerably speeds up the computation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.09641](http://arxiv.org/abs/1901.09641)

##### PDF
[http://arxiv.org/pdf/1901.09641](http://arxiv.org/pdf/1901.09641)

