---
layout: post
title: "Solution Dominance over Constraint Satisfaction Problems"
date: 2018-12-21 15:54:34
categories: arXiv_AI
tags: arXiv_AI Optimization Relation
author: Tias Guns, Peter J. Stuckey, Guido Tack
mathjax: true
---

* content
{:toc}

##### Abstract
Constraint Satisfaction Problems (CSPs) typically have many solutions that satisfy all constraints. Often though, some solutions are preferred over others, that is, some solutions dominate other solutions. We present solution dominance as a formal framework to reason about such settings. We define Constraint Dominance Problems (CDPs) as CSPs with a dominance relation, that is, a preorder over the solutions of the CSP. This framework captures many well-known variants of constraint satisfaction, including optimization, multi-objective optimization, Max-CSP, minimal models, minimum correction subsets as well as optimization over CP-nets and arbitrary dominance relations. We extend MiniZinc, a declarative language for modeling CSPs, to CDPs by introducing dominance nogoods; these can be derived from dominance relations in a principled way. A generic method for solving arbitrary CDPs incrementally calls a CSP solver and is compatible with any existing solver that supports MiniZinc. This encourages experimenting with different solution dominance relations for a problem, as well as comparing different solvers without having to modify their implementations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.09207](http://arxiv.org/abs/1812.09207)

##### PDF
[http://arxiv.org/pdf/1812.09207](http://arxiv.org/pdf/1812.09207)

