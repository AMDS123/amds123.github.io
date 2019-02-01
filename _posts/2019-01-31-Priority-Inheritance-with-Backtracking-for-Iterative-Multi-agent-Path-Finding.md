---
layout: post
title: "Priority Inheritance with Backtracking for Iterative Multi-agent Path Finding"
date: 2019-01-31 09:27:22
categories: arXiv_RO
tags: arXiv_RO Tracking
author: Keisuke Okumura, Manao Machida, Xavier D&#xe9;fago, Yasumasa Tamura
mathjax: true
---

* content
{:toc}

##### Abstract
The Multi-agent Path Finding (MAPF) problem consists of all agents having to move to their own destinations while avoiding collisions. In practical applications of the problem, such as for navigation in an automated warehouse, MAPF must be solved iteratively. We present a novel approach for iterative MAPF, that we call Priority Inheritance with Backtracking (PIBT). In our method, a unique priority is assigned to each agent every timestep, so that movements are prioritized. Priority inheritance aims to deal effectively with priority inversion in path adjustment in a small time window. When a low-priority agent X impedes the movement of a higher-priority agent Y, agent X inherits the higher-priority of agent Y. Priority inheritance can be applied iteratively and the backtracking protocol prevents the presence of a stuck agent. We proved that, regardless of the number of agents, all agents are guaranteed to reach their own destinations within a finite time after the destinations are given, as long as the environment is a biconnected graph. Our implementation of PIBT can be fully decentralized in the sense that it has no single point of control and does not rely on global communication (all communication is local within 2-hops). Experimental results over various domains demonstrate that the practicality of the proposed algorithm which is shown to produce sophisticated coordination.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.11282](http://arxiv.org/abs/1901.11282)

##### PDF
[http://arxiv.org/pdf/1901.11282](http://arxiv.org/pdf/1901.11282)

