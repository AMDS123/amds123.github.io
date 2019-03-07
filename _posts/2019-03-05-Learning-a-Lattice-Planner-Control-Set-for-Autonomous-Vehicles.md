---
layout: post
title: "Learning a Lattice Planner Control Set for Autonomous Vehicles"
date: 2019-03-05 20:36:03
categories: arXiv_AI
tags: arXiv_AI Sparse
author: Ryan De Iaco, Stephen L. Smith, Krzysztof Czarnecki
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we introduce a method to compute a sparse lattice planner control set that is suited to a particular task by learning from a representative dataset of vehicle paths. To do this, we use a scoring measure similar to the Fr\'echet distance and propose an algorithm for evaluating a given control set according to the scoring measure. Control actions are then selected from a dense control set according to an objective function that rewards improvements in matching the dataset while also encouraging sparsity. This method is evaluated across several experiments involving real and synthetic datasets, and it is shown to generate smaller control sets when compared to the previous state-of-the-art lattice control set computation technique, with these smaller control sets maintaining a high degree of manoeuvrability in the required task. This results in a planning time speedup of up to 4.31x when using the learned control set over the state-of-the-art computed control set. In addition, we show the learned control sets are better able to capture the driving style of the dataset in terms of path curvature.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.02044](http://arxiv.org/abs/1903.02044)

##### PDF
[http://arxiv.org/pdf/1903.02044](http://arxiv.org/pdf/1903.02044)

