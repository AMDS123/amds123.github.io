---
layout: post
title: "A Roadmap-Path Reshaping Algorithm for Real-Time Motion Planning"
date: 2019-02-28 12:50:25
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Chaoyi Sun (1), Qing Li (1), Li Li (1) ((1) Tsinghua University)
mathjax: true
---

* content
{:toc}

##### Abstract
Real-time motion planning is a vital function of robotic systems. Different from existing roadmap algorithms which first determine the free space and then determine the collision-free path, researchers recently proposed several convex relaxation based smoothing algorithms which first select an initial path to link the starting configuration and the goal configuration and then reshape this path to meet other requirements (e.g., collision-free conditions) by using convex relaxation. However, convex relaxation based smoothing algorithms often fail to give a satisfactory path, since the initial paths are selected randomly. Moreover, the curvature constraints were not considered in the existing convex relaxation based smoothing algorithms. In this paper, we show that we can first grid the whole configuration space to pick a candidate path and reshape this shortest path to meet our goal. This new algorithm inherits the merits of the roadmap algorithms and the convex feasible set algorithm. We further discuss how to meet the curvature constraints by using both the Beamlet algorithm to select a better initial path and an iterative optimization algorithm to adjust the curvature of the path. Theoretical analyzing and numerical testing results show that it can almost surely find a feasible path and use much less time than the recently proposed convex feasible set algorithm.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.11056](http://arxiv.org/abs/1902.11056)

##### PDF
[http://arxiv.org/pdf/1902.11056](http://arxiv.org/pdf/1902.11056)

