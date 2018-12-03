---
layout: post
title: "Runtime Analysis for Self-adaptive Mutation Rates"
date: 2018-11-30 14:38:05
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Benjamin Doerr, Carsten Witt, Jing Yang
mathjax: true
---

* content
{:toc}

##### Abstract
We propose and analyze a self-adaptive version of the $(1,\lambda)$ evolutionary algorithm in which the current mutation rate is part of the individual and thus also subject to mutation. A rigorous runtime analysis on the OneMax benchmark function reveals that a simple local mutation scheme for the rate leads to an expected optimization time (number of fitness evaluations) of $O(n\lambda/\log\lambda+n\log n)$ when $\lambda$ is at least $C \ln n$ for some constant $C &gt; 0$. For all values of $\lambda \ge C \ln n$, this performance is asymptotically best possible among all $\lambda$-parallel mutation-based unbiased black-box algorithms. 
 Our result shows that self-adaptation in evolutionary computation can find complex optimal parameter settings on the fly. At the same time, it proves that a relatively complicated self-adjusting scheme for the mutation rate proposed by Doerr, Gie{\ss}en, Witt, and Yang~(GECCO~2017) can be replaced by our simple endogenous scheme. 
 On the technical side, the paper contributes new tools for the analysis of two-dimensional drift processes arising in the analysis of dynamic parameter choices in EAs, including bounds on occupation probabilities in processes with non-constant drift.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.12824](http://arxiv.org/abs/1811.12824)

##### PDF
[http://arxiv.org/pdf/1811.12824](http://arxiv.org/pdf/1811.12824)

