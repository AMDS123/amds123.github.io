---
layout: post
title: "Deep Counterfactual Regret Minimization"
date: 2018-11-01 00:07:02
categories: arXiv_AI
tags: arXiv_AI
author: Noam Brown, Adam Lerer, Sam Gross, Tuomas Sandholm
mathjax: true
---

* content
{:toc}

##### Abstract
Counterfactual Regret Minimization (CFR) is the leading algorithm for solving large imperfect-information games. It iteratively traverses the game tree in order to converge to a Nash equilibrium. In order to deal with extremely large games, CFR typically uses domain-specific heuristics to simplify the target game in a process known as abstraction. This simplified game is solved with tabular CFR, and its solution is mapped back to the full game. This paper introduces Deep Counterfactual Regret Minimization (Deep CFR), a form of CFR that obviates the need for abstraction by instead using deep neural networks to approximate the behavior of CFR in the full game. We show that Deep CFR is principled and achieves strong performance in the benchmark game of heads-up no-limit Texas hold'em poker. This is the first successful use of function approximation in CFR for large games.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.00164](http://arxiv.org/abs/1811.00164)

##### PDF
[http://arxiv.org/pdf/1811.00164](http://arxiv.org/pdf/1811.00164)

