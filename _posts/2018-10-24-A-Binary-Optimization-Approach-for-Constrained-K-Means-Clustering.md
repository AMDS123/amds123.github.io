---
layout: post
title: "A Binary Optimization Approach for Constrained K-Means Clustering"
date: 2018-10-24 00:11:33
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Huu Le, Anders Eriksson, Thanh-Toan Do, Michael Milford
mathjax: true
---

* content
{:toc}

##### Abstract
K-Means clustering still plays an important role in many computer vision problems. While the conventional Lloyd method, which alternates between centroid update and cluster assignment, is primarily used in practice, it may converge to a solution with empty clusters. Furthermore, some applications may require the clusters to satisfy a specific set of constraints, e.g., cluster sizes, must-link/cannot-link. Several methods have been introduced to solve constrained K-Means clustering. Due to the non-convex nature of K-Means, however, existing approaches may result in sub-optimal solutions that poorly approximate the true clusters. In this work, we provide a new perspective to tackle this problem. Particularly, we reconsider constrained K-Means as a Binary Optimization Problem and propose a novel optimization scheme to search for feasible solutions in the binary domain. This approach allows us to solve constrained K-Means where multiple types of constraints can be simultaneously enforced. Experimental results on synthetic and real datasets show that our method provides better clustering accuracy with faster runtime compared to several commonly used techniques.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.10134](http://arxiv.org/abs/1810.10134)

##### PDF
[http://arxiv.org/pdf/1810.10134](http://arxiv.org/pdf/1810.10134)

