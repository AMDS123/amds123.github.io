---
layout: post
title: "An Abstraction-Free Method for Multi-Robot Temporal Logic Optimal Control Synthesis"
date: 2019-09-02 03:30:45
categories: arXiv_RO
tags: arXiv_RO
author: Xusheng Luo, Yiannis Kantaros, Michael M. Zavlanos
mathjax: true
---

* content
{:toc}

##### Abstract
The majority of existing Linear Temporal Logic (LTL) planning methods rely on the construction of a discrete product automaton, that combines a discrete abstraction of robot mobility and a B$\ddot{\text{u}}$chi automaton that captures the LTL specification. Representing this product automaton as a graph and using graph search techniques, optimal plans that satisfy the LTL task can be synthesized. However, constructing expressive discrete abstractions makes the synthesis problem computationally intractable. In this paper, we propose a new sampling-based LTL planning algorithm that does not require any discrete abstraction of robot mobility. Instead, it builds incrementally trees that explore the product state-space, until a maximum number of iterations is reached or a feasible plan is found. The use of trees makes data storing and manipulation tractable, which significantly increases the scalability of our algorithm. To accelerate the construction of feasible plans, we introduce bias in the sampling process which is guided by transitions in the B$\ddot{\text{u}}$chi automaton that belong to the shortest path to the accepting states. We show that our planning algorithm is probabilistically complete and asymptotically optimal. Finally, we present numerical experiments showing that our method outperforms relevant temporal logic planning methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00526](http://arxiv.org/abs/1909.00526)

##### PDF
[http://arxiv.org/pdf/1909.00526](http://arxiv.org/pdf/1909.00526)

