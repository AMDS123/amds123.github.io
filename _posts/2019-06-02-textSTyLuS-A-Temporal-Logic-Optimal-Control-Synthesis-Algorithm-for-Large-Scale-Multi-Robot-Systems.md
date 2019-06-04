---
layout: post
title: "$text{STyLuS}^{*}$: A Temporal Logic Optimal Control Synthesis Algorithm for Large-Scale Multi-Robot Systems"
date: 2019-06-02 02:10:29
categories: arXiv_RO
tags: arXiv_RO
author: Yiannis Kantaros, Michael M. Zavlanos
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a new highly scalable and asymptotically optimal control synthesis algorithm from linear temporal logic specifications, called $\text{STyLuS}^{*}$ for large-Scale optimal Temporal Logic Synthesis, that is designed to solve complex temporal planning problems in large-scale multi-robot systems. Existing planning approaches with temporal logic specifications rely on graph search techniques applied to a product automaton constructed among the robots. In our previous work, we have proposed a more tractable sampling-based algorithm that builds incrementally trees that approximate the state-space and transitions of the synchronous product automaton and does not require sophisticated graph search techniques. Here, we extend our previous work by introducing bias in the sampling process which is guided by transitions in the B$\ddot{\text{u}}$chi automaton that belong to the shortest path to the accepting states. This allows us to synthesize optimal motion plans from product automata with hundreds of orders of magnitude more states than those that existing optimal control synthesis methods or off-the-shelf model checkers can manipulate. We show that $\text{STyLuS}^{*}$ is probabilistically complete and asymptotically optimal and has exponential convergence rate. This is the first time that convergence rate results are provided for sampling-based optimal control synthesis methods. We provide simulation results that show that $\text{STyLuS}^{*}$ can synthesize optimal motion plans for very large multi-robot systems which is impossible using state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.08345](http://arxiv.org/abs/1809.08345)

##### PDF
[http://arxiv.org/pdf/1809.08345](http://arxiv.org/pdf/1809.08345)

