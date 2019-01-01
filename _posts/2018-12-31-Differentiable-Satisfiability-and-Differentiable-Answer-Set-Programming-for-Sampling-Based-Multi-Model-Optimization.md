---
layout: post
title: "Differentiable Satisfiability and Differentiable Answer Set Programming for Sampling-Based Multi-Model Optimization"
date: 2018-12-31 18:39:58
categories: arXiv_AI
tags: arXiv_AI Optimization Inference Gradient_Descent
author: Matthias Nickles
mathjax: true
---

* content
{:toc}

##### Abstract
We propose Differentiable Satisfiability and Differentiable Answer Set Programming (Differentiable SAT/ASP) for multi-model optimization. Models (answer sets or satisfying truth assignments) are sampled using a novel SAT/ASP solving approach which uses a gradient descent-based branching mechanism. Sampling proceeds until the value of a user-defined multi-model cost function reaches a given threshold. As major use cases for our approach we propose distribution-aware model sampling and expressive yet scalable probabilistic logic programming. As our main algorithmic approach to Differentiable SAT/ASP, we introduce an enhancement of the state-of-the-art CDNL/CDCL algorithm for SAT/ASP solving. Additionally, we present alternative algorithms which use an unmodified ASP solver (Clingo/clasp) and map the optimization task to conventional answer set optimization or use so-called propagators. We also report on the open source software DelSAT, a recent prototype implementation of our main algorithm, and on initial experimental results which indicate that DelSATs performance is, when applied to the use case of probabilistic logic inference, on par with Markov Logic Network (MLN) inference performance, despite having advantageous properties compared to MLNs, such as the ability to express inductive definitions and to work with probabilities as weights directly in all cases. Our experiments also indicate that our main algorithm is strongly superior in terms of performance compared to the presented alternative approaches which reduce a common instance of the general problem to regular SAT/ASP.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.11948](http://arxiv.org/abs/1812.11948)

##### PDF
[http://arxiv.org/pdf/1812.11948](http://arxiv.org/pdf/1812.11948)

