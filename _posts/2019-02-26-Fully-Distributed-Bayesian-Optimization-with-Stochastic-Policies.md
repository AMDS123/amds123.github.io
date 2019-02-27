---
layout: post
title: "Fully Distributed Bayesian Optimization with Stochastic Policies"
date: 2019-02-26 15:13:17
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Javier Garcia-Barcos, Ruben Martinez-Cantin
mathjax: true
---

* content
{:toc}

##### Abstract
Bayesian optimization has become a popular method for high-throughput computing, like the design of computer experiments or hyperparameter tuning of expensive models, where sample efficiency is mandatory. In these applications, distributed and scalable architectures are a necessity. However, Bayesian optimization is mostly sequential. Even parallel variants require certain computations between samples, limiting the parallelization bandwidth. Thompson sampling has been previously applied for distributed Bayesian optimization. But, when compared with other acquisition functions in the sequential setting, Thompson sampling is known to perform suboptimally. In this paper, we present a new method for fully distributed Bayesian optimization, which can be combined with any acquisition function. Our approach considers Bayesian optimization as a partially observable Markov decision process. In this context, stochastic policies, such as the Boltzmann policy, have some interesting properties which can also be studied for Bayesian optimization. Furthermore, the Boltzmann policy trivially allows a distributed Bayesian optimization implementation with high level of parallelism and scalability. We present results in several benchmarks and applications that shows the performance of our method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.09992](http://arxiv.org/abs/1902.09992)

##### PDF
[http://arxiv.org/pdf/1902.09992](http://arxiv.org/pdf/1902.09992)

