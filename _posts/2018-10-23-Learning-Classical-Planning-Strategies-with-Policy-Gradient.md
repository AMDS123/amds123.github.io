---
layout: post
title: "Learning Classical Planning Strategies with Policy Gradient"
date: 2018-10-23 15:44:44
categories: arXiv_AI
tags: arXiv_AI
author: Pawel Gomoluch, Dalal Alrajeh, Alessandra Russo
mathjax: true
---

* content
{:toc}

##### Abstract
A common paradigm in classical planning is heuristic forward search. Forward search planners often rely on relatively simple best-first search algorithm, which remains fixed throughout the search process. In this paper, we introduce a novel search framework capable of alternating between several forward search approaches while solving a particular planning problem. Selection of the approach is performed using a trainable stochastic policy. This enables tailoring the search strategy to a particular distribution of planning problems and a selected performance metric, such as the IPC score or running time. We construct a strategy space using five search algorithms and a two-dimensional representation of the planner's state. Strategies are then trained on randomly generated planning problems using policy gradient. Experimental results show that the learner is able to discover domain-specific search strategies, thus improving the planner's performance with respect to the chosen metric.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.09923](http://arxiv.org/abs/1810.09923)

##### PDF
[http://arxiv.org/pdf/1810.09923](http://arxiv.org/pdf/1810.09923)

