---
layout: post
title: "On the Tour Towards DPLL and Beyond"
date: 2019-07-11 23:50:09
categories: arXiv_AI
tags: arXiv_AI
author: Pavel Surynek
mathjax: true
---

* content
{:toc}

##### Abstract
We discuss milestones on the tour towards DPLL(MAPF), a multi-agent path finding (MAPF) solver fully integrated with the Davis-Putnam-Logemann-Loveland (DPLL) propositional satisfiability testing algorithm through satisfiability modulo theories (SMT). The task in MAPF is to navigate agents in an undirected graph in a non-colliding way so that each agent eventually reaches its unique goal vertex. At most one agent can reside in a vertex at a time. Agents can move instantaneously by traversing edges provided the movement does not result in a collision. Recently attempts to solve MAPF optimally w.r.t. the sum-of-costs or the makespan based on the reduction of MAPF to propositional satisfiability (SAT) have appeared. The most successful methods rely on building the propositional encoding for the given MAPF instance lazily by a process inspired in the SMT paradigm. The integration of satisfiability testing by the SAT solver and the high-level construction of the encoding is however relatively loose in existing methods. Therefore the ultimate goal of research in this direction is to build the DPLL(MAPF) algorithm, a MAPF solver where the construction of the encoding is fully integrated with the underlying SAT solver. We discuss the current state-of-the-art in MAPF solving and what steps need to be done to get DPLL(MAPF). The advantages of DPLL(MAPF) in terms of its potential to be alternatively parametrized with MAPF$^R$, a theory of continuous MAPF with geometric agents, are also discussed.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.07631](http://arxiv.org/abs/1907.07631)

##### PDF
[http://arxiv.org/pdf/1907.07631](http://arxiv.org/pdf/1907.07631)

