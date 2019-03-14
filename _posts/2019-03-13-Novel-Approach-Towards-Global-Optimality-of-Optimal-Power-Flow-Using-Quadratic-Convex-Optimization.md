---
layout: post
title: "Novel Approach Towards Global Optimality of Optimal Power Flow Using Quadratic Convex Optimization"
date: 2019-03-13 10:18:20
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Hadrien Godard (CEDRIC - OC, UMA), Sourour Elloumi (CEDRIC), Am&#xe9;lie Lambert (CEDRIC), Jean Maeght, Manuel Ruiz (G-SCOP_OC)
mathjax: true
---

* content
{:toc}

##### Abstract
Optimal Power Flow (OPF) can be modeled as a non-convex Quadratically Constrained Quadratic Program (QCQP). Our purpose is to solve OPF to global optimality. To this end, we specialize the Mixed-Integer Quadratic Convex Reformulation method (MIQCR) to (OPF). This is a method in two steps. First, a Semi-Definite Programming (SDP) relaxation of (OPF) is solved. Then the optimal dual variables of this relaxation are used to reformulate OPF into an equivalent new quadratic program, where all the non-convexity is moved to one additional constraint. In the second step, this reformulation is solved within a branch-and-bound algorithm, where at each node a quadratic and convex relaxation of the reformulated problem, obtained by relaxing the non-convex added constraint, is solved. The key point of our approach is that the lower bound at the root node of the branch-and-bound tree is equal to the SDP relaxation value. We test this method on several OPF cases, from two-bus networks to more-than-a-thousand-buses networks from the MAT-POWER repository. Our first results are very encouraging.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.05390](http://arxiv.org/abs/1903.05390)

##### PDF
[http://arxiv.org/pdf/1903.05390](http://arxiv.org/pdf/1903.05390)

