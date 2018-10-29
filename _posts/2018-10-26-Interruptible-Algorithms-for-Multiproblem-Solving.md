---
layout: post
title: "Interruptible Algorithms for Multiproblem Solving"
date: 2018-10-26 12:35:58
categories: arXiv_AI
tags: arXiv_AI Knowledge
author: Spyros Angelopoulos, Alejandro Lopez-Ortiz
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we address the problem of designing an interruptible system in a setting in which $n$ problem instances, all equally important, must be solved concurrently. The system involves scheduling executions of contract algorithms (which offer a trade-off between allowable computation time and quality of the solution) in m identical parallel processors. When an interruption occurs, the system must report a solution to each of the $n$ problem instances. The quality of this output is then compared to the best-possible algorithm that has foreknowledge of the interruption time and must, likewise, produce solutions to all $n$ problem instances. This extends the well-studied setting in which only one problem instance is queried at interruption time. 
 In this work we first introduce new measures for evaluating the performance of interruptible systems in this setting. In particular, we propose the deficiency of a schedule as a performance measure that meets the requirements of the problem at hand. We then present a schedule whose performance we prove that is within a small factor from optimal in the general, multiprocessor setting. We also show several lower bounds on the deficiency of schedules on a single processor. More precisely, we prove a general lower bound of (n+1)/n, an improved lower bound for the two-problem setting (n=2), and a tight lower bound for the class of round-robin schedules. Our techniques can also yield a simpler, alternative proof of the main result of [Bernstein et al, IJCAI 2003] concerning the performance of cyclic schedules in multiprocessor environments.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.11291](http://arxiv.org/abs/1810.11291)

##### PDF
[http://arxiv.org/pdf/1810.11291](http://arxiv.org/pdf/1810.11291)

