---
layout: post
title: "The Potential of Restarts for ProbSAT"
date: 2019-04-26 10:51:11
categories: arXiv_AI
tags: arXiv_AI
author: Jan-Hendrik Lorenz, Julian Nickerl
mathjax: true
---

* content
{:toc}

##### Abstract
This work analyses the potential of restarts for probSAT, a quite successful algorithm for k-SAT, by estimating its runtime distributions on random 3-SAT instances that are close to the phase transition. We estimate an optimal restart time from empirical data, reaching a potential speedup factor of 1.39. Calculating restart times from fitted probability distributions reduces this factor to a maximum of 1.30. A spin-off result is that the Weibull distribution approximates the runtime distribution for over 93% of the used instances well. A machine learning pipeline is presented to compute a restart time for a fixed-cutoff strategy to exploit this potential. The main components of the pipeline are a random forest for determining the distribution type and a neural network for the distribution's parameters. ProbSAT performs statistically significantly better than Luby's restart strategy and the policy without restarts when using the presented approach. The structure is particularly advantageous on hard problems.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.11757](http://arxiv.org/abs/1904.11757)

##### PDF
[http://arxiv.org/pdf/1904.11757](http://arxiv.org/pdf/1904.11757)

