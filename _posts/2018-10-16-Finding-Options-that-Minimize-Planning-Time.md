---
layout: post
title: "Finding Options that Minimize Planning Time"
date: 2018-10-16 23:24:18
categories: arXiv_AI
tags: arXiv_AI
author: Yuu Jinnai, David Abel, Michael Littman, George Konidaris
mathjax: true
---

* content
{:toc}

##### Abstract
While adding temporally abstract actions, or options, to an agent's action repertoire can often accelerate learning and planning, existing approaches for determining which specific options to add are largely heuristic. We aim to formalize the problem of selecting the optimal set of options for planning, in two contexts: 1) finding the set of $k$ options that minimize the number of value-iteration passes until convergence, and 2) computing the smallest set of options so that planning converges in less than a given maximum of $\ell$ value-iteration passes. We first show that both problems are NP-hard. We then provide a polynomial-time approximation algorithm for computing the optimal options for tasks with bounded return and goal states. We prove that the algorithm has bounded suboptimality for deterministic tasks. Finally, we empirically evaluate its performance against both the optimal options and a representative collection of heuristic approaches in simple grid-based domains including the classic four rooms problem.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.07311](http://arxiv.org/abs/1810.07311)

##### PDF
[http://arxiv.org/pdf/1810.07311](http://arxiv.org/pdf/1810.07311)

