---
layout: post
title: "Road-network-based Rapid Geolocalization"
date: 2019-06-25 01:54:21
categories: arXiv_AI
tags: arXiv_AI
author: Yongfei Li, Dongfang Yang, Shicheng Wang, Hao He
mathjax: true
---

* content
{:toc}

##### Abstract
It has always been a research hotspot to use geographic information to assist the navigation of unmanned aerial vehicles. In this paper, a road-network-based localization method is proposed. We match roads in the measurement images to the reference road vector map, and realize successful localization on areas as large as a whole city. The road network matching problem is treated as a point cloud registration problem under two-dimensional projective transformation, and solved under a hypothesise-and-test framework. To deal with the projective point cloud registration problem, a global projective invariant feature is proposed, which consists of two road intersections augmented with the information of their tangents. We call it two road intersections tuple. We deduce the closed-form solution for determining the alignment transformation from a pair of matching two road intersections tuples. In addition, we propose the necessary conditions for the tuples to match. This can reduce the candidate matching tuples, thus accelerating the search to a great extent. We test all the candidate matching tuples under a hypothesise-and-test framework to search for the best match. The experiments show that our method can localize the target area over an area of 400 within 1 second on a single cpu.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.12174](http://arxiv.org/abs/1906.12174)

##### PDF
[http://arxiv.org/pdf/1906.12174](http://arxiv.org/pdf/1906.12174)

