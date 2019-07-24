---
layout: post
title: "Multilevel Monte-Carlo for Solving POMDPs Online"
date: 2019-07-23 03:13:23
categories: arXiv_RO
tags: arXiv_RO
author: Marcus Hoerger, Hanna Kurniawati, Alberto Elfes
mathjax: true
---

* content
{:toc}

##### Abstract
Planning under partial obervability is essential for autonomous robots. A principled way to address such planning problems is the Partially Observable Markov Decision Process (POMDP). Although solving POMDPs is computationally intractable, substantial advancements have been achieved in developing approximate POMDP solvers in the past two decades. However, computing robust solutions for systems with complex dynamics remain challenging. Most on-line solvers rely on a large number of forward-simulations and standard Monte-Carlo methods to compute the expected outcomes of actions the robot can perform. For systems with complex dynamics, e.g., those with non-linear dynamics that admit no closed form solution, even a single forward simulation can be prohibitively expensive. Of course, this issue exacerbates for problems with long planning horizons. This paper aims to alleviate the above difficulty. To this end, we propose a new on-line POMDP solver, called Multilevel POMDP Planner (MLPP), that combines the commonly known Monte-Carlo-Tree-Search with the concept of Multilevel Monte-Carlo to speed-up our capability in generating approximately optimal solutions for POMDPs with complex dynamics. Experiments on four different problems of POMDP-based torque control, navigation and grasping indicate that MLPP substantially outperforms state-of-the-art POMDP solvers.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.09673](http://arxiv.org/abs/1907.09673)

##### PDF
[http://arxiv.org/pdf/1907.09673](http://arxiv.org/pdf/1907.09673)

