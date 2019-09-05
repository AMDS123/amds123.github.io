---
layout: post
title: "Exploration Without Global Consistency Using Local Volume Consolidation"
date: 2019-09-03 19:53:21
categories: arXiv_RO
tags: arXiv_RO
author: Titus Cieslewski, Andreas Ziegler, Davide Scaramuzza
mathjax: true
---

* content
{:toc}

##### Abstract
In exploration, the goal is to build a map of an unknown environment. Most state-of-the-art approaches use map representations that require drift-free state estimates to function properly. Real-world state estimators, however, exhibit drift. In this paper, we present a 2D map representation for exploration that is robust to drift. Rather than a global map, it uses local metric volumes connected by relative pose estimates. This pose-graph does not need to be globally consistent. Overlaps between the volumes are resolved locally, rather than on the faulty estimate of space. We demonstrate our representation with a frontier-based exploration approach, evaluate it under different conditions and compare it with a commonly-used grid-based representation. We show that, at the cost of longer exploration time, using the proposed representation allows full coverage of space even for very large drift in the state estimate, contrary to the grid-based representation. The system is validated in a real world experiment and we discuss its extension to 3D.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.01423](http://arxiv.org/abs/1909.01423)

##### PDF
[http://arxiv.org/pdf/1909.01423](http://arxiv.org/pdf/1909.01423)

