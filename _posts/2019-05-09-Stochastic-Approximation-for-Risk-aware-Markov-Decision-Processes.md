---
layout: post
title: "Stochastic Approximation for Risk-aware Markov Decision Processes"
date: 2019-05-09 05:22:47
categories: arXiv_AI
tags: arXiv_AI
author: Wenjie Huang, William B. Haskell
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we develop a stochastic approximation type algorithm to solve finite state/action, infinite-horizon, risk-aware Markov decision processes. Our algorithm has two loops. The inner loop computes the risk by solving a stochastic saddle-point problem. We show that several widely investigated risk measures (e.g. conditional value-at-risk, optimized certainty equivalent, and absolute semi-deviation) can be expressed as stochastic saddle-point problems. The outer loop does $Q-$learning to compute an optimal risk-aware policy. We establish the almost sure convergence and convergence rate of our overall algorithm. For an error tolerance $\epsilon&gt;0$ and learning rate $k\in(1/2,\,1]$, the overall convergence rate of our algorithm is $\Omega((\ln(1/\delta\epsilon)/\epsilon^{2})^{1/k}+(\ln(1/\epsilon))^{1/(1-k)})$ with probability at least $1-\delta$

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.04238](http://arxiv.org/abs/1805.04238)

##### PDF
[http://arxiv.org/pdf/1805.04238](http://arxiv.org/pdf/1805.04238)

