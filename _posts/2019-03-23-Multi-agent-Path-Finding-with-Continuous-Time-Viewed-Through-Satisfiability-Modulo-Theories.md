---
layout: post
title: "Multi-agent Path Finding with Continuous Time Viewed Through Satisfiability Modulo Theories"
date: 2019-03-23 13:27:32
categories: arXiv_AI
tags: arXiv_AI
author: Pavel Surynek
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses a variant of multi-agent path finding (MAPF) in continuous space and time. We present a new solving approach based on satisfiability modulo theories (SMT) to obtain makespan optimal solutions. The standard MAPF is a task of navigating agents in an undirected graph from given starting vertices to given goal vertices so that agents do not collide with each other in vertices of the graph. In the continuous version (MAPF$^\mathcal{R}$) agents move in an $n$-dimensional Euclidean space along straight lines that interconnect predefined positions. For simplicity, we work with circular omni-directional agents having constant velocities in the 2D plane. As agents can have different sizes and move smoothly along lines, a non-colliding movement along certain lines with small agents can result in a collision if the same movement is performed with larger agents. Our SMT-based approach for MAPF$^\mathcal{R}$ called SMT-CBS$^\mathcal{R}$ reformulates the Conflict-based Search (CBS) algorithm in terms of SMT concepts. We suggest lazy generation of decision variables and constraints. Each time a new conflict is discovered, the underlying encoding is extended with new variables and constraints to eliminate the conflict. We compared SMT-CBS$^\mathcal{R}$ and adaptations of CBS for the continuous variant of MAPF experimentally.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.09820](http://arxiv.org/abs/1903.09820)

##### PDF
[http://arxiv.org/pdf/1903.09820](http://arxiv.org/pdf/1903.09820)

