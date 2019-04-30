---
layout: post
title: "Fast path planning algorithms for Unmanned Aerial Vehicles"
date: 2019-04-28 09:00:17
categories: arXiv_RO
tags: arXiv_RO Adversarial
author: Mohammad Reza Ranjbar Divkoti, Mostafa Nouri-Baygi
mathjax: true
---

* content
{:toc}

##### Abstract
Path planning is a major problem in autonomous vehicles. In recent years, with the increase in applications of Unmanned Aerial Vehicles (UAVs), one of the main challenges is path planning, particularly in adversarial environments. In this paper, we consider the problem of planning a collision-free path for a UAV in a polygonal domain from a source point to a target point. Based on the characteristics of UAVs, we assume two basic limitations on the generated paths: an upper bound on the turning angle at each turning point (maximum turning angle) and a lower bound on the distance between two consecutive turns (minimum route leg length). 
 We describe an algorithm that runs in $O(n^4)$ time and finds a feasible path in accordance with the above limitations, where $n$ is the number of obstacle vertices. As shown by experiments, the output of the algorithm is much close to the shortest path with this requirements. We further demonstrate how to decompose the algorithm into two phases, preprocessing time and query time. In this way, given a fixed start point and a set of obstacles, we can preprocess a data-structure of size $O(n^4)$ in $O(n^4)$ time, such that for any query target point we can find a path with the given requirements in $O(n^2)$ time. Finally, we modify the algorithm to find a feasible (almost shortest) path that reach the target point within a given range of directions.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.12283](http://arxiv.org/abs/1904.12283)

##### PDF
[http://arxiv.org/pdf/1904.12283](http://arxiv.org/pdf/1904.12283)

