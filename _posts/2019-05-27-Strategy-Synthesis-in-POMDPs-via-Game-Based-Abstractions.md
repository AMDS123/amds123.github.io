---
layout: post
title: "Strategy Synthesis in POMDPs via Game-Based Abstractions"
date: 2019-05-27 10:19:03
categories: arXiv_AI
tags: arXiv_AI
author: Leonore Winterer, Sebastian Junges, Ralf Wimmer, Nils Jansen, Ufuk Topcu, Joost-Pieter Katoen, Bernd Becker
mathjax: true
---

* content
{:toc}

##### Abstract
We study synthesis problems with constraints in partially observable Markov decision processes (POMDPs), where the objective is to compute a strategy for an agent that is guaranteed to satisfy certain safety and performance specifications. Verification and strategy synthesis for POMDPs are, however, computationally intractable in general. We alleviate this difficulty by focusing on planning applications and exploiting typical structural properties of such scenarios; for instance, we assume that the agent has the ability to observe its own position inside an environment. We propose an abstraction refinement framework which turns such a POMDP model into a (fully observable) probabilistic two-player game (PG). For the obtained PGs, efficient verification and synthesis tools allow to determine strategies with optimal safety and performance measures, which approximate optimal schedulers on the POMDP. If the approximation is too coarse to satisfy the given specifications, an refinement scheme improves the computed strategies. As a running example, we use planning problems where an agent moves inside an environment with randomly moving obstacles and restricted observability. We demonstrate that the proposed method advances the state of the art by solving problems several orders-of-magnitude larger than those that can be handled by existing POMDP solvers. Furthermore, this method gives guarantees on safety constraints, which is not supported by the majority of the existing solvers.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1708.04236](http://arxiv.org/abs/1708.04236)

##### PDF
[http://arxiv.org/pdf/1708.04236](http://arxiv.org/pdf/1708.04236)

