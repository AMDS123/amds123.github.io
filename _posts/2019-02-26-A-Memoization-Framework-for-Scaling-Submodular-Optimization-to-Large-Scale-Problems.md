---
layout: post
title: "A Memoization Framework for Scaling Submodular Optimization to Large Scale Problems"
date: 2019-02-26 19:22:57
categories: arXiv_AI
tags: arXiv_AI Summarization Optimization
author: Rishabh Iyer, Jeff Bilmes
mathjax: true
---

* content
{:toc}

##### Abstract
We are motivated by large scale submodular optimization problems, where standard algorithms that treat the submodular functions in the \emph{value oracle model} do not scale. In this paper, we present a model called the \emph{precomputational complexity model}, along with a unifying memoization based framework, which looks at the specific form of the given submodular function. A key ingredient in this framework is the notion of a \emph{precomputed statistic}, which is maintained in the course of the algorithms. We show that we can easily integrate this idea into a large class of submodular optimization problems including constrained and unconstrained submodular maximization, minimization, difference of submodular optimization, optimization with submodular constraints and several other related optimization problems. Moreover, memoization can be integrated in both discrete and continuous relaxation flavors of algorithms for these problems. We demonstrate this idea for several commonly occurring submodular functions, and show how the precomputational model provides significant speedups compared to the value oracle model. Finally, we empirically demonstrate this for large scale machine learning problems of data subset selection and summarization.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.10176](http://arxiv.org/abs/1902.10176)

##### PDF
[http://arxiv.org/pdf/1902.10176](http://arxiv.org/pdf/1902.10176)

