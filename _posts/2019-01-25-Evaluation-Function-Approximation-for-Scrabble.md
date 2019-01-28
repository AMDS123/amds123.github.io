---
layout: post
title: "Evaluation Function Approximation for Scrabble"
date: 2019-01-25 04:05:52
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Rishabh Agarwal
mathjax: true
---

* content
{:toc}

##### Abstract
The current state-of-the-art Scrabble agents are not learning-based but depend on truncated Monte Carlo simulations and the quality of such agents is contingent upon the time available for running the simulations. This thesis takes steps towards building a learning-based Scrabble agent using self-play. Specifically, we try to find a better function approximation for the static evaluation function used in Scrabble which determines the move goodness at a given board configuration. In this work, we experimented with evolutionary algorithms and Bayesian Optimization to learn the weights for an approximate feature-based evaluation function. However, these optimization methods were not quite effective, which lead us to explore the given problem from an Imitation Learning point of view. We also tried to imitate the ranking of moves produced by the Quackle simulation agent using supervised learning with a neural network function approximator which takes the raw representation of the Scrabble board as the input instead of using only a fixed number of handcrafted features.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.08728](http://arxiv.org/abs/1901.08728)

##### PDF
[http://arxiv.org/pdf/1901.08728](http://arxiv.org/pdf/1901.08728)

