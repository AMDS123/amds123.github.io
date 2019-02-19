---
layout: post
title: "Re-determinizing Information Set Monte Carlo Tree Search in Hanabi"
date: 2019-02-16 09:42:41
categories: arXiv_AI
tags: arXiv_AI
author: James Goodman
mathjax: true
---

* content
{:toc}

##### Abstract
This technical report documents the winner of the Computational Intelligence in Games(CIG) 2018 Hanabi competition. We introduce Re-determinizing IS-MCTS, a novel extension of Information Set Monte Carlo Tree Search (IS-MCTS) \cite{IS-MCTS} that prevents a leakage of hidden information into opponent models that can occur in IS-MCTS, and is particularly severe in Hanabi. Re-determinizing IS-MCTS scores higher in Hanabi for 2-4 players than previously published work. Given the 40ms competition time limit per move we use a learned evaluation function to estimate leaf node values and avoid full simulations during MCTS. For the Mixed track competition, in which the identity of the other players is unknown, a simple Bayesian opponent model is used that is updated as each game proceeds.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.06075](http://arxiv.org/abs/1902.06075)

##### PDF
[http://arxiv.org/pdf/1902.06075](http://arxiv.org/pdf/1902.06075)

